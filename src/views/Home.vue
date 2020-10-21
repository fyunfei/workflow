<template>
  <div class="home">
    <vue-editor></vue-editor>
  </div>
</template>

<script>
// @ is an alias to /src
import VueEditor from "@/components/VueEditor";
export default {
  name: "Home",
  components: { VueEditor }
};
</script>
