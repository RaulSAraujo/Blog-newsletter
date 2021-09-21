<template>
  <v-main class="red lighten-4">
    <v-container >
      <v-tabs-items v-model="$store.state.tab">
        <v-tab-item class="red lighten-4">
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
              <v-sheet rounded="lg" min-height="268" elevation="4">
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
              lg="6"
              order-lg="2"
              order-xl="2"
            >
              <v-sheet class="text-center" min-height="300" rounded="lg" elevation="4">
                <v-img class="red lighten-5 pt-7" src="../assets/img-s1.jpg" :aspect-ratio="16/9" position="center 7%"></v-img>
                <v-toolbar short color="red lighten-4">
                  <v-toolbar-title class="text-h4 white--text font-weight-light fonrt">QUEM SOU :</v-toolbar-title>
                </v-toolbar>
                <p class="text-body-1 font-weight-medium mt-5 mx-3">Ana Júlia Rodrigues Silva, mas pode me chamar de Ana, muito prazer!</p>
                <p class="text-body-1 font-weight-medium mx-3">Tenho 20 anos e moro em Franca interior de São Paulo.</p>
                <p class="text-body-1 font-weight-medium mx-3"> Trabalho a 3 anos com o Instagram abordando conteúdos de influencia digital entre  Autoestima, Moda, Beleza e todo universo Feminino, onde me apaixonei pelo marketing digital e pelo alcance das vendas nas redes sociais.</p>
                <p class="text-body-1 font-weight-medium mx-3">Sou formada em Administração e atualmente estou no último semestre de Marketing Digital para disponibilizar aos meus clientes um trabalho profissional e de qualidade.</p>
                <p class="text-body-1 font-weight-medium mx-3 pb-4">Sejam Muito bem vindos e fiquem a vontade para explorar e conhecer sobre os meus trabalhos.</p>
              </v-sheet>
            </v-col>

            <v-col
              sm="6"
              order-sm="2"
              cols="12"
              md="6"
              order-md="2"
              lg="3"
              order-lg="3"
              order-xl="3"
            >
              <v-sheet rounded="lg" min-height="360" min-width="250" elevation="4">
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

        <v-tab-item class="red lighten-4">
          <v-row>
            <v-col sm="12" >
              <v-sheet class="text-center"  rounded="lg" min-height="268" elevation="4">
                <v-toolbar color="red lighten-3">
                  <v-spacer></v-spacer>
                    <v-toolbar-title class="white--text">OBJETIVOS</v-toolbar-title>
                  <v-spacer></v-spacer>
                </v-toolbar>
                <p class="text-body-1 font-weight-regular mx-7 mt-3">Meu objetivo como social media vai além das tradicionais propagandas e vitrines virtuais que estamos acostumados a ver.minha responsabilidade é gerenciar as redes sociais de sua empresa:</p>

                 <v-row class="my-5 mx-5">
                  <v-col 
                  sm="12"
                  order-sm="1"
                  cols="12"
                  md="4"
                  order-md="1"
                  lg="4"
                  order-lg="1"
                  order-xl="1"
                  >
                    <v-hover v-slot="{ hover }">
                      <v-card max-height="350" min-height="250" class="text-center" rounded="lg" :elevation="hover ? 12 : 2" :class="{ 'on-hover': hover }">
                        <v-card-title >
                          <v-spacer></v-spacer>
                          <p class="text-h4">📝</p>
                          <v-spacer></v-spacer>
                        </v-card-title>
                        <v-card-subtitle>Elaborando estratégias personalizadas.</v-card-subtitle>
                        <v-card-text>É uma abordagem de Marketing focada em traçar estratégias específicas para o seu próprio negócio, buscando resultados em curto, médio e longo prazo. É essencial, pois ajuda a entender o seu público-alvo e acaba gerando resultados mais assertivos e eficazes, ou seja, mais conversões com menos esforço.</v-card-text>
                      </v-card>
                    </v-hover>
                  </v-col>
                  
                  <v-col 
                  sm="12"
                  order-sm="2"
                  cols="12"
                  md="4"
                  order-md="2"
                  lg="4"
                  order-lg="2"
                  order-xl="2"
                  >
                    <v-hover v-slot="{ hover }">
                      <v-card max-height="350" min-height="250" class="text-center" rounded="lg" :elevation="hover ? 12 : 2" :class="{ 'on-hover': hover }">
                        <v-card-title>
                          <v-spacer></v-spacer>
                          <p class="text-h4">📚</p>
                          <v-spacer></v-spacer>
                        </v-card-title>
                        <v-card-subtitle>Criando conteúdos relevantes e autênticos.</v-card-subtitle>
                        <v-card-text>O princípio de conteúdo autêntico é aquele que tem produção própria, que trabalha em cima do discurso que adota e expõe para o seu público. Esse tipo de conteúdo criado pelo influenciador digital deve imprimir o seu olhar sobre determinada categoria.</v-card-text>
                      </v-card>
                    </v-hover>
                  </v-col>

                  <v-col 
                  sm="12"
                  order-sm="3"
                  cols="12"
                  md="4"
                  order-md="3"
                  lg="4"
                  order-lg="3"
                  order-xl="3"
                  >
                    <v-hover v-slot="{ hover }">
                      <v-card max-height="350" min-height="250" class="text-center" rounded="lg" :elevation="hover ? 12 : 2" :class="{ 'on-hover': hover }">
                        <v-card-title>
                          <v-spacer></v-spacer>
                          <p class="text-h4">📊</p>
                          <v-spacer></v-spacer>
                        </v-card-title>
                        <v-card-subtitle>Acompanhando de perto todos os resultados  e métricas das mídias.</v-card-subtitle>
                        <v-card-text>Mensurar a qualidade do conteúdo da mensagem, adequação dos meios de comunicação utilizados, aderência dos objetivos de comunicação previstos e qualidade na execução,quantidade de pessoas atingidas pela mensagem, resultados de pesquisa online.</v-card-text>
                      </v-card>
                    </v-hover>
                  </v-col>
                </v-row>
                <p class="text-body-1 font-weight-regular mx-7">Aumentando assim sua visibilidade no mercado, se destacando entre os concorrentes e também modernizando  a experiência do cliente na sua empresa, seja ela on-line ou física, atraindo cada vez mais clientes para o seu negócio.</p>

                <v-toolbar color="red lighten-3">
                  <v-spacer></v-spacer>
                    <v-toolbar-title class="white--text">ESTRATÉGIAS</v-toolbar-title>
                  <v-spacer></v-spacer>
                </v-toolbar>
                
                <v-row class="my-5 mx-5">
                  <v-col 
                  sm="12"
                  order-sm="1"
                  cols="12"
                  md="4"
                  order-md="1"
                  lg="4"
                  order-lg="1"
                  order-xl="1"
                  >
                    <v-hover v-slot="{ hover }">
                      <v-card max-height="250" min-height="200" class="text-center" rounded="lg" :elevation="hover ? 12 : 2" :class="{ 'on-hover': hover }">
                        <v-card-title >
                          <v-spacer></v-spacer>
                          <v-img max-width="40" src="../assets/icons/ads_1_.png"></v-img>
                          <v-spacer></v-spacer>
                        </v-card-title>
                        <v-card-subtitle>Gestão de Anúncios</v-card-subtitle>
                        <v-card-text>Realizamos a gestão de tráfego da sua empresa de forma estratégica para maximizar retorno sobre o investimento (ROI) de campanhas e ações.</v-card-text>
                      </v-card>
                    </v-hover>
                  </v-col>
                  
                  <v-col
                  sm="12"
                  order-sm="2"
                  cols="12"
                  md="4"
                  order-md="2"
                  lg="4"
                  order-lg="2"
                  order-xl="2"
                  >
                    <v-hover v-slot="{ hover }">
                      <v-card max-height="250" min-height="200" class="text-center" rounded="lg" :elevation="hover ? 12 : 2" :class="{ 'on-hover': hover }">
                        <v-card-title>
                          <v-spacer></v-spacer>
                          <v-img max-width="40" src="../assets/icons/simbolo-de-pesquisa-seo.png"></v-img>
                          <v-spacer></v-spacer>
                        </v-card-title>
                        <v-card-subtitle>Otimização de Sites (SEO)</v-card-subtitle>
                        <v-card-text>Utilizamos técnicas de SEO para melhorar o rankeamento do seu websites ou loja online dentro do google.</v-card-text>
                      </v-card>
                    </v-hover>
                  </v-col>

                  <v-col 
                  sm="12"
                  order-sm="3"
                  cols="12"
                  md="4"
                  order-md="3"
                  lg="4"
                  order-lg="3"
                  order-xl="3"
                  >
                    <v-hover v-slot="{ hover }">
                      <v-card max-height="250" min-height="200" class="text-center" rounded="lg" :elevation="hover ? 12 : 2" :class="{ 'on-hover': hover }">
                        <v-card-title>
                          <v-spacer></v-spacer>
                          <v-img max-width="40" src="../assets/icons/like_1_.png"></v-img>
                          <v-spacer></v-spacer>
                        </v-card-title>
                        <v-card-subtitle>Gestão de mídias sociais</v-card-subtitle>
                        <v-card-text>Trabalhamos com foco na persona e usamos estratégias de conteúdo baseadas em análise de dados para gerar mais engajamento e relevância, construindo uma base engajada.</v-card-text>
                      </v-card>
                    </v-hover>
                  </v-col>
                </v-row>

                <v-row class="my-5 mx-5">
                  <v-col 
                  sm="12"
                  order-sm="1"
                  cols="12"
                  md="4"
                  order-md="1"
                  lg="4"
                  order-lg="1"
                  order-xl="1"
                  >
                    <v-hover v-slot="{ hover }">
                      <v-card max-height="250" min-height="200" class="text-center" rounded="lg" :elevation="hover ? 12 : 2" :class="{ 'on-hover': hover }">
                        <v-card-title >
                          <v-spacer></v-spacer>
                          <v-img max-width="40" src="../assets/icons/esx.png"></v-img>
                          <v-spacer></v-spacer>
                        </v-card-title>
                        <v-card-subtitle>Elaboração de relatórios</v-card-subtitle>
                        <v-card-text>Realização de planilhas para controle de metricas e estruturação de novas estratégias</v-card-text>
                      </v-card>
                    </v-hover>
                  </v-col>
                  
                  <v-col 
                  sm="12"
                  order-sm="2"
                  cols="12"
                  md="4"
                  order-md="2"
                  lg="4"
                  order-lg="2"
                  order-xl="2"
                  >
                    <v-hover v-slot="{ hover }">
                      <v-card max-height="250" min-height="200" class="text-center" rounded="lg" :elevation="hover ? 12 : 2" :class="{ 'on-hover': hover }">
                        <v-card-title>
                          <v-spacer></v-spacer>
                          <v-img max-width="40" src="../assets/icons/networking.png"></v-img>
                          <v-spacer></v-spacer>
                        </v-card-title>
                        <v-card-subtitle>Sistema de atendimento ao cliente</v-card-subtitle>
                        <v-card-text>Utilizamos técnicas de SEO para melhorar o rankeamento do seu websites ou loja online dentro do google.</v-card-text>
                      </v-card>
                    </v-hover>
                  </v-col>

                  <v-col 
                  sm="12"
                  order-sm="3"
                  cols="12"
                  md="4"
                  order-md="3"
                  lg="4"
                  order-lg="3"
                  order-xl="3"
                  >
                    <v-hover v-slot="{ hover }">
                      <v-card max-height="250" min-height="200" class="text-center" rounded="lg" :elevation="hover ? 12 : 2" :class="{ 'on-hover': hover }">
                        <v-card-title>
                          <v-spacer></v-spacer>
                          <v-img max-width="40" src="../assets/icons/estrategia.png"></v-img>
                          <v-spacer></v-spacer>
                        </v-card-title>
                        <v-card-subtitle>Estrategia de conteudo</v-card-subtitle>
                        <v-card-text>Trabalhamos com foco na persona e usamos estratégias de conteúdo baseadas em análise de dados para gerar mais engajamento e relevância, construindo uma base engajada.</v-card-text>
                      </v-card>
                    </v-hover>
                  </v-col>
                </v-row>
                
              </v-sheet>
            </v-col>
          </v-row>
        </v-tab-item>

        <v-tab-item class="red lighten-4">
          <v-row>
            <v-col sm="12">
              <v-sheet class="text-center" rounded="lg" min-height="268" elevation="4">
                
              </v-sheet>
            </v-col>
          </v-row>
        </v-tab-item>

      </v-tabs-items>
    </v-container>
  </v-main>
</template>

<script>
export default {
  name: "Home",
  components: {},
  data() {
    return {
      cardC:'red lighten-3',
      transparent: 'rgba(255, 255, 255, 0)',
    };
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
.v-card {
  transition: opacity .4s ease-in-out;
}
.v-card:not(.on-hover) {
  opacity: 0.7;
 }

</style>
