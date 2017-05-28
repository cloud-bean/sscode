<template>


  <div class="content row">
    <video-item class="col-md-4 item"></video-item>
    <video-item class="col-md-4 item"></video-item>
    <video-item class="col-md-4 item"></video-item>
    <video-item class="col-md-4 item"></video-item>

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

.content{
  text-align: left;
  margin: 0 auto;
  padding-top: 1rem;
}
.item{
  margin-bottom: 1rem;
}

</style>
