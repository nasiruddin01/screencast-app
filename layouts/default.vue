<template>
  <div class="container-secondary">
    <div id="nav-bar">
      <nuxt-link class="button--green" to="/">Home</nuxt-link>
      <nuxt-link class="button--green" to="/videos">Videos</nuxt-link>
    </div>
    <div id="default-body">
      <Nuxt />
    </div>
  </div>
</template>

<style>
.container-secondary {
  width: 800px;
  height: 100vh;
  margin: auto;
   
  
 
}
#nav-bar {
  height: 40px;
  width: 100%;
  background-color: #84c4d6;
  
}
#default-body {
  max-width: 100%;
  margin-top: 1rem;
  
}
html {
  font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI",
    Roboto, "Helvetica Neue", Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  /* border: 1px solid #3b8070; */
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}
</style>
