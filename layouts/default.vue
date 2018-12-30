<template>
  <div>
    <header-view />
    <div id="app-container" class="app-container container">
      <left-nav></left-nav>
      <div class="app-main ">
        <nuxt/>
      </div>
      <right-nav></right-nav>
    </div>
  </div>
</template>
<script>
import Header from '~/components/layout/header'
import LeftNav from '~/components/layout/leftNav'
import RightNav from '~/components/layout/rightNav'
export default {
  data() {
    return {}
  },
  components: {
    HeaderView: Header,
    LeftNav,
    RightNav
  }
}
</script>

<style lang="scss" scoped>
.app-main {
  float: left;
  width: 45.5em;
  margin-left: 12.5em;
  height: 100em;
  background: #ffffff;
  margin-top: 1.5em;
  &:-moz-full-screen {
    overflow-y: auto;
  }
    
  &:-webkit-full-screen {
    overflow-y: auto;
  }
    
  &:fullscreen {
    overflow-y: auto;
  }

}
</style>

