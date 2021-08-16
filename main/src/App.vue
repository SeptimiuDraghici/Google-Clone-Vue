<template>
  <div id="app">
    <myHeader/>
    <myContent/>
    <myFooter/>
  </div>
</template>

<script>
import myHeader from './components/myHeader.vue'
import myContent from './components/myContent.vue'
import myFooter from './components/myFooter.vue'

export default {
  name: 'App',
  components: {
    myHeader,
    myContent,
    myFooter
  }
}
</script>

<style>
#app {
  height: 100%;
  font-family: 'Roboto', sans-serif;
  display: flex;
  flex-direction: column;
}

* {
  margin: 0;
}

html, body {
  height: 100%;
}

@media only screen and (max-width: 600px) {
  .wrapper{
    width: 100%;
  }
  .search-bar {
    width: 370px;
    }
  .input {
    width: 280px;
  }
  .footer {
    flex-direction: column;
    height: fit-content;
  }
}
</style>
