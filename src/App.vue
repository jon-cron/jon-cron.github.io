<template>
  <header>
    <!-- <Navbar /> -->
  </header>
  <main class="bg-white">
    <router-view />
  </main>
  <OptionsOffCanvas/>
  <TodoModal/>
  <TowerModal/>
  <RecipeModal/>
  <KeepModal/>
</template>

<script>
import { computed } from 'vue'
import { AppState } from './AppState'
import Navbar from './components/Navbar.vue'
import OptionsOffCanvas from "./components/OptionsOffCanvas.vue"
import TodoModal from "./components/TodoModal.vue"
import TowerModal from "./components/TowerModal.vue"
import RecipeModal from "./components/RecipeModal.vue"
import KeepModal from "./components/KeepModal.vue"

export default {
  setup() {
    return {
      appState: computed(() => AppState)
    }
  },
  components: { Navbar, OptionsOffCanvas, TodoModal, TowerModal, RecipeModal, KeepModal }
}
</script>
<style lang="scss">
@import "./assets/scss/main.scss";

:root{
  --main-height: calc(100vh - 32px - 64px);
}


footer {
  display: grid;
  place-content: center;
  height: 32px;
}
</style>
