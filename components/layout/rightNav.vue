<template>
  <div class="left_nav">
    <section class="intrduce">
      <div class="nick_photo"></div>
      <span class="nick_name">清风徐徐</span>
      <div class="content">
        <p class="list_item sign">
          <i class="icon iconfont icon-blue-person"></i>
           <strong>浪</strong> 蝶游蜂，迈步九云中
        </p>
        <p class="list_item sign">
          <i class="icon iconfont icon-blue-aircraft"></i>
           <strong>微信</strong> xulang1992win
        </p>
        <p class="list_item sign">
          <i class="icon iconfont icon-blue-like"></i>
           <strong>微</strong> xulang1992win
        </p>
      </div>
    </section>
  </div>
</template>

<script>
// import nickPhoto from '~/assets/image/nick_img.jpg'
export default {
  data () {
    // nickPhoto: require('../../assets/image/nick_img.jpg')
  }
}
</script>

<style lang="scss" scoped>
.left_nav {
  float: right;
  display: block;
  width: 16em;
  margin-top: 1.5em;
  background: #ffffff;
}
.intrduce {
  display: flex;
  align-items: center;
  flex-direction: column;
  margin-bottom: 1em;
  .nick_photo {
    width: 5em;
    height: 5em;
    background: url('/images/nick_img.jpg') no-repeat;
    background-size: contain;
    border-radius: 50%;
    margin-top: 1em;
  }
  .nick_name {
    font-size: 1.5em;
    padding: 0.5em 0;
  }
  .content {
    width: 100%;
    border-top: 1px solid #f7f7f9;
    border-bottom: 1px solid #f7f7f9;
    .list_item {
      font-size: 0.8em;
      padding: 0.3em 0.5em;
      padding-left: 2em;
      .icon {
        position: relative;
        top: 0.1em;
        font-size: 1.4em;
        margin-right: 0.5em;
        color: #999
      }
      &.sign {
        font-weight: 700;
      }
    }
  }
}
</style>
