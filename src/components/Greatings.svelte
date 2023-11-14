<script lang="ts">
  const currentTime = new Date();
  const currentHour = currentTime.getHours()

  let greating=""
  if (currentHour<12) {
    greating = "Buenos días"
  }else if(currentHour<18) {
    greating = "Buenas tardes"
  }else{
    greating= "Buenas noches"
  }
</script>

<h1 class="text-3xl font-bold">{greating}</h1>