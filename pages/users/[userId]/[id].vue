<template>
    <h1>This is my pokemon route with the parameter {{ $route.params.id }} and {{ $route.params.userId }}</h1>
    <img :src="`https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/${ $route.params.id }.png`" alt="pokemon sprite">
</template>

<script>

</script>