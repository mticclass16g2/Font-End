<template>
  <v-content>
    <v-container>
      <div>
        <h1>NOTICIAS</h1>
        <br />
        <v-img
          dark
          contain
          height="500"
          src="https://i.ibb.co/71xMtsj/noticias-blog-01-1920x1080.jpg"
        ></v-img>
        <br />
        <h2>Nuestro Blog</h2>
        <br />
        <p>
          En este espacio podrás encontrar noticias y enlaces a publicaciones de
          interés, relacionadas con búsqueda de empleo, emprendimiento,
          crecimiento personal y desarrollo profesional.
          <br />
          <br />
          Te invitamos a incluirla en tus favoritos.
        </p>
        <br />
        <v-divider></v-divider>
        <br />
      </div>
      <v-row dense>
        <v-col>
          <v-card hover class="mx-auto" max-width="375">
            <v-img
              dark
              content
              class="black--text align-end"
              src="https://www.portafolio.co/files/article_multimedia/uploads/2019/01/28/5c4f12efa7dda.jpeg"
            >
              <v-card-title>
                <div>
                  Abren segundo plazo para aplicar a <br />
                  subsidios por contratar a jóvenes
                </div>
              </v-card-title>
            </v-img>
            <v-card-subtitle class="pb-0">Agosto 31, 2021</v-card-subtitle>
            <v-card-text class="text--primary">
              <div>
                Empleadores interesados podrán presentarse del 1 al 9 de
                septiembre ante la entidad financiera con la que tengan su
                cuenta de depósito.
              </div>
            </v-card-text>
            <v-divider></v-divider>
            <v-card-actions>
              <v-btn
                color="orange"
                text
                href="https://www.portafolio.co/economia/empleo/segundo-plazo-para-aplicar-a-subsidios-por-contratar-jovenes-ministerio-del-trabajo-555747"
                target="blank"
              >
                Leer noticia completa
              </v-btn>
            </v-card-actions>
          </v-card>
        </v-col>
        <v-col>
          <v-card hover class="mx-auto" max-width="375">
            <v-img
              dark
              content
              class="white--text align-end"
              src="https://www.portafolio.co/files/article_multimedia/uploads/2021/07/10/60e950565588a.jpeg"
            >
              <v-card-title>
                <div>
                  En julio, mujeres consiguieron más <br />
                  trabajo que los hombres
                </div>
              </v-card-title>
            </v-img>
            <v-card-subtitle class="pb-0">Agosto 31, 2021</v-card-subtitle>
            <v-card-text class="text--primary">
              <div>
                El Dane destacó cómo de 2,9 millones de puestos de trabajo que
                se recuperaron, ellas ocuparon 1,5 millones.
              </div>
            </v-card-text>
            <v-divider></v-divider>
            <v-card-actions>
              <v-btn
                color="orange"
                text
                href="https://www.portafolio.co/economia/empleo/en-julio-se-recupero-mas-el-empleo-femenino-que-el-de-hombres-555734"
                target="blank"
              >
                Leer noticia completa
              </v-btn>
            </v-card-actions>
          </v-card>
        </v-col>
        <v-col>
          <v-card hover class="mx-auto" max-width="375">
            <v-img
              dark
              content
              class="white--text align-end"
              src="https://www.portafolio.co/files/article_multimedia/uploads/2021/09/02/613170550e90e.jpeg"
            >
              <v-card-title>
                <div>
                  Más de 209.000 personas se <br />
                  'convirtieron' al teletrabajo durante <br />
                  2020
                </div>
              </v-card-title>
            </v-img>
            <v-card-subtitle class="pb-0">Septiembre 02, 2021</v-card-subtitle>
            <v-card-text class="text--primary">
              <div>
                El año pasado, cuatro de cada 10 empresas implementaron una
                modalidad de trabajo remoto y dos de cada 10 lo acogieron de
                manera formal.
              </div>
            </v-card-text>
            <v-divider></v-divider>
            <v-card-actions>
              <v-btn
                color="orange"
                text
                href="https://www.portafolio.co/innovacion/personas-que-se-convirtieron-en-teletrabajadores-en-colombia-durante-2020-ministerio-de-las-tic-555837"
                target="blank"
              >
                Leer noticia completa
              </v-btn>
            </v-card-actions>
          </v-card>
        </v-col>
      </v-row>
      <v-row>
        <v-col>
          <v-card hover class="mx-auto" max-width="375">
            <v-img
              dark
              content
              class="white--text align-end"
              src="https://www.portafolio.co/files/article_multimedia/uploads/2020/12/29/5feb8ec096adb.jpeg"
            >
              <v-card-title>
                <div>
                  Samsung abre curso para 600 <br />
                  jóvenes en codificación y <br />
                  programación
                </div>
              </v-card-title>
            </v-img>
            <v-card-subtitle class="pb-0">Septiembre 03, 2021</v-card-subtitle>
            <v-card-text class="text--primary">
              <div>
                La multinacional, en alianza con la Universidad Javeriana,
                realizará las capacitaciones gratuitas en habilidades
                tecnológicas.
              </div>
            </v-card-text>
            <v-divider></v-divider>
            <v-card-actions>
              <v-btn
                color="orange"
                text
                href="https://www.portafolio.co/tendencias/samsung-abre-curso-para-600-jovenes-en-codificacion-y-programacion-555866"
                target="blank"
              >
                Leer noticia completa
              </v-btn>
            </v-card-actions>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </v-content>
</template>

<script>
export default {
  name: "Nosotros",

  data: () => ({}),

  methods: {
    verlogin() {
      this.$router.push("login");
      // this.$router.push({name: 'login', path: '/login'})
    },
  },
};
</script>

<style scoped>
h1 {
  text-align: center;
  color: #364c63;
}

h3 {
  text-align: center;
  color: #f3b340;
}
</style>