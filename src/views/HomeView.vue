<script setup lang="ts">
</script>

<template>
  <main>
    <header>
      <img alt="Vue logo" class="logo" src="../assets/logo.svg" />
      <div class="motto" >
        <span class="a-decor1"><a class="motto-a" href="">永远追求</a></span>，
        <span class="a-decor2"><a class="motto-a" href="">永远尝试</a></span>。
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

.logo {
  width: 33rem;
  height: 6rem;
  margin: 0;
  user-select: none;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  -webkit-user-drag: none;
}

.motto {
  color: antiquewhite;
  font-size: 18px;
  font-weight: bold;
  padding: 20px;
  white-space: normal;
  user-select: none;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
}

.motto-a {
  color: antiquewhite;
  font-weight: bold;
}

.a-decor1 {
  padding: 3px 0 3px 0;
  background: linear-gradient(to right, #736efe, #00bfe8) no-repeat right bottom;
  background-size: 0 2px;
  transition: background-size 500ms;
}
.a-decor1:hover {
  background-position-x: left;
  background-size: 100% 2px;
}
.a-decor2 {
  padding: 3px 0 3px 0;
  background: linear-gradient(to right, #00bfe8, #736efe) no-repeat right bottom;
  background-size: 0 2px;
  transition: background-size 500ms;
}
.a-decor2:hover {
  background-position-x: left;
  background-size: 100% 2px;
}

a {
  text-decoration: none;
}

a:hover {
  color: aliceblue;
  text-decoration: none;
}
</style>
