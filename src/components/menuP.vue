<template>
  <v-app>

    <v-toolbar
      app
      justify="space-around"
    >
      <v-app-bar-nav-icon @click="drawer = !drawer">
      </v-app-bar-nav-icon>

      <v-toolbar-title>Carrito</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-btn  depressed>
        INICIO
      </v-btn>

      <v-btn depressed>
        MARCA
      </v-btn>

       <v-btn depressed>
        CARRITO 
      </v-btn>

    </v-toolbar>

    <v-navigation-drawer app v-model="drawer" temporary dark>
      <v-layout mt-4 column align-center>

        <v-flex>
          <v-avatar>
            <img src="" alt="">
          </v-avatar>
        </v-flex>

        <v-flex>
          <p class="white--text mt-3 headline ">Yohan M</p>
        </v-flex>

      </v-layout>

    </v-navigation-drawer>

    <v-content>
      <router-view/>
    </v-content>
    

  </v-app>
</template>

<script>

export default {
  name: 'menuP',

  data: () => ({
    drawer: true,
    items: [

    ]
  }),
  components: {

  }
};
</script>

<style >
</style>