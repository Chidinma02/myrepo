<template>
  <div>
    <div class="nv">
      <b-navbar toggleable="lg" class="nv pt-3 container navbar-dark">
        <b-navbar-brand href="#" class="navi">CO.</b-navbar-brand>

        <b-navbar-toggle class="tar" target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav>
            <!-- <b-nav-item href="#">Link</b-nav-item> -->
            <!-- <b-nav-item href="#" disabled>Disabled</b-nav-item> -->
          </b-navbar-nav>

          <!-- Right aligned nav items -->
          <b-navbar-nav class="ml-auto">
            <b-nav-item href="#" class="ml-5"
              ><router-link to="/" class="navi">Home</router-link></b-nav-item
            >
            <b-nav-item href="#" class="ml-5"
              ><router-link to="/about" class="navi"
                >About</router-link
              ></b-nav-item
            >
            <b-nav-item
              href="https://chidinmablog.hashnode.dev/"
              class="ml-5 navi"
            >
              Blog
            </b-nav-item>
            <b-nav-item
              href="https://github.com/Chidinma02/OkwuohaChidinma.git"
              class="ml-5 navi"
            >
              Github
            </b-nav-item>

            <a
              href="../assets/Chidinma's Resume (1).pdf"
              download
              class="btn btn-lg butt pl-3 pr-3 ml-5 navi"
              >Download Cv</a
            >
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  // props: {
  // msg: String,
  // },
  props: ["mode"],
};
</script>

<style scoped>
* {
  color: white !important;
}

.nv {
  background-color: black;
}
.butt {
  background-color: black;
  color: white;
  border: 2px solid;
  border: 1px solid #15bf50;
}
.navi {
  color: white !important;
  font-weight: bold;
}
.tar {
  background-color: black;
  color: white !important;
}
.b-nav-item {
  color: white !important;
}
</style>