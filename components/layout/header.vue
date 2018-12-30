<template>
  <header class="header">
    <nav class="navbar">
      <div class="nav_header container">
        <h4 class="logo"></h4>
        <span class="gentel">道之所在，虽千万人吾往矣</span>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'AppHeader',
  data() {
    return {}
  }
}
</script>

<style lang="scss" scoped>
.header {
  z-index: 999;
  opacity: 0.9;
  .navbar {
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    width: 100%;
    height: 4em;
    background: #ffffff;
  }
  .nav_header {
    display: flex;
    align-items: center;
    height: 4rem;;
    .logo {
      width: 5.5em;
      height: 2.2em;;
      background: url('/logo1.png') no-repeat;
      background-size: contain;
      color: #93b642;
      font-family: sans-serif;
      display:  inline-block;
      margin-right: 4rem;
      span {
        color: #007bff;
      }
    }
    .gentel {
      color: #007bff;
      font-size: 0.8em;
    }
  }
  
}
</style>
