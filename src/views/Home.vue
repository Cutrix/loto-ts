<template>
  <div>
    <loto></loto>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import Loto from "@/components/Loto.vue"; // @ is an alias to /src

@Component({
  components: {
    Loto
  }
})
export default class Home extends Vue {}
</script>
