<script>
    export let fltNum = "WGN9999";
    export let fromCity = "RSW";
    export let toCity = "PPT";
    export let skd = "18:00";
    export let tailNum = "N799JN";
</script>


<div class="card">
    <div>
        <span class="large">{fltNum}</span>
        <br />
        <span class="medium">{fromCity} - {toCity}</span>
    </div>
    <div class="vertcenter medium">{skd}</div>
    <div class="vertcenter medium">{tailNum}</div>
</div>

<style>
    .card {
        font-family: 'Work Sans';
        display: grid;
        height: 4rm;
        grid-template-columns: 1.5fr 1fr 1fr;
        border: 1px solid black;
        border-radius: 4px;
        padding: 4px;
    }

    .vertcenter {
        display: flex;
        justify-items: center;
        align-items: center;
    }

    .large {
        font-size: 1.5em;
        font-weight: 600;
    }

    .medium {
        font-size: 1.2em;
    }
</style>
