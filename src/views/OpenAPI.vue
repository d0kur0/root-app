<script lang="ts">
import { defineComponent } from "vue";

import "@d0kur0/open-api/dist/open-api.css";
import "@d0kur0/uikit/dist/uikit.css";

import OpenAPI from "@d0kur0/open-api";
import { Button } from "@d0kur0/uikit";

export default defineComponent({
  name: "Home",
  components: {
    OpenAPI,
    Button
  },
}); 
</script>
  
<template>
  <OpenAPI />
  <Button>Hoba</Button>
  <Button :transparent="true">Hoba</Button>
</template> 

