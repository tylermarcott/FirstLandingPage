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
            <div class="col-3 icon text-center">
              <i class="mdi mdi-github"></i>
            </div>
            <div class="col-3 icon text-center">
              <i class="mdi mdi-linkedin"></i>
            </div>
            <div class="col-3 icon text-center">
              <i class="mdi mdi-email"></i>
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
        <div class="col-12 summary-title text-center">
          About me
        </div>
        <div class="col-10 summary-card elevatation-2">
          <div class="row text-center p-3">
            <h3>
              Hi, I'm Tyler!
            </h3>
            <p class="p-3">
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
      <div class="row skill-stack">
        <div class="col-1">
          <img class="dev-icon" src="https://img.icons8.com/?size=96&id=PXTY4q2Sq2lG&format=png" alt="">
        </div>
        <div class="col-1">
          <img src="https://img.icons8.com/?size=96&id=20909&format=png" alt="">
        </div>
        <div class="col-1">
          <img src="https://img.icons8.com/?size=96&id=7gdY5qNXaKC0&format=png" alt="">
        </div>
        <div class="col-1">
          <img src="https://img.icons8.com/?size=96&id=rY6agKizO9eb&format=png" alt="">
        </div>
        <div class="col-1">
          <img src="https://img.icons8.com/?size=96&id=54087&format=png" alt="">
        </div>
        <div class="col-1">
          <img src="https://img.icons8.com/?size=96&id=9nLaR5KFGjN0&format=png" alt="">
        </div>
        <div class="col-1">
          <img src="https://img.icons8.com/?size=96&id=55251&format=png" alt="">
        </div>
        <div class="col-1">
          <img src="https://img.icons8.com/?size=96&id=40669&format=png" alt="">
        </div>
        <div class="col-1">
          <img src="https://img.icons8.com/?size=96&id=g9mmSxx3SwAI&format=png" alt="">
        </div>
        <div class="col-1">
          <img src="https://img.icons8.com/?size=128&id=QEQQKirln6Tf&format=png" alt="">
        </div>
        <div class="col-1 mongodb-icon">
          <img src="https://www.vectorlogo.zone/logos/mongodb/mongodb-icon.svg" alt="">
        </div>
        <div class="col-1">

        </div>







      </div>
    </section>
    <section>
      <div class="row project-background justify-content-center">
        <div class="col-10 project-card">
          Projects summaries and links will go here
        </div>
      </div>
    </section>
    <section>
      <div class="row contact-background justify-content-center">
        <div class="col-6 contact-card">

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
  color: #f0f0f0;
  margin-top: 10vh;
  margin-left: 20vh;
  font-size: 60px;
}

.summary-title {
  margin-top: 1em;
  font-size: 40px;
  color: #f0f0f0;
}

.summary-background {
  height: 70vh;
  background-color: #122331;
}

.summary-card {
  background-color: #f0f0f0;
  margin: 1em;
  border-radius: 10px;
  height: 40vh;
}

.project-background {
  height: 70vh;
  background-color: #122331;
}

.project-card {
  background-color: #f0f0f0;
  margin: 1em;
  margin-top: 4em;
  border-radius: 10px;
  height: 40vh;
}

.contact-background {
  height: 100vh;
  background-color: #010200;
}

.contact-card {
  background-color: #f0f0f0;
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
  font-size: 50px;
}

.dev-icon {
  // height: 20px;
  // width: 20px;
  cursor: pointer;
}

// .mongodb-icon {
//   height: 5vh;
// }

.dev-icon:hover {
  transform: scale(1.10);
}

.icon:hover {
  transform: scale(1.2);
}

.skill-stack {
  margin-top: 1em;
  margin-bottom: 1em;
}

.title-footer {
  color: white;
  font-size: 30px;
  margin-left: 20vh;
}
</style>
