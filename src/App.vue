<template>
  <nav class="contenedor">
      <div class="fondo-yo">
        <router-link class="yo" to="/">Yo,</router-link>
      </div> 
      <div class="fondo-simon">
       <router-link class="simon" to="/about">Simón</router-link>
      </div>

 
  </nav>
  <router-view/>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  margin-top: 30px;
  color: rgb(228, 228, 8);
  display: grid;
  grid-template-columns: 50% 50%;
  width: 100%;

  a {
    display: flex;
    width: 100%;
    height: 50px;
    justify-content: center;
    align-items: center;
    font-weight: bold;
    font-size: 30px;
    color: #88c921;


    &.router-link-exact-active {
      color: #eb10eb;
      
    }
  }
}
.yo{
  font-size: 25px;
}
.simon{
  font-size: 25px;
}
.fondo-yo{
  border: 1px;
  display: inline-block;
  width: auto;
  margin: 0 20px;
  text-align: justify;
  background-color: rgb(70, 43, 56);
  opacity: .6;
}
.fondo-simon{
  border: 1px;
  display: inline-block;
  width: auto;
  margin: 0 20px;
  text-align: justify;
  background-color: rgb(125, 143, 27);
  opacity: .6;

}
</style>
