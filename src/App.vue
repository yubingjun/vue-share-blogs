<template>
  <div id="app">
    <Header id="header"></Header>
    <main id="main">
      <router-view/>
    </main>
    <Footer id="footer"></Footer>
  </div>
</template>

<script>
import Header from './components/header'
import Footer from './components/footer'

export default {
  name: 'App',
  components:{
      Header,Footer
  }
}
</script>

<style lang="less">

@import "./assets/common";

@media (max-width: 768px) { // 也就是说0-768的宽度使用下面的样式   响应式
  #app {
    grid-template-columns: 10px auto 10px;
    #header,#footer {
      padding-left: 10px;
      padding-right: 10px;
    }
  }
}

#app {
  display: grid;
  grid-template-columns: 12% auto 12%;
  grid-template-rows: auto 1fr auto;
  grid-template-areas:"header header header"
                       ".       main       ."
                       "footer footer footer";
}
#header {
  grid-area: header;
  padding-left: 12%;
  padding-right: 12%;
}

#main {
  grid-area: main;
}

#footer {
  grid-area: footer;
  padding-left: 12%;
  padding-right: 12%;
}
</style>
