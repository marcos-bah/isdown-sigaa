<template>
  <div class="card column is-half">
    <div class="card-content">
      <div class="content is-vcentered">
        <p class="title is-4">Offline</p>
        <p class="subtitle is-6">@isdown</p>
      </div>

      <div class="content">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus nec
        iaculis mauris.

        <br />
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
//import { useStore } from "vuex";
export default defineComponent({
  setup() {
    //const store = useStore();
  },
  name: "CardResult",
  components: {},
});
</script>

<style>
</style>