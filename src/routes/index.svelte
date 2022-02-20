<script>
    import FlightCard from "$lib/flightCard.svelte";
    import FlightList from "$lib/flightList.svelte";

    import Position from "$lib/position.svelte";
</script>

<svelte:head>
    <title>Welcome</title>
    <style>
        @font-face {
            font-family: 'Work Sans';
            src: url('/fonts/WorkSans-VariableFont_wght.ttf');
        }
    </style>
</svelte:head>

<FlightList>
    <FlightCard />
</FlightList>
