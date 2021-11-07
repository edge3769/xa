<script>
import FlightType from "./FlightType.svelte";


</script>

<div class="flighttypes">
    <!-- Round Trip -->
    <FlightType
        options
        value = 'Round Trip'
    />

    <!-- 1 Passenger -->
    <FlightType
        options
        value = '1 Passenger'
    />

    <!-- Economy -->
    <FlightType
        options
        value
    />
  </div>