<template>
  <div class="home">
    <v-content>
      <v-container id="sec_container" fluid fill-height>
        <v-row id="section-1" no-gutters>
          <video autoplay muted loop id="intro">
            <source src="../assets/background.mp4" type="video/mp4" />
          </video>
        </v-row>
        <!--  Starten på video CV sektion  -->
        <v-row id="videoRow">
          <v-row id="videoCV" no-gutters>
            <v-col id="videoCol" cols="12" lg="6" md="6" sm="6" xs="12">
              <v-col id="videoTextCol" cols="12" lg="6" md="5" sm="7" xs="12">
                <h2>
                  Om mig
                </h2>
                <h3 class="black--text">Adobe Premiere Pro</h3>
                <p class="black--text">
                  Hej og velkommen til mit portfolio!
                  <br />
                  Denne video er klippet samt redigeret i programmet Adobe
                  Premiere Pro. Her vil du kunne være en lille smule om mig,
                  mine interesser, hobbier, kompetencer og lidt andet.
                </p>
              </v-col>
            </v-col>

            <v-col id="youtubeCol" cols="12" lg="6" md="6" sm="6" xs="12">
              <iframe
                class="embed-responsive-item"
                id="youtubeCV"
                src="https://www.youtube.com/embed/8DAwTgAoRcM"
                allow="autoplay; encrypted-media"
                allowfullscreen
              ></iframe>
            </v-col>
          </v-row>
        </v-row>
        <!--  Alle mine projekter kommer nedenunder her  -->

        <v-row id="projects">
          <!--  Container der indeholder alle mine projekter  -->

          <v-container id="projectsContainer">
            <!--  Projekt 1 nedenfor  -->

            <v-row class="ma-0 auto">
              <v-col
                cols="12"
                lg="6"
                md="6"
                sm="6"
                xs="12"
                id="projectPictures"
              >
                <iframe
                  id="video"
                  src="https://www.youtube.com/embed/c0kDZb6SMcc"
                  allow="autoplay; encrypted-media"
                  frameborder="0"
                  allowfullscreen
                ></iframe>
              </v-col>
              <v-col
                cols="12"
                lg="6"
                md="6"
                sm="6"
                xs="12"
                id="projectText"
                class="red darken-5"
              >
                <v-col
                  style="max-width: 80%; margin:0 auto;"
                  cols="12"
                  lg="6"
                  md="3"
                  sm="5"
                  xs="12"
                >
                  <h1>
                    Animal Oddity Show
                  </h1>

                  <h3>
                    Adobe Illustrator / Character Animator / Premiere Pro
                  </h3>

                  <p>
                    I udarbejdelse af dette projekt fik vi til opgave, at lave
                    en infomercial og emnet var valgfrit.
                    <br />
                    Vores gruppe valgte at lave en infomercial om forskellige
                    dyr, hvor vi fortæller lidt om dem, imens de står på en
                    scene som et talentshow.
                  </p>
                </v-col>
              </v-col>
            </v-row>

            <!--  Projekt 2 nedenfor  -->

            <v-row class="ma-0 auto">
              <v-col
                cols="12"
                lg="6"
                md="6"
                sm="6"
                xs="12"
                id="projectText"
                class="grey darken-4
"
              >
                <v-col
                  style="max-width: 80%; margin:0 auto;"
                  cols="12"
                  lg="6"
                  md="3"
                  sm="5"
                  xs="12"
                >
                  <h1 style="font-size: 43px;">
                    Reklame film
                  </h1>

                  <h3>
                    Adobe Premiere Pro
                  </h3>

                  <p>
                    En af vores andre anden semesters opgaver, skulle vi lave en
                    reklamefilm til CMS, der skulle illustere hvad de kan lære
                    på kurset, samt hvordan de skulle håndtere kritiske
                    situationer, når de er ude på havet.
                  </p>
                </v-col>
              </v-col>
              <v-col
                cols="12"
                lg="6"
                md="6"
                sm="6"
                xs="12"
                id="projectPictures"
              >
                <iframe
                  id="video"
                  src="https://www.youtube.com/embed/ROfdiBKBTlY"
                  frameborder="0"
                  allow="autoplay; encrypted-media"
                  allowfullscreen
                ></iframe>
              </v-col>
            </v-row>

            <!--  Projekt 3 nedenfor  -->

            <v-row class="ma-0 auto">
              <v-col
                cols="12"
                lg="6"
                md="6"
                sm="6"
                xs="12"
                id="projectPictures"
              >
                <iframe
                  id="video"
                  src="https://www.youtube.com/embed/VaDvrAkslCk"
                  frameborder="0"
                  allow="autoplay; encrypted-media"
                  allowfullscreen
                ></iframe>
              </v-col>
              <v-col
                cols="12"
                lg="6"
                md="6"
                sm="6"
                xs="12"
                id="projectText"
                class="red darken-5"
              >
                <v-col
                  style="max-width: 80%; margin:0 auto;"
                  cols="12"
                  lg="6"
                  md="3"
                  sm="5"
                  xs="12"
                >
                  <h1>
                    Commercial
                  </h1>

                  <h3>
                    Adobe Premiere Pro
                  </h3>

                  <p>
                    Som et af vores første projekter i AV, skulle vi lave en
                    kort reklame, hvor af vores gruppe lavede denne sjove video
                    som skulle være en extension til tinder, vi kaldte dette
                    produkt snifter.
                  </p>
                </v-col>
              </v-col>
            </v-row>

            <!--  Projekt 4 nedenfor  -->

            <v-row class="ma-0 auto">
              <v-col
                cols="12"
                class="grey darken-4"
                lg="6"
                md="6"
                sm="6"
                xs="12"
                id="projectText"
              >
                <v-col
                  style="max-width: 80%; margin:0 auto;"
                  cols="12"
                  lg="6"
                  md="3"
                  sm="5"
                  xs="12"
                >
                  <h1>
                    Scene Recreation
                  </h1>

                  <h3>
                    Adobe Premiere Pro
                  </h3>

                  <p>
                    Derudover har vi fået denne her sjove opgave, hvor vi skulle
                    genskabe hvilken som helst scene. Vi fik en begrænset mængde
                    tid, hvor vores gruppe valgte at lave danse scenen fra
                    filmen Joker.
                  </p>
                </v-col>
              </v-col>
              <v-col
                cols="12"
                lg="6"
                md="6"
                sm="6"
                xs="12"
                id="projectPictures"
              >
                <iframe
                  id="video"
                  src="https://www.youtube.com/embed/aMF6Mrzyy04"
                  frameborder="0"
                  allow="autoplay; encrypted-media"
                  allowfullscreen
                ></iframe>
              </v-col>
            </v-row>
          </v-container>
        </v-row>
      </v-container>
    </v-content>
  </div>
</template>

<script>
export default {
  name: "Home",
  components: {},
};
</script>

<style lang="scss">
@import url("https://use.typekit.net/bwi1epw.css");

#sec_container {
  padding: 0;
  margin: 0;
}

#section-1 {
  width: 100vw;
  margin-top: -64px;
}

#intro {
  width: 100%;
}

#videoRow {
  width: 80%;
  max-width: 80%;
  margin: 0 auto;
  background-color: white;
}

#videoCV {
  height: 100vh;
  width: 100vw;
}

#videoCol {
  margin: 0;
  padding: 0;
  display: flex;
  align-items: center;
  justify-content: center;
  width: 50%;
}

#videoTextCol {
  max-width: 80%;
}

#youtubeCol {
  margin: 0;
  padding: 0;
  display: flex;
  align-items: center;
  width: 50%;
}

#video {
  width: 100%;
  height: 100%;
}

#youtubeCV {
  width: 100%;
  height: 60vh;
}

#projects {
  width: 80%;
  max-width: 80%;
  margin: 0 auto;
  background-color: white;
}

#projectsContainer {
  padding: 0;
  margin: 0;
  width: 100%;
  max-width: 100%;
  height: 100%;
}

#img {
  height: 450px;
  object-fit: contain;
}

#projectPictures {
  overflow: hidden;
  height: 450px;
  margin: 0;
  padding: 0;
  width: 50%;
}

#projectText {
  height: 450px;
  background-color: #616161;
  margin: 0;
  padding: 0;
  display: flex;
  align-items: center;
  width: 50%;
}

h1 {
  text-align: left;
  font-size: 45px;
  text-transform: uppercase;
  font-weight: 800;
  line-height: 48px;
  color: white;
}
h2 {
  text-align: left;
  font-size: 30px;
  text-transform: uppercase;
}

h3 {
  text-align: left;
  color: white;
  font-size: 14px;
}

p {
  color: white;
  font-family: bilo, sans-serif;
  font-weight: 400;
  font-style: normal;
  font-size: 14px;
  text-align: left;
  line-height: 22px;
}

a {
  font-family: bilo, sans-serif;
  font-style: regular;
  font-weight: 500;
}
</style>
