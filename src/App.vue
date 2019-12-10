<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view />
    <a-button-group>
      <a-button type="primary" ghhost="true" loading="true">Button</a-button>
      <a-button type="primary" ghhost="true" loading="false">Button</a-button>
      <a-button type="primary" icon="search"></a-button>
    </a-button-group>
    <!--<a-dropdown-button>-->
      <!--<a-button type="primary" icon="search">1</a-button>-->
      <!--<a-button type="primary" icon="search">2</a-button>-->
      <!--<a-button type="primary" icon="search">3</a-button>-->
    <!--</a-dropdown-button>-->
  </div>
</template>

<style lang="less">
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
