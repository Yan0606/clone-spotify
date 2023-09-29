<template>
  <div id="app" >
    <div>
      <All />
      <nav class="bg-black p-1">
        <Nave />
      </nav>

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
