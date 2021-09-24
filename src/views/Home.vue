<template>
  <v-main class="red lighten-4">
    <v-container fluid>
      <v-tabs-items v-model="$store.state.tab">
        <v-tab-item class="red lighten-4">
          <v-row>
            <v-col
              class="mt-n3"
              cols="12"
              sm="12"
              order-sm="1"
              md="6"
              order-md="1"
              lg="3"
              order-lg="1"
              order-xl="1"
            >
              <v-item-group>
                <v-col>
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
                        <span class="font-weight-bold text-overline"
                          >Whatsapp</span
                        >
                      </v-btn>
                    </v-col>
                  </v-sheet>
                </v-col>

                <v-col v-if="clientsTestimonialsPages == 4">
                  <v-sheet rounded="lg" min-height="268" elevation="4">
                    <v-row
                      align="center"
                      justify="center"
                      no-gutters
                      class="ma-auto"
                    >
                      <v-col
                        v-for="foto in fotos"
                        :key="foto"
                        class="d-flex child-flex"
                        cols="4"
                      >
                        <v-img
                          :src="foto"
                          :lazy-src="foto"
                          aspect-ratio="1"
                          position="top"
                          class="grey lighten-2"
                        >
                          <template v-slot:placeholder>
                            <v-row
                              class="fill-height ma-0"
                              align="center"
                              justify="center"
                            >
                              <v-progress-circular
                                indeterminate
                                color="grey lighten-5"
                              ></v-progress-circular>
                            </v-row>
                          </template>
                        </v-img>
                      </v-col>
                    </v-row>
                  </v-sheet>
                </v-col>
              </v-item-group>
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
              class="mt-n3"
              cols="12"
              sm="12"
              order-sm="2"
              md="6"
              order-md="2"
              lg="3"
              order-lg="2"
              order-xl="2"
            >
              <v-item-group>
                <v-col>
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

                <v-col v-if="clientsTestimonialsPages == 4">
                  <v-sheet rounded="lg" min-height="268" elevation="4">
                    <v-row
                      align="center"
                      justify="center"
                      no-gutters
                      class="ma-auto"
                    >
                      <v-col class="d-flex child-flex mt-2">
                        <iframe
                          src="https://www.facebook.com/plugins/video.php?height=476&href=https%3A%2F%2Fwww.facebook.com%2Fanajulia.rodriguessilva.79%2Fvideos%2F592778045004824%2F&show_text=false&width=267&t=0"
                          width="267"
                          height="770"
                          style="border: none; overflow: hidden"
                          scrolling="no"
                          frameborder="0"
                          allowfullscreen="true"
                          allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
                        ></iframe>
                      </v-col>
                    </v-row>
                  </v-sheet>
                </v-col>
              </v-item-group>
            </v-col>

            <v-col
              v-if="clientsTestimonialsPages <= 3"
              order-sm="5"
              order-md="5"
              order-lg="5"
              order-xl="5"
            >
              <v-sheet rounded="lg" min-height="268" elevation="4">
                <v-row
                  align="center"
                  justify="center"
                  no-gutters
                  class="ma-auto"
                >
                  <v-col
                    v-for="foto in fotos"
                    :key="foto"
                    class="d-flex child-flex"
                    cols="6"
                    sm="4"
                    md="3"
                    lg="3"
                  >
                    <v-img
                      :src="foto"
                      :lazy-src="foto"
                      aspect-ratio="1"
                      position="top"
                      class="grey lighten-2"
                    >
                      <template v-slot:placeholder>
                        <v-row
                          class="fill-height ma-0"
                          align="center"
                          justify="center"
                        >
                          <v-progress-circular
                            indeterminate
                            color="grey lighten-5"
                          ></v-progress-circular>
                        </v-row>
                      </template>
                    </v-img>
                  </v-col>
                </v-row>
              </v-sheet>
            </v-col>

            <v-col
              v-if="clientsTestimonialsPages == 1"
              order-sm="6"
              order-md="6"
              order-lg="6"
              order-xl="6"
            >
              <v-sheet rounded="lg" min-height="268" elevation="4">
                <v-row
                  align="center"
                  justify="center"
                  no-gutters
                  class="ma-auto"
                >
                  <v-col
                    cols="12"
                    sm="12"
                    md="12"
                    lg="3"
                    v-for="video in videos"
                    :key="video"
                    class="d-flex child-flex"
                  >
                    <iframe
                      :src="video"
                      width="100%"
                      height="840"
                      style="border: none; overflow: hidden"
                      scrolling="no"
                      frameborder="0"
                      allowfullscreen="true"
                      allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
                    ></iframe>
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
                      max-height="400"
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
                      <v-card-actions class="ml-n4">
                        <v-row class="mx-auto">
                          <v-col cols="12" sm="4" md="12" lg="6" xl="4">
                            <v-chip
                              id="chip"
                              class="mx-2"
                              small
                              :style="{
                                backgroundImage: createBackgroundString,
                              }"
                              label
                              text-color="white"
                            >
                              <v-icon color="white" size="20" left
                                >mdi-google-ads</v-icon
                              >
                              Google Ads
                            </v-chip>
                          </v-col>
                          <v-col cols="12" sm="4" md="12" lg="6" xl="4">
                            <v-chip
                              id="chip"
                              class="mx-2"
                              small
                              :style="{
                                backgroundImage: createBackgroundString,
                              }"
                              label
                              text-color="white"
                            >
                              <v-icon color="white" size="20" left
                                >mdi-instagram</v-icon
                              >
                              Instagram Ads
                            </v-chip>
                          </v-col>
                          <v-col cols="12" sm="4" md="12" lg="12" xl="4">
                            <v-chip
                              id="chip"
                              class="mx-2"
                              small
                              :style="{
                                backgroundImage: createBackgroundString,
                              }"
                              label
                              text-color="white"
                            >
                              <v-icon color="white" size="20" left
                                >mdi-facebook</v-icon
                              >
                              Facebook Ads
                            </v-chip>
                          </v-col>
                        </v-row>
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
                      max-height="400"
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
                      <v-card-actions class="ml-n4">
                        <v-row class="mx-auto">
                          <v-col cols="12" sm="4" md="12" lg="6" xl="4">
                            <v-chip
                              id="chip"
                              class="mx-2"
                              small
                              :style="{
                                backgroundImage: createBackgroundString,
                              }"
                              label
                              text-color="white"
                            >
                              Ferramenta de buscas
                            </v-chip>
                          </v-col>
                          <v-col cols="12" sm="4" md="12" lg="6" xl="4">
                            <v-chip
                              id="chip"
                              class="mx-2"
                              small
                              :style="{
                                backgroundImage: createBackgroundString,
                              }"
                              label
                              text-color="white"
                            >
                              Palavras chaves
                            </v-chip>
                          </v-col>
                          <v-col cols="12" sm="4" md="12" lg="12" xl="4">
                            <v-chip
                              id="chip"
                              class="mx-2"
                              small
                              :style="{
                                backgroundImage: createBackgroundString,
                              }"
                              label
                              text-color="white"
                            >
                              URLs facilitadas
                            </v-chip>
                          </v-col>
                        </v-row>
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
                      max-height="400"
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
                      <v-card-actions class="px-1">
                        <v-row class="mx-auto">
                          <v-col cols="12" sm="5" md="12" lg="6" xl="4">
                            <v-chip
                              id="chip"
                              small
                              :style="{
                                backgroundImage: createBackgroundString,
                              }"
                              label
                              text-color="white"
                            >
                              Linguagem personalizada
                            </v-chip>
                          </v-col>
                          <v-col cols="12" sm="3" md="12" lg="6" xl="4">
                            <v-chip
                              id="chip"
                              small
                              :style="{
                                backgroundImage: createBackgroundString,
                              }"
                              label
                              text-color="white"
                            >
                              Público alvo
                            </v-chip>
                          </v-col>
                          <v-col cols="12" sm="4" md="12" lg="12" xl="4">
                            <v-chip
                              id="chip"
                              small
                              :style="{
                                backgroundImage: createBackgroundString,
                              }"
                              label
                              text-color="white"
                            >
                              Conexão com seguidores
                            </v-chip>
                          </v-col>
                        </v-row>
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
                      max-height="500"
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
                      <v-card-actions class="ml-n4">
                        <v-row class="mx-auto">
                          <v-col cols="12" sm="6" md="12" lg="6" xl="6">
                            <v-chip
                              id="chip"
                              class="mx-2"
                              small
                              :style="{
                                backgroundImage: createBackgroundString,
                              }"
                              label
                              text-color="white"
                            >
                              Resumo de vendas
                            </v-chip>
                          </v-col>
                          <v-col cols="12" sm="6" md="12" lg="6" xl="6">
                            <v-chip
                              id="chip"
                              class="mx-2"
                              small
                              :style="{
                                backgroundImage: createBackgroundString,
                              }"
                              label
                              text-color="white"
                            >
                              Dados e analises
                            </v-chip>
                          </v-col>
                          <v-col cols="12" sm="6" md="12" lg="6" xl="6">
                            <v-chip
                              id="chip"
                              class="mx-2"
                              small
                              :style="{
                                backgroundImage: createBackgroundString,
                              }"
                              label
                              text-color="white"
                            >
                              insights
                            </v-chip>
                          </v-col>
                          <v-col cols="12" sm="6" md="12" lg="6" xl="6">
                            <v-chip
                              id="chip"
                              class="mx-2"
                              small
                              :style="{
                                backgroundImage: createBackgroundString,
                              }"
                              label
                              text-color="white"
                            >
                              Planilhas em excel
                            </v-chip>
                          </v-col>
                        </v-row>
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
                      max-height="500"
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
                      <v-card-actions class="ml-n4">
                        <v-row class="mx-auto">
                          <v-col cols="12" sm="6" md="12" lg="6" xl="6">
                            <v-chip
                              id="chip"
                              class="mx-2"
                              small
                              :style="{
                                backgroundImage: createBackgroundString,
                              }"
                              label
                              text-color="white"
                            >
                              Atendimento humanizado
                            </v-chip>
                          </v-col>
                          <v-col cols="12" sm="6" md="12" lg="6" xl="6">
                            <v-chip
                              id="chip"
                              class="mx-2"
                              small
                              :style="{
                                backgroundImage: createBackgroundString,
                              }"
                              label
                              text-color="white"
                            >
                              Solução de problemas
                            </v-chip>
                          </v-col>
                          <v-col cols="12" sm="6" md="12" lg="6" xl="6">
                            <v-chip
                              id="chip"
                              class="mx-2"
                              small
                              :style="{
                                backgroundImage: createBackgroundString,
                              }"
                              label
                              text-color="white"
                            >
                              Dúvidas
                            </v-chip>
                          </v-col>
                          <v-col cols="12" sm="6" md="12" lg="6" xl="6">
                            <v-chip
                              id="chip"
                              class="mx-2"
                              small
                              :style="{
                                backgroundImage: createBackgroundString,
                              }"
                              label
                              text-color="white"
                            >
                              Transparência
                            </v-chip>
                          </v-col>
                        </v-row>
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
                      max-height="500"
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
                      <v-card-actions class="ml-n4">
                        <v-row class="mx-auto">
                          <v-col cols="12" sm="6" md="12" lg="6" xl="6">
                            <v-chip
                              id="chip"
                              class="mx-2"
                              :style="{
                                backgroundImage: createBackgroundString,
                              }"
                              small
                              label
                              text-color="white"
                            >
                              Organização de conteudo
                            </v-chip>
                          </v-col>
                          <v-col cols="12" sm="6" md="12" lg="6" xl="6">
                            <v-chip
                              id="chip"
                              class="mx-2"
                              :style="{
                                backgroundImage: createBackgroundString,
                              }"
                              small
                              label
                              text-color="white"
                            >
                              Planejamento estratégico
                            </v-chip>
                          </v-col>
                          <v-col cols="12" sm="6" md="12" lg="6" xl="6">
                            <v-chip
                              id="chip"
                              class="mx-2"
                              :style="{
                                backgroundImage: createBackgroundString,
                              }"
                              small
                              label
                              text-color="white"
                            >
                              Agendamento de posts
                            </v-chip>
                          </v-col>
                          <v-col cols="12" sm="6" md="12" lg="6" xl="6">
                            <v-chip
                              id="chip"
                              class="mx-2"
                              :style="{
                                backgroundImage: createBackgroundString,
                              }"
                              small
                              label
                              text-color="white"
                            >
                              Relatorio de "TRENDS"
                            </v-chip>
                          </v-col>
                        </v-row>
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
      clientsTestimonialsPages: 0,
      fotos: [
        "https://scontent.frao1-1.fna.fbcdn.net/v/t1.6435-9/60392939_294337464848885_8838573710509080576_n.jpg?_nc_cat=111&ccb=1-5&_nc_sid=8bfeb9&_nc_eui2=AeEQemgW5yskB0GHB4xy9SfEMCuOjghyQpcwK46OCHJCl1z8Zyc2YUE9_FFiawDUW_L9ZOPraAPDvQGr5rXWE6_G&_nc_ohc=zS0enal5T9kAX-cGCZM&tn=ys-wSt6kKdayP6SI&_nc_ht=scontent.frao1-1.fna&oh=5c734d7c3e2d80ebd0b360ab14a293c6&oe=61733A7F",
        "https://scontent.frao1-2.fna.fbcdn.net/v/t1.6435-9/58373092_1496543293810036_1270141835108417536_n.jpg?_nc_cat=101&ccb=1-5&_nc_sid=8bfeb9&_nc_eui2=AeEup8GZdW2bQ97BNpz-rXJC2UrIECF5X__ZSsgQIXlf_3qv6MeVMMk5Bf1xbqDgvm_ny5_QDRLpa3S-7jjMy2ZN&_nc_ohc=u02ojVMhtV8AX8Parsg&_nc_ht=scontent.frao1-2.fna&oh=38622cb8dabf0def67237eaf25d49571&oe=6172902D",
        "https://scontent.frao1-2.fna.fbcdn.net/v/t1.6435-9/56334640_263163637966268_5436294343117766656_n.jpg?_nc_cat=102&ccb=1-5&_nc_sid=8bfeb9&_nc_eui2=AeHJVhYvwpCDZ6CUGHEOQWupD2uhkP2o4ssPa6GQ_ajiy03Qbjw7GmZXNMri_gG38-agsi8dikejCJGmXWwPwe2Z&_nc_ohc=aQKA4OaM6qUAX9urmVf&_nc_ht=scontent.frao1-2.fna&oh=749cb3374adc07040a22bab7d54a36b9&oe=6172A4AA",
        "https://scontent.frao1-1.fna.fbcdn.net/v/t1.6435-9/53264647_333807407488791_7696115390480384000_n.jpg?_nc_cat=107&ccb=1-5&_nc_sid=8bfeb9&_nc_eui2=AeEqzh8y-9Eq91KS1KLGJaROdFyK0OwS7xZ0XIrQ7BLvFnjE3wTA-gE_BSsAbyrjHu11lYD9mkIpMhNarN89YUG_&_nc_ohc=VtS1DvzAhg4AX_Clr6A&_nc_ht=scontent.frao1-1.fna&oh=b788005031ccc6742b65ea8f56aee45f&oe=61738212",
        "https://scontent.frao1-1.fna.fbcdn.net/v/t1.6435-9/176948704_792935484989078_798200316349910626_n.jpg?_nc_cat=106&ccb=1-5&_nc_sid=09cbfe&_nc_eui2=AeEW0A-YRrFKUrJI-WFNgvwQoRjNccZux7ihGM1xxm7HuHXglHvJs6RhrZHkJFId9WSgMjMTpdWvsrub01hCEF_n&_nc_ohc=_QrJs7rC0CkAX_BSmXh&_nc_ht=scontent.frao1-1.fna&oh=8d67d561b44fd2276ac563d3bc18aeb7&oe=61746DCB",
        "https://scontent.frao1-1.fna.fbcdn.net/v/t1.6435-9/97450934_553843295564966_6091512224260554752_n.jpg?_nc_cat=108&ccb=1-5&_nc_sid=174925&_nc_eui2=AeFB06GL_zZcH8-ObuELoSESDPELg4XeaIgM8QuDhd5oiGsXoavT2sMC88--mQ7kwoY8VI1lsTldYbjdPLUeogqD&_nc_ohc=zCxNOZZDo7cAX_NgU5j&_nc_ht=scontent.frao1-1.fna&oh=97802bf8f2a0a4bb67598774299b735b&oe=61745911",
        "https://scontent.frao1-1.fna.fbcdn.net/v/t1.6435-9/67460409_342235606725737_1899849478823739392_n.jpg?_nc_cat=107&ccb=1-5&_nc_sid=174925&_nc_eui2=AeFL8sinnNzDkCSFyVJuLPsiJ7iW_QPJfWknuJb9A8l9aT3EcAGg-K78leEK6fyrFmwssl_YllOOrWggbzpW3jcB&_nc_ohc=AYCcyg5jrO0AX-Iv63o&_nc_ht=scontent.frao1-1.fna&oh=4b4ade6137fea5f8bfdabc5ad9910356&oe=617312AE",
        "https://scontent.frao1-1.fna.fbcdn.net/v/t1.6435-9/67079560_334633534152611_2678004519572340736_n.jpg?_nc_cat=106&ccb=1-5&_nc_sid=174925&_nc_eui2=AeGYV14pLY9SDA9QFakjeYzIMAqWVKlddWgwCpZUqV11aB4gXroHuOn3UW4ilZ2T5G9Pt8NHTdmZrjzXT47fDcVA&_nc_ohc=7M0nIyCefEsAX9nQxy5&_nc_ht=scontent.frao1-1.fna&oh=15723de8f3a36157d9263a105bacfa70&oe=61713D07",
        "https://scontent.frao1-1.fna.fbcdn.net/v/t1.6435-9/55861128_266652994283999_444034824529772544_n.jpg?_nc_cat=106&ccb=1-5&_nc_sid=8bfeb9&_nc_eui2=AeFNljTiVVtUycptdx5aIMWWul5Cy_AJTdm6XkLL8AlN2c9W44Y0_Ca_LSIGV_NPomMks6RBCH7BkUiwEPHQhzXH&_nc_ohc=oHQTCSLVhcQAX9KotNt&_nc_ht=scontent.frao1-1.fna&oh=fb7bb15f0d43154cc93e396af11fa6eb&oe=61749EF2",
        "https://scontent.frao1-2.fna.fbcdn.net/v/t1.6435-9/55489183_261559434793355_4692068195387834368_n.jpg?_nc_cat=100&ccb=1-5&_nc_sid=19026a&_nc_eui2=AeGcTeiQIxJx1RqGvaMi3kY0_G04iyQfcG_8bTiLJB9wb5RqwP7gM3L-i3tNAyUCvD8nfh5P7-1O6v-urpwwrFR-&_nc_ohc=uIoOBY6493AAX-x4DGw&_nc_ht=scontent.frao1-2.fna&oh=9168acf8fdfb79727ef1dbc213d869a4&oe=6172C6DE",
      ],
      videos: [
        "https://www.facebook.com/plugins/video.php?height=476&href=https%3A%2F%2Fwww.facebook.com%2Fanajulia.rodriguessilva.79%2Fvideos%2F592778045004824%2F&show_text=false&width=267&t=0",
        "https://www.facebook.com/plugins/video.php?height=476&href=https%3A%2F%2Fwww.facebook.com%2Fanajulia.rodriguessilva.79%2Fvideos%2F486891108926852%2F&show_text=false&width=380&t=0",
      ],
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
  methods: {
    winWidth: function () {
      setInterval(() => {
        var w = window.innerWidth;
        if (w < 768) {
          this.clientsTestimonialsPages = 1;
        } else if (w < 960) {
          this.clientsTestimonialsPages = 2;
        } else if (w < 1260) {
          this.clientsTestimonialsPages = 3;
        } else {
          this.clientsTestimonialsPages = 4;
        }
      }, 100);
    },
  },
  mounted() {
    //callback once mounted
    this.winWidth();
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
#chip {
  text-align: center;
  display: inline-block;
  padding: 0 auto;
  width: 100%;
}
</style>
