<template>

  <div class="video-item">
    <div class="video-title">
      觅色
    </div>
    <div class="video-content">
      <img src="../assets/1.jpeg" alt="" />
    </div>
    <div class="video-info">
      这一期节目主要为了食色代码寻觅一个主持人，在师大、政法新校区开展
    </div>
    <!-- <div class="video-footer">
      点赞
    </div> -->
  </div>
</template>

<script>
export default {
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
  /*padding-left: 2rem;*/
}
h1, h2 {
  font-weight: normal;
  margin-bottom: 0;

}
h3{
  margin-top: 0;

}
.video-item{
  background-color: hotpink;
  border-radius: 10px;
  padding: 0;
  margin: 20px 5px;
}
.video-title{
  font-size: 2rem;
  color: #777;
  padding: 5px;
}
.video-info{
  padding: 5px;
}
.video-content img{
  width: 100%;
}
.logo img{
  width:5rem;
}
</style>
