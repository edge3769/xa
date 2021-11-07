<script>
    export let mode

    const setMode = (value) => {
        mode = value
    }
</script>

<div class="flightbooking__top">
    <div on:click={()=>{setMode('flight')}} class="flight__option">
      <a href="">
        Book Flight
        <div class="./flightbooking.html"><i class="fas fa-plane"></i></div>
      </a>
    </div>
    <div on:click={()=>{setMode('bus')}} class="flight__option active">
      <a href=''>
        Book Bus
        <div class="#"><i class="fas fa-bus"></i></div>
      </a>
    </div>
    <div on:click={()=>{setMode('train')}} class="flight__option">
      <a href="">
        Book Train
        <div class="#"><i class="fas fa-train"></i></div>
      </a>
    </div>
  </div>