<template>
  <nav id="navigation">
    <v-toolbar app flat id="nav">
      <v-spacer></v-spacer>
      <v-spacer></v-spacer>
      <v-toolbar-title class="headline text-uppercase" id="nav-bar">
        <span class="font-weight-light white--text">
          <li>
            <a
              href="#videoCV"
              v-smooth-scroll="{ duration: 1000 }"
              id="link"
              class="white--text ml-5 mr-5 "
              >Om mig</a
            >
          </li>
          <li>
            <a
              href="#projects"
              v-smooth-scroll="{ duration: 1000 }"
              id="link"
              class="white--text mr-5"
              >Projekter</a
            >
          </li>
          <li>
            <a
              href="https://firebasestorage.googleapis.com/v0/b/mmd-portfolio-2020-4686e.appspot.com/o/AdnanCV.pdf?alt=media&token=c6f51d7e-f67a-4bdf-9f84-8857a32f2894"
              id="link"
              class="white--text"
              >CV</a
            >
          </li>
          <li>
            <a
              href="mailto:adna0179@easv365.dk"
              id="link"
              class="white--text ml-5"
              >Kontakt</a
            >
          </li>
        </span>
      </v-toolbar-title>
    </v-toolbar>
  </nav>
</template>

<style lang="scss">
#nav {
  background-color: #ffffff00;
}

#nav-bar {
  width: 33%;
  text-align: center;
}

#nav {
  position: relative;
  z-index: 1;
}

li {
  display: inline-block;
  color: white;
}

li #link {
  display: inline-block;
  text-decoration: none;
  color: #ffffff;
}

#link::after {
  content: "";
  display: block;
  width: 0;
  height: 2px;
  background: #ffffff;
  transition: width 0.3s;
}

#link:hover::after {
  width: 100%;
  transition: width 0.3s;
}
</style>

<script></script>
