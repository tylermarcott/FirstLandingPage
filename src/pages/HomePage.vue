
<template>
  <div class="overflow-correction">
    <section class="header-img">
      <div class="row">
        <div class="col-8 col-md-5 title">
          Tyler Marcott
        </div>
        <div class="col-4 col-md-4 contact-icons">
          <div class="row text-light justify-content-end">
            <div class="col-1 col-md-3 text-center icon">
              <a href="https://github.com/tylermarcott" target="_blank" rel="noopener noreferrer">
                <i class="mdi mdi-github icon-color" title="Link to my GitHub!"></i>
              </a>
            </div>
            <div class="col-1 col-md-3 icon text-center">
              <a href="https://www.linkedin.com/in/tyler-marcott-225277204/" target="_blank" rel="noopener noreferrer">
                <i class="mdi mdi-linkedin icon-color" title="Link to my LinkedIn!"></i>
              </a>
            </div>
            <div class="col-1 col-md-3 icon text-center">
              <a href="mailto:tylerjmarcott@gmail.com?subject=Hello%20Tyler!&body=Hello%2C%20I'm%20interested%20in...">
                <i class="mdi mdi-email icon-color" title="Send me an email!"></i>
              </a>
            </div>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-12">
          <p class="title-footer">
            Full Stack Software Developer
          </p>
        </div>
      </div>
    </section>



    <section>
      <div class="row summary-background justify-content-center align-items-center">
        <div class="col-12 summary-title">
          A little about me
        </div>
        <div class="col-12 col-md-10 summary-card elevation-2">
          <div class="row p-3">
            <div class="col-12 col-md-6">
              <h4 class="summary-intro">
                Hi, I'm Tyler! 👋🏼
              </h4>
              <p class="summary-paragraph">
                I am a Junior Software Developer with a passion for creativity, team work and full stack design. I
                thoroughly enjoy the process of organizing, planning and executing a project, as well as combining my
                teammate's
                ideas into a singular vision. I strive to design applications with top-tier accessibility and creativity
                centered around customer ease of use and practicality. My goal is to enhance any team with not just my
                technical skills, but also a positive and inclusive attitude.
              </p>
              <p class="summary-paragraph">
                With a background in automotive performance, I bring the organized and meticulous mindset required to work
                on high-performance vehicles into my coding practices. This results in clean, concise and reusable code,
                as well as a polished final product.
              </p>
              <p class="summary-paragraph">
                Outside of coding, I enjoy trying new recipes, losing myself in a good book, snowboarding with friends,
                playing acoustic
                guitar and more. I strive to stay healthy in body and mind, and create for myself a healthy balance
                between working and play. I believe that in order to bring your best self to the table for someone
                else, you have to take care of yourself first and foremost!
              </p>
              <p class="summary-paragraph">
                Curious to see how I can contribute to your team with my unique blend of passion, precision and
                creativity? Let's connect!
              </p>
            </div>
            <div class="col-12 col-md-6 text-center mt-3 position-relative">
              <img src="../assets/img/Headshot.jpg" class="headshot" alt="">
            </div>
          </div>
        </div>
      </div>
    </section>


    <section>
      <div class="row skill-stack justify-content-between px-4">
        <div class="col-12 skill-stack-title">
          My Skills
        </div>
        <div class="col-3 col-md-1 text-center icon-spacing">
          <span v-if="jshover" class="hover-text">
            Javascript
          </span>
          <span v-else class="placeholder">
            placeholder
          </span>
          <img @mouseover="jshover = true" @mouseleave="jshover = false" class="dev-icon"
            src="https://img.icons8.com/?size=96&id=PXTY4q2Sq2lG&format=png" alt="js-icon">
        </div>
        <div class="col-3 col-md-1 text-center icon-spacing">
          <span v-if="htmlhover" class="hover-text">
            HTML
          </span>
          <span v-else class="placeholder">
            placeholder
          </span>
          <img @mouseover="htmlhover = true" @mouseleave="htmlhover = false" class="dev-icon"
            src="https://img.icons8.com/?size=96&id=20909&format=png" alt="html-icon">
        </div>
        <div class="col-3 col-md-1 text-center icon-spacing">
          <span v-if="csshover" class="hover-text">
            CSS
          </span>
          <span v-else class="placeholder">
            placeholder
          </span>
          <img @mouseover="csshover = true" @mouseleave="csshover = false" class="dev-icon"
            src="https://img.icons8.com/?size=96&id=7gdY5qNXaKC0&format=png" alt="">
        </div>
        <div class="col-3 col-md-1 text-center icon-spacing">
          <span v-if="vuehover" class="hover-text">
            Vue.js
          </span>
          <span v-else class="placeholder">
            placeholder
          </span>
          <img @mouseover="vuehover = true" @mouseleave="vuehover = false" class="dev-icon"
            src="https://img.icons8.com/?size=96&id=rY6agKizO9eb&format=png" alt="">
        </div>
        <div class="col-3 col-md-1 text-center icon-spacing">
          <span v-if="nodehover" class="hover-text">
            Node.js
          </span>
          <span v-else class="placeholder">
            placeholder
          </span>
          <img @mouseover="nodehover = true" @mouseleave="nodehover = false" class="dev-icon"
            src="https://img.icons8.com/?size=96&id=54087&format=png" alt="">
        </div>
        <div class="col-3 col-md-1 text-center icon-spacing">
          <span v-if="sqlhover" class="hover-text">
            MySQL
          </span>
          <span v-else class="placeholder">
            placeholder
          </span>
          <img @mouseover="sqlhover = true" @mouseleave="sqlhover = false" class="dev-icon"
            src="https://img.icons8.com/?size=96&id=9nLaR5KFGjN0&format=png" alt="">
        </div>
        <div class="col-3 col-md-1 text-center icon-spacing">
          <span v-if="csharphover" class="hover-text">
            C#
          </span>
          <span v-else class="placeholder">
            placeholder
          </span>
          <img @mouseover="csharphover = true" @mouseleave="csharphover = false" class="dev-icon"
            src="https://img.icons8.com/?size=96&id=55251&format=png" alt="">
        </div>
        <div class="col-3 col-md-1 text-center icon-spacing">
          <span v-if="cplusplushover" class="hover-text">
            C++
          </span>
          <span v-else class="placeholder">
            placeholder
          </span>
          <img @mouseover="cplusplushover = true" @mouseleave="cplusplushover = false" class="dev-icon"
            src="https://img.icons8.com/?size=96&id=40669&format=png" alt="">
        </div>
        <div class="col-3 col-md-1 text-center icon-spacing">
          <span v-if="bshover" class="hover-text">
            Bootstrap
          </span>
          <span v-else class="placeholder">
            placeholder
          </span>
          <img @mouseover="bshover = true" @mouseleave="bshover = false" class="dev-icon"
            src="https://img.icons8.com/?size=96&id=g9mmSxx3SwAI&format=png" alt="">
        </div>
        <div class="col-3 col-md-1 mongodb-icon text-center icon-spacing">
          <span v-if="mongohover" class="hover-text">
            MongoDB
          </span>
          <span v-else class="placeholder">
            placeholder
          </span>
          <img @mouseover="mongohover = true" @mouseleave="mongohover = false" class="dev-icon"
            src="https://img.icons8.com/?size=96&id=74402&format=png" alt="">
        </div>
        <div class="col-3 col-md-1 text-center icon-spacing">
          <span v-if="awshover" class="hover-text">
            AWS
          </span>
          <span v-else class="placeholder">
            placeholder
          </span>
          <img @mouseover="awshover = true" @mouseleave="awshover = false" class="dev-icon aws-icon"
            src="https://img.icons8.com/?size=128&id=wU62u24brJ44&format=png" alt="">
        </div>
      </div>
    </section>



    <!-- FIXME: it looks pretty good right now in almost all sizes, but the github buttons are being wonky now. They aren't adjusting position absolute. Need to figure out why. -->
    <!-- NOTE: it also needs a lot of work on mobile. The changes I have made for non mobile have messed up stuff in mobile pretty good lol -->

    <!-- NOTE: I think the solution to the buttons is to just make it less fancy. Put the button for github and link to live sites below text, leave images static -->


    <section>
      <div class="row project-background justify-content-center">
        <div class="col-12 project-title">
          My Portfolio
        </div>
        <div class="col-12 col-md-10 project-card">
          <div class="row mt-5 mb-5 align-items-center">
            <div class="col-5 relative-container">
              <div class="absolute-left project-hover stackify-img">
              </div>
            </div>
            <div class="col-12 col-md-7 project-spacing">
              <div class="row ms-3 me-1">
                <h3 class="fst-italic">
                  Stackify
                </h3>
                <p class="ms-2">
                  Stackify is a full-stack application designed to help amateur event planners and DJs manage their
                  event's music selection. Users can create events, then create playlists inside their events. The
                  playlists can be tailored to be any length, as well as integrating silent time-blocks for when they need
                  a length of time without music playing in their event.
                </p>
                <p class="ms-2">
                  Stackify is integrated with Spotify's API and PKCE auth, which allows the user to log directly into
                  their
                  Spotify Premium account within the application. Stackify utilizes a Vue.js front-end and a Node.js
                  backend, with MongoDB for database storage. This application is hosted using Render.
                </p>
              </div>
              <div class="row align-items-center ms-2">
                <div class="col-1 text-end github-links me-4">
                  <a href="https://github.com/tylermarcott/StackifyCapstone" target="_blank" rel="noopener noreferrer">
                    <i class="mdi mdi-github icon-color" title="Link to Stackify on GitHub!"></i>
                  </a>
                </div>
                <div class="col-6">
                  <a href="https://stackify-jch3.onrender.com/#/" target="_blank" rel="noopener noreferrer">
                    <p class="btn btn-default live-site-button" title="View the site live!">
                      View Live Site
                    </p>
                  </a>
                </div>
              </div>
            </div>
          </div>


          <div class="row pb-5">
            <div class="col-12 col-md-7 project-spacing">
              <div class="row me-3 ms-1">
                <h3 class="fst-italic">
                  Keepr
                </h3>
                <p class="ms-2">
                  Keepr is a social media application twist on Pinterest. Users are able to view other user's Keeps
                  (photos with a caption) and Vaults (collections of keeps). If the user creates an account, they have the
                  ability to create and manage their own keeps and vaults, as well as edit various account details.
                </p>
                <p class="ms-2">
                  Keepr uses a Vue.js front end with a C# .NET backend, and a mySQL database maintained from an EC2/ AWS
                  server.
                </p>
              </div>
              <div class="row ms-5">
                <div class="col-1 text-center github-links">
                  <a href="https://github.com/tylermarcott/KeeprFinalCheckpoint" target="_blank" rel="noopener noreferrer">
                    <i class="mdi mdi-github icon-color" title="Link to Keepr on GitHub!"></i>
                  </a>
                </div>
              </div>
            </div>
            <div class="col-5 relative-container">
              <div class="project-image-right absolute-right keepr-img">
              </div>
            </div>
          </div>


          <div class="row pt-5">
            <div class="col-12 col-md-5 relative-container">
              <div class="absolute-left-altered tower-img">
              </div>
            </div>
            <div class="col-12 col-md-7 project-spacing">
              <div class="row ms-3 tower-adjust">
                <h3 class="fst-italic">
                  Tower
                </h3>
                <p class="ms-2">
                  Tower is a full-stack independently built event based application, where users can create and manage
                  events, as well as purchase tickets to other people's events.
                </p>
                <p class="ms-2">
                  Tower uses a Vue.js front end and a Node.js backend with a MongoDB database.
                </p>
              </div>
              <div class="row ms-5">
                <div class="col-1 text-center github-links">
                  <a href="https://github.com/tylermarcott/TowerCheckpoint" target="_blank" rel="noopener noreferrer">
                    <i class="mdi mdi-github icon-color" title="Link to Tower on GitHub!"></i>
                  </a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section>
      <div class="row contact-background justify-content-center">
        <div class="col-9">
          <h3 class="contact-title">
            Contact me!
          </h3>
        </div>
        <div class="col-10 col-md-6 contact-card">
          <form ref="form" @submit.prevent="sendEmail">
            <div>
              <div class="m-3">
                <label for="name" class="form-label">Name</label>
                <input type="text" name="from_name" v-model="name" required="true" class="form-control input-color">
              </div>
              <div class="m-3">
                <label for="email" class="form-label">Email</label>
                <input type="email" name="from_email" v-model="email" required="true" class="form-control input-color">
              </div>
              <div class="m-3">
                <label for="message" class="form-label">Message</label>
                <textarea name="message" class="form-control input-color" v-model="message" required="true"
                  rows="10"></textarea>
              </div>
              <button type="submit" value="Send" class="btn btn-primary ms-3">Submit</button>
            </div>
          </form>
        </div>
      </div>
    </section>
  </div>
</template>


<script>
import emailjs from '@emailjs/browser';
import { logger } from "../utils/Logger.js";
import Pop from "../utils/Pop.js";
export default {
  data() {
    return {
      name: '',
      email: '',
      message: '',
      jshover: false,
      htmlhover: false,
      csshover: false,
      vuehover: false,
      nodehover: false,
      sqlhover: false,
      csharphover: false,
      cplusplushover: false,
      bshover: false,
      mongohover: false,
      awshover: false,
      dockerhover: false,
    }
  },
  methods: {
    sendEmail() {
      emailjs.sendForm('tylers_service', 'template_r85grzq', this.$refs.form, 'RRmplMbCGEcvXHOSX')
        .then((result) => {
          logger.log('Successful email sent!', result.text);
          Pop.toast('Thanks for sending me a message, I will respond as soon as I can!', 'success', 'top')
        }, (error) => {
          logger.log('The email did not send, check logs.', error.text);
        });
      this.name = '',
        this.email = '',
        this.message = ''
    }
  }
}
</script>



<style scoped lang="scss">
.overflow-correction {
  overflow: hidden;
}

.header-img {
  background-image: url(../assets/img/laptop-background.jpg);
  background-size: contain;
  background-position: top;
  height: 90vh;
  box-shadow: 0px -15px 15px 0px #414141b0 inset;
}

.title {
  color: #E1D9D1;
  margin-top: 10vh;
  margin-left: 20vh;
  font-size: 70px;
  font-family: 'Times New Roman', Times, serif;
}

.title-footer {
  color: #E1D9D1;
  font-size: 40px;
  margin-left: 20vh;
  font-family: 'Times New Roman', Times, serif;
  font-style: italic;
}

.contact-icons {
  margin-top: 11vh;
}

.icon {
  cursor: pointer;
  transition: transform 0.7s ease-in-out; //NOTE: the ease transition needs to go on the actual class, not the hover class.
  font-size: 50px;
}

.icon-color {
  color: #2899C3;
}

.icon-color:hover {
  color: #E1D9D1;
}

.summary-title {
  padding-left: 1em;
  font-size: 40px;
  font-weight: 400;
  color: #E1D9D1;
}

.summary-intro {
  font-style: italic;
}

.summary-background {
  padding: 5em;
  height: auto;
}

.summary-card {
  background-color: #122331;
  color: #E1D9D1;
  margin: 1em;
  padding-top: 1em;
  border-radius: 10px;
  // min-height: 110vh;
  height: auto;
  box-shadow: 0px 0px 8px #989696b0;
}

.summary-paragraph {
  padding-left: 1em;
  padding-right: 1em;
  padding-top: 1em;
}

.headshot {
  // max-height: auto;
  max-width: 80%;
  margin-top: 17vh;
  border-radius: 10px;
}

.placeholder {
  opacity: 0;
}

.hover-text {
  opacity: 1;
  color: #E1D9D1;
  font-family: 'Times New Roman', Times, serif;
  font-size: 20px;
  transition: opacity 0.5s ease, transform 0.5s ease;
}

.dev-icon {
  cursor: pointer;
  transition: transform 0.5s ease-in-out;
}

.dev-icon:hover {
  transform: scale(1.10);
}

.icon:hover {
  transform: scale(1.2);
}

.icon-spacing {
  height: 20vh;
}

.aws-icon {
  max-width: 13vh;
}

.skill-stack {
  height: auto;
  background-color: #122331;
  box-shadow: 0 0 2px 2px #122331;
  padding-top: 1em;
  padding-bottom: 2em;
}

.skill-stack-title {
  padding-left: 2em;
  font-size: 40px;
  color: #E1D9D1;
}

.project-title {
  padding-left: 2em;
  margin-top: 2em;
  margin-bottom: 0.5em;
  font-size: 40px;
  color: #E1D9D1;
}

.project-background {
  height: auto;
  padding-left: 5em;
  padding-right: 5em;
  background-color: #010200;
  box-shadow: 0px 15px 30px -10px #989696b0 inset;
}

.project-card {
  background-color: #122331;
  color: #E1D9D1;
  margin-left: 1em;
  margin-right: 1em;
  margin-bottom: 1em;
  border-radius: 10px;
  padding-bottom: 7em;
  height: auto;
  box-shadow: 0px 0px 8px #989696b0;
}

.stackify-img {
  background-image: url('../assets/img/StackifySnapshot.png');
  background-position: center;
  background-size: cover;
  height: 35vh;
  aspect-ratio: 1.8/1;
  transition: opacity 0.8s ease-in-out;
  box-shadow: -3px -3px 8px #555353b0;
  border-radius: 3px;
  z-index: 2;
}

.keepr-img {
  background-image: url('../assets/img/KeeprSnapshot.png');
  background-position: center;
  background-size: cover;
  height: 35vh;
  aspect-ratio: 1.8/1;
  margin-left: 0.5em;
  margin-top: 1em;
  transition: opacity 0.8s ease-in-out;
  box-shadow: 5px 5px 8px #555353b0;
  border-radius: 3px;
}

.tower-img {
  background-image: url('../assets/img/TowerSnapshot.png');
  background-position: center;
  background-size: cover;
  height: 35vh;
  aspect-ratio: 1.8/1;
  transition: opacity 0.8s ease-in-out;
  box-shadow: -4px -4px 8px #555353b0;
  border-radius: 3px;
}

.live-site-button{
  margin: 0px;
  border-radius: 5px;
  background-color: #393d40;
  color: #E1D9D1;
  transition: all 0.7s;
}

.live-site-button:hover{
  transform: scale(1.1);
}

.github-links{
  font-size: 50px;
  transition: all 0.7s;
}

.github-links:hover{
  transform: scale(1.2);
}

.relative-container {
  position: relative;
}

.contact-title {
  color: #E1D9D1;
}

.contact-background {
  height: auto;
  background-color: #010200;
}

.contact-card {
  background-color: #393d40;
  color: #E1D9D1;
  margin: 1em;
  padding-bottom: 1em;
  border-radius: 10px;
  height: auto;
  box-shadow: 0px 0px 8px #989696b0;
}

input:required {
  border: 1px solid #ccc;
  outline: none;
}

textarea:required {
  border: 1px solid #ccc;
  outline: none;
}

.input-color {
  background-color: rgb(214, 214, 214);
}

.absolute-left {
  position: absolute;
  left: -80px;
  top: -120px;
}

.absolute-right {
  position: absolute;
  right: -80px;
}

.absolute-left-altered {
  position: absolute;
  left: -80px;
}


// NOTE: media queries, just like in plain css, have to be AFTER the styles that they are changing.
@media (max-width: 1440px) {

  .project-image-left {
    max-height: 40vh;
    max-width: 70vh;
  }

  .project-image-right {
    max-height: 40vh;
    max-width: 70vh;
  }

  .project-image-left-ss {
    max-height: 40vh;
    max-width: 70vh;
  }

  .project-image-right {
    max-height: 40vh;
    max-width: 70vh;
  }

  .contact-title {
    margin-top: 3.5em;
    margin-left: 4.5em;
  }

  .contact-title {
    margin-top: 3em;
  }
}



// FIXME: I think pretty much all I need to fix at this point is the project images in mobile.

@media (max-width: 450px) {
  .header-img {
    height: 34vh;
  }

  .title {
    color: #E1D9D1;
    margin-top: -0.6vh;
    font-size: 40px;
    font-family: 'Times New Roman', Times, serif;
    margin-left: 1vh;
  }

  .contact-icons {
    margin-top: -11vh;
    margin-left: 33vh;
  }

  .icon {
    padding: 20px;
    font-size: 30px;
  }

  .title-footer {
    font-size: 25px;
    margin-top: -3vh;
    margin-left: 2vh;
  }

  .summary-title {
    padding: 0vh;
    margin-top: 0vh;
    font-size: 30px;
  }

  .summary-background{
    padding: 2em;
  }

  .summary-card {
    margin: 0.5vh;
    padding-top: 0em;
  }

  .headshot{
    margin-top: 0em;
    margin-bottom: 1em;
  }


  .summary-paragraph {
    padding-left: 0em;
    padding-right: 0em;
    padding-top: 1em;
  }

  .skill-stack-title {
    padding-left: 0em;
    margin-top: 1em;
    margin-bottom: 2em;
    font-size: 30px;
    height: 0vh;
  }

  .skill-stack {
    padding-top: 0em;
    padding-bottom: 1em;
  }

  .relative-container {
    position: static;
  }

  .project-background {
    padding-left: 2em;
    padding-right: 2em;
  }

  .project-card {
    margin-left: 0em;
    margin-right: 0em;
  }

  .project-title {
    padding-left: 0.2em;
    margin-top: 1.2em;
    margin-bottom: 0.4em;
    font-size: 30px;
  }
}

  // FIXME: why the fuck is this altering my full sized screen styling, need to look into this, noootttt ok lolol

  // NOTE: might be an issue with min vs max. Need to mess around with this a bit.

  // .project-spacing{
  //   padding-bottom: 10em;
  // }

  // .absolute-left{
  //   left: 0px;
  //   top: 100px;
  // }

@media (max-width: 375px) {}
</style>
