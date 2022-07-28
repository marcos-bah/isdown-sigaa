<template>
  <time datetime="2016-1-1">11:09 PM - 1 Jan 2016</time>
</template>

<script lang="ts">
import { defineComponent } from "vue";
//import { useStore } from "vuex";
export default defineComponent({
  setup() {
    //const store = useStore();
  },
  name: "Time",
  components: {},
  data() {
    return {
      time: new Date() as Date,
    };
  },
  computed: {
    timeString() {
      return this.time.toLocaleTimeString();
    },
  },
});
</script>

<style>
</style>