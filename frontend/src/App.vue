<script setup>
import login from './components/login.vue';
import register from './components/register.vue';
import home from './components/home.vue';
import Sidebar from './components/Sidebar.vue';
import Options from './components/Options.vue';
</script>

<template>

  <main style="display: flex;">
    <aside style="position:sticky; display: grid; top: 0;">
      <options />
    </aside>
    <aside style="position:sticky; display: grid; top: 0; left: 4%;">
      <sidebar />
    </aside>
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
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
}
</style>
