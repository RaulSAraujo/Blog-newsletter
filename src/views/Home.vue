<template>
  <v-main class="pink lighten-5">
    <v-container >
      <v-tabs-items v-model="$store.state.tab">
        <v-tab-item class="pink lighten-5">
          <v-row>
            <v-col
              sm="6"
              order-sm="1"
              cols="12"
              md="6"
              order-md="1"
              lg="3"
              order-lg="1"
              order-xl="1"
            >
              <v-sheet rounded="lg" min-height="268">
                <v-col>
                  <v-btn text disabled class="font-weight-bold text-h6"
                    >REDES SOCIAIS</v-btn
                  >
                </v-col>
                <v-col>
                  <v-btn
                    width="100%"
                    id="btn"
                    text
                    href="https://www.instagram.com/anajuliarodrigues01/"
                  >
                    <v-icon>mdi-instagram</v-icon>
                    <span class="font-weight-bold text-overline"
                      >@anajuliarodrigues01</span
                    >
                  </v-btn>
                </v-col>
                <v-col>
                  <v-btn
                    width="100%"
                    id="btn"
                    text
                    href="https://www.facebook.com/anajulia.rodriguessilva.79"
                  >
                    <v-icon>mdi-facebook</v-icon>
                    <span class="font-weight-bold text-overline"
                      >anajulia.rodriguessilva.79</span
                    >
                  </v-btn>
                </v-col>
                <v-col>
                  <v-btn
                    width="100%"
                    id="btn"
                    text
                    href="mailto:anajuliarodrigues01@hotmail.com"
                  >
                    <v-icon>mdi-email</v-icon>
                    <span class="font-weight-bold text-overline"
                      >anajuliarodrigues01@hotmail.com</span
                    >
                  </v-btn>
                </v-col>
                <v-col>
                  <v-btn width="100%" id="btn" text href="#">
                    <v-icon>mdi-twitter</v-icon>
                    <span class="font-weight-bold text-overline"
                      >@anajuliarodrigues01</span
                    >
                  </v-btn>
                </v-col>
                <v-col>
                  <v-btn
                    width="100%"
                    id="btn"
                    text
                    href="http://api.whatsapp.com/send?1=pt_BR&phone=5516990501299"
                  >
                    <v-icon>mdi-whatsapp</v-icon>
                    <span class="font-weight-bold text-overline">Whatsapp</span>
                  </v-btn>
                </v-col>
              </v-sheet>
            </v-col>

            <v-col
              sm="12"
              order-sm="3"
              cols="12"
              md="12"
              order-md="3"
              lg="7"
              order-lg="2"
              order-xl="2"
            >
              <v-sheet min-height="700" rounded="lg">test </v-sheet>
            </v-col>

            <v-col
              sm="6"
              order-sm="2"
              cols="12"
              md="6"
              order-md="2"
              lg="2"
              order-lg="3"
              order-xl="3"
            >
              <v-sheet rounded="lg" min-height="360" min-width="250">
                <v-col>
                  <v-btn text disabled class="font-weight-bold text-h5"
                    >VEJA TAMBEM</v-btn
                  >
                </v-col>
                <v-col>
                  <v-btn
                    width="100%"
                    id="btn"
                    text
                    href="https://www.instagram.com/brindearteoficial/"
                  >
                    <v-icon>mdi-instagram</v-icon>
                    <span class="font-weight-bold text-overline"
                      >@brindearteoficial</span
                    >
                  </v-btn>
                </v-col>
              </v-sheet>
            </v-col>
          </v-row>
        </v-tab-item>
        <v-tab-item class="pink lighten-5"></v-tab-item>
        <v-tab-item class="pink lighten-5"></v-tab-item>
      </v-tabs-items>
    </v-container>
  </v-main>
</template>

<script>
export default {
  name: "Home",
  components: {},
  data() {
    return {};
  },
};
</script>

<style scoped>
#btn {
  transition: 0.2s linear;
}
#btn:hover {
  color: rgb(255, 182, 182);
}
</style>
