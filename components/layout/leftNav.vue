<template>
  <div class="left_nav">
    <ul class="nav_list">
      <a href="">
        <li class="active">
          <i class="icon iconfont icon-blue-home"></i>
          <span>首页</span>
        </li>
      </a>
      <a href="">
        <li class="">
          <i class="icon iconfont icon-blue-collect"></i>
          <span>热门</span>
        </li>
      </a>
      <a href="">
        <li class="">
          <i class="icon iconfont icon-blue-aircraft"></i>
          <span>历程</span>
        </li>
      </a>
      <a href="">
        <li class="">
          <i class="icon iconfont icon-blue-collect"></i>
          <span>藏宝阁</span>
        </li>
      </a>
      <a href="">
        <li class="">
          <i class="icon iconfont icon-blue-edit"></i>
          <span>留言板</span>
        </li>
      </a>
    </ul>
  </div>
</template>

<script>
export default {
  
}
</script>

<style lang="scss" scoped>
.left_nav {
  position: fixed;
  width: 11.5em;
  top: 5.5em;
  left: calc((100% - 75em) / 2);
}
.nav_list {
  list-style: none;
  li {
    line-height: 3rem;
    font-family: webfont-normal,DINRegular;
    font-weight: 700;
    color: #757575;
    padding-left: 1.5em;
    text-decoration: none;
    text-transform: uppercase;
    font-size: 0.9em;
    .icon {
      position: relative;
      top: 0.1em;
      font-size: 1.2em;
      margin-right: 0.7em;
    }
    span {
      letter-spacing: 0.5px;
      &:hover {
        cursor:hand; 
      }
    }
    &:hover {
      color:#1e84f1;
      cursor:hand; 
    }
    &.active {
      background: #ffffff;
      color:#1e84f1;
      cursor:hand; 
    }
  }
  
}
</style>
