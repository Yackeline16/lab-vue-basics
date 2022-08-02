<template>
  <nav class="navbar-a">
        <router-link to="/">Home</router-link> |
        <router-link to="/about">About</router-link>
  </nav>
    <router-view/>
</template>

<script>
import NavBar from '@/components/NavBar.vue'
export default {
    component: {
        NavBar
    }

}
</script>

<style>
.navbar-a{
    background-color: aqua;
    border: solid 2px black;
}

</style>