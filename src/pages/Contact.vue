<template>
    <div>
        <div class="body-overlay"></div>

        <!-- Document Wrapper
        ============================================= -->
        <div id="wrapper" class="clearfix">

            <Header/>
            <!-- Page Title
            ============================================= -->
            <section id="content">
                <div class="content-wrap py-0">
                    <div id="section-sponsor" class="page-section page-title  bg-dark">
                        <div class="container clearfix">
                            <div class="wow fadeInUp center" data-wow-delay="100ms">
                                <h1 class="fw-900 mb-2">Contact</h1>
                                <span class="fc-muted wow fadeInUp" data-wow-delay="200ms">Get in touch with Us</span>
                            </div>
                        </div>
                    </div>
                </div>
            </section><!-- #page-title end -->

            <!-- Content
            ============================================= -->
            <section id="content">
                <div class="content-wrap py-0">
                    <div id="section-contact" class="page-section py-0 contact bg-dark">
                        <div class="container clearfix pb-6">

                            <h2 class="center mb-3 text-capitalize fw-bold font-body wow fadeInUp" data-wow-delay="300ms">Any question? Contact us</h2>

                            <div class="row gy-4 mt-6">
                                <div class="col-md-3 wow fadeInUp" data-wow-delay="300ms">
                                    <a href="https://goo.gl/maps/KEQRrDXi7SucRiPC6" target="_blank">
                                        <div class="card-contact p-4 center">
                                            <div class="square-icon">
                                                <i class="bi bi-geo-alt"></i>
                                            </div>
                                            <h4 class="my-3">Head Office</h4>
                                            <span class="fc-muted">Jl. Pasteur No. 28, Bandung 40161 <br> Jawa Barat Indonesia</span>
                                        </div>
                                    </a>
                                </div>
                                <div class="col-md-3 wow fadeInUp" data-wow-delay="400ms">
                                    <a href="mailto:hackathon@biofarma.co.id">
                                        <div class="card-contact p-4 center">
                                            <div class="square-icon">
                                                <i class="bi bi-envelope"></i>
                                            </div>
                                            <h4 class="my-3">Email</h4>
                                            <span class="fc-muted">Send to <br> hackathon@biofarma.co.id</span>
                                        </div>
                                    </a>
                                </div>
                                <div class="col-md-3 wow fadeInUp" data-wow-delay="500ms">
                                    <a href="tel:+62813-2184-4185">
                                        <div class="card-contact p-4 center">
                                            <div class="square-icon">
                                                <i class="bi bi-telephone"></i>
                                            </div>
                                            <h4 class="my-3">Phone</h4>
                                            <!-- <a href="https://wa.me/+6282261177737"></a> -->
                                            <span class="fc-muted">Feni Febriani Hastuti <br>+62 813-2184-4185</span>
                                        </div>
                                    </a>
                                </div>
                                <div class="col-md-3 wow fadeInUp" data-wow-delay="500ms">
                                    <a href="https://instagram.com/hi.dhc" target="_blank">
                                        <div class="card-contact p-4 center">
                                            <div class="square-icon">
                                                <i class="bi bi-instagram"></i>
                                            </div>
                                            <h4 class="my-3">Instagram</h4>
                                                <span class="fc-muted">Follow us <br> @hi.dhc</span>
                                        </div>
                                    </a>
                                </div>
                            </div>

                        </div>

                        <div class="d-none d-md-block px-0 map z-depth-1-half map-container wow fadeInUp" id="map-container-google-1">
                            <iframe data-wow-delay="100ms" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3960.926352745875!2d107.5982121147204!3d-6.899411595014623!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e68e643100f64e5%3A0xb642fd4d3a68face!2sBio%20Farma!5e0!3m2!1sen!2sid!4v1649660480054!5m2!1sen!2sid" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
                        </div>
                    </div>

                </div>
            </section><!-- #content end -->

            <Footer/>

        </div><!-- #wrapper end -->
    </div>
</template>

<script setup>
import Header from '../components/Header.vue'
import Footer from '../components/Footer.vue'
</script>