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
    

  <v-parallax
  height="900"
    dark
    src="https://cdn.vuetifyjs.com/images/backgrounds/vbanner.jpg"
  >
    <v-row
      align="center"
      justify="center"
    >
      <v-col
        class="text-center"
        cols="12"
      >
        <h1 class="text-h4 font-weight-thin mb-4">
          Vuetify
        </h1>
        <h4 class="subheading">
          Build your application today!
        </h4>
      </v-col>
    </v-row>
  </v-parallax>


<v-layout wrap class="mt-5" justify-center>
   <v-flex class="mt-5" xs6 sm6 md6 lg6 xl6>
  
      <h1 class="display-4">
      TULUM
      </h1>
        <p class="mt-5 display-1 text-xs-center">
          En el siglo XIII un importante puerto marítimo para comerciantes mayas; 
        </p>
          <p class="mt-5">
          En el siglo XIII un importante puerto marítimo para comerciantes mayas; 
          hoy en día Tulum es un destino con una gran riqueza histórica que debe 
          ser experimentada por todo quien lo visita.
        </p>
        <p>
          Hogar de algunos de los sitios arqueológicos mejor conservados de la región, 
          Tulum forma parte de la Riviera Maya y se ubica a menos de dos horas del 
          Aeropuerto Internacional de Cancún. Hay camiones que salen directamente 
          desde el aeropuerto de Cancún a Tulum o Playa del Carmen, por si planeas 
          hacer una excursión durante el día a alguno de los cenotes, lagunas o 
          sitios arqueológicos que se encuentran a los alrededores
        </p>

        <v-container fluid>
    <v-row justify="space-around">
      <v-col>
        <v-img
          src="https://picsum.photos/510/300?random"
          aspect-ratio="2"
        ></v-img>
      </v-col>
    </v-row>
  </v-container>

       <h1 class="mt-5 display-2">
      DIAS DE PLAYA
      </h1>
          <p class="mt-5 display-1 ">
         Además de su belleza arqueológica, Tulum es popular por sus playas que se 
         extienden a lo largo de 16 kilómetros hasta la Reserva de la Biósfera Sian 
         Ka'an. 
        </p>

         <p class="mt-5">
          Este destino está conformado por tres diferentes zonas: la zona 
         arqueológica, "El Pueblo" (El Centro) y la zona hotelera, que se divide 
         en norte y sur. Si buscas grandes extensiones de arena, dirígete al lado 
         norte; pero si estás en busca de un ambiente un poco más animado, ve al 
         lado sur, pues allí se encuentran algunos de los más populares clubes de 
         playa, hoteles y restaurantes que suelen contar con DJ's.
        </p>

      <p class="mt-5">
        Aunque "El Pueblo" cuenta con varias opciones de hospedaje, la mayoría de 
        los viajeros optan por reservar algún hotel que se encuentre frente a la playa. 
        Las opciones incluyen glampings, bungalows con techos hechos de palapa, lujosos 
        hoteles boutique con albercas privadas, haciéndolo un lugar muy popular para parejas 
        y grupos de amigos. A diferencia de los otros destinos que también forman parte de 
        la Riviera Maya, Tulum no cuenta con muchas opciones de hoteles todo incluido, 
        los hoteles tienden a ser pequeños y de plan europeo, que ofrecen una experiencia 
        más íntima y suelen tener un enfoque de bienestar, ofreciendo amenidades como 
        yoga al amanecer y spas ubicados frente al mar.
      </p>


      </v-flex>
    </v-layout>

 <v-container grid-list-xl>
    <v-layout 
    class="mt-5 secondary" 
    justify-center 
    align-center 
    row 
    wrap 
    style="height:600px"
    >
      <v-flex xs12 sm3>
        <v-card>

          <v-img src="https://picsum.photos/id/11/500/300">
            <v-container>
              <v-layout>
                <v-flex>
                  <span class="headline white--text">lorem, ipsum dolor </span>
                </v-flex>
              </v-layout>
            </v-container>
          </v-img>

          <v-card-title>
              <h2>lorem </h2>
          </v-card-title>

          <v-card-text>
          <p>
            lorem ipsum dolor sit amet, consectetur
          </p>
          </v-card-text>
          

          <v-card-actions>
            <v-btn color="info" flat>ACCION</v-btn>

          </v-card-actions>

        </v-card>
      </v-flex>

      <v-flex xs12 sm3>
        <v-card>

          <v-img src="https://picsum.photos/id/11/500/300">
            
          </v-img>

          <v-card-title>
              <h2>lorem </h2>
          </v-card-title>

          <v-card-text>
          <p>
            lorem ipsum dolor sit amet, consectetur
          </p>
          </v-card-text>
          

          <v-card-actions>
            <v-btn color="info" flat>ACCION</v-btn>

          </v-card-actions>

        </v-card>
      </v-flex>

       <v-flex xs12 sm3>
        <v-card>

          <v-img src="https://picsum.photos/id/11/500/300">
            
          </v-img>

          <v-card-title>
              <h2>lorem </h2>
          </v-card-title>

          <v-card-text>
          <p>
            lorem ipsum dolor sit amet, consectetur
          </p>
          </v-card-text>
          

          <v-card-actions>
            <v-btn color="info" flat>ACCION</v-btn>

          </v-card-actions>

        </v-card>
      </v-flex>

    </v-layout>
  </v-container>

   <v-container grid-list-xl>
    <v-layout 
    class=" secondary" 
    justify-center 
    align-center 
    row 
    wrap 
    style="height:600px"
    >
      <v-flex xs12 sm3>
        <v-card>

          <v-img src="https://picsum.photos/id/11/500/300">
            <v-container>
              <v-layout>
                <v-flex>
                  <span class="headline white--text">lorem, ipsum dolor </span>
                </v-flex>
              </v-layout>
            </v-container>
          </v-img>

          <v-card-title>
              <h2>lorem </h2>
          </v-card-title>

          <v-card-text>
          <p>
            lorem ipsum dolor sit amet, consectetur
          </p>
          </v-card-text>
          

          <v-card-actions>
            <v-btn color="info" flat>ACCION</v-btn>

          </v-card-actions>

        </v-card>
      </v-flex>

      <v-flex xs12 sm3>
        <v-card>

          <v-img src="https://picsum.photos/id/11/500/300">
            
          </v-img>

          <v-card-title>
              <h2>lorem </h2>
          </v-card-title>

          <v-card-text>
          <p>
            lorem ipsum dolor sit amet, consectetur
          </p>
          </v-card-text>
          

          <v-card-actions>
            <v-btn color="info" flat>ACCION</v-btn>

          </v-card-actions>

        </v-card>
      </v-flex>

       <v-flex xs12 sm3>
        <v-card>

          <v-img src="https://picsum.photos/id/11/500/300">
            
          </v-img>

          <v-card-title>
              <h2>lorem </h2>
          </v-card-title>

          <v-card-text>
          <p>
            lorem ipsum dolor sit amet, consectetur
          </p>
          </v-card-text>
          

          <v-card-actions>
            <v-btn color="info" flat>ACCION</v-btn>

          </v-card-actions>

        </v-card>
      </v-flex>

    </v-layout>
  </v-container>


  </v-app>
</template>

<script>

export default {
  name: 'App',

  data: () => ({
    drawer: true
  }),
};
</script>
