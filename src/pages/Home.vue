<template>
  <div>
    <div class="body-overlay"></div>

    <!-- Document Wrapper
        ============================================= -->
    <div id="wrapper" class="clearfix">
      <Header />

      <!-- Slider
            ============================================= -->
      <section
        id="slider"
        class="slider-element min-vh-100 bgchanger include-header bg-dark hero"
      >
        <div class="slider-inner">
          <div class="vertical-middle slider-element-fade">
            <div class="container text-start py-6">
              <div class="row align-items-center gx-6 gy-6">
                <div class="col-lg-6 text-md-start">
                  <div class="logo mb-3">
                    <img
                      data-wow-delay="100ms"
                      class="me-4 wow fadeInUp"
                      src="../frontend/assets/logo/Biofarma-Group-Logo-White.png"
                      alt="Image"
                    />
                    <img
                      data-wow-delay="200ms"
                      class="wow fadeInUp"
                      src="../frontend/assets/logo/MIT-Logo-White.png"
                      alt="Image"
                    />
                  </div>
                  <div class="emphasis-title bottommargin-sm">
                    <h1 class="fw-900 mb-3 wow fadeInUp" data-wow-delay="300ms">
                      Bio Farma X MIT Hacking Medicine
                    </h1>
                    <p
                      class="opmargin-sm mb-0 fc-muted wow fadeInUp"
                      data-wow-delay="400ms"
                    >
                      The Bio Farma x MIT Hacking Medicine hackathon will bring
                      together people from technology and healthcare backgrounds
                      to work on innovative solutions for existent problems.
                      Will be held in Bali, August 2023.
                    </p>
                  </div>
                  <div class="mb-5">
                    <div class="row gy-4">
                      <div class="col-xl-6 wow fadeInUp" data-wow-delay="500ms">
                        <div class="d-flex">
                          <div class="me-4 fc-primary">
                            <div
                              class="rounded-icon d-flex rounded-14 align-items-center justify-content-center"
                            >
                              <i class="bi bi-calendar"></i>
                            </div>
                          </div>

                          <div>
                            <h4 class="mb-1 fw-bold">August 24-27, 2023</h4>
                            <span class="fc-muted">Date</span>
                          </div>
                        </div>
                      </div>
                      <div class="col-xl-6 wow fadeInUp" data-wow-delay="600ms">
                        <div class="d-flex">
                          <div class="me-4 fc-primary">
                            <div
                              class="rounded-icon d-flex rounded-14 align-items-center justify-content-center"
                            >
                              <i class="bi bi-geo-alt"></i>
                            </div>
                          </div>

                          <div>
                            <h4 class="mb-1 fw-bold">Bali, Indonesia</h4>
                            <span class="fc-muted">Place</span>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <RouterLink to="/register">
                    <button
                      data-wow-delay="700ms"
                      class="button button-large button-circle fw-medium wow fadeInUp"
                    >
                      Register Now
                    </button>
                  </RouterLink>
                  <RouterLink to="/contact">
                    <button
                      data-wow-delay="800ms"
                      class="button button-large button-border button-circle fw-medium wow fadeInUp"
                    >
                      Contact Us
                    </button>
                  </RouterLink>
                </div>

                <div
                  data-wow-delay="100ms"
                  class="col-lg-6 text-center wow fadeInUp"
                >
                  <img
                    src="../frontend/assets/images/header-photo.png"
                    alt="Header"
                  />
                </div>
              </div>
            </div>
          </div>

          <a
            data-scroll
            href="#section-about"
            class="one-page-arrow d-none d-md-block"
          >
            <div class="scroll-inner">
              <div class="scroll-wheel"></div>
            </div>
          </a>
        </div>
      </section>
      <!-- #slider end -->

      <!-- Content
            ============================================= -->
      <section id="content">
        <div class="content-wrap py-0">
          <div id="section-about" class="page-section about bg-dark pt-6">
            <div class="container clearfix">
              <div class="row gx-6 gy-5 align-items-center mb-6">
                <div class="col-lg-6">
                  <h5
                    class="text-uppercase ls4 fw-normal mb-3 fc-secondary wow fadeInUp"
                    data-wow-delay="100ms"
                  >
                    About
                  </h5>
                  <h2
                    class="text-capitalize fw-bold font-body wow fadeInUp"
                    data-wow-delay="200ms"
                  >
                    Bio Farma, The Pharmaceutical SOE Holding
                  </h2>
                  <p data-wow-delay="300ms" class="fc-muted mb-0 wow fadeInUp">
                    The Pharmaceutical SOE Holding was formed on January 31,
                    2020, consisting of PT Bio Farma (Persero), PT Kimia Farma
                    Tbk, and PT Indofarma Tbk. In 2021, PT INUKI also joined the
                    holding company. Each members of the Holding have different
                    business focus : PT Bio Farma (Persero) focuses on life
                    science business, PT Kimia Farma Tbk focuses on medicine
                    business, PT Indofarma Tbk focuses on herbal and medical
                    device business, and PT INUKI operates in the nuclear
                    technology industry. The purpose of Pharmaceutical SOE
                    Holding establishment is to strengthen the national
                    pharmaceutical industry independence, increase national
                    product availability, and create joint innovations in supply
                    of pharmaceutical products.
                  </p>
                </div>

                <div class="col-lg-6">
                  <div data-wow-delay="100ms" class="wow fadeInUp">
                    <img
                      src="../frontend/assets/images/biofarma-photo.jpg"
                      alt="biofarma"
                      class="rounded-14"
                    />
                  </div>
                </div>
              </div>

              <div class="row gx-6 gy-5 align-items-center">
                <div class="col-lg-6 order-last order-lg-first">
                  <div data-wow-delay="100ms" class="wow fadeInUp">
                    <img
                      src="../frontend/assets/images/mit-photo.jpg"
                      alt="biofarma"
                      class="rounded-14"
                    />
                  </div>
                </div>

                <div class="col-lg-6 order-first order-lg-last">
                  <h5
                    class="text-uppercase ls4 fw-normal mb-3 fc-secondary wow fadeInUp"
                    data-wow-delay="100ms"
                  >
                    About
                  </h5>
                  <h2
                    class="text-capitalize fw-bold font-body wow fadeInUp"
                    data-wow-delay="200ms"
                  >
                    MIT Hacking Medicine
                  </h2>
                  <p data-wow-delay="300ms" class="fc-muted wow fadeInUp">
                    MIT Hacking Medicine has facilitated hackathon events in
                    nearly a dozen countries and multiple U.S. states. It aims
                    to energize the healthcare community and accelerate medical
                    innovation.
                  </p>
                  <p data-wow-delay="400ms" class="fc-muted mb-0 wow fadeInUp">
                    MIT Hacking Medicine routinely collaborates with prominent
                    organizations and corporations, such as The Kauffman
                    Foundation, Massachusetts General Hospital, Emergency Nurses
                    Association, Pfizer, Microsoft, Samsung, GE, Merck, and
                    AthenaHealth. The group has also been featured in top media
                    outlets such as SXSW, The Wall Street Journal, Slate, and
                    Wired.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div id="section-event" class="page-section journey pt-6 bg-dark-2">
          <h5
            class="text-uppercase ls4 fw-normal mb-3 fc-secondary text-center wow fadeInUp"
            data-wow-delay="100ms"
          >
            Journey
          </h5>

          <h2
            class="center mb-3 text-capitalize fw-bold font-body wow fadeInUp"
            data-wow-delay="200ms"
          >
            Hackathon Journey
          </h2>

          <div class="row mt-6 gy-lg-0 gy-4">
            <div class="col-12 col-sm-4 col-lg">
              <div
                class="card-journey p-4 center wow fadeInUp"
                data-wow-delay="300ms"
              >
                <div class="square-icon fw-bold">1</div>
                <div class="icon my-4">
                  <img
                    src="../frontend/assets/images/carbon_events-alt.svg"
                    alt=""
                  />
                </div>
                <h4 class="my-3">
                  Collaborate to generate ideas with other participants
                </h4>
              </div>
            </div>
            <div class="col-12 col-sm-4 col-lg">
              <div
                class="card-journey p-4 center wow fadeInUp"
                data-wow-delay="400ms"
              >
                <div class="square-icon fw-bold">2</div>
                <div class="icon my-4">
                  <img src="../frontend/assets/images/carbon_idea.svg" alt="" />
                </div>
                <h4 class="my-3">Hack the problems and create the solutions</h4>
              </div>
            </div>
            <div class="col-12 col-sm-4 col-lg">
              <div
                class="card-journey p-4 center wow fadeInUp"
                data-wow-delay="500ms"
              >
                <div class="square-icon fw-bold">3</div>
                <div class="icon my-4">
                  <img
                    src="../frontend/assets/images/carbon_collaborate.svg"
                    alt=""
                  />
                </div>
                <h4 class="my-3">Receive feedback from mentors</h4>
              </div>
            </div>
            <div class="col-12 col-sm">
              <div
                class="card-journey p-4 center wow fadeInUp"
                data-wow-delay="600ms"
              >
                <div class="square-icon fw-bold">4</div>
                <div class="icon my-4">
                  <img
                    src="../frontend/assets/images/carbon_group-presentation.svg"
                    alt=""
                  />
                </div>
                <h4 class="my-3">Present your solution to the judging panel</h4>
              </div>
            </div>
            <div class="col-12 col-sm">
              <div
                class="card-journey p-4 center wow fadeInUp"
                data-wow-delay="700ms"
              >
                <div class="square-icon fw-bold">5</div>
                <div class="icon my-4">
                  <img
                    src="../frontend/assets/images/carbon_trophy.svg"
                    alt=""
                  />
                </div>
                <h4 class="my-3">Winners and runners-up announcement</h4>
              </div>
            </div>
          </div>
        </div>

        <div id="section-timeline" class="page-section timeline bg-dark pt-6">
          <div class="container clearfix" style="transform: none">
            <h5
              class="text-uppercase ls4 fw-normal mb-3 fc-secondary text-center fadeInUp animated"
              data-animate="fadeInUp"
              data-delay="10"
            >
              Agenda
            </h5>

            <h2
              class="center mb-3 text-capitalize fw-bold font-body fadeInUp animated"
              data-animate="fadeInUp"
              data-delay="20"
            >
              Hackathon Agenda
            </h2>

            <!-- Desktop -->
            <div class="d-none d-md-block mb-5" style="transform: none">
              <div
                id="side-navigation"
                class="row mt-6 gx-6 ui-tabs ui-corner-all ui-widget ui-widget-content"
                data-plugin="tabs"
                style="transform: none"
              >
                <div
                  class="col-md-6 sticky-sidebar-wrap"
                  style="
                    position: relative;
                    overflow: visible;
                    box-sizing: border-box;
                    min-height: 1px;
                  "
                >
                  <div
                    class="scwStickySidebar"
                    style="
                      padding-top: 0px;
                      padding-bottom: 1px;
                      position: static;
                      transform: none;
                      left: 111.6px;
                      top: 0px;
                    "
                  >
                    <div class="sticky-sidebar">
                      <ul
                        class="sidenav bg-dark mb-0 ui-tabs-nav ui-corner-all ui-helper-reset ui-helper-clearfix ui-widget-header"
                        role="tablist"
                      >
                        <li
                          data-animate="fadeInUp"
                          data-delay="30"
                          class="ui-tabs-tab ui-corner-top ui-state-default ui-tab fadeInUp animated"
                          :class="selectedTab === 'content-1' && 'ui-tabs-active ui-state-active'"
                          role="tab"
                          tabindex="0"
                          aria-controls="snav-content1"
                          aria-labelledby="ui-id-1"
                          aria-selected="true"
                          aria-expanded="true"
                        >
                          <a
                            @click="setSelectedTab('content-1')"
                            class="d-flex ui-tabs-anchor"
                            role="presentation"
                            tabindex="-1"
                            id="ui-id-1"
                          >
                            <div class="me-4">
                              <div class="rounded-icon">
                                <i class="bi bi-calendar"></i>
                              </div>
                            </div>

                            <div>
                              <h4 class="mb-1 fw-bold">
                                Day 1-2 : Hackathon Intro
                              </h4>
                              <span class="fc-muted"
                                >Thursday, August 24 – Friday, August 25,
                                2023</span
                              >
                            </div>
                          </a>
                        </li>
                        <li
                          data-animate="fadeInUp"
                          data-delay="40"
                          class="my-4 ui-tabs-tab ui-corner-top ui-state-default ui-tab fadeInUp animated"
                          :class="selectedTab === 'content-2' && 'ui-tabs-active ui-state-active'"
                          role="tab"
                          tabindex="-1"
                          aria-controls="snav-content2"
                          aria-labelledby="ui-id-2"
                          aria-selected="false"
                          aria-expanded="false"
                        >
                          <a
                            @click="setSelectedTab('content-2')"
                            class="d-flex ui-tabs-anchor"
                            role="presentation"
                            tabindex="-1"
                            id="ui-id-2"
                          >
                            <div class="me-4">
                              <div class="rounded-icon">
                                <i class="bi bi-calendar"></i>
                              </div>
                            </div>

                            <div>
                              <h4 class="mb-1 fw-bold">Day 3 : Pitching Day</h4>
                              <span class="fc-muted"
                                >Saturday, August 26, 2023</span
                              >
                            </div>
                          </a>
                        </li>
                        <li
                          data-animate="fadeInUp"
                          data-delay="50"
                          role="tab"
                          tabindex="-1"
                          class="ui-tabs-tab ui-corner-top ui-state-default ui-tab fadeInUp animated"
                          :class="selectedTab === 'content-3' && 'ui-tabs-active ui-state-active'"
                          aria-controls="snav-content3"
                          aria-labelledby="ui-id-3"
                          aria-selected="false"
                          aria-expanded="false"
                        >
                          <a
                            @click="setSelectedTab('content-3')"
                            class="d-flex ui-tabs-anchor"
                            role="presentation"
                            tabindex="-1"
                            id="ui-id-3"
                          >
                            <div class="me-4">
                              <div class="rounded-icon">
                                <i class="bi bi-calendar"></i>
                              </div>
                            </div>

                            <div>
                              <h4 class="mb-1 fw-bold">Day 4 : Conference</h4>
                              <span class="fc-muted"
                                >Sunday, August 27, 2023</span
                              >
                            </div>
                          </a>
                        </li>
                      </ul>
                    </div>
                    <div
                      class="resize-sensor"
                      style="
                        position: absolute;
                        inset: 0px;
                        overflow: hidden;
                        z-index: -1;
                        visibility: hidden;
                      "
                    >
                      <div
                        class="resize-sensor-expand"
                        style="
                          position: absolute;
                          left: 0;
                          top: 0;
                          right: 0;
                          bottom: 0;
                          overflow: hidden;
                          z-index: -1;
                          visibility: hidden;
                        "
                      >
                        <div
                          style="
                            position: absolute;
                            left: 0px;
                            top: 0px;
                            transition: all 0s ease 0s;
                            width: 698px;
                            height: 425px;
                          "
                        ></div>
                      </div>
                      <div
                        class="resize-sensor-shrink"
                        style="
                          position: absolute;
                          left: 0;
                          top: 0;
                          right: 0;
                          bottom: 0;
                          overflow: hidden;
                          z-index: -1;
                          visibility: hidden;
                        "
                      >
                        <div
                          style="
                            position: absolute;
                            left: 0;
                            top: 0;
                            transition: 0s;
                            width: 200%;
                            height: 200%;
                          "
                        ></div>
                      </div>
                    </div>
                  </div>
                </div>

                <div
                  class="col-md-6 fadeIn animated"
                  data-animate="fadeIn"
                  data-delay="30"
                >

                  <div
                    id="snav-content1"
                    aria-labelledby="ui-id-1"
                    role="tabpanel"
                    class="ui-tabs-panel ui-corner-bottom ui-widget-content"
                    aria-hidden="false"
                    style=""
                    v-if="selectedTab === 'content-1'"
                  >
                    <div>
                      <h4 class="mb-4 fc-muted text-uppercase ls4 fw-normal">
                        Day 1-2 Agenda
                      </h4>
                      <div class="d-flex mb-4">
                        <div class="me-4">
                          <div
                            class="number fw-bold d-flex align-items-center justify-content-center"
                          >
                            <span>1.</span>
                          </div>
                        </div>
                        <div>
                          <h4 class="mb-1 fw-bold">Registration</h4>
                          <span class="fc-muted"
                            >Registrants will be shortlisted into 100
                            participants per track, for a total of 200
                            participants</span
                          >
                        </div>
                      </div>
                      <div class="d-flex mb-4">
                        <div class="me-4">
                          <div
                            class="number fw-bold d-flex align-items-center justify-content-center"
                          >
                            <span>2.</span>
                          </div>
                        </div>
                        <div>
                          <h4 class="mb-1 fw-bold">
                            Introducing Bio x MIT Hacking Medicine
                          </h4>
                          <span class="fc-muted"
                            >Speakers : Chief Transformation and Digital Officer
                            of Pharmaceutical SOE Holding, MoH, MoSOE, founders
                            and Chief levels of startups</span
                          >
                        </div>
                      </div>
                      <div class="d-flex mb-4">
                        <div class="me-4">
                          <div
                            class="number fw-bold d-flex align-items-center justify-content-center"
                          >
                            <span>3.</span>
                          </div>
                        </div>
                        <div>
                          <h4 class="mb-1 fw-bold">Team Formation</h4>
                          <span class="fc-muted">4-7 people per team</span>
                        </div>
                      </div>
                      <div class="d-flex mb-4">
                        <div class="me-4">
                          <div
                            class="number fw-bold d-flex align-items-center justify-content-center"
                          >
                            <span>4.</span>
                          </div>
                        </div>
                        <div>
                          <h4 class="mb-1 fw-bold">Hackathon Day 1 Start</h4>
                          <span class="fc-muted">48 hours of hacking</span>
                        </div>
                      </div>
                    </div>
                  </div>

                  <div
                    id="snav-content2"
                    aria-labelledby="ui-id-2"
                    role="tabpanel"
                    class="ui-tabs-panel ui-corner-bottom ui-widget-content"
                    aria-hidden="true"
                    v-else-if="selectedTab === 'content-2'"
                  >
                    <div>
                      <h4 class="mb-4 fc-muted text-uppercase ls4 fw-normal">
                        Agenda Day 3
                      </h4>
                      <div class="d-flex mb-4">
                        <div class="me-4">
                          <div
                            class="number fw-bold d-flex align-items-center justify-content-center"
                          >
                            <span>1.</span>
                          </div>
                        </div>
                        <div>
                          <h4 class="mb-1 fw-bold">Judges</h4>
                          <span class="fc-muted"
                            >Internal, Government and Private Sector</span
                          >
                        </div>
                      </div>
                      <div class="d-flex mb-4">
                        <div class="me-4">
                          <div
                            class="number fw-bold d-flex align-items-center justify-content-center"
                          >
                            <span>2.</span>
                          </div>
                        </div>
                        <div>
                          <h4 class="mb-1 fw-bold">Networking Dinner</h4>
                          <span class="fc-muted">Get connected with other participants, MIT Team, and mentors</span>
                        </div>
                      </div>
                    </div>
                  </div>

                  <div
                    id="snav-content3"
                    aria-labelledby="ui-id-3"
                    role="tabpanel"
                    class="ui-tabs-panel ui-corner-bottom ui-widget-content"
                    aria-hidden="true"
                    v-else-if="selectedTab === 'content-3'"
                  >
                    <div>
                      <h4 class="mb-4 fc-muted text-uppercase ls4 fw-normal">
                        Agenda Day 4
                      </h4>
                      <div class="d-flex mb-4">
                        <div class="me-4">
                          <div
                            class="number fw-bold d-flex align-items-center justify-content-center"
                          >
                            <span>1.</span>
                          </div>
                        </div>
                        <div>
                          <h4 class="mb-1 fw-bold">Conference</h4>
                          <span class="fc-muted"
                            >Gain insight from seasoned professionals</span
                          >
                        </div>
                      </div>
                      <div class="d-flex mb-4">
                        <div class="me-4">
                          <div
                            class="number fw-bold d-flex align-items-center justify-content-center"
                          >
                            <span>2.</span>
                          </div>
                        </div>
                        <div>
                          <h4 class="mb-1 fw-bold">Digital Expo</h4>
                          <span class="fc-muted"
                            >IT, Healthcare and Business Exhibition</span
                          >
                        </div>
                      </div>
                      <div class="d-flex mb-4">
                        <div class="me-4">
                          <div
                            class="number fw-bold d-flex align-items-center justify-content-center"
                          >
                            <span>3.</span>
                          </div>
                        </div>
                        <div>
                          <h4 class="mb-1 fw-bold">Workshop</h4>
                          <span class="fc-muted"
                            >On hands activities with skillful experts</span
                          >
                        </div>
                      </div>
                      <div class="d-flex mb-4">
                        <div class="me-4">
                          <div
                            class="number fw-bold d-flex align-items-center justify-content-center"
                          >
                            <span>4.</span>
                          </div>
                        </div>
                        <div>
                          <h4 class="mb-1 fw-bold">Awarding Night</h4>
                          <span class="fc-muted"
                            >Winner announcement</span
                          >
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <!-- Mobile -->
            <div class="d-md-none d-md-block">
              <div class="accordion mb-0 mt-6">
                <div
                  class="accordion-card py-3"
                >
                  <div class="accordion-header accordion-active">
                    <div class="accordion-title">
                      <a @click="setSelectedTab('content-1')" class="d-flex">
                        <div class="me-4">
                          <div class="rounded-icon">
                            <i class="bi bi-calendar"></i>
                          </div>
                        </div>

                        <div>
                          <h4 class="mb-1 fw-bold">
                            Day 1-2 : Hackathon Intro
                          </h4>
                          <span class="fc-muted"
                            >Thursday, August 24 – Friday, August 25, 2023</span
                          >
                        </div>
                      </a>
                    </div>
                    <div class="accordion-icon d-flex">
                      <i class="accordion-closed bi bi-chevron-down"></i>
                      <i class="accordion-open bi bi-chevron-up"></i>
                    </div>
                  </div>
                  <div class="accordion-content" :style="{display: selectedTab === 'content-1' ? 'block' : 'hidden'}">
                    <div class="accordion-title">
                      <h4 class="mb-4 fc-muted text-uppercase ls4 fw-normal">
                        Day 1-2 Agenda
                      </h4>
                      <div class="d-flex mb-4">
                        <div class="me-4">
                          <div
                            class="number fw-bold d-flex align-items-center justify-content-center"
                          >
                            <span>1.</span>
                          </div>
                        </div>
                        <div>
                          <h4 class="mb-1 fw-bold">Registration</h4>
                          <span class="fc-muted"
                            >Registrants will be shortlisted into 100
                            participants per track, for a total of 200
                            participants</span
                          >
                        </div>
                      </div>
                      <div class="d-flex mb-4">
                        <div class="me-4">
                          <div
                            class="number fw-bold d-flex align-items-center justify-content-center"
                          >
                            <span>2.</span>
                          </div>
                        </div>
                        <div>
                          <h4 class="mb-1 fw-bold">
                            Introducing Bio x MIT Hacking Medicine
                          </h4>
                          <span class="fc-muted"
                            >Speakers : Chief Transformation and Digital Officer
                            of Pharmaceutical SOE Holding, MoH, MoSOE, founders
                            and Chief levels of startups</span
                          >
                        </div>
                      </div>
                      <div class="d-flex mb-4">
                        <div class="me-4">
                          <div
                            class="number fw-bold d-flex align-items-center justify-content-center"
                          >
                            <span>3.</span>
                          </div>
                        </div>
                        <div>
                          <h4 class="mb-1 fw-bold">Team Formation</h4>
                          <span class="fc-muted">4-7 people per team</span>
                        </div>
                      </div>
                      <div class="d-flex mb-4">
                        <div class="me-4">
                          <div
                            class="number fw-bold d-flex align-items-center justify-content-center"
                          >
                            <span>4.</span>
                          </div>
                        </div>
                        <div>
                          <h4 class="mb-1 fw-bold">Hackathon Day 1 Start</h4>
                          <span class="fc-muted">48 hours of hacking</span>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>

                <div
                  class="accordion-card py-3"
                >
                  <div class="accordion-header">
                    <div class="accordion-title">
                      <a @click="setSelectedTab('content-2')" class="d-flex">
                        <div class="me-4">
                          <div class="rounded-icon">
                            <i class="bi bi-calendar"></i>
                          </div>
                        </div>

                        <div>
                          <h4 class="mb-1 fw-bold">Day 3 : Pitching Day</h4>
                          <span class="fc-muted"
                            >Saturday, August 26, 2023</span
                          >
                        </div>
                      </a>
                    </div>
                    <div class="accordion-icon d-flex">
                      <i class="accordion-closed bi bi-chevron-down"></i>
                      <i class="accordion-open bi bi-chevron-up"></i>
                    </div>
                  </div>
                  <div class="accordion-content" :style="{display: selectedTab === 'content-2' ? 'block' : 'hidden'}">
                    <div class="accordion-title">
                      <h4 class="mb-4 fc-muted text-uppercase ls4 fw-normal">
                        Agenda Day 3
                      </h4>
                      <div class="d-flex mb-4">
                        <div class="me-4">
                          <div
                            class="number fw-bold d-flex align-items-center justify-content-center"
                          >
                            <span>1.</span>
                          </div>
                        </div>
                        <div>
                          <h4 class="mb-1 fw-bold">Judges</h4>
                          <span class="fc-muted"
                            >Internal, Government and Private Sector</span
                          >
                        </div>
                      </div>
                      <div class="d-flex mb-4">
                        <div class="me-4">
                          <div
                            class="number fw-bold d-flex align-items-center justify-content-center"
                          >
                            <span>2.</span>
                          </div>
                        </div>
                        <div>
                          <h4 class="mb-1 fw-bold">Networking Dinner</h4>
                          <span class="fc-muted">Get connected with other participants, MIT Team, and mentors</span>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>

                <div
                  class="accordion-card py-3"
                >
                  <div class="accordion-header">
                    <div class="accordion-title">
                      <a @click="setSelectedTab('content-3')" class="d-flex">
                        <div class="me-4">
                          <div class="rounded-icon">
                            <i class="bi bi-calendar"></i>
                          </div>
                        </div>

                        <div>
                          <h4 class="mb-1 fw-bold">Day 4 : Conference</h4>
                          <span class="fc-muted">Sunday, August 27, 2023 </span>
                        </div>
                      </a>
                    </div>
                    <div class="accordion-icon d-flex">
                      <i class="accordion-closed bi bi-chevron-down"></i>
                      <i class="accordion-open bi bi-chevron-up"></i>
                    </div>
                  </div>
                  <div class="accordion-content" :style="{display: selectedTab === 'content-3' ? 'block' : 'hidden'}">
                    <div class="accordion-title">
                      <h4 class="mb-4 fc-muted text-uppercase ls4 fw-normal">
                        Agenda Day 4
                      </h4>
                      <div class="d-flex mb-4">
                        <div class="me-4">
                          <div
                            class="number fw-bold d-flex align-items-center justify-content-center"
                          >
                            <span>1.</span>
                          </div>
                        </div>
                        <div>
                          <h4 class="mb-1 fw-bold">Conference</h4>
                          <span class="fc-muted"
                            >Gain insight from seasoned professionals</span
                          >
                        </div>
                      </div>
                      <div class="d-flex mb-4">
                        <div class="me-4">
                          <div
                            class="number fw-bold d-flex align-items-center justify-content-center"
                          >
                            <span>2.</span>
                          </div>
                        </div>
                        <div>
                          <h4 class="mb-1 fw-bold">Digital Expo</h4>
                          <span class="fc-muted"
                            >IT, Healthcare and Business Exhibition</span
                          >
                        </div>
                      </div>
                      <div class="d-flex mb-4">
                        <div class="me-4">
                          <div
                            class="number fw-bold d-flex align-items-center justify-content-center"
                          >
                            <span>3.</span>
                          </div>
                        </div>
                        <div>
                          <h4 class="mb-1 fw-bold">Workshop</h4>
                          <span class="fc-muted"
                            >On hands activities with skillful experts</span
                          >
                        </div>
                      </div>
                      <div class="d-flex mb-4">
                        <div class="me-4">
                          <div
                            class="number fw-bold d-flex align-items-center justify-content-center"
                          >
                            <span>4.</span>
                          </div>
                        </div>
                        <div>
                          <h4 class="mb-1 fw-bold">Awarding Night</h4>
                          <span class="fc-muted"
                            >Winner announcement</span
                          >
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <div
            id="section-track"
            class="section parallax min-vh-100 dark m-0 border-0 d-flex track"
            data-bottom-top="background-position:0px 0px;"
            data-top-bottom="background-position:0px -200px;"
          >
            <div
              class="shape-divider"
              data-shape="wave"
              data-position="bottom"
              data-height="100"
              data-fill="#1F2642"
            ></div>
            <div class="vertical-middle">
              <div class="container" data-wow-delay="100ms">
                <div class="wow fadeInUp">
                  <h2 class="center mb-1 text-capitalize fw-bold font-body">
                    Hackathon Track
                  </h2>
                  <p class="mb-5 text-center">
                    Choose one of these options that you will tackle in the
                    event
                  </p>
                </div>

                <div class="row align-items-start gutter-40">
                  <div class="col-md-6">
                    <h2
                      class="text-capitalize fw-bold font-body mb-2 wow fadeInUp"
                      data-wow-delay="200ms"
                    >
                      Upstream
                    </h2>
                    <h4 class="mb-4 wow fadeInUp" data-wow-delay="300ms">
                      Pharmaceutical & Biotechnology
                    </h4>
                    <div class="pb-0 wow fadeInUp" data-wow-delay="400ms">
                      <p>
                        The Pharmaceutical SOE Holding, Bio Farma Group
                        (including Kimia Farma and Indofarma) is experiencing an
                        overstock of products worth 74 million USD, including
                        vaccines, drugs, and medical devices.However, despite
                        this overstock, customers often experience shortages of
                        their requested products. The Group’s supply chain data
                        is currently neither properly streamed nor uniformly
                        calculated, making it difficult to identify the root
                        cause of the problem.
                      </p>
                      <p>
                        Any kind of disruption in the supply chain could lead to
                        a domino effect, leading to unavailabity of products
                        downstream.
                      </p>
                    </div>
                  </div>

                  <div class="col-md-6">
                    <h2
                      class="text-capitalize fw-bold font-body mb-2 wow fadeInUp"
                      data-wow-delay="400ms"
                    >
                      Downstream
                    </h2>
                    <h4 class="mb-4 wow fadeInUp" data-wow-delay="500ms">
                      Healthcare Providers & Retailers
                    </h4>
                    <div class="pb-0 wow fadeInUp" data-wow-delay="600ms">
                      <p>
                        In Indonesia's e-retailing landscape, no healthcare
                        player is currently offering a comprehensive end-to-end
                        solution. There are still gaps in the business models of
                        existing players; and significant opportunities to
                        optimize sales in existing outlets by improving the
                        supply chain, packaging, and the online-to-offline
                        experience for customers and patients.
                      </p>
                      <p>
                        Most players currently also do not address the need for
                        continuity of care. Speaking of real case, Kimia Farma
                        Mobile, a mobile application by Kimia Farma, which
                        currently has a strong presence in e-pharmacy retail
                        apparently still lacking and need a lot of improvement
                        in addressing the need for continuity of care. The app
                        also in the need of more development on the
                        online-to-offline experience.
                      </p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <div
            id="section-participant"
            class="page-section participant bg-dark-2 pt-6 pb-0"
          >
            <div class="center container">
              <h5
                class="text-uppercase ls4 fw-normal mb-2 fc-secondary wow fadeInUp"
                data-wow-delay="100ms"
              >
                Participants
              </h5>
              <h2
                class="text-capitalize fw-bold font-body wow fadeInUp"
                data-wow-delay="200ms"
              >
                Participant Roles
              </h2>
              <p data-wow-delay="300ms" class="fc-muted mb-4 wow fadeInUp">
                200 international participants, from all across G20 countries
                and ASEAN member states
              </p>
            </div>

            <div class="row clearfix mt-6 bg-dark">
              <div class="row align-items-stretch">
                <!-- <div data-animate="fadeInLeft" data-delay="40" class="col-lg-4 d-none d-md-block" style="background: url('assets/images/participant.jpg') center center no-repeat; background-size: cover;"></div> -->
                <div class="col-lg-12">
                  <div class="row align-items-stretch grid-border clearfix">
                    <div
                      class="col-lg-4 col-md-6 col-padding wow fadeInUp"
                      data-wow-delay="500ms"
                    >
                      <div class="feature-box fbox-center fbox-dark fbox-plain">
                        <div class="fbox-icon">
                          <img
                            src="../frontend/assets/images/user.svg"
                            alt=""
                          />
                        </div>
                        <div class="fbox-content fbox-content-sm">
                          <h4>Business Strategists</h4>
                        </div>
                      </div>
                    </div>
                    <div
                      class="col-lg-4 col-md-6 col-padding wow fadeInUp"
                      data-wow-delay="600ms"
                    >
                      <div class="feature-box fbox-center fbox-dark fbox-plain">
                        <div class="fbox-icon">
                          <img
                            src="../frontend/assets/images/pentool.svg"
                            alt=""
                          />
                        </div>
                        <div class="fbox-content fbox-content-sm">
                          <h4>Designers</h4>
                        </div>
                      </div>
                    </div>
                    <div
                      class="col-lg-4 col-md-6 col-padding wow fadeInUp"
                      data-wow-delay="700ms"
                    >
                      <div class="feature-box fbox-center fbox-dark fbox-plain">
                        <div class="fbox-icon">
                          <img
                            src="../frontend/assets/images/user-plus.svg"
                            alt=""
                          />
                        </div>
                        <div class="fbox-content fbox-content-sm">
                          <h4>Healthcare Professionals</h4>
                        </div>
                      </div>
                    </div>
                    <div
                      class="col-lg-4 col-md-6 col-padding wow fadeInUp"
                      data-wow-delay="800ms"
                    >
                      <div class="feature-box fbox-center fbox-dark fbox-plain">
                        <div class="fbox-icon">
                          <img
                            src="../frontend/assets/images/activity.svg"
                            alt=""
                          />
                        </div>
                        <div class="fbox-content fbox-content-sm">
                          <h4>Customers / Patients</h4>
                        </div>
                      </div>
                    </div>
                    <div
                      class="col-lg-4 col-md-6 col-padding wow fadeInUp"
                      data-wow-delay="900ms"
                    >
                      <div class="feature-box fbox-center fbox-dark fbox-plain">
                        <div class="fbox-icon">
                          <img
                            src="../frontend/assets/images/briefcase.svg"
                            alt=""
                          />
                        </div>
                        <div class="fbox-content fbox-content-sm">
                          <h4>Entrepreneurs</h4>
                        </div>
                      </div>
                    </div>
                    <div
                      class="col-lg-4 col-md-6 col-padding wow fadeInUp"
                      data-wow-delay="1000ms"
                    >
                      <div class="feature-box fbox-center fbox-dark fbox-plain">
                        <div class="fbox-icon">
                          <img
                            src="../frontend/assets/images/code.svg"
                            alt=""
                          />
                        </div>
                        <div class="fbox-content fbox-content-sm">
                          <h4>Developers</h4>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <div
              class="d-none d-lg-block parallax min-vh-100 dark m-0 border-0 d-flex participant-image-desktop participant-dark-bg"
              data-bottom-top="background-position:0px 0px;"
              data-top-bottom="background-position:0px -300px;"
            ></div>
          </div>

          <div
            id="section-participant-image"
            class="page-section bg-dark-2 pb-0 pt-5 d-md-none d-md-block"
          >
            <div class="container clearfix">
              <div class="d-lg-none d-lg-block m-0 border-0">
                <img
                  src="../frontend/assets/images/participant-mobile.png"
                  alt="Participant"
                />
              </div>
            </div>
          </div>

          <div id="section-winner" class="page-section winner pt-6">
            <div class="container clearfix">
              <div class="center">
                <h5
                  class="text-uppercase ls4 fw-normal mb-2 fc-secondary wow fadeInUp"
                  data-wow-delay="100ms"
                >
                  Winners
                </h5>
                <h2
                  class="text-capitalize fw-bold font-body wow fadeInUp"
                  data-wow-delay="200ms"
                >
                  Prize for the Winners
                </h2>
              </div>

              <div class="row clearfix mt-6 gx-6">
                <!-- <div data-wow-delay="300ms" class="col-lg-6 mb-5">
                                    <img src="assets/images/winner.svg" alt="Winner">
                                </div> -->
                <div class="col-lg-6">
                  <div
                    class="d-flex align-items-center justify-content-center justify-content-lg-start mb-3 wow fadeInUp"
                    data-wow-delay="300ms"
                  >
                    <div class="prize mb-3 px-5 py-4 text-center">
                      <h4 class="mb-0 fw-bold">16,000 USD Total Prize</h4>
                    </div>
                  </div>
                  <div class="mb-5">
                    <h4
                      class="mb-3 fw-bold wow fadeInUp"
                      data-wow-delay="400ms"
                    >
                      The top 3 teams will be rewarded with:
                    </h4>
                    <div
                      class="d-flex mb-3 align-items-center wow fadeInUp"
                      data-wow-delay="500ms"
                    >
                      <div
                        class="me-3 icon d-flex align-items-center justify-content-center"
                      >
                        <i class="bi bi-check2"></i>
                      </div>
                      <span class="fc-muted"
                        >Funds and cloud vouchers worth a total of 10,000
                        USD</span
                      >
                    </div>
                    <div
                      class="d-flex mb-3 align-items-center wow fadeInUp"
                      data-wow-delay="600ms"
                    >
                      <div
                        class="me-3 icon d-flex align-items-center justify-content-center"
                      >
                        <i class="bi bi-check2"></i>
                      </div>
                      <span class="fc-muted"
                        >Sponsored implementation of their projects as a pilot
                      </span>
                    </div>
                    <div
                      class="d-flex align-items-center wow fadeInUp"
                      data-wow-delay="700ms"
                    >
                      <div
                        class="me-3 icon d-flex align-items-center justify-content-center"
                      >
                        <i class="bi bi-check2"></i>
                      </div>
                      <span class="fc-muted">Total funding of 6,000 USD </span>
                    </div>
                  </div>
                </div>
                <div class="col-lg-6">
                  <div
                    class="d-flex align-items-center justify-content-center justify-content-lg-start mb-3 wow fadeInUp"
                    data-wow-delay="300ms"
                  >
                    <div class="flight mb-3 px-5 py-4 text-center">
                      <h4 class="mb-0 fw-bold">Flight to Boston</h4>
                    </div>
                  </div>
                  <h4 class="mb-3 fw-bold wow fadeInUp" data-wow-delay="700ms">
                    Outstanding Participants
                  </h4>
                  <div
                    class="d-flex mb-3 align-items-center wow fadeInUp"
                    data-wow-delay="800ms"
                  >
                    <div
                      class="me-3 icon d-flex align-items-center justify-content-center"
                    >
                      <i class="bi bi-check2"></i>
                    </div>
                    <span class="fc-muted"
                      >A golden ticket to Boston including a flight worth 5,000
                      USD</span
                    >
                  </div>
                </div>
              </div>
            </div>
          </div>

          <div id="section-partner" class="page-section partner bg-dark pt-6">
            <div class="container clearfix">
              <div class="center">
                <h5
                  class="text-uppercase ls4 fw-normal mb-2 fc-secondary wow fadeInUp"
                  data-wow-delay="100ms"
                >
                  Partners
                </h5>
                <h2
                  class="text-capitalize fw-bold font-body wow fadeInUp"
                  data-wow-delay="200ms"
                >
                  Our Partners are Indonesia’s topmost healthcare and digital
                  Organizations & Companies
                </h2>
              </div>

              <div
                class="list clearfix mt-6 wow fadeInUp"
                data-wow-delay="300ms"
              >
                <div class="row gy-2 justify-content-center">
                  <div
                    class="col-xl-2 col-lg-3 col-md-4 col-6 p-4 center d-flex align-items-center justify-content-center"
                  >
                    <img
                      src="../frontend/assets/partners/BUMN.png"
                      alt="Image"
                    />
                  </div>
                  <div
                    class="col-xl-2 col-lg-3 col-md-4 col-6 p-4 center d-flex align-items-center justify-content-center"
                  >
                    <img
                      src="../frontend/assets/partners/biofarma.svg"
                      alt="Image"
                    />
                  </div>
                  <div
                    class="col-xl-2 col-lg-3 col-md-4 col-6 p-4 center d-flex align-items-center justify-content-center"
                  >
                    <img
                      src="../frontend/assets/partners/kimia-farma.svg"
                      alt="Image"
                    />
                  </div>
                  <div
                    class="col-xl-2 col-lg-3 col-md-4 col-6 p-4 center d-flex align-items-center justify-content-center"
                  >
                    <img
                      src="../frontend/assets/partners/indofarma.svg"
                      alt="Image"
                    />
                  </div>
                  <div
                    class="col-xl-2 col-lg-3 col-md-4 col-6 p-4 center d-flex align-items-center justify-content-center"
                  >
                    <img
                      src="../frontend/assets/partners/Mediverse.png"
                      alt="Image"
                    />
                  </div>
                  <div
                    class="col-xl-2 col-lg-3 col-md-4 col-6 p-4 center d-flex align-items-center justify-content-center"
                  >
                    <img
                      src="../frontend/assets/partners/Medevo.png"
                      alt="Image"
                    />
                  </div>
                  <div
                    class="col-xl-2 col-lg-3 col-md-4 col-6 p-4 center d-flex align-items-center justify-content-center"
                  >
                    <img
                      src="../frontend/assets/partners/Medwell.png"
                      alt="Image"
                    />
                  </div>
                  <div
                    class="col-xl-2 col-lg-3 col-md-4 col-6 p-4 center d-flex align-items-center justify-content-center"
                  >
                    <img
                      src="../frontend/assets/partners/Medbiz.png"
                      alt="Image"
                    />
                  </div>
                  <div
                    class="col-xl-2 col-lg-3 col-md-4 col-6 p-4 center d-flex align-items-center justify-content-center"
                  >
                    <img
                      src="../frontend/assets/partners/Q100.png"
                      alt="Image"
                    />
                  </div>
                  <div
                    class="col-xl-2 col-lg-3 col-md-4 col-6 p-4 center d-flex align-items-center justify-content-center"
                  >
                    <img
                      src="../frontend/assets/partners/google-cloud.svg"
                      alt="Image"
                    />
                  </div>
                  <div
                    class="col-xl-2 col-lg-3 col-md-4 col-6 p-4 center d-flex align-items-center justify-content-center"
                  >
                    <img
                      src="../frontend/assets/partners/Hello-Sehat.png"
                      alt="Image"
                    />
                  </div>
                  <div
                    class="col-xl-2 col-lg-3 col-md-4 col-6 p-4 center d-flex align-items-center justify-content-center"
                  >
                    <img
                      src="../frontend/assets/partners/Pemimpin.id.png"
                      alt="Image"
                    />
                  </div>
                  <div
                    class="col-xl-2 col-lg-3 col-md-4 col-6 p-4 center d-flex align-items-center justify-content-center"
                  >
                    <img
                      src="../frontend/assets/partners/Jabar-Digital-Service.png"
                      alt="Image"
                    />
                  </div>
                  <div
                    class="col-xl-2 col-lg-3 col-md-4 col-6 p-4 center d-flex align-items-center justify-content-center"
                  >
                    <img
                      src="../frontend/assets/partners/1001-Startup-Digital.png"
                      alt="Image"
                    />
                  </div>
                  <div
                    class="col-xl-2 col-lg-3 col-md-4 col-6 p-4 center d-flex align-items-center justify-content-center"
                  >
                    <img
                      src="../frontend/assets/partners/Agility-Transformation.png"
                      alt="Image"
                    />
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- #content end -->

      <Footer />
    </div>
    <!-- #wrapper end -->
  </div>
</template>

<script setup>
import Header from "../components/Header.vue";
import Footer from "../components/Footer.vue";

import { ref, onMounted } from 'vue'

const selectedTab = ref('')

function setSelectedTab(id){
  selectedTab.value = id
}

onMounted(()=>{
  selectedTab.value = 'content-1'
})

// import Header from './Header.vue'
// import Footer from './Footer.vue'
// export default {
//     components: { Header, Footer }
// }
</script>
