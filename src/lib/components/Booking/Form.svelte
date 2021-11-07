<script>
    export let from
    export let to
    export let leaveOn
    export let returnOn
import DateOption from "./DateOption.svelte";
import DestinationOption from "./DestinationOption.svelte";


</script>

<form action="" class="flightform">
    <div class="flightform__conn">
      <div class="flightform__from">
        <DestinationOption
            bind:value={from}
        />
        <DestinationOption
            bind:value={to}
        />
      </div>

      <div class="flightform__date">
        <DateOption
            bind:value={leaveOn}
        />
        <DateOption
            bind:value={returnOn}
        />
      </div>
    </div>

    <div class="submitdiv">
      <input type="submit" value="Let's Go" class="flightsubmit" />
    </div>
  </form>