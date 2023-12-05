<template>
<h1>¿Quién es este pokémon</h1>
<PokemonPicture :pokemonId="4" :showPokemon="true"/>
<PokemonOptions/>
</template>

<script>
import PokemonPicture from '@/components/PokemonPicture.vue'
import PokemonOptions from '@/components/PokemonOptions.vue'


export default {
  components: { PokemonOptions,PokemonPicture },

}
</script>

