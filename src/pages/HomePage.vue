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
    <section class="container">
      <div class="row summary-card">
        <div>
          Summary/ about section
        </div>
      </div>
    </section>
    <section>
      <div class="row">
        <div>
          Projects summaries and links will go here
        </div>
      </div>
    </section>
    <section>
      <div class="row">
        <div>
          Section with list of skills and associated icons will go here
        </div>
      </div>
    </section>
    <section>
      <div class="row">
        <div>
          contanct info down here, either put links to email, linkedin and github at top or bottom
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
  background-image: url('https://images.unsplash.com/photo-1531297484001-80022131f5a1?auto=format&fit=crop&q=80&w=2020&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D');
  background-size: contain;
  height: 150vh;
  overflow: hidden;
}

.title {
  color: white;
  margin-top: 10vh;
  margin-left: 20vh;
  font-size: 60px;
}

.summary-card {
  height: 50vh;
}

.contact-icons {
  margin-top: 11vh;
}

.icon {
  cursor: pointer;
  font-size: 50px;
}

.icon:hover {
  transform: scale(1.2);
}

.title-footer {
  color: white;
  font-size: 30px;
  margin-left: 20vh;
}
</style>
