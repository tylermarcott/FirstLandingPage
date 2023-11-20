
<template>
  <div class="overflow-correction">
    <section class="header-img">
      <div class="row">
        <div class="col-12 col-md-5 title">
          Tyler Marcott
        </div>
        <div class="col-4 contact-icons">
          <div class="row text-light justify-content-end">
            <div class="col-3 text-center icon">
              <a href="https://github.com/tylermarcott" target="_blank" rel="noopener noreferrer">
                <i class="mdi mdi-github icon-color" title="Link to my GitHub!"></i>
              </a>
            </div>
            <div class="col-3 icon text-center">
              <a href="https://www.linkedin.com/in/tyler-marcott-225277204/" target="_blank" rel="noopener noreferrer">
                <i class="mdi mdi-linkedin icon-color" title="Link to my LinkedIn!"></i>
              </a>
            </div>
            <div class="col-3 icon text-center">
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
      <div class="row summary-background justify-content-center">
        <div class="col-12 summary-title">
          A little about me
        </div>
        <div class="col-10 summary-card elevation-2">
          <div class="row p-3">
            <div class="col-6">
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
            <div class="col-6 text-center mt-3 position-relative">
              <img src="../assets/img/headshot.jpg" class="headshot" alt="">
            </div>
          </div>
        </div>
        <div class="col-12 skill-stack-title">
          My Skills
        </div>
      </div>
    </section>


    <section>
      <div class="row skill-stack justify-content-between px-4">
        <div class="col-1 text-center icon-spacing">
          <span v-if="jshover" class="hover-text">
            Javascript
          </span>
          <span v-else class="placeholder">
            placeholder
          </span>
          <img @mouseover="jshover = true" @mouseleave="jshover = false" class="dev-icon"
            src="https://img.icons8.com/?size=96&id=PXTY4q2Sq2lG&format=png" alt="">
        </div>
        <div class="col-1 text-center icon-spacing">
          <span v-if="htmlhover" class="hover-text">
            HTML
          </span>
          <span v-else class="placeholder">
            placeholder
          </span>
          <img @mouseover="htmlhover = true" @mouseleave="htmlhover = false" class="dev-icon"
            src="https://img.icons8.com/?size=96&id=20909&format=png" alt="">
        </div>
        <div class="col-1 text-center icon-spacing">
          <span v-if="csshover" class="hover-text">
            CSS
          </span>
          <span v-else class="placeholder">
            placeholder
          </span>
          <img @mouseover="csshover = true" @mouseleave="csshover = false" class="dev-icon"
            src="https://img.icons8.com/?size=96&id=7gdY5qNXaKC0&format=png" alt="">
        </div>
        <div class="col-1 text-center icon-spacing">
          <span v-if="vuehover" class="hover-text">
            Vue.js
          </span>
          <span v-else class="placeholder">
            placeholder
          </span>
          <img @mouseover="vuehover = true" @mouseleave="vuehover = false" class="dev-icon"
            src="https://img.icons8.com/?size=96&id=rY6agKizO9eb&format=png" alt="">
        </div>
        <div class="col-1 text-center icon-spacing">
          <span v-if="nodehover" class="hover-text">
            Node.js
          </span>
          <span v-else class="placeholder">
            placeholder
          </span>
          <img @mouseover="nodehover = true" @mouseleave="nodehover = false" class="dev-icon"
            src="https://img.icons8.com/?size=96&id=54087&format=png" alt="">
        </div>
        <div class="col-1 text-center icon-spacing">
          <span v-if="sqlhover" class="hover-text">
            MySQL
          </span>
          <span v-else class="placeholder">
            placeholder
          </span>
          <img @mouseover="sqlhover = true" @mouseleave="sqlhover = false" class="dev-icon"
            src="https://img.icons8.com/?size=96&id=9nLaR5KFGjN0&format=png" alt="">
        </div>
        <div class="col-1 text-center icon-spacing">
          <span v-if="csharphover" class="hover-text">
            C#
          </span>
          <span v-else class="placeholder">
            placeholder
          </span>
          <img @mouseover="csharphover = true" @mouseleave="csharphover = false" class="dev-icon"
            src="https://img.icons8.com/?size=96&id=55251&format=png" alt="">
        </div>
        <div class="col-1 text-center icon-spacing">
          <span v-if="cplusplushover" class="hover-text">
            C++
          </span>
          <span v-else class="placeholder">
            placeholder
          </span>
          <img @mouseover="cplusplushover = true" @mouseleave="cplusplushover = false" class="dev-icon"
            src="https://img.icons8.com/?size=96&id=40669&format=png" alt="">
        </div>
        <div class="col-1 text-center icon-spacing">
          <span v-if="bshover" class="hover-text">
            Bootstrap
          </span>
          <span v-else class="placeholder">
            placeholder
          </span>
          <img @mouseover="bshover = true" @mouseleave="bshover = false" class="dev-icon"
            src="https://img.icons8.com/?size=96&id=g9mmSxx3SwAI&format=png" alt="">
        </div>
        <div class="col-1 mongodb-icon text-center icon-spacing">
          <span v-if="mongohover" class="hover-text">
            MongoDB
          </span>
          <span v-else class="placeholder">
            placeholder
          </span>
          <img @mouseover="mongohover = true" @mouseleave="mongohover = false" class="dev-icon"
            src="https://img.icons8.com/?size=96&id=74402&format=png" alt="">
        </div>
        <div class="col-1 text-center icon-spacing">
          <span v-if="awshover" class="hover-text">
            AWS
          </span>
          <span v-else class="placeholder">
            placeholder
          </span>
          <img @mouseover="awshover = true" @mouseleave="awshover = false" class="dev-icon aws-icon"
            src="https://img.icons8.com/?size=128&id=wU62u24brJ44&format=png" alt="">
        </div>
        <div class="col-1 text-center icon-spacing">
          <span v-if="dockerhover" class="hover-text">
            Docker
          </span>
          <span v-else class="placeholder">
            placeholder
          </span>
          <img @mouseover="dockerhover = true" @mouseleave="dockerhover = false" class="dev-icon"
            src="https://img.icons8.com/?size=96&id=22813&format=png" alt="">
        </div>
      </div>
    </section>


    <!-- FIXME: need to add media queries to compensate for smaller screen sizes, on Sam's laptop, she said that the images are skewed. I need to size these down. See the screenshots that she sent to you. -->

    <section>
      <div class="row project-background justify-content-center">
        <div class="col-12 project-title">
          My Portfolio
        </div>
        <div class="col-10 project-card">
          <div class="row mt-5 mb-5 single-project">
            <div class="col-6 project-container">
              <div class="project-image-left absolute-left project-hover stackify-img">
              </div>
              <a href="https://github.com/tylermarcott/StackifyCapstone" target="_blank" rel="noopener noreferrer">
                <i class="mdi mdi-github stackify-links" title="Link to Stackify on GitHub!"></i>
              </a>
            </div>
            <div class="col-6">
              <div class="row project-description">
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
                  backend, with MongoDB for database storage.
                </p>
              </div>
            </div>
          </div>


          <div class="row mb-5 single-project">
            <div class="col-6">
              <div class="row project-description">
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
            </div>
            <div class="col-6 keepr-container">
              <div class="project-image-right keepr-img">
              </div>
              <a href="https://github.com/tylermarcott/KeeprFinalCheckpoint" target="_blank" rel="noopener noreferrer">
                <i class="mdi mdi-github keepr-links" title="Link to Keepr on GitHub!"></i>
              </a>
            </div>
          </div>


          <div class="row mb-5 single-project">
            <div class="col-6 scarest-container">
              <div class="project-image-left-ss absolute-left-altered scarest-img">
              </div>
              <a href="https://github.com/tylermarcott/KeeprFinalCheckpoint" target="_blank" rel="noopener noreferrer">
                <i class="mdi mdi-github scarest-links" title="Link to Scare St. on GitHub!"></i>
              </a>
            </div>
            <div class="col-6">
              <div class="row project-description">
                <h3 class="fst-italic">
                  Scare St.
                </h3>
                <p class="ms-2">
                  Scare St. is trivia-based horror game where the user chooses a character and tries to make it through
                  all the houses on Scare St. In each house, users are prompted with various sets of horror-based trivia
                  questions. Answer 3 questions right to move on to the next house. Answering wrong questions will
                  subtract courage from your courage bar. If your courage is depleted, you run back to the beginning. This
                  application was built at a Halloween Hackathon by a team 4 under a tight deadline.
                </p>
                <p class="ms-2">
                  Scare st. uses of a Vue.js front end that utilizes a movie trivia API, and a Node.js backend and MongoDB
                  database for storing player high scores.
                </p>
              </div>
            </div>
          </div>


          <div class="row single-project">
            <div class="col-6">
              <div class="row project-description">
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
            </div>
            <div class="col-6 tower-container">
              <div class="project-image-right absolute-right tower-img">
              </div>
              <a href="https://github.com/tylermarcott/KeeprFinalCheckpoint" target="_blank" rel="noopener noreferrer">
                <i class="mdi mdi-github tower-links" title="Link to Tower on GitHub!"></i>
              </a>
            </div>
          </div>
          <h3 class="contact-title">
            Contact me!
          </h3>
        </div>
      </div>
    </section>

    <!-- FIXME: put contact me outside of card to match the rest of the page, Sam says that it looks unsymmetrical bc of this. -->

    <section>
      <div class="row contact-background justify-content-center">
        <div class="col-6 contact-card">
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
      stackifyhover: false
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
  height: 100vh;
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
  transition: transform 0.3s ease-in-out; //NOTE: the ease transition needs to go on the actual class, not the hover class.
  font-size: 50px;
}

.icon-color {
  color: #2899C3;
}

.icon-color:hover {
  color: #E1D9D1;
}

.summary-title {
  padding-left: 2em;
  margin-top: 1em;
  font-size: 40px;
  font-weight: 400;
  color: #E1D9D1;
}

.summary-intro {
  font-style: italic;
}

.summary-background {
  padding: 5em;
  height: 157vh;
  background-color: #010200;
  box-shadow: 0px 0px 20px #eeececb0 inset, 0px 10px 20px 2px #eeececb0;
}

.summary-card {
  background-color: #122331;
  color: #E1D9D1;
  margin: 1em;
  padding-top: 1em;
  border-radius: 10px;
  height: 99vh;
  box-shadow: 0px 0px 8px #989696b0;
}

.summary-paragraph {
  padding-left: 1em;
  padding-right: 1em;
  padding-top: 1em;
}

.headshot {
  max-height: 75vh;
  margin-top: 5vh;
  max-width: 70vh;
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
  background-color: #122331;
  box-shadow: 0 0 2px 2px #122331;
  padding-top: 2em;
  padding-bottom: 2em;
}

.skill-stack-title {
  padding-left: 2em;
  margin-top: 3.2em;
  margin-bottom: 1em;
  font-size: 40px;
  color: #E1D9D1;
}

.project-title {
  padding-left: 2em;
  margin-top: 3.2em;
  margin-bottom: 0.5em;
  font-size: 40px;
  color: #E1D9D1;
}

.project-background {
  height: 264vh;
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
  height: 232vh;
  box-shadow: 0px 0px 8px #989696b0;
}

.single-project {
  height: 50vh;
  padding: 2em;
}

.stackify-img {
  background-image: url('../assets/img/StackifySnapshot.png');
  background-position: center;
  background-size: cover;
  height: 50vh;
  width: 80vh;
  transition: opacity 0.8s ease-in-out;
}

.keepr-img {
  background-image: url('../assets/img/KeeprSnapshot.png');
  background-position: center;
  background-size: cover;
  height: 60vh;
  width: 80vh;
  margin-left: 0.5em;
  transition: opacity 0.8s ease-in-out;
}

.scarest-img {
  background-image: url('../assets/img/ScareStSnapshot.png');
  background-position: center;
  background-size: cover;
  height: 50vh;
  width: 80vh;
  transition: opacity 0.8s ease-in-out;
}

.tower-img {
  background-image: url('../assets/img/TowerSnapshot.png');
  background-position: center;
  background-size: cover;
  height: 50vh;
  width: 80vh;
  transition: opacity 0.8s ease-in-out;
}

.project-image-left {
  max-height: 44vh;
  box-shadow: -3px -3px 8px #555353b0;
  border-radius: 3px;
  z-index: 2;
}

.project-image-left-ss {
  max-height: 43vh;
  box-shadow: -4px -4px 8px #555353b0;
  border-radius: 3px;
}

.project-image-right {
  max-height: 45vh;
  box-shadow: 5px 5px 8px #555353b0;
  border-radius: 3px;
}

.project-container {
  position: relative;
}

.project-description {
  margin-left: 1em;
}

.stackify-links {
  position: absolute;
  top: 35%;
  left: 35%;
  font-size: 70px;
  opacity: 0;
  transition: opacity 0.5s ease-in-out;
  transition: ease-in-out 0.5s;
  color: #E1D9D1;
}

.stackify-links:hover {
  transform: scale(1.15);
}

.project-container:hover .project-img {
  opacity: 0.2;
}

.project-container:hover {
  .stackify-links {
    opacity: 1;
    z-index: 3;
    cursor: pointer;
  }

  .stackify-img {
    opacity: 0.2;
  }
}

.keepr-container:hover .keepr-img {
  opacity: 0.2;
}

.keepr-container:hover {
  .keepr-links {
    opacity: 1;
    z-index: 3;
    cursor: pointer;
  }

  .keepr-img {
    opacity: 0.2;
  }
}

.keepr-container {
  position: relative;
}

.keepr-links {
  position: absolute;
  top: 35%;
  left: 55%;
  font-size: 70px;
  opacity: 0;
  transition: opacity 0.5s ease-in-out;
  transition: ease-in-out 0.5s;
  color: #E1D9D1;
}

.keepr-links:hover {
  transform: scale(1.15);
}

.scarest-container:hover .scarest-img {
  opacity: 0.2;
}

.scarest-container:hover {
  .scarest-links {
    opacity: 1;
    z-index: 3;
    cursor: pointer;
  }

  .scarest-img {
    opacity: 0.2;
  }
}

.scarest-container {
  position: relative;
}

.scarest-links {
  position: absolute;
  top: 32%;
  left: 35%;
  font-size: 70px;
  opacity: 0;
  transition: opacity 0.5s ease-in-out;
  transition: ease-in-out 0.5s;
  color: #E1D9D1;
}

.scarest-links:hover {
  transform: scale(1.15);
}

.tower-container:hover .tower-img {
  opacity: 0.2;
}

.tower-container:hover {
  .tower-links {
    opacity: 1;
    z-index: 3;
    cursor: pointer;
  }

  .tower-img {
    opacity: 0.2;
  }
}

.tower-container {
  position: relative;
}

.tower-links {
  position: absolute;
  top: 38%;
  left: 52%;
  font-size: 70px;
  opacity: 0;
  transition: opacity 0.5s ease-in-out;
  transition: ease-in-out 0.5s;
  color: #E1D9D1;
}

.tower-links:hover {
  transform: scale(1.15);
}

.contact-title {
  margin-top: 2.5em;
  margin-left: 4.5em;
}

.contact-background {
  height: 100vh;
  background-color: #010200;
}

.contact-card {
  background-color: #393d40;
  color: #E1D9D1;
  margin: 1em;
  margin-top: 4em;
  border-radius: 10px;
  height: 81.5vh;
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
}

.absolute-right {
  position: absolute;
  right: -80px;
}

.absolute-left-altered {
  position: absolute;
  left: -80px;
  bottom: 45px;
}


// NOTE: media queries, just like in plain css, have to be AFTER the styles that they are changing.
@media (min-width: 1440px) {

  .header-img {
    height: 86vh;
  }

  .headshot {
    max-height: 65vh;
    margin-top: 8vh;
    max-width: 70vh;
  }

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
}
</style>
