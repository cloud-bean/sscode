<template>
<div class="container">

  <div class="hello row">
    <div class="logo">
      <img src="../assets/timg.jpeg" alt="" />

    </div>
    <div class="title">
      <h1>食色代码</h1>
      <h3><small>Beautiful Coding</small></h3>
    </div>

  </div>
  <div class="content row">
    <video-item class="col-md-4 item"></video-item>
    <video-item class="col-md-4 item"></video-item>
    <video-item class="col-md-4 item"></video-item>
    <video-item class="col-md-4 item"></video-item>

  </div>
</div>

</template>

<script>
import VideoItem from './VideoItem';

export default {
  components: {
    VideoItem,
  },
  data() {
    return {
      msg: 'Welcome to Your Vue.js App',
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello{
  display: flex;
  display: -webkit-flex; /* Safari */
  justify-content: flex-start;
  align-items: baseline;
  padding-left: 2rem;
  /*border-bottom: 1px solid #ccc;*/
}
h1, h2 {
  font-weight: normal;
  margin-bottom: 0;

}
h3{
  margin-top: 0;

}
.content{
  text-align: left;
  margin: 0 auto;
  padding-top: 1rem;
}
.item{
  margin-bottom: 1rem;
}
.logo img{
  width:5rem;
}
</style>
