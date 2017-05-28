<template>
  <div id="app" class="container">
    <div class="hello">
      <div class="logo">
        <img src="./assets/timg.jpeg" alt="" />

      </div>
      <div class="title">
        <h1>食色代码</h1>
        <h3><small>Beautiful Coding</small></h3>
      </div>

    </div>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app',
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.hello{
  display: flex;
  display: -webkit-flex; /* Safari */
  justify-content: flex-start;
  align-items: baseline;
  /*padding-left: 2rem;*/
  /*border-bottom: 1px solid #ccc;*/
}
h1, h2 {
  font-weight: normal;
  margin-bottom: 0;

}
h3{
  margin-top: 0;

}
.logo img{
  width:5rem;
}
</style>
