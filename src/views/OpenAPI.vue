<script lang="ts">
import { defineComponent } from "vue";
import "@d0kur0/open-api/dist/open-api.css"
import OpenAPI from "@d0kur0/open-api";

export default defineComponent({
  name: "Home",
  components: {
    OpenAPI,
  },
}); 
</script>
  
<template>
  <OpenAPI />
</template> 

