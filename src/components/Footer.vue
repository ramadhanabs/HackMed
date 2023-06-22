<template>
    <!-- Footer
    ============================================= -->
    <footer id="footer" class="bg-dark-2 footer">
        <div class="container">
            <!-- Footer Widgets
            ============================================= -->
            <div class="footer-widgets-wrap">

                <div class="row clearfix gy-5">

                    <div class="col-lg-6">

                        <div class="row">
                            <div class="col-lg-8">
                                <div class="clearfix mb-4 wow fadeInUp" data-wow-delay="100ms">
                                    <RouterLink to="/">
                                        <img src="../frontend/assets/logo/logo-mit-light.svg" alt="Image" class="">
                                    </RouterLink>
                                </div>
                                <div class="clearfix wow fadeInUp" data-wow-delay="200ms">
                                    <p class="mb-0 fc-muted">Solutions to existing problems, developed through collaborative, intense, and innovative teamwork in a short amount of time.</p>
                                </div>
                            </div>
                        </div>

                    </div>

                    <div class="col-lg-6">

                        <div class="clearfix dark">
                            <div class="row">
                                <div class="col-6 wow fadeInUp" data-wow-delay="300ms">
                                    <ul class="mb-0">
                                        <!-- <li class="mb-3"><a href="index.html">Home</a></li> -->
                                        <li class="mb-3">
                                            <RouterLink to="/speakers">
                                                Conference Speakers
                                            </RouterLink>
                                        </li>
                                        <li class="mb-3">
                                            <RouterLink to="/judges">
                                                Judges
                                            </RouterLink>
                                        </li>
                                        <li class="mb-3">
                                            <RouterLink to="/mentors">
                                               Mentors
                                            </RouterLink>
                                        </li>
                                    </ul>
                                </div>

                                <div class="col-6 wow fadeInUp" data-wow-delay="400ms">
                                    <ul class="mb-0">
                                        <li class="mb-3">
                                            <RouterLink to="/sponsorship">
                                                Sponsorship
                                            </RouterLink>
                                        </li>
                                        <li class="mb-3">
                                            <RouterLink to="/contact">
                                                Contact
                                            </RouterLink>
                                        </li>
                                        <li class="mb-3">
                                            <RouterLink to="/faq">
                                                FAQ
                                            </RouterLink>
                                        </li>
                                        <!-- <li class="mb-3">
                                            <RouterLink to="/terms">
                                                Terms of Service
                                            </RouterLink>
                                        </li>
                                        <li class="mb-3">
                                            <RouterLink to="/privacy">
                                                Privacy Policy
                                            </RouterLink>
                                        </li> -->
                                    </ul>
                                </div>
                            </div>
                        </div>

                    </div>

                </div>

            </div><!-- .footer-widgets-wrap end -->
        </div>

        <!-- Copyrights
        ============================================= -->
        <div id="copyrights bg-dark-2">
            <div class="container pb-4">

                <div class="line mb-4 mt-0"></div>

                <div class="row justify-content-between d-flex align-items-center gy-4">
                    <div class="col-12 col-lg-auto text-center text-lg-start copyrights fc-muted animate__animated animate__fadeInUp animate__delay-100ms" data-wow-delay="500ms">
                        Copyrights &copy; 2023 All Rights Reserved by 
                        <RouterLink to="/">
                            Bio Farma X MIT Hacking Medicine
                        </RouterLink>
                    </div>

                    <div class="col-12 col-lg-auto text-center text-lg-end animate__animated animate__fadeInUp animate__delay-200ms" data-wow-delay="600ms">
                        <div class=" d-flex justify-content-center">
								<a href="https://instagram.com/hi.dhc" class="social-icon inline-block si-small si-borderless mb-0 si-instagram">
									<i class="icon-instagram"></i>
									<i class="icon-instagram"></i>
								</a>
	
								<a href="mailto:feni.febriani@biofarma.co.id" class="social-icon inline-block si-small si-borderless mb-0 si-gplus">
									<i class="icon-email"></i>
									<i class="icon-email"></i>
								</a>
	
								<a href="tel:+62813-2184-4185" class="social-icon inline-block si-small si-borderless mb-0 si-linkedin">
									<i class="icon-phone"></i>
									<i class="icon-phone"></i>
								</a>
							</div>
                    </div>
                </div>

            </div>
        </div><!-- #copyrights end -->
    </footer><!-- #footer end -->
</template>

<script setup>
import { RouterLink } from 'vue-router'
</script>