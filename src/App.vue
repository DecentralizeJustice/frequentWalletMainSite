<template>
  <v-app dark>
    <v-container  text-xs-center fluid pa-0>
    <v-content>
      <section>

        <v-img
        gradient="to top right, rgba(105,105,105,.7), rgba(105,105,105,.7)"
        height='600'
    dark
    src="https://images.pexels.com/photos/1061579/pexels-photo-1061579.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260"
  >
    <v-container fill-height>
      <v-layout align-center>
        <v-flex text-xs-center>
          <h3 class="display-3 white--text">Everday Crypto Wallet</h3>
        </v-flex>
      </v-layout>
    </v-container>
  </v-img>
      </section>

      <section>
        <v-layout
          column
          wrap
          class="my-5"
          align-center
        >
          <v-flex xs12 sm6 class="my-3">
            <div class="text-xs-center">
              <h2 class="headline">This project is under development. Here are our main categories of work: </h2>
            </div>
          </v-flex>

            <v-container grid-list-xl fluid>
              <v-layout align-center justify-center row fill-height>
                <v-flex xs12 md4>
                  <v-card >
                     <v-img
                       src="https://images.pexels.com/photos/1120347/pexels-photo-1120347.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260"
                       aspect-ratio="2"
                     ></v-img>
                   <v-card-title primary-title class="justify-center">
                     <div>
                       <h3 class="headline mb-0">Documentation</h3>
                     </div>
                   </v-card-title>
                   <v-card-actions class="justify-center">
                     <v-btn flat color="orange" href="https://www.multisigcrypto.com/docs">Study</v-btn>
                   </v-card-actions>
                 </v-card>
                </v-flex>

                <v-flex xs12 md4>
                  <v-card>
                     <v-img
                       src="https://images.pexels.com/photos/1370295/pexels-photo-1370295.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260"
                       aspect-ratio="2"
                     ></v-img>
                   <v-card-title primary-title class="justify-center">
                     <div>
                       <h3 class="headline mb-0">Blog</h3>
                     </div>
                   </v-card-title>
                   <v-card-actions class="justify-center">
                     <v-btn flat color="orange" href="https://www.decentralizejustice.com/blog">Read</v-btn>
                   </v-card-actions>
                 </v-card>
                </v-flex>

              </v-layout>
            </v-container>
        </v-layout>
      </section>

    </v-content>
    </v-container>
  </v-app>
</template>

<script>
export default {
  name: 'App',
  components: {
  },
  data () {
    return {
      //
    }
  }
}
</script>
