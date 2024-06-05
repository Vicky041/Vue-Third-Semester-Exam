<script setup>
  import gitHubIcon from './icons/gitHubIcon.vue';
</script>

<template>

  <nav>
    <div class="navbar">
      <gitHubIcon class="github-icon"/>
      <h1 class="text">Osemeke C. Victor Github Repo</h1>
    </div>
  </nav>

</template>
 
<style scoped>

.navbar {
  position:relative;
  display: flex; 
  align-items: center;
  gap: 10px;
  justify-content: center;
  background-color: #0a5fc0;
  text-align: center;
  padding: 20px;
  margin-bottom: 100px
}

.github-icon {
  font-size: 3rem;
}

.text {
  font-style: italic;
  text-decoration: solid;
}
</style>
