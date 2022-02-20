<script>
    import FlightCard from "$lib/flightCard.svelte";
    import FlightList from "$lib/flightList.svelte";

    import Position from "$lib/position.svelte";
</script>

<svelte:head>
    <title>Welcome</title>
</svelte:head>

<FlightList>
    <FlightCard />
</FlightList>
