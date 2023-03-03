

<template>
<div class="h-screen ">
    <Navbar/>
    <Header/>
    <Companies/>
    <Principle/>
    <Power/>
    <SoloutionVue/>
    <Customiza/>
    <!-- <Videotools/> -->
    <Footer/>
   
   
</div>

</template>

<script>
import Navbar from './components/Navbar.vue';
import Header from './components/Header.vue';
import Companies from './components/Companies.vue';
import Power from './components/Power.vue';
import Principle from './components/Principle.vue';
// import Videotools from './components/Videotools.vue';
import SoloutionVue from './components/Soloution.vue';
import Customiza from './components/Customiza.vue';
import Footer from './components/Footer.vue';

export default {
    name:"App",
    components:{
        Navbar,
        Header,
        Companies,
        Principle,
        Power,
        SoloutionVue,
        Customiza,
        // Videotools,
        Footer,
       
        
    }
}

</script>

<style >

</style>


