<template>
    <div>
        <Layout>
            <div class="header">
                <HeaderImage>
                    <g-image
                        src="~/assets/header.jpg"
                        height="1300"
                    />
                </HeaderImage>
                <FloatingImage>
                    <g-image src="~/assets/logo.png" />
                </FloatingImage>
                <p class="blurb-text"><span>Hope</span><span>Forward Movement</span><span>Joy</span></p>
            </div>
            <div class="body">
                <h1>Are you ready for change?</h1>
                <h3>Do you find yourself struggling to find your place in the world?</h3>
                <h3>Are you tired of feeling anxious, depressed, or stuck in a rut?</h3>
                <CallToAction target="https://live.vcita.com/site/kapelmentoring/action/aeyv39bga3302uxf">Schedule a free consultation!</CallToAction>
                <!-- <a
                    href="
                    https://live.vcita.com/site/kapelmentoring/online-scheduling?service=m7x4is74tiyoycz5&staff=h6qjqvcg8ccr2o4o"
                    target="blank"
                    class="livesite-schedule"
                    data-service="m7x4is74tiyoycz5"
                    data-staff="h6qjqvcg8ccr2o4o"
                >schedule</a> -->
                <div class="about">
                    <div class="headshot">
                        <g-image
                            src="~/assets/headshot1.jpg"
                            width="294"
                            height="400"
                            fit="contain"
                        />
                    </div>
                    <div class='text'>
                        <h2>I'm so glad you're here!</h2>
                        <p>My name is Mary Chambers. For the last 13 years, I have been helping others to increase their emotional and physical health.</p>
                        <p>My journey began in 1997 when I was diagnosed with a large brain tumor. Through the trials following that experience, and thanks to my God, my family, friends and mentors, I gained light and purpose.</p>
                        <p>Now, I am an active participant in life
                            and I love increasing light, truth, and awareness
                            in the world through mentoring the one.</p>
                        <p>I assist individuals in creating “a new reality” and embarking on a journey that is truly life changing.</p>
                    </div>
                </div>
                <div class="package-description">
                    <h1>What I Offer</h1>
                    <p>Through-out life, we accumulate junk – in the form of negative thoughts, emotions, and limiting beliefs. We come by this junk honestly. Some of it we were told when we were young, some of it we decided was true based on our perceptions.</p>
                    <p>As your holistic mentor, I will:
                        <ul>
                            <li>Help identify and remove blocks that are holding you back so you can move to your desired future.</li>
                            <li>Teach you to recognize your self-defeating patterns and behaviors.</li>
                            <li>Give you tools and teach you a mindset that helps you create on purpose (rather than by accident).</li>
                        </ul>
                    </p>
                </div>
                <div class="packages">
                    <div class="package">
                        <div class="background">
                            <g-image
                                src="~/assets/wildflower.jpg"
                                width="300"
                                height="400"
                            />
                        </div>
                        <div class="content">
                            <h1>Wildflower</h1>
                            <h2>3</h2>
                            <span class="description"> Holistic Mentoring Appointments</span>
                            <span class="price">$250</span>
                            <a
                                class="package-select"
                                href="https://live.vcita.com/site/kapelmentoring/online-scheduling?service=abhf6uy7tsf318sd"
                                target="_blank"
                            >Sign Up</a>
                        </div>
                    </div>
                    <div class="package">
                        <div class="background">
                            <g-image
                                src="~/assets/aspen.jpg"
                                width="300"
                                height="400"
                            />
                        </div>
                        <div class="content">
                            <h1>Aspen</h1>
                            <h2>5</h2>
                            <span class="description"> Holistic Mentoring Appointments</span>
                            <span class="price">$395</span>
                            <a
                                class="package-select"
                                href="https://live.vcita.com/site/kapelmentoring/online-scheduling?service=nstj68p96mh7werj"
                                target="_blank"
                            >Sign Up</a>
                        </div>
                    </div>
                    <div class="package">
                        <div class="background">
                            <g-image
                                src="~/assets/peak.jpg"
                                width="300"
                                height="400"
                            />
                        </div>
                        <div class="content">
                            <h1>Peak</h1>
                            <h2>7</h2>
                            <span class="description"> Holistic Mentoring Appointments</span>
                            <span class="price">$525</span>
                            <a
                                class="package-select"
                                href="https://live.vcita.com/site/kapelmentoring/online-scheduling?service=reucli7f4wcitcup"
                                target="_blank"
                            >Sign Up</a>
                        </div>
                    </div>
                </div>
                <CallToAction target="https://live.vcita.com/site/kapelmentoring/action/aeyv39bga3302uxf">Schedule a free consultation!</CallToAction>
                <div class="spacer" />
                <h1>Connect with me!</h1>
                <div class="social">
                    <a
                        href="https://www.facebook.com/kapel_mentoring/"
                        class="icon"
                    >
                        <g-image
                            src="~/assets/facebook-f.svg"
                            alt="facebook logo"
                            width="35"
                            height="35"
                        />
                    </a>
                    <a
                        href="https://www.instagram.com/kapel_mentoring/"
                        class="icon"
                    >
                        <g-image
                            src="~/assets/instagram.svg"
                            alt="instagram logo"
                            width="35"
                            height="35"
                        />
                    </a>
                    <a
                        href="mailto:kapelmentoring@gmail.com"
                        class="icon"
                    >
                        <g-image
                            src="~/assets/envelope.svg"
                            alt="facebook logo"
                            width="35"
                            height="35"
                        />
                    </a>
                </div>
                <div class="spacer" />
                <h1>Certified</h1>
                <div class="certs">
                    <g-image src="~/assets/emotion-code.jpg" />
                    <g-image src="~/assets/the-elite.png" />
                </div>
            </div>
            <Footer>
                Copyright &copy; {{year}} Kapel Mentoring. All rights reserved.
            </Footer>
        </Layout>
        <Modal
            v-if="consultationModalShow"
            @close="toggleConsultationModal(false)"
        >
            <iframe
                src="https://www.vcita.com/widgets/scheduler/exjr1p8wttxzrs1k?frontage_iframe=true"
                width="100%"
                height="508"
                frameborder="0"
                style=" "
            >
                <p>Use my online scheduling page by vCita to schedule an appointment with me:</p>
                <a href='https://www.vcita.com/v/exjr1p8wttxzrs1k/online_scheduling?frontage_iframe=true&invite=vr_sched_pb-exjr1p8wttxzrs1k'>Online Scheduling with Mary Chambers</a>
            </iframe>
        </Modal>
        <Modal
            v-if="wildflowerModalShow"
            @close="toggleWildflowerModal(false)"
        >
            <iframe
                src="https://www.vcita.com/widgets/scheduler/exjr1p8wttxzrs1k?frontage_iframe=true"
                width="100%"
                height="508"
                frameborder="0"
                style=" "
            >
                <p>Use my online scheduling page by vCita to schedule an appointment with me:</p>
                <a href='https://www.vcita.com/v/exjr1p8wttxzrs1k/online_scheduling?frontage_iframe=true&invite=vr_sched_pb-exjr1p8wttxzrs1k'>Online Scheduling with Mary Chambers</a>
            </iframe>
        </Modal>
        <Modal
            v-if="aspenModalShow"
            @close="toggleAspenModal(false)"
        >
            <iframe
                src="https://www.vcita.com/widgets/scheduler/exjr1p8wttxzrs1k?frontage_iframe=true"
                width="100%"
                height="508"
                frameborder="0"
                style=" "
            >
                <p>Use my online scheduling page by vCita to schedule an appointment with me:</p>
                <a href='https://www.vcita.com/v/exjr1p8wttxzrs1k/online_scheduling?frontage_iframe=true&invite=vr_sched_pb-exjr1p8wttxzrs1k'>Online Scheduling with Mary Chambers</a>
            </iframe>
        </Modal>
        <Modal
            v-if="peakModalShow"
            @close="togglePeakModal(false)"
        >
            <iframe
                src="https://www.vcita.com/widgets/scheduler/exjr1p8wttxzrs1k?frontage_iframe=true"
                width="100%"
                height="508"
                frameborder="0"
                style=" "
            >
                <p>Use my online scheduling page by vCita to schedule an appointment with me:</p>
                <a href='https://www.vcita.com/v/exjr1p8wttxzrs1k/online_scheduling?frontage_iframe=true&invite=vr_sched_pb-exjr1p8wttxzrs1k'>Online Scheduling with Mary Chambers</a>
            </iframe>
        </Modal>
    </div>
</template>

<script>
import HeaderImage from '../components/HeaderImage'
import FloatingImage from '../components/FloatingImage'
import CallToAction from '../components/CallToAction'
import Footer from '../components/Footer'
import TextWithBackgroundImage from '../components/TextWithBackgroundImage'
import Modal from '../components/Modal'

export default {
  metaInfo: {
    title: 'Home'
  },
  data() {
      return {
          consultationModalShow: false,
          wildflowerModalShow: false,
          aspenModalShow: false,
          peakModalShow: false,
      }
  },
  components: {
    HeaderImage,
    FloatingImage,
    CallToAction,
    Footer,
    TextWithBackgroundImage,
    Modal
  },
  computed: {
      year() {
          return new Date().getFullYear()
      }
  },
  methods: {
      toggleConsultationModal(state) {
          this.consultationModalShow = state
      },
      toggleWildflowerModal(state) {
          this.wildflowerModalShow = state
      },
      toggleAspenModal(state) {
          this.aspenModalShow = state
      },
      togglePeakModal(state) {
          this.peakModalShow = state
      }
  }
}
</script>

<style scoped>
.body {
    display: flex;
    flex-direction: column;
    align-items: center;
}
h1 {
    font-family: "Amatic SC", cursive;
    font-size: 50px;
    margin: 0;
    text-align: center;
}
h3 {
    font-size: 25px;
    margin: 15px;
    text-align: center;
}
.home-links a {
    margin-right: 1rem;
}
.spacer {
    height: 50px;
}
.about {
    display: flex;
    width: 100%;
    /* height: min-content; */
    justify-content: center;
    margin: 50px 0px;
    flex-wrap: wrap;
}
.headshot {
    margin: 15px;
}
.text {
    max-width: 500px;
    margin: 0px 15px;
}
.packages {
    display: flex;
    justify-content: space-around;
    width: 100%;
    /* margin: 25px; */
    flex-wrap: wrap;
}
.header {
    position: relative;
    font-family: "Amatic SC", cursive;
}
.blurb-text {
    position: absolute;
    top: 50%;
    left: 10%;
    width: 33%;
    max-width: 500px;
    display: flex;
    justify-content: space-between;
    font-size: 45px;
    font-weight: 600;
    color: white;
    text-shadow: 1px 1px 2px black;
}

.package {
    position: relative;
    height: 400px;
    margin: 15px;
    padding: 5px;
    border: 1px solid black;
}
/* .package:hover {
    box-shadow: 2px 2px 4px black;
} */
.package-select {
    border: 1px solid white;
    background: rgba(0, 0, 0, 0.35);
    color: white;
    padding: 0.5rem 0.75rem;
    font-size: 20px;
    margin: 15px;
    cursor: pointer;
}
.package-description {
    width: 80%;
}
.package h1 {
    text-shadow: 2px 2px 2px grey;
}
.package h2 {
    font-size: 30px;
    margin-bottom: 10px;
}
.package .content {
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    color: white;
    display: flex;
    flex-direction: column;
    align-items: center;
}
.package .description {
    text-align: center;
    font-size: 24px;
}
.package .content .price {
    margin-top: auto;
    margin-bottom: 15px;
    font-size: 24px;
    font-weight: bold;
}

.package .background {
    overflow: hidden;
    width: 100%;
    height: 100%;
    background-color: black;
}

.package img {
    opacity: 0.75;
}

.certs {
    display: flex;
    justify-content: center;
    margin: 15px;
    flex-wrap: wrap;
}

.certs img {
    margin: 15px;
}
.social {
    display: flex;
    max-width: 400px;
    width: 100%;
    justify-content: space-around;
}
.icon {
    height: 35px;
    width: 35px;
    border: 1px solid black;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 10px;
    border-radius: 100px;
}

.icon img {
    height: 100%;
}

@media screen and (max-width: 1024px) {
    .blurb-text {
        font-size: 40px;
    }
}
@media screen and (max-width: 884px) {
    .blurb-text {
        font-size: 30px;
    }
}
@media screen and (max-width: 725px) {
    .blurb-text {
        top: unset;
        max-width: unset;
        left: 0;
        justify-content: space-around;
        bottom: 0px;
        width: 100%;
        font-size: 30px;
    }
}
</style>
