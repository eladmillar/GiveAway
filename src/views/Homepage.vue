<template>
  <div>
    <Intro />
    <SellingPoints />
    <Productiveness />
  </div>
</template>

<script>
import Intro from "../cmps/Intro.vue";
import SellingPoints from "../cmps/SellingPoints.vue";
import Productiveness from "../cmps/Productiveness.vue";
export default {
  components: {
    Intro,
    SellingPoints,
    Productiveness
  }
};
</script>