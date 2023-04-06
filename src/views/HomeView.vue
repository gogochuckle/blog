<script setup lang="ts">
</script>

<template>
  <main>
    <header>
      <a href="" class="a-logo" >
        <img alt="Vue logo" class="logo" src="../assets/logo.svg" />
      </a>
      <div class="motto" >
        <a class="motto-a" href="">永远追求</a>，
        <a class="motto-a" href="">永远尝试</a>。
      </div>
    </header>
  </main>
</template>

<style scoped>

header {
  display: flex;
  flex-direction: column;
  place-items: center;
}

.a-logo {
  user-select: none;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  -webkit-user-drag: none;
}

.logo {
  width: 55rem;
  height: 10rem;
  margin: 0;
  user-select: none;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  -webkit-user-drag: none;
}

.motto {
  color: #000;
  font-size: 20px;
  font-weight: bold;
  padding: 20px;
  white-space: normal;
  user-select: none;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
}

motto-a {
  color: #000;
  font-size: 20px;
  font-weight: bold;
}

a {
  text-decoration: none
}
</style>
