<template>

  <div class="content row">
    <div class="col-md-8 col-md-offset-2">
      <div class="title">
        海阔任鱼跃，天高任鸟飞
      </div>
      <div class="video">
        <embed src='http://player.youku.com/player.php/sid/XMjc3NzY4ODM5Ng==/v.swf' allowFullScreen='true' quality='high' width="100%" align='middle' allowScriptAccess='always' type='application/x-shockwave-flash'></embed>
      </div>
      <div class="info">
        想说却还没说的 还很多
        攒着是因为想写成歌
        让人轻轻地唱着 淡淡地记着
        就算终于忘了 也值了
        说不定我一生涓滴意念
        侥幸汇成河
        然后我俩各自一端
        望着大河弯弯 终于敢放胆
        嘻皮笑脸 面对 人生的难
        也许我们从未成熟
        还没能晓得 就快要老了
        尽管心里活着的还是那个
      </div>
    </div>

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
.content{
  text-align: left;
  margin: 0 auto;
}
.title{
  font-size: 2rem;
  margin-bottom: 1rem;
}
.video{
  padding: 1rem;
}
.video embed{
}
.info{
  /*width:80%;*/
}
</style>
