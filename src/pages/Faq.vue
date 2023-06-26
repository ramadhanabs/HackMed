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
                    <div id="section-faq" class="page-section page-title  bg-dark">
                        <div class="container clearfix">
                            <div class="wow fadeInUp center" data-wow-delay="100ms">
                                <h1 class="fw-900 mb-2">FAQ</h1>
                                <span class="fc-muted wow fadeInUp" data-wow-delay="200ms">All your questions answered in one place</span>
                            </div>
                        </div>
                    </div>
                </div>
            </section><!-- #page-title end -->

            <!-- Content
            ============================================= -->
            <section id="content">
                <div class="content-wrap py-0">
                    <div id="section-faq" class="page-section py-0 faq bg-dark">
                        <div class="container clearfix pb-6">

                            <h2 class="center mb-3 text-capitalize fw-bold font-body wow fadeInUp" data-wow-delay="300ms">Bio Farma X MIT Hacking Medicine 2023 FAQs</h2>

                            <div class="clearfix gx-6 mt-6">

                                <div class=" wow fadeInUp"  data-wow-delay="300ms">
                                    <div class="accordion" id="accordionExample">
                                        <div class="accordion-item">
                                            <h2 class="accordion-header" id="headingOne">
                                            <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapse1" aria-expanded="true" aria-controls="collapse1" @click="setSelectedTab('content-1')">
                                                What is a healthcare hackathon?
                                            </button>
                                            </h2>
                                            <div id="collapse1" class="accordion-collapse collapse" :class="selectedTab === 'content-1' && 'show'" aria-labelledby="headingOne" data-bs-parent="#accordionExample">
                                            <div class="accordion-body">
                                                A Hackathon is an event in which people with different backgrounds and expertise form teams, collaborate within a limited time frame, and focus on a specific problem or idea in healthcare to come up with innovative, disruptive ideas and solutions. By bringing together diverse minds alike in their interest for solving healthcare’s biggest challenges, problems can be diagnosed from multiple different perspectives. Watch 
                                                <a href="https://www.youtube.com/watch?v=9SubjvrEh6U&t=2s">this video </a>
                                                from GrandHack 2023 to feel the passion of MIT Healthcare Grandhack!
                                            </div>
                                            </div>
                                        </div>
                                        <div class="accordion-item">
                                            <h2 class="accordion-header" id="headingTwo">
                                            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapse2" aria-expanded="false" aria-controls="collapse2" @click="setSelectedTab('content-2')">
                                                What is the Bio Farma X MIT Hackathon?
                                            </button>
                                            </h2>
                                            <div id="collapse2" class="accordion-collapse collapse" :class="selectedTab === 'content-2' && 'show'" aria-labelledby="headingTwo" data-bs-parent="#accordionExample">
                                            <div class="accordion-body">
                                                Bio Farma, in collaboration with MIT is bringing a healthcare hackathon to Indonesia. We’re hard at work to make this Bio Farma X MIT Hacking Medicine a wonderful experience. Interested in innovating for healthcare’s toughest pain points? This is the weekend to meet, ideate, and hack with hundreds of like-minded entrepreneurs, designers, engineers, and healthcare professionals.
                                            </div>
                                            </div>
                                        </div>
                                        <div class="accordion-item">
                                            <h2 class="accordion-header" id="headingThree">
                                            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapse3" aria-expanded="false" aria-controls="collapse3" @click="setSelectedTab('content-3')">
                                                How can I get involved?
                                            </button>
                                            </h2>
                                            <div id="collapse3" class="accordion-collapse collapse" :class="selectedTab === 'content-3' && 'show'" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
                                            <div class="accordion-body">
                                                The application for participating at the MIT Grand Hack is available
                                                <RouterLink to="/register">
                                                    here!
                                                </RouterLink>
                                                Applications will be accepted on a rolling basis. Upon acceptance, we will route you to a confirmation call to RSVP and confirm your participation.
                                            </div>
                                            </div>
                                        </div>
                                        <div class="accordion-item">
                                            <h2 class="accordion-header" id="headingThree">
                                            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapse4" aria-expanded="false" aria-controls="collapse4" @click="setSelectedTab('content-4')">
                                                When is the event?
                                            </button>
                                            </h2>
                                            <div id="collapse4" class="accordion-collapse collapse" :class="selectedTab === 'content-4' && 'show'" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
                                            <div class="accordion-body">
                                                Bio Farma X MIT Hacking Medicine runs from Thursday, August 22nd to Sunday, August 27th.
                                            </div>
                                            </div>
                                        </div>
                                        <div class="accordion-item">
                                            <h2 class="accordion-header" id="headingThree">
                                            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapse5" aria-expanded="false" aria-controls="collapse5" @click="setSelectedTab('content-5')">
                                                Is the event free?
                                            </button>
                                            </h2>
                                            <div id="collapse5" class="accordion-collapse collapse" :class="selectedTab === 'content-5' && 'show'" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
                                            <div class="accordion-body">
                                                Yes! Participating in the Bio Farma X MIT Hacking Medicine is free but everyone is required to apply and be accepted due to a limited number of spots.
                                            </div>
                                            </div>
                                        </div>
                                        <div class="accordion-item">
                                            <h2 class="accordion-header" id="headingThree">
                                            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapse6" aria-expanded="false" aria-controls="collapse6" @click="setSelectedTab('content-6')">
                                                What are the tracks and which track should I participate in?
                                            </button>
                                            </h2>
                                            <div id="collapse6" class="accordion-collapse collapse" :class="selectedTab === 'content-6' && 'show'" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
                                            <div class="accordion-body">
                                                A track is an area of focus for healthcare innovation. There are 2 tracks at the Bio Farma X MIT Hacking Medicine. Applicants get admitted into a track, participants form team with other people in their track, and ultimately get judged by a panel of experts in that track. 
                                                Even though your project may fit into more than one theme, you can only give a final presentation in one track. The 2 tracks are very diverse and there is something for everyone.

                                            </div>
                                            </div>
                                        </div>
                                        <div class="accordion-item">
                                            <h2 class="accordion-header" id="headingThree">
                                                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapse7" aria-expanded="false" aria-controls="collapse7" @click="setSelectedTab('content-7')">
                                                    When will I hear about which track I am placed in?
                                                </button>
                                            </h2>
                                            <div id="collapse7" class="accordion-collapse collapse" :class="selectedTab === 'content-7' && 'show'" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
                                                <div class="accordion-body">
                                                The application will ask you for your track preferences. Track assignments will be sent out closer to the start of the Bio Farma X MIT Hacking Medicine. 
                                                Participants will form team with other people within their track and get judged by a panel of experts in that area of healthcare. Even though your project may fit into more than one theme, you can only give one final presentation in one track. 

                                                </div>
                                            </div>
                                        </div>
                                        <div class="accordion-item">
                                            <h2 class="accordion-header" id="headingThree">
                                                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapse8" aria-expanded="false" aria-controls="collapse8" @click="setSelectedTab('content-8')">
                                                    
                                                    Am I allowed to switch tracks?
                                                </button>
                                            </h2>
                                            <div id="collapse8" class="accordion-collapse collapse" :class="selectedTab === 'content-8' && 'show'" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
                                                <div class="accordion-body">
                                                 <b>No,</b> unfortunately we do not allow participants to switch tracks in order to maintain an even distribution of experts and participants across the event.
                                                </div>
                                            </div>
                                        </div>
                                        <div class="accordion-item">
                                            <h2 class="accordion-header" id="headingThree">
                                                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapse9" aria-expanded="false" aria-controls="collapse9" @click="setSelectedTab('content-9')">
                                                    
                                                    When is the application deadline?
                                                </button>
                                            </h2>
                                            <div id="collapse9" class="accordion-collapse collapse" :class="selectedTab === 'content-9' && 'show'" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
                                                <div class="accordion-body">
                                                    We will update the deadline of the application
                                                    <RouterLink to="/register">
                                                        here.
                                                    </RouterLink>
                                                    However, admissions are sent out on a rolling basis, so we encourage you to get your application in as early as possible.
                                                </div>
                                            </div>
                                        </div>
                                        <div class="accordion-item">
                                            <h2 class="accordion-header" id="headingThree">
                                                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapse10" aria-expanded="false" aria-controls="collapse10" @click="setSelectedTab('content-10')">
                                                    
                                                    When will I hear back?
                                                </button>
                                            </h2>
                                            <div id="collapse10" class="accordion-collapse collapse" :class="selectedTab === 'content-10' && 'show'" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
                                                <div class="accordion-body">
                                                    We review applications regularly as they come in. However, given the large volume of applications, it may take 3-5 weeks after your application submission for us to get back to you.
                                                </div>
                                            </div>
                                        </div>
                                        <div class="accordion-item">
                                            <h2 class="accordion-header" id="headingThree">
                                                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapse11" aria-expanded="false" aria-controls="collapse11" @click="setSelectedTab('content-11')">
                                                    
                                                    I have not received an email I think I should have received!
                                                </button>
                                            </h2>
                                            <div id="collapse11" class="accordion-collapse collapse" :class="selectedTab === 'content-11' && 'show'" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
                                                <div class="accordion-body">
                                                    Please check your spam folder. Otherwise you can contact us
                                                    <RouterLink to="/contact">
                                                        here.
                                                    </RouterLink>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="accordion-item">
                                            <h2 class="accordion-header" id="headingThree">
                                                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapse12" aria-expanded="false" aria-controls="collapse12" @click="setSelectedTab('content-12')">
                                                    
                                                    What should I prepare for the hackathon? Will hacking resources be provided?
                                                </button>
                                            </h2>
                                            <div id="collapse12" class="accordion-collapse collapse" :class="selectedTab === 'content-12' && 'show'" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
                                                <div class="accordion-body">
                                                    All participants will require an internet-connected device to be able to access the virtual hacking resources. We recommend using a laptop, but you could also bring a tablet or a smartphone. 

                                                    Typically hack participants have just used their own computers and tablet/smartphone devices to play with, but use whatever you think you will need! If you have resources at home (arduinos, circuit boards, other rapid prototyping materials) that you think will be useful for your project, you are welcome to use them.

                                                </div>
                                            </div>
                                        </div>
                                        <div class="accordion-item">
                                            <h2 class="accordion-header" id="headingThree">
                                                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapse13" aria-expanded="false" aria-controls="collapse13" @click="setSelectedTab('content-13')">
                                                    
                                                    Will meals be provided at the event?
                                                </button>
                                            </h2>
                                            <div id="collapse13" class="accordion-collapse collapse" :class="selectedTab === 'content-13' && 'show'" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
                                                <div class="accordion-body">
                                                    <b>Yes,</b> meals will be provided! All meals during the hackathon will be covered from Thursday to Sunday.  We want you to be able to focus on innovating with your team, so don’t worry about bringing food! That being said, you are still welcome to purchase your own food in the area, as long as it fits within your team’s schedule.

                                                </div>
                                            </div>
                                        </div>
                                        <div class="accordion-item">
                                            <h2 class="accordion-header" id="headingThree">
                                                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapse14" aria-expanded="false" aria-controls="collapse14" @click="setSelectedTab('content-14')">
                                                    
                                                    Will any accommodation be provided for participants?
                                                </button>
                                            </h2>
                                            <div id="collapse14" class="accordion-collapse collapse" :class="selectedTab === 'content-14' && 'show'" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
                                                <div class="accordion-body">
                                                    Unfortunately, we can not provide  hotels for the participants. But, we do prepare cars and other transportation for you.

                                                </div>
                                            </div>
                                        </div>
                                        <div class="accordion-item">
                                            <h2 class="accordion-header" id="headingThree">
                                                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapse15" aria-expanded="false" aria-controls="collapse15" @click="setSelectedTab('content-15')">
                                                    
                                                    I am a foreigner, can I join Bio Farma X MIT Hacking Medicine?
                                                </button>
                                            </h2>
                                            <div id="collapse15" class="accordion-collapse collapse" :class="selectedTab === 'content-15' && 'show'" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
                                                <div class="accordion-body">
                                                    Of course! You are free to join this event.

                                                </div>
                                            </div>
                                        </div>
                                        <div class="accordion-item">
                                            <h2 class="accordion-header" id="headingThree">
                                                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapse16" aria-expanded="false" aria-controls="collapse16" @click="setSelectedTab('content-16')">
                                                    As a foreigner, what do I need to prepare to enter Indonesia (Bali)?
                                                </button>
                                            </h2>
                                            <div id="collapse16" class="accordion-collapse collapse" :class="selectedTab === 'content-16' && 'show'" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
                                                <div class="accordion-body">
                                                    
                                                    You can refer to 
                                                    <RouterLink to="/contact">
                                                        this site to see the specific requirements.
                                                    </RouterLink>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="accordion-item">
                                            <h2 class="accordion-header" id="headingThree">
                                                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapse17" aria-expanded="false" aria-controls="collapse17" @click="setSelectedTab('content-17')">
                                                    Am I going to be placed on a team or am I some version of a free agent?
                                                </button>
                                            </h2>
                                            <div id="collapse17" class="accordion-collapse collapse" :class="selectedTab === 'content-17' && 'show'" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
                                                <div class="accordion-body">
                                                    A little bit of both. On Thursday, participants will have a chance to pitch problems. After hearing all of the pitches, you will have a chance to mingle, talk to people whose problems you found compelling (and/or talk to people who found your problem compelling) and form teams. You can join a team around someone else’s pitch or form a team around something you pitched.
                                                </div>
                                            </div>
                                        </div>
                                        <div class="accordion-item">
                                            <h2 class="accordion-header" id="headingThree">
                                                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapse18" aria-expanded="false" aria-controls="collapse18" @click="setSelectedTab('content-18')">
                                                    What is the expectation from participants in this event? I want to make sure I am well prepared as my idea is only in the “idea” stage.
                                                </button>
                                            </h2>
                                            <div id="collapse18" class="accordion-collapse collapse" :class="selectedTab === 'content-18' && 'show'" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
                                                <div class="accordion-body">
                                                    Participants are expected to come ready to participate – you can either pitch a “pain point” for 60 seconds or join a team once teams begin forming. We ask that the pitches are kept to describing problems, not solutions.
                                                </div>
                                            </div>
                                        </div>
                                        <div class="accordion-item">
                                            <h2 class="accordion-header" id="headingThree">
                                                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapse19" aria-expanded="false" aria-controls="collapse19" @click="setSelectedTab('content-19')">
                                                    What if I’m coming in with more than an idea?
                                                </button>
                                            </h2>
                                            <div id="collapse19" class="accordion-collapse collapse" :class="selectedTab === 'content-19' && 'show'" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
                                                <div class="accordion-body">
                                                    <p>In the spirit of the hackathon, we ask that participants come in with an open mind to meet new people and listen to other people’s ideas. Our methodology starts with the problem, not ‘idea-solution’.</p> 
                                                    
                                                    Out of fairness to all participants, we ask that projects worked on over the weekend have not been extensively worked on prior to the hackathon. Please do not come to recruit for your startup. Instead, think about the theme and challenge questions and what could be specific problems within that area that are interesting.

                                                </div>
                                            </div>
                                        </div>
                                        <div class="accordion-item">
                                            <h2 class="accordion-header" id="headingThree">
                                                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapse20" aria-expanded="false" aria-controls="collapse20" @click="setSelectedTab('content-20')">
                                                    Where is the event located?
                                                </button>
                                            </h2>
                                            <div id="collapse20" class="accordion-collapse collapse" :class="selectedTab === 'content-20' && 'show'" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
                                                <div class="accordion-body">
                                                    Bio Farma X MIT Hacking Medicine will take place in Bali, Indonesia. Exact location will be announced later.
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>

                                <!-- <div class="col-lg-6 order-1 order-lg-2 text-lg-end text-center mb-5 sticky-sidebar-wrap">
                                    <div class="sticky-sidebar">
                                        <div>
                                            <h5 class="text-uppercase ls4 fw-normal mb-2 fc-secondary" data-wow-delay="100ms">Faq</h5>
                                            <h2 class="text-capitalize fw-bold font-body wow fadeInUp" data-wow-delay="300ms">Frequently Asked <br class="d-none d-lg-block">Questions</h2>
                                        </div>
                                        <img src="../frontend/assets/images/faq.svg" alt="FAQ" class="wow fadeInUp"  data-wow-delay="400ms">
                                    </div>
                                </div> -->

                            </div>

                            <div class="center mt-6 wow fadeInUp" data-wow-delay="100ms">
                                <h4>
                                    For any other questions about the application process, please email 
                                    <a href="mailto:feni.febriani@biofarma.co.id">feni.febriani@biofarma.co.id</a> 
                                </h4>
                                <!-- <h3 class="text-capitalize fw-bold font-body">
                                    Can’t find the answer?
                                </h3>
                                <RouterLink to="/contact">
                                    <button class="button button-large button-circle button-large fw-medium">Contact Us</button>
                                </RouterLink> -->
                            </div>

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

import { ref, onMounted } from 'vue'

const selectedTab = ref('content-1')

function setSelectedTab(id){
  selectedTab.value = id
}

</script>