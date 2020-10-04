<template>
    <div class="d-flex flex-column">
        <div class="d-flex mb-5">
            <div @click="character='mattis'" :class="{'active': character=='mattis'}" class="bordered">Mattis</div>
            <div @click="character='keith'" :class="{'active': character=='keith'}" class="bordered">Keith</div>
        </div>
        <component :is="character"></component>
    </div>
</template>

<script>
import Mattis from './components/Mattis/outterTemplate.vue'
import Keith from './components/Keith/outterTemplate.vue'

export default {
  name: 'App',
  data: function() {
    return {
        character: 'mattis'
    }
  },
  components: {
    Mattis,
    Keith
  }
}
</script>
<style scoped lang="css">

    .bordered {
        border: 1px solid black;
        border-radius: 6px;
        padding: 5px;
    }
    .bordered:hover {
        cursor: pointer;
        filter: brightness(80%);
    }
    .bordered.active {
        filter: brightness(80%);
    }
</style>
