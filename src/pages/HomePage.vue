<template>
  <!-- FIXME: make sure to remove overflow -->
  <div>
    <section class="header-img">
      <div class="row">
        <div class="col-5 title">
          Tyler Marcott
        </div>
        <div class="col-4 contact-icons">
          <div class="row text-light">
            <div class="col-3 text-center icon">
              <a href="https://github.com/tylermarcott" target="_blank" rel="noopener noreferrer">
                <i class="mdi mdi-github icon-color"></i>
              </a>
            </div>
            <div class="col-3 icon text-center">
              <a href="https://www.linkedin.com/in/tyler-marcott-225277204/" target="_blank" rel="noopener noreferrer">
                <i class="mdi mdi-linkedin icon-color"></i>
              </a>
            </div>
            <div class="col-3 icon text-center">
              <a href="mailto:tylerjmarcott@gmail.com?subject=Hello%20Tyler!&body=Hello%2C%20I'm%20interested%20in...">
                <i class="mdi mdi-email icon-color"></i>
              </a>
            </div>
          </div>
        </div>
      </div>

      <!-- FIXME: maybe invert the dark and light colors. dark background and light text, might be a little better/ easier to read...? -->

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
          About me
        </div>
        <div class="col-10 summary-card elevatation-2">
          <div class="row p-3">
            <h4>
              Hi, I'm Tyler!
            </h4>
            <p class="p-4">
              I am a junior software engineer with a passion for creativity, team work and full stack design.

              Lorem ipsum dolor sit, amet consectetur adipisicing elit. Esse sint amet tempore, in quidem cupiditate nisi
              harum, repellat odio ducimus modi dolores minima debitis consequatur? Repudiandae eveniet saepe doloremque
              nihil?
              Eveniet, ratione est, ipsum eaque eos ipsa qui voluptatum officia nam mollitia, sit necessitatibus
              voluptatibus vero. Ut dignissimos, maiores totam quaerat blanditiis, quam deleniti incidunt necessitatibus
              sint, eligendi suscipit? Quod?
              Sit eveniet praesentium alias eius facilis adipisci hic laborum velit assumenda recusandae aliquam
              cupiditate et reiciendis quisquam molestiae, itaque harum perferendis temporibus quibusdam? Beatae aut quis
              optio itaque culpa voluptate!
            </p>
          </div>
        </div>
      </div>
    </section>
    <section>
      <div class="row skill-stack justify-content-between px-3">
        <div class="col-12 skill-stack-title">
          My Skills
        </div>
        <div class="col-1">
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
          <img class="dev-icon" src="https://img.icons8.com/?size=96&id=33039&format=png" alt="">
        </div>







      </div>
    </section>
    <section>
      <div class="row project-background justify-content-center">
        <div class="col-10 project-card">
          Projects summaries and links will go here
          <div>
            Stackify
          </div>
          <div>
            Keepr
          </div>
          <div>
            Tower
          </div>
          <div>
            maybe others like scare st or allspice..? tbd
          </div>
        </div>
      </div>
    </section>
    <section>
      <div class="row contact-background justify-content-center">
        <div class="col-6 contact-card">
          <form action="">
            <div>
              <h3>
                Contact me!
              </h3>
              <div class="mb-3">
                <label for="name" class="form-label">Name</label>
                <input type="string" class="form-control" id="nameInput" required="true">
              </div>
              <div class="mb-3">
                <label for="email" class="form-label">Email</label>
                <input type="email" class="form-control" id="emailInput" required="true">
              </div>
              <div class="mb-3">
                <label for="message" class="form-label">Message</label>
                <textarea type="message" class="form-control" id="messageInput" required="true" rows="10"></textarea>
              </div>
              <button type="submit" class="btn btn-primary">Submit</button>
            </div>
          </form>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  setup() {
    return {}
  }
}
</script>



<style scoped lang="scss">
.header-img {
  background-image: url(../assets/img/laptop-background.jpg);
  background-size: contain;
  background-position: top;
  height: 100vh;
  overflow: hidden;
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

.summary-title {
  padding-left: 2em;
  margin-top: 1em;
  font-size: 40px;
  font-weight: 300;
  color: #E1D9D1;
}

.summary-background {
  height: 70vh;
  background-color: #010200;
  border: solid 1px #E1D9D1;
}

.summary-card {
  background-color: #122331;
  color: #E1D9D1;
  margin: 1em;
  border-radius: 10px;
  height: 40vh;
  border: solid 1px #E1D9D1;
}

.project-background {
  height: 70vh;
  background-color: #010200;
  border: solid 1px #E1D9D1;
}

.project-card {
  background-color: #122331;
  color: #E1D9D1;
  margin: 1em;
  margin-top: 4em;
  border-radius: 10px;
  height: 40vh;
  border: solid 1px #E1D9D1;
}

.contact-background {
  height: 100vh;
  background-color: #122331;
}

.contact-card {
  background-color: #E1D9D1;
  margin: 1em;
  margin-top: 4em;
  border-radius: 10px;
  height: 80vh;
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

.dev-icon {
  // height: 20px;
  // width: 20px;
  cursor: pointer;
}

.dev-icon:hover {
  transform: scale(1.10);
}

.icon:hover {
  transform: scale(1.2);
}

.skill-stack {
  background-color: #E1D9D1;
  padding-top: 1em;
  padding-bottom: 1em;
}

.skill-stack-title {
  padding-left: 1em;
  margin-top: 0.3em;
  font-size: 40px;
  color: #010200;
}
</style>
