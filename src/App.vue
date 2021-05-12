<template>
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
    <button class="btn btn-outline">neutral</button>
    <div class="w-64 carousel rounded-box">
      <div class="w-full carousel-item">
        <img src="https://picsum.photos/id/500/256/144" class="w-full" />
      </div>
      <div class="w-full carousel-item">
        <img src="https://picsum.photos/id/501/256/144" class="w-full" />
      </div>
      <div class="w-full carousel-item">
        <img src="https://picsum.photos/id/502/256/144" class="w-full" />
      </div>
      <div class="w-full carousel-item">
        <img src="https://picsum.photos/id/503/256/144" class="w-full" />
      </div>
      <div class="w-full carousel-item">
        <img src="https://picsum.photos/id/504/256/144" class="w-full" />
      </div>
      <div class="w-full carousel-item">
        <img src="https://picsum.photos/id/505/256/144" class="w-full" />
      </div>
      <div class="w-full carousel-item">
        <img src="https://picsum.photos/id/506/256/144" class="w-full" />
      </div>
    </div>
  </div>
  <router-view />
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
