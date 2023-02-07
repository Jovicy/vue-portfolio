<template>
  <v-app
    id="home"
    :style="{ background: $vuetify.theme.themes.dark.background }"
  >
    <!-- navbar -->
    <Navbar />
    <!-- navbar -->
    <section>
      <div>
        <!-- hero-section -->
        <section class="hero">
          <div class="hero-container contains">
            <h2 class="hero-heading">hello!</h2>
            <h1 class="hero-subheading">I'm Victor</h1>
            <h3 class="position">frontend developer</h3>
            <div>
              <v-btn tile color="227909" dark>About Me</v-btn>
            </div>
          </div>
        </section>
        <!-- hero-section -->
        <!-- about section -->
        <section class="about" id="about">
          <div class="about-container">
            <div class="about-testimonial">
              <div class="skill">
                <!-- skills -->
                <div class="child bgColor1">
                  <v-icon color="#227909" x-large class="ml-3">
                    fas fa-palette
                  </v-icon>
                  <h3 class="white--text ml-3 mt-4">Front-End Development</h3>
                  <p class="grey--text ml-3 mt-6">
                    Lorem, ipsum dolor sit amet <br />
                    consectetur adipisicing elit.
                  </p>
                  <v-btn class="skill-btn" color="#227909" dark text>
                    <a href="notion.com" class="white--text">Know More</a>
                    <v-icon right> fas fa-arrow-right </v-icon>
                  </v-btn>
                </div>
                <div class="child bgColor1">
                  <v-icon color="#227909" x-large class="ml-3" dark
                    >fas fa-car</v-icon
                  >
                  <h3 class="white--text ml-3 mt-4">Front-End Development</h3>
                  <p class="grey--text ml-3 mt-6">
                    Lorem ipsum dolor sit amet <br />
                    consectetur adipisicing elit.
                  </p>
                  <v-btn class="skill-btn" color="#227909" dark text>
                    <a href="notion.com" class="white--text">Know More</a>
                    <v-icon right> fas fa-arrow-right </v-icon>
                  </v-btn>
                </div>
                <div class="child bgColor1">
                  <v-icon color="#227909" x-large class="ml-3">
                    fas fa-book
                  </v-icon>
                  <h3 class="white--text ml-3 mt-4">Front-End Development</h3>
                  <p class="grey--text ml-3 mt-6">
                    Lorem, ipsum dolor sit amet <br />
                    consectetur adipisicing elit.
                  </p>
                  <v-btn class="skill-btn" color="#227909" dark text>
                    <a href="notion.com" class="white--text">Know More</a>
                    <v-icon right> fas fa-arrow-right </v-icon>
                  </v-btn>
                </div>
              </div>
              <!-- Testimonials -->
              <div class="testimonial">
                <div class="tesimonial-cont1">
                  <h1 class="green--text text-darken-4 mt-4 number">3</h1>
                  <h3 class="white--text mt-4">Years Experience</h3>
                </div>
                <div class="tesimonial-cont2">
                  <div class="cont-child">
                    <div class="childcol">
                      <div class="child2 mButton padding bgColor1">
                        <h1 class="green--text text-darken-4">03</h1>
                        <p class="grey--text">Years Experience</p>
                      </div>
                    </div>
                    <div cols="12" class="childcol">
                      <div class="child2 padding bgColor1">
                        <h1 class="green--text text-darken-4">10</h1>
                        <p class="grey--text">Achievements</p>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="tesimonial-cont3">
                  <div class="cont-child">
                    <div class="childcol">
                      <div class="child2 mButton padding bgColor1">
                        <h1 class="green--text text-darken-4">03</h1>
                        <p class="grey--text">Years Experience</p>
                      </div>
                    </div>
                    <div cols="12" class="childcol">
                      <div class="child2 padding bgColor1">
                        <h1 class="green--text text-darken-4">10</h1>
                        <p class="grey--text">Achievements</p>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </section>
        <!-- about section -->
        <!-- project section -->
        <section class="project" id="projects">
          <div class="project-main">
            <div>
              <h4 class="white--text">FEATURED PROJECTS</h4>
              <p class="white--text">This are my featured project.</p>
            </div>
            <div>
              <v-btn
                tile
                color="#227909"
                href="https://github.com/Jovicy?tab=repositories"
                dark
                >View All</v-btn
              >
            </div>
          </div>
          <div class="project-container">
            <div class="card">
              <div class="card-img">
                <img src="4.jpg" />
              </div>
              <div class="card-title">
                <button class="card-title-btn">
                  <a
                    href="https://github.com/Jovicy?tab=repositories"
                    class="white--text"
                    >Time-Track</a
                  >
                </button>
              </div>
              <div class="card-creator">
                <img src="vicky.jpeg" class="creator-img" />
                <div class="creator-name">
                  Creation of <span class="creator">Vico</span>
                </div>
              </div>
            </div>
            <div class="card">
              <div class="card-img">
                <img src="2.jpg" />
              </div>
              <div class="card-title">
                <button class="card-title-btn">
                  <a
                    href="https://github.com/Jovicy?tab=repositories"
                    class="white--text"
                    >Time-Track</a
                  >
                </button>
              </div>
              <div class="card-creator">
                <img src="vicky.jpeg" class="creator-img" />
                <div class="creator-name">
                  Creation of <span class="creator">Vico</span>
                </div>
              </div>
            </div>
            <div class="card">
              <div class="card-img">
                <img src="1.jpg" />
              </div>
              <div class="card-title">
                <button class="card-title-btn">
                  <a
                    href="https://github.com/Jovicy?tab=repositories"
                    class="white--text"
                    >Time-Track</a
                  >
                </button>
              </div>
              <div class="card-creator">
                <img src="vicky.jpeg" class="creator-img" />
                <div class="creator-name">
                  Creation of <span class="creator">Vico</span>
                </div>
              </div>
            </div>
            <div class="card">
              <div class="card-img">
                <img src="4.jpg" />
              </div>
              <div class="card-title">
                <button class="card-title-btn">
                  <a
                    href="https://github.com/Jovicy?tab=repositories"
                    class="white--text"
                    >Time-Track</a
                  >
                </button>
              </div>
              <div class="card-creator">
                <img src="vicky.jpeg" class="creator-img" />
                <div class="creator-name">
                  Creation of <span class="creator">Vico</span>
                </div>
              </div>
            </div>
            <div class="card">
              <div class="card-img">
                <img src="3.jpg" />
              </div>
              <div class="card-title">
                <button class="card-title-btn">
                  <a
                    href="https://github.com/Jovicy?tab=repositories"
                    class="white--text"
                    >Time-Track</a
                  >
                </button>
              </div>
              <div class="card-creator">
                <img src="vicky.jpeg" class="creator-img" />
                <div class="creator-name">
                  Creation of <span class="creator">Vico</span>
                </div>
              </div>
            </div>
            <div class="card">
              <div class="card-img">
                <img src="2.jpg" />
              </div>
              <div class="card-title">
                <button class="card-title-btn">
                  <a
                    href="https://github.com/Jovicy?tab=repositories"
                    class="white--text"
                    >Time-Track</a
                  >
                </button>
              </div>
              <div class="card-creator">
                <img src="vicky.jpeg" class="creator-img" />
                <div class="creator-name">
                  Creation of <span class="creator">Vico</span>
                </div>
              </div>
            </div>
            <div class="card">
              <div class="card-img">
                <img src="1.jpg" />
              </div>
              <div class="card-title">
                <button class="card-title-btn">
                  <a
                    href="https://github.com/Jovicy?tab=repositories"
                    class="white--text"
                    >Time-Track</a
                  >
                </button>
              </div>
              <div class="card-creator">
                <img src="vicky.jpeg" class="creator-img" />
                <div class="creator-name">
                  Creation of <span class="creator">Vico</span>
                </div>
              </div>
            </div>
            <div class="card">
              <div class="card-img">
                <img src="4.jpg" />
              </div>
              <div class="card-title">
                <button class="card-title-btn">
                  <a
                    href="https://github.com/Jovicy?tab=repositories"
                    class="white--text"
                    >Time-Track</a
                  >
                </button>
              </div>
              <div class="card-creator">
                <img src="vicky.jpeg" class="creator-img" />
                <div class="creator-name">
                  Creation of <span class="creator">Vico</span>
                </div>
              </div>
            </div>
          </div>
        </section>
        <!-- project section -->
        <!-- Contact section -->
        <div class="contact">
          <div class="contact-cont" id="contact">
            <div class="contact-main">
              <div>
                <h1 class="white--text">
                  Let's work together on your next <br />
                  project
                </h1>
                <p class="grey--text">
                  Thanks for visiting my portfolio! Let me know if you have any
                  questions or projects you would like to discuss.
                  <br />
                </p>
              </div>
              <div>
                <v-btn tile color="#227909" dark>Contact</v-btn>
              </div>
            </div>
          </div>
        </div>
        <!-- Contact section -->
        <!-- Bottom Navigation -->
        <div class="bottom-navigation-container" dark flat>
          <div class="bottom-navigaton">
            <v-btn class="white--text" text @click="scroll('home')">Home</v-btn>
            <v-btn class="white--text" text @click="scroll('projects')">Project</v-btn>
            <v-btn class="white--text" text @click="scroll('about')">About</v-btn>
            <v-btn class="white--text" text @click="scroll('contact')">Contacts</v-btn>
          </div>
        </div>
        <!-- Bottom Navigation -->
      </div>
    </section>
    <!-- footer -->
    <Footer />
    <!-- footer -->
  </v-app>
</template>

<script>
import Navbar from "@/components/NavbarItem";
import Footer from "@/components/FooterItem";

export default {
  name: "HomeView",

  methods: {
    scroll(refName) {
      const element = document.getElementById(refName);
      element.scrollIntoView({ behavior: "smooth" });
    },
  },

  components: {
    Navbar,
    Footer,
  },
};
</script>

<style scoped>
@import "../../dist/css/app.css";
@import "../../dist/css/queries.css";
</style>