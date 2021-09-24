<template>
  <v-main class="red lighten-4">
    <v-container>
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
              <v-sheet
                class="text-center"
                min-height="300"
                rounded="lg"
                elevation="4"
              >
                <v-img
                  class="red lighten-5 pt-7"
                  src="../assets/img-s1.jpg"
                  :aspect-ratio="16 / 9"
                  position="center 7%"
                ></v-img>
                <v-toolbar short color="red lighten-4">
                  <v-toolbar-title
                    class="text-h4 white--text font-weight-light fonrt"
                    >QUEM SOU :</v-toolbar-title
                  >
                </v-toolbar>
                <p class="text-body-1 font-weight-medium mt-5 mx-3">
                  Ana Júlia Rodrigues Silva, mas pode me chamar de Ana, muito
                  prazer!
                </p>
                <p class="text-body-1 font-weight-medium mx-3">
                  Tenho 20 anos e moro em Franca interior de São Paulo.
                </p>
                <p class="text-body-1 font-weight-medium mx-3">
                  Trabalho a 3 anos com o Instagram abordando conteúdos de
                  influencia digital entre Autoestima, Moda, Beleza e todo
                  universo Feminino, onde me apaixonei pelo marketing digital e
                  pelo alcance das vendas nas redes sociais.
                </p>
                <p class="text-body-1 font-weight-medium mx-3">
                  Sou formada em Administração e atualmente estou no último
                  semestre de Marketing Digital para disponibilizar aos meus
                  clientes um trabalho profissional e de qualidade.
                </p>
                <p class="text-body-1 font-weight-medium mx-3 pb-4">
                  Sejam Muito bem vindos e fiquem a vontade para explorar e
                  conhecer sobre os meus trabalhos.
                </p>
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
              <v-sheet
                rounded="lg"
                min-height="360"
                min-width="250"
                elevation="4"
              >
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
            <v-col sm="12">
              <v-sheet
                class="text-center"
                rounded="lg"
                min-height="268"
                elevation="4"
              >
                <v-toolbar
                  :style="{ backgroundImage: createBackgroundString1 }"
                >
                  <v-spacer></v-spacer>
                  <v-toolbar-title class="white--text"
                    >OBJETIVOS</v-toolbar-title
                  >
                  <v-spacer></v-spacer>
                </v-toolbar>
                <p class="text-body-1 font-weight-regular mx-7 mt-3">
                  Meu objetivo como social media vai além das tradicionais
                  propagandas e das vitrines virtuais que estamos acostumados a
                  ver, minha responsabilidade é gerenciar as redes sociais da
                  sua empresa:
                </p>

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
                    <v-card
                      max-height="350"
                      min-height="250"
                      class="text-center"
                      rounded="lg"
                    >
                      <v-card-title>
                        <v-spacer></v-spacer>
                        <v-img
                          max-width="50"
                          src="../assets/icons/book.png"
                        ></v-img>
                        <v-spacer></v-spacer>
                      </v-card-title>
                      <v-card-subtitle
                        >Elaborando estratégias personalizadas.</v-card-subtitle
                      >
                      <v-card-text
                        >É uma abordagem onde foco em traçar estratégias
                        específicas para o seu próprio negócio, buscando
                        resultados em curto, médio e longo prazo. É essencial,
                        pois ajuda a entender o seu público-alvo e acaba gerando
                        resultados mais assertivos e eficazes.</v-card-text
                      >
                    </v-card>
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
                    <v-card
                      max-height="350"
                      min-height="250"
                      class="text-center"
                      rounded="lg"
                    >
                      <v-card-title>
                        <v-spacer></v-spacer>
                        <v-img
                          max-width="50"
                          src="../assets/icons/animation-play-outline.png"
                        ></v-img>
                        <v-spacer></v-spacer>
                      </v-card-title>
                      <v-card-subtitle
                        >Criando conteúdos relevantes e
                        autênticos.</v-card-subtitle
                      >
                      <v-card-text
                        >Desenvolver, planejar, criar, postar, interagir,
                        analisalisar e fazer tudo acontecer. Estou sempre
                        conectada com as novas tendências do mercado e as
                        novidades que surgem nas redes sociais, para produzir
                        conteúdos relevantes e que sejam interessantes ao
                        público, assim gereando engajamento. e elevando sua
                        presença no meio digital.</v-card-text
                      >
                    </v-card>
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
                    <v-card
                      max-height="300"
                      min-height="200"
                      class="text-center"
                      rounded="lg"
                    >
                      <v-card-title>
                        <v-spacer></v-spacer>
                        <v-img
                          max-width="50"
                          src="../assets/icons/finance.png"
                        ></v-img>
                        <v-spacer></v-spacer>
                      </v-card-title>
                      <v-card-subtitle
                        >Acompanhando de perto todos os resultados e métricas
                        das mídias.</v-card-subtitle
                      >
                      <v-card-text
                        >Apresentação de dados e análises. Faço uma análise
                        global de todas as ações desenvolvidas durante o mês e
                        como elas impactaram o desempenho do seu negócio nas
                        redes sociais, a fim de propor novas ações e estratégias
                        para o mês seguinte. O Relatório de analise é
                        explicativo e simples para melhor entendimento das
                        estratégias utilizadas e dos resultados
                        alcançados.</v-card-text
                      >
                    </v-card>
                  </v-col>
                </v-row>
                <p class="text-body-1 font-weight-regular mx-7">
                  Aumentando assim sua visibilidade no mercado, se destacando
                  entre os concorrentes e também modernizando a experiência do
                  cliente na sua empresa, seja ela on-line ou física, atraindo
                  cada vez mais clientes para o seu negócio.
                </p>

                <v-toolbar
                  :style="{ backgroundImage: createBackgroundString1 }"
                >
                  <v-spacer></v-spacer>
                  <v-toolbar-title class="white--text"
                    >ESTRATÉGIAS</v-toolbar-title
                  >
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
                    <v-card
                      max-height="250"
                      min-height="200"
                      class="text-center"
                      rounded="lg"
                    >
                      <v-card-title class="mb-2">
                        <v-spacer></v-spacer>
                        <v-img
                          max-width="35"
                          src="../assets/icons/ads_1_.png"
                        ></v-img>
                        <v-spacer></v-spacer>
                      </v-card-title>
                      <v-card-subtitle>Gestão de Anúncios</v-card-subtitle>
                      <v-card-text
                        >Realizamos e planejamos a gestão de tráfego da sua
                        empresa de forma estratégica para otimizar o retorno de
                        clientes e obter um melhor desempenho.</v-card-text
                      >
                      <v-card-actions class="my-n4">
                        <v-spacer></v-spacer>
                        <v-chip
                          id="chip"
                          class="mx-2"
                          small
                          :style="{ backgroundImage: createBackgroundString }"
                          label
                          text-color="white"
                        >
                          <v-icon color="white" size="20" left
                            >mdi-google-ads</v-icon
                          >
                          Google Ads
                        </v-chip>
                        <v-spacer></v-spacer>
                        <v-chip
                          id="chip"
                          class="mx-2"
                          small
                          :style="{ backgroundImage: createBackgroundString }"
                          label
                          text-color="white"
                        >
                          <v-icon color="white" size="20" left
                            >mdi-instagram</v-icon
                          >
                          Instagram Ads
                        </v-chip>
                        <v-spacer></v-spacer>
                        <v-chip
                          id="chip"
                          class="mx-2"
                          small
                          :style="{ backgroundImage: createBackgroundString }"
                          label
                          text-color="white"
                        >
                          <v-icon color="white" size="20" left
                            >mdi-facebook</v-icon
                          >
                          Facebook Ads
                        </v-chip>
                        <v-spacer></v-spacer>
                      </v-card-actions>
                    </v-card>
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
                    <v-card
                      max-height="300"
                      min-height="200"
                      class="text-center"
                      rounded="lg"
                    >
                      <v-card-title>
                        <v-spacer></v-spacer>
                        <v-img
                          max-width="40"
                          src="../assets/icons/simbolo-de-pesquisa-seo.png"
                        ></v-img>
                        <v-spacer></v-spacer>
                      </v-card-title>
                      <v-card-subtitle
                        >Otimização de Sites (SEO)</v-card-subtitle
                      >
                      <v-card-text
                        >Utilizamos técnicas de SEO para melhorar o rankeamento
                        do seu websites ou loja online dentro do
                        google.</v-card-text
                      >
                      <v-card-actions class="my-n4">
                        <v-spacer></v-spacer>
                        <v-chip
                          id="chip"
                          class="mx-2"
                          small
                          :style="{ backgroundImage: createBackgroundString }"
                          label
                          text-color="white"
                        >
                          Ferramenta de buscas
                        </v-chip>
                        <v-spacer></v-spacer>
                        <v-chip
                          id="chip"
                          class="mx-2"
                          small
                          :style="{ backgroundImage: createBackgroundString }"
                          label
                          text-color="white"
                        >
                          Palavras chaves
                        </v-chip>
                        <v-spacer></v-spacer>
                        <v-chip
                          id="chip"
                          class="mx-2"
                          small
                          :style="{ backgroundImage: createBackgroundString }"
                          label
                          text-color="white"
                        >
                          URLs facilitadas
                        </v-chip>
                        <v-spacer></v-spacer>
                      </v-card-actions>
                    </v-card>
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
                    <v-card
                      max-height="300"
                      min-height="200"
                      class="text-center"
                      rounded="lg"
                    >
                      <v-card-title class="mb-2">
                        <v-spacer></v-spacer>
                        <v-img
                          max-width="40"
                          src="../assets/icons/like_1_.png"
                        ></v-img>
                        <v-spacer></v-spacer>
                      </v-card-title>
                      <v-card-subtitle
                        >Gestão de mídias sociais</v-card-subtitle
                      >
                      <v-card-text
                        >Trabalhamos com foco na persona, colocando em ação as
                        ferramentas que mais usamos em nosso cotidiano, para
                        aproximar seus clientes.</v-card-text
                      >
                      <v-card-actions class="mt-n6">
                        <v-spacer></v-spacer>
                        <v-chip
                          id="chip"
                          class="mx-2"
                          small
                          :style="{ backgroundImage: createBackgroundString }"
                          label
                          text-color="white"
                        >
                          Linguagem personalizada
                        </v-chip>
                        <v-spacer></v-spacer>
                        <v-chip
                          id="chip2"
                          class="mx-2"
                          small
                          :style="{ backgroundImage: createBackgroundString }"
                          label
                          text-color="white"
                        >
                          Público alvo
                        </v-chip>
                        <v-spacer></v-spacer>
                        <v-chip
                          id="chip"
                          class="mx-2"
                          small
                          :style="{ backgroundImage: createBackgroundString }"
                          label
                          text-color="white"
                        >
                          Conexão com seguidores
                        </v-chip>
                        <v-spacer></v-spacer>
                      </v-card-actions>
                    </v-card>
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
                    <v-card
                      max-height="300"
                      min-height="200"
                      class="text-center pb-3"
                      rounded="lg"
                    >
                      <v-card-title class="mb-2">
                        <v-spacer></v-spacer>
                        <v-img
                          max-width="40"
                          src="../assets/icons/esx.png"
                        ></v-img>
                        <v-spacer></v-spacer>
                      </v-card-title>
                      <v-card-subtitle
                        >Elaboração de relatórios</v-card-subtitle
                      >
                      <v-card-text
                        >Elaboramos planilhas e relatórios para controle de
                        métricas e estruturação de novos métodos, estipulando
                        novas táticas e objetivos</v-card-text
                      >
                      <v-card-actions class="mt-n4">
                        <v-spacer></v-spacer>
                        <v-chip
                          id="chip"
                          class="mx-2"
                          small
                          :style="{ backgroundImage: createBackgroundString }"
                          label
                          text-color="white"
                        >
                          Resumo de vendas
                        </v-chip>
                        <v-spacer></v-spacer>
                        <v-chip
                          id="chip"
                          class="mx-2"
                          small
                          :style="{ backgroundImage: createBackgroundString }"
                          label
                          text-color="white"
                        >
                          Dados e analises
                        </v-chip>
                        <v-spacer></v-spacer>
                      </v-card-actions>
                      <v-card-actions>
                        <v-spacer></v-spacer>
                        <v-chip
                          id="chip"
                          class="mx-2"
                          small
                          :style="{ backgroundImage: createBackgroundString }"
                          label
                          text-color="white"
                        >
                          insights
                        </v-chip>
                        <v-spacer></v-spacer>
                        <v-chip
                          id="chip"
                          class="mx-2"
                          small
                          :style="{ backgroundImage: createBackgroundString }"
                          label
                          text-color="white"
                        >
                          Planilhas em excel
                        </v-chip>
                        <v-spacer></v-spacer>
                      </v-card-actions>
                    </v-card>
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
                    <v-card
                      max-height="300"
                      min-height="200"
                      class="text-center"
                      rounded="lg"
                    >
                      <v-card-title class="mb-2">
                        <v-spacer></v-spacer>
                        <v-img
                          max-width="40"
                          src="../assets/icons/networking.png"
                        ></v-img>
                        <v-spacer></v-spacer>
                      </v-card-title>
                      <v-card-subtitle
                        >Sistema de atendimento ao cliente</v-card-subtitle
                      >
                      <v-card-text
                        >Prezamos por relacionamentos verdadeiros e experiências
                        inesquecíveis, para que isso se torne possível
                        implementamos um atendimento personalizado e de exelente
                        qualidade.</v-card-text
                      >
                      <v-card-actions class="mt-n4">
                        <v-spacer></v-spacer>
                        <v-chip
                          id="chip"
                          class="mx-2"
                          small
                          :style="{ backgroundImage: createBackgroundString }"
                          label
                          text-color="white"
                        >
                          Atendimento humanizado
                        </v-chip>
                        <v-spacer></v-spacer>
                        <v-chip
                          id="chip"
                          class="mx-2"
                          small
                          :style="{ backgroundImage: createBackgroundString }"
                          label
                          text-color="white"
                        >
                          Solução de problemas
                        </v-chip>
                        <v-spacer></v-spacer>
                      </v-card-actions>
                      <v-card-actions>
                        <v-spacer></v-spacer>
                        <v-chip
                          id="chip"
                          class="mx-2"
                          small
                          :style="{ backgroundImage: createBackgroundString }"
                          label
                          text-color="white"
                        >
                          Dúvidas
                        </v-chip>
                        <v-spacer></v-spacer>
                        <v-chip
                          id="chip"
                          class="mx-2"
                          small
                          :style="{ backgroundImage: createBackgroundString }"
                          label
                          text-color="white"
                        >
                          Transparência
                        </v-chip>
                        <v-spacer></v-spacer>
                      </v-card-actions>
                    </v-card>
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
                    <v-card
                      max-height="300"
                      min-height="200"
                      class="text-center"
                      rounded="lg"
                    >
                      <v-card-title class="mb-2">
                        <v-spacer></v-spacer>
                        <v-img
                          max-width="40"
                          src="../assets/icons/estrategia.png"
                        ></v-img>
                        <v-spacer></v-spacer>
                      </v-card-title>
                      <v-card-subtitle>Estrategia de conteudo</v-card-subtitle>
                      <v-card-text
                        >Um forte aliado que usamos ao nosso favor,
                        desenvolvendo conteúdos autênticos e relevantes baseado
                        em analise de dados para gerar mais engajamento e elevar
                        sua influência no meio digital.</v-card-text
                      >
                      <v-card-actions class="mt-n4">
                        <v-spacer></v-spacer>
                        <v-chip
                          id="chip"
                          class="mx-2"
                          :style="{ backgroundImage: createBackgroundString }"
                          small
                          label
                          text-color="white"
                        >
                          Organização de conteudo
                        </v-chip>
                        <v-spacer></v-spacer>
                        <v-chip
                          id="chip"
                          class="mx-2"
                          :style="{ backgroundImage: createBackgroundString }"
                          small
                          label
                          text-color="white"
                        >
                          Planejamento estratégico
                        </v-chip>
                        <v-spacer></v-spacer>
                      </v-card-actions>
                      <v-card-actions>
                        <v-spacer></v-spacer>
                        <v-chip
                          id="chip"
                          class="mx-2"
                          :style="{ backgroundImage: createBackgroundString }"
                          small
                          label
                          text-color="white"
                        >
                          Agendamento de posts
                        </v-chip>
                        <v-spacer></v-spacer>
                        <v-chip
                          id="chip"
                          class="mx-2"
                          :style="{ backgroundImage: createBackgroundString }"
                          small
                          label
                          text-color="white"
                        >
                          Relatorio de "TRENDS"
                        </v-chip>
                        <v-spacer></v-spacer>
                      </v-card-actions>
                    </v-card>
                  </v-col>
                </v-row>
              </v-sheet>
            </v-col>
          </v-row>
        </v-tab-item>

        <v-tab-item class="red lighten-4">
          <v-row>
            <v-col sm="12">
              <v-sheet
                class="text-center"
                rounded="lg"
                min-height="268"
                elevation="4"
              >
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
      angle: "25",
      color1: "#9f9ae4",
      color2: "#d12d9c",
      angle1: "0",
      color3: "#EF9A9A",
      color4: "#FFCDD2",
    };
  },
  computed: {
    createBackgroundString() {
      return `linear-gradient(${this.angle}deg, ${this.color1}, ${this.color2})`;
    },
    createBackgroundString1() {
      return `linear-gradient(${this.angle1}deg, ${this.color3}, ${this.color4}`;
    },
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
#chip{
  text-align: center;
  display: block;
  padding: auto;
  width: 50%;
}
#chip2{
  text-align: center;
  display: block;
  padding: auto;
  width: 30%;
}
</style>
