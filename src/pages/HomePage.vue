


<!-- TODO NOTES;

Ok, so what left do i have to do on my landing page to make it polished?

1: add some sort of label or text that appears on hover for dev icons

2: run portfolio project descriptions through GPT and see if there needs to be any changes

3: figure out why contact form isn't working to send emails to you.

4: an overall check of spacing, spelling etc, one final comb through and maybe some peer review with Sam or one of the boys

5: add GitHub links on hover for each of the projects so people can view your code. Will need to be able to have an icon in there eventually that will take you to the app as well.


-->








<template>
  <div class="overflow-correction">
    <section class="header-img">
      <div class="row">
        <div class="col-5 title">
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
            <div class="col-6 text-center mt-3">
              <img src="../assets/img/headshot.jpg" class="headshot" alt="">
            </div>
          </div>
        </div>
        <div class="col-12 skill-stack-title">
          My Skills
        </div>
      </div>
    </section>
    <!-- TODO: I want to create an effect that shows the name of the technology on hover. I messed with it a bit but can't get it. Come back to this when you are done and work on it. -->
    <section>
      <div class="row skill-stack justify-content-between px-4">
        <!-- <div class="col-1 hover-text">
          hover test
        </div> -->
        <div class="col-1">
          <!-- <p class="hover-text">
            TEST TEXT
          </p> -->
          <img class="dev-icon" src="https://img.icons8.com/?size=96&id=PXTY4q2Sq2lG&format=png" alt="">
        </div>
        <div class="col-1">
          <img class="dev-icon" src="https://img.icons8.com/?size=96&id=20909&format=png" alt="">
        </div>
        <div class="col-1">
          <img class="dev-icon" src="https://img.icons8.com/?size=96&id=7gdY5qNXaKC0&format=png" alt="">
        </div>
        <div class="col-1">
          <img class="dev-icon" src="https://img.icons8.com/?size=96&id=rY6agKizO9eb&format=png" alt="">
        </div>
        <div class="col-1">
          <img class="dev-icon" src="https://img.icons8.com/?size=96&id=54087&format=png" alt="">
        </div>
        <div class="col-1">
          <img class="dev-icon" src="https://img.icons8.com/?size=96&id=9nLaR5KFGjN0&format=png" alt="">
        </div>
        <div class="col-1">
          <img class="dev-icon" src="https://img.icons8.com/?size=96&id=55251&format=png" alt="">
        </div>
        <div class="col-1">
          <img class="dev-icon" src="https://img.icons8.com/?size=96&id=40669&format=png" alt="">
        </div>
        <div class="col-1">
          <img class="dev-icon" src="https://img.icons8.com/?size=96&id=g9mmSxx3SwAI&format=png" alt="">
        </div>
        <div class="col-1 mongodb-icon">
          <img class="dev-icon" src="https://img.icons8.com/?size=96&id=74402&format=png" alt="">
        </div>
        <div class="col-1">
          <img class="dev-icon aws-icon" src="https://img.icons8.com/?size=128&id=wU62u24brJ44&format=png" alt="">
        </div>
        <div class="col-1">
          <img class="dev-icon" src="https://img.icons8.com/?size=96&id=22813&format=png" alt="">
        </div>
      </div>
    </section>
    <section>
      <div class="row project-background justify-content-center">
        <div class="col-12 project-title">
          My Portfolio
        </div>




        <!-- TODO: make sure you review/ correct these descriptions, these descriptions are in rough draft. -->

        <div class="col-10 project-card">
          <div class="row mt-5 mb-5 single-project">
            <div class="col-6 project-offset">
              <img src="../assets/img/StackifySnapshot.png" class="project-image-left absolute-left" alt="">
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
                  Stackify is integrated with Spotify's API and PKCE auth, which allows you to log directly into your
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
            <div class="col-6">
              <img src="../assets/img/KeeprSnapshot.png" class="project-image-right absolute-right size-adjust" alt="">
            </div>
          </div>


          <div class="row mb-5 single-project">
            <div class="col-6">
              <img src="../assets/img/ScareStSnapshot.png" class="project-image-left-ss absolute-left-altered size-adjust"
                alt="">
            </div>
            <div class="col-6">
              <div class="row project-description">
                <h3 class="fst-italic">
                  Scare St.
                </h3>
                <p class="ms-2">
                  Scare St. is trivia-based horror game where the user will choose a character and try to make it through
                  all the houses on Scare St. This application was built at a Halloween Hackathon by a team 4 under a
                  tight deadline.
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
                  Tower uses a Vue.js front end and a Node.js backend with a MongoDB database. This application is also
                  hosted using AWS, EC2, Nginx and Docker.
                </p>
              </div>
            </div>
            <div class="col-6">
              <img src="../assets/img/TowerSnapshot.png" class="project-image-right absolute-right size-adjust" alt="">
            </div>
          </div>






        </div>
      </div>
    </section>
    <!-- FIXME: add form control on here, so people can't put in BS stuff into the form fields lol. Probably will look better, who knows, maybe someone will try to mess with it as a test -->
    <section>
      <div class="row contact-background justify-content-center">
        <div class="col-6 contact-card">
          <form>
            <div>
              <h3 class="m-3">
                Contact me!
              </h3>
              <div class="m-3">
                <label for="name" class="form-label">Name</label>
                <input type="string" class="form-control" id="nameInput" v-model="name" required="true">
              </div>
              <div class="m-3">
                <label for="email" class="form-label">Email</label>
                <input type="email" class="form-control" id="emailInput" v-model="email" required="true">
              </div>
              <div class="m-3">
                <label for="message" class="form-label">Message</label>
                <textarea type="message" class="form-control" id="messageInput" v-model="message" required="true"
                  rows="10"></textarea>
              </div>
              <button type="submit" value="send" class="btn btn-primary ms-3">Submit</button>
            </div>
          </form>
        </div>
      </div>
    </section>
  </div>
</template>


<!-- FIXME: this does not work, look into why. The form submits, and the emailJS is setup and verified with my email. -->
<script>
import emailjs from 'emailjs-com';
import { logger } from "../utils/Logger.js";
export default {
  name: 'ContactUs',
  data() {
    return {
      name: '',
      email: '',
      message: ''
    }
  },
  methods: {
    sendEmail(e) {
      try {
        emailjs.sendForm('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', e.target,
          'YOUR_USER_ID', {
          name: this.name,
          email: this.email,
          message: this.message
        })
        logger.log('email was sent successfully')
      } catch (error) {
        logger.log({ error })
      }
      // Reset form field
      this.name = ''
      this.email = ''
      this.message = ''
    },
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

.dev-icon:hover .hover-text {
  visibility: visible;
  color: red;
}

.icon-color {
  color: #2899C3;
}

.icon-color:hover {
  color: #E1D9D1;
}

.hover-text {
  // visibility: hidden;
  color: white;
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

.dev-icon {
  cursor: pointer;
  transition: transform 0.3s ease-in-out; //NOTE: the ease transition needs to go on the actual class, not the hover class.
}

.dev-icon:hover {
  transform: scale(1.10);
}

.icon:hover {
  transform: scale(1.2);
}

.aws-icon {
  max-width: 13vh;
}

.skill-stack {
  background-color: #122331;
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
  box-shadow: 0px 0px 20px #eeececb0 inset;
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

.project-offset {
  position: relative;
}

.single-project {
  height: 50vh;
  padding: 2em;
}

.project-image-left {
  max-height: 43vh;
  box-shadow: -3px -3px 8px #555353b0;
  border-radius: 3px;
}

.project-image-left-ss {
  max-height: 43vh;
  box-shadow: -4px -4px 8px #555353b0;
  border-radius: 3px;
}

.project-image-right {
  max-height: 43vh;
  box-shadow: 5px 5px 8px #555353b0;
  border-radius: 3px;
}

.size-adjust {
  max-height: 40vh;
}

.project-description {
  margin-left: 1em;
}

.contact-background {
  height: 100vh;
  background-color: #122331;
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

// .hover-text {
//   position: relative;
//   op
// }

.absolute-left {
  position: absolute;
  left: -80px;
}

.absolute-right {
  position: absolute;
  right: 120px;
}

.absolute-left-altered {
  position: absolute;
  left: 120px;
}
</style>
