<script>
    import { Temporal } from "@js-temporal/polyfill";

    let days;
    let hours;
    let minutes;
    let seconds;

    const updateTime = () => {
        const duration = Temporal.Now.plainDateTimeISO().until(
            Temporal.PlainDateTime.from("2022-05-15T00:00"),
            { largestUnit: "day" }
        );
        days = duration.days;
        hours = duration.hours;
        minutes = duration.minutes;
        seconds = duration.seconds;
    };

    updateTime();

    setInterval(() => {
        updateTime();
    }, 1000);
</script>

<div class="grid grid-flow-col gap-5 text-center auto-cols-max">
    <div class="flex flex-col">
        <span class="countdown font-mono text-5xl">
            <span style="--value:{days};" />
        </span>
        days
    </div>
    <div class="flex flex-col">
        <span class="countdown font-mono text-5xl">
            <span style="--value:{hours};" />
        </span>
        hours
    </div>
    <div class="flex flex-col">
        <span class="countdown font-mono text-5xl">
            <span style="--value:{minutes};" />
        </span>
        min
    </div>
    <div class="flex flex-col">
        <span class="countdown font-mono text-5xl">
            <span style="--value:{seconds}" />
        </span>
        sec
    </div>
</div>
