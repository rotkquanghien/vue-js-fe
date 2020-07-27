<template>
  <div id="app">
    <Header></Header>
    <Banner></Banner>
    <Info></Info>
    <CountInfo></CountInfo>
    <Choosing></Choosing>
    <Case></Case>
    <OurCase></OurCase>
    <Core></Core>
    <Banner2></Banner2>
    <PriceTable></PriceTable>
    <BuyIt></BuyIt>
    <OurTeams></OurTeams>
    <Contact></Contact>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from './components/Header'
import Banner from './components/Banner'
import Info from './components/InfoContent'
import CountInfo from './components/CountInfo'
import Choosing from './components/WhyChoose'
import Case from './components/CaseStudies'
import OurCase from './components/OurCase'
import Core from './components/CoreCompete'
import Banner2 from './components/Banner2'
import PriceTable from './components/PriceTable'
import BuyIt from './components/BuyIt'
import OurTeams from './components/OurTeams'
import Contact from './components/Contact'
import Footer from './components/Footer'
export default {
  name: 'App',
  components: {
    Header,
    Banner,
    Info,
    CountInfo,
    Choosing,
    Case,
    OurCase,
    Core,
    Banner2,
    PriceTable,
    BuyIt,
    OurTeams,
    Contact,
    Footer
  }
}
</script>
<style lang="scss">
@import "scss/style.scss";

#app {
}
</style>
