<template>
  <div>
    <Restaurant />
  </div>
</template>

<script>
import Restaurant from '../../components/Restaurant.vue';

export default {
  name: 'Login',
  data() {
    return {}; // isDisplayed: false;
  },
  props: {
    msg: String,
  },

  components: {
    Restaurant,
    // AvailableRestaurants,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
