<template>
 <rentCar/>




</template>

<script>
// @ is an alias to /src
import rentCar from "../components/rentCar";
import fiveSteps from "../components/fiveSteps";

export default {
  name: 'HomeView',
  components: {
    rentCar,fiveSteps
  },
};
</script>
