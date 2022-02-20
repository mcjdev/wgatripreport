<script>
    import FlightCard from "$lib/flightCard.svelte";
    import FlightList from "$lib/flightList.svelte";
</script>

<svelte:head>
    <title>Welcome</title>
</svelte:head>

<main>
    <FlightList>
        <FlightCard />
    </FlightList>
</main>