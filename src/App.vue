<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/Profile.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="profile" src="@/assets/profile.jpg" width="210" height="220" style="margin-right: 50px; border-radius: 100px;" />

    <div class="wrapper">
      <HelloWorld msg="NEYNA ANGGRAENY"/>

      <!-- <nav>
        <RouterLink to="/">Profile</RouterLink>
        <RouterLink to="/Skill">Skill</RouterLink>
      </nav> -->
    </div>
  </header>

  <RouterView />
</template>

<style scoped>
header {
  line-height: 1.5;
  max-height: 100vh;
}

.profile {

  margin-top: -400px;
}

nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  margin-top: 2rem;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }

  nav {
    text-align: left;
    margin-left: -1rem;
    font-size: 1rem;

    padding: 1rem 0;
    margin-top: 1rem;
  }
}
</style>
