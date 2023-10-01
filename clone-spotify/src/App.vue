<template>
  <div id="app" >
    <div class="flex">
    <div class="w-1/4">
      <nav class="bg-black p-1">
        <Nave />
      </nav>
    </div>
    <div class="w-3/4 bg-black p-1">
      <!-- Conteúdo da Main.vue -->
      <Main/>
    </div>
    </div>
  </div>
</template>

<script>
import All from "./components/All.vue";
import Nave from "./components/Nave.vue";
import Main from "./components/Main.vue";

export default {
  components: {
    All,
    Nave,
    Main,
  },

  methods: {
    // adiciona as funções aqui
  },

};

</script>

<style></style>
