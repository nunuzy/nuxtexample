<template>
  <v-row justify="center" align="center">
    <v-col cols="12">
      <v-card class="logo py-4 d-flex justify-center">
        <!-- <NuxtLogo />
        <VuetifyLogo /> -->
        <img src="/thelorax.png" alt="banner" />
      </v-card>
      <v-card>
        <v-card-title class="headline justify-center">
          MOVIE TIME
        </v-card-title>
        <v-card-text>
          <p>
            Lorem Ipsum is simply dummy text of the printing and typesetting
            industry. Lorem Ipsum has been the industry's standard dummy text
            ever since the 1500s, when an unknown printer took a galley of type
            and scrambled it to make a type specimen book.
          </p>
          <div class="text-xs-right">
            <em><small>&mdash; ANF</small></em>
          </div>
          <v-container fluid>
            <v-row class="gap-4">
              <v-card class="mx-auto" max-width="300">
                <v-img
                  src="https://content.internetvideoarchive.com/content/photos/7549/850318_068.jpg"
                  height="200px"
                ></v-img>
                <v-card-title> Dr Seuss' The Lorax </v-card-title>
                <v-card-subtitle> Coming Soon </v-card-subtitle>
                <v-card-actions>
                  <v-btn color="orange lighten-2" text> Description </v-btn>
                  <v-spacer></v-spacer>
                  <v-btn icon @click="show = !show">
                    <v-icon>{{
                      show ? 'mdi-chevron-up' : 'mdi-chevron-down'
                    }}</v-icon>
                  </v-btn>
                </v-card-actions>
                <v-expand-transition>
                  <div v-show="show">
                    <v-divider></v-divider>
                    <v-card-text>
                      I'm a thing. But, like most politicians, he promised more
                      than he could deliver. You won't have time for sleeping,
                      soldier, not with all the bed making you'll be doing. Then
                      we'll go with that data file! Hey, you add a one and two
                      zeros to that or we walk! You're going to do his laundry?
                      I've got to find a way to escape.
                    </v-card-text>
                  </div>
                </v-expand-transition>
              </v-card>

              <v-card class="mx-auto" max-width="300">
                <v-img
                  src="https://observer.case.edu/wp-content/uploads/2022/10/the-sea-beast-900x506.jpg"
                  height="200px"
                ></v-img>
                <v-card-title> The Sea Beast </v-card-title>
                <v-card-subtitle> Hot Movies </v-card-subtitle>
                <v-card-actions>
                  <v-btn color="orange lighten-2" text> Description </v-btn>
                  <v-spacer></v-spacer>
                  <v-btn icon @click="show = !show">
                    <v-icon>{{
                      show ? 'mdi-chevron-up' : 'mdi-chevron-down'
                    }}</v-icon>
                  </v-btn>
                </v-card-actions>
                <v-expand-transition>
                  <div v-show="show">
                    <v-divider></v-divider>
                    <v-card-text>
                      I'm a thing. But, like most politicians, he promised more
                      than he could deliver. You won't have time for sleeping,
                      soldier, not with all the bed making you'll be doing. Then
                      we'll go with that data file! Hey, you add a one and two
                      zeros to that or we walk! You're going to do his laundry?
                      I've got to find a way to escape.
                    </v-card-text>
                  </div>
                </v-expand-transition>
              </v-card>

              <v-card class="mx-auto" max-width="300">
                <v-img
                  src="https://esports.id/img/article/670620230414082604.jpg"
                  height="200px"
                ></v-img>
                <v-card-title> Arcane </v-card-title>
                <v-card-subtitle> On Going </v-card-subtitle>
                <v-card-actions>
                  <v-btn color="orange lighten-2" text> Description </v-btn>
                  <v-spacer></v-spacer>
                  <v-btn icon @click="show = !show">
                    <v-icon>{{
                      show ? 'mdi-chevron-up' : 'mdi-chevron-down'
                    }}</v-icon>
                  </v-btn>
                </v-card-actions>
                <v-expand-transition>
                  <div v-show="show">
                    <v-divider></v-divider>
                    <v-card-text>
                      I'm a thing. But, like most politicians, he promised more
                      than he could deliver. You won't have time for sleeping,
                      soldier, not with all the bed making you'll be doing. Then
                      we'll go with that data file! Hey, you add a one and two
                      zeros to that or we walk! You're going to do his laundry?
                      I've got to find a way to escape.
                    </v-card-text>
                  </div>
                </v-expand-transition>
              </v-card>
            </v-row>
          </v-container>

          <hr class="my-3" />
          <a
            href="https://nuxtjs.org/"
            target="_blank"
            rel="noopener noreferrer"
          >
            Nuxt Documentation
          </a>
        </v-card-text>
        <v-card-actions>
          <v-spacer />
          <v-btn color="primary" nuxt to="/about"> More </v-btn>
        </v-card-actions>
      </v-card>
    </v-col>
  </v-row>
</template>

<script>
export default {
  name: 'IndexPage',
  data: () => ({
    show: false,
  }),
}
</script>
