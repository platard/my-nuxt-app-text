<template>
    <h1>My first view</h1>
    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Asperiores, harum? Reprehenderit optio deserunt, beatae repudiandae alias voluptas amet, molestiae accusamus enim saepe, tempore pariatur velit ut. Labore ea rerum expedita!</p>
    <MyWelcome />
    <NuxtLink to="/">Home</NuxtLink>
    <NuxtLink :to="`users/${1 }/${ 2 }`" >Pokemon</NuxtLink >
</template>