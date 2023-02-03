<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark px-3 justify-content-end fixed-top">
    <div class="col-lg-1 col-md-2 col-6 text-center p-1"><span class="btn-style selectable btn">About Me</span></div>
    <div class="col-lg-1 col-md-2 col-6 text-center p-1"><span class="btn-style selectable btn">Frontend</span></div>
    <div class="col-lg-1 col-md-2 col-6 text-center p-1"><span class="btn-style selectable btn">Backend</span></div>
    <div class="col-lg-1 col-md-2 col-6 text-center p-1"><span class="btn-style selectable btn">Contact Me</span></div>
    <div class="col-lg-1 col-md-2 col-6 text-center p-1"><span  title="see linkedin"><a class="btn-style selectable btn" href="https://www.linkedin.com/in/jonathan-cronmannon-60a777219/">Jon Cron</a></span></div>
      <!-- <i class="mdi mdi-reorder-horizontal selectable" data-bs-target="#optionsOffcanvas" data-bs-toggle="offcanvas" aria-controls="offcanvasTop" type="button"></i> -->
  </nav>
</template>

<script>
export default {
  setup() {
    return {}
  },
}
</script>

<style scoped>
a:hover {
  text-decoration: none;
}

.nav-link {
  text-transform: uppercase;
}

.navbar-nav .router-link-exact-active {
  border-bottom: 2px solid var(--bs-success);
  border-bottom-left-radius: 0;
  border-bottom-right-radius: 0;
}
.navbar{
  height: 6em;
  box-shadow: 3pt 3pt 2pt rgba(31, 29, 29, 0.438);
}

@media screen and (min-width: 768px) {
  nav {
    height: 64px;
  }
}
.btn-style{
  padding: 2pt;
  font-size: large;
  color: whitesmoke;
}
.btn-style:hover{
  font-weight: bold;
  cursor: pointer;
}

</style>
