<template>
    <div>
        <div class="body-overlay"></div>

        <!-- Document Wrapper
        ============================================= -->
        <div id="wrapper" class="clearfix">

            <Header/>
            <ComingSoon/>
            <Footer/>

        </div><!-- #wrapper end -->
    </div>
</template>

<script setup>
import Header from '../components/Header.vue'
import ComingSoon from '../components/ComingSoon.vue'
import Footer from '../components/Footer.vue'
</script>