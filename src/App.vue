<template>
  <Navbar/>
  <Banner/>
  <Wrapper/>
  <Lang/>
  <Solution/>
  
  <Stocks/>
  <Do/>
  <Help/>
  <Cost/>
  <Wants/>
  <Wave/>
  <Footer/>
  
  
</template>

<script>
import Navbar from './components/Navbar.vue'
import Banner from './components/Banner.vue'
import Wrapper from './components/Wrapper.vue'
import Lang from './components/Lang.vue'
import Solution from './components/Solution.vue'
import Stocks from './components/Stocks.vue'
import Do from './components/Do.vue'
import Help from './components/Help.vue'
import Cost from './components/Cost.vue'
import Wants from './components/Wants.vue'
import Wave from './components/Wave.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    Banner,
    Wrapper,
    Lang,
    Solution,
    Stocks,
    Do,
    Help,
    Cost,
    Wants,
    Wave,
    Footer,
  }
}
</script>

<style>

</style>
