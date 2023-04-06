<script setup lang="ts">
</script>

<template>
  <main>
    <div class="filter-layer" >
    <header>
      <img alt="gogochuckle" class="logo" src="../assets/logo.svg" />
      <div class="motto" >
        <span class="a-decor1"><a class="motto-a" href="">永远追求</a></span>，
        <span class="a-decor2"><a class="motto-a" href="">永远尝试</a></span>。
      </div>
    </header>
  </div>
  </main>
</template>

<style scoped>

main {
  background: url('https://image.gogochuckle.com/gitee/spaceX.jpg') 100% no-repeat #aaa;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
}

.filter-layer {
  height: 100vh;
  width: 100vw;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: rgb(61,66,96,.4);
  background-image: linear-gradient(140deg,rgba(61,66,96,.4) 15%,rgba(31,34,49,.6));
  opacity: .9;
}


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
  z-index: 1000;
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
