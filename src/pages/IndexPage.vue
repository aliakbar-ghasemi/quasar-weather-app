<template>
  <q-page class="flex column"> weather app </q-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'IndexPage',
  components: {},
  setup() {
    return {};
  },
});
</script>

<style lang="scss">
.q-page {
  background: #136a8a; /* fallback for old browsers */
  background: -webkit-linear-gradient(
    to bottom,
    #136a8a,
    #267871
  ); /* Chrome 10-25, Safari 5.1-6 */
  background: linear-gradient(
    to bottom,
    #136a8a,
    #267871
  ); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
}
</style>
