<template>
  <section id="download">
     <!-- <v-parallax :src="require(`@/assets/img/bgx.jpg`)" height="800"> -->
    <v-container fluid >
      <v-row align="center" justify="center">
        <v-col cols="10">
          <v-row align="center" justify="center">
            <v-col sm="4" class="hidden-xs-only">
        
              <v-img :src="require(`@/assets/img/Arvore.png`)" class="d-block ml-auto mr-auto" max-width="2000"
             />
               
            </v-col>
            <v-col cols="12" sm="8" class="dark--text ">
              <h1 class="centered-text font-weight-bold mt-6 display-2 mt-12 mb-6">Sobre nós</h1>
              <v-col>
                <h3 class="font-weight centered-text mt-4">
           Somos uma clínica multidisciplinar com profissionais qualificados da área da saúde que visam o bem-estar
           emocional e físico de seus pacientes.
           Temos como premissa básica proporcionar momentos de escuta e conforto, com ética, atenção, eficiência,
           qualidade e sigilo.
           Nossa grande paixão, são as pessoas! Com isso, objetivamos nosso trabalho no processo de alívio, facilitando
           o caminho ao auto entendimento, com sustentação, para que o paciente consiga lidar com suas queixas e/ou
           possível diagnóstico de forma saudável e verdadeira, unificando seu cuidado em um espaço de carinho e
           cuidado.

                </h3>
                </v-col>
               
              <v-btn  rounded outlined color="#03989E" @click="$vuetify.goTo('#especialidades')" large class="mt-12 mb-12">
                <v-icon class="mr-3">
                  mdi-book
                </v-icon>
                <h4>Agende sua Consulta</h4>
              </v-btn>
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </v-container>
     <!-- </v-parallax> -->
  </section>
</template>

<style scoped>
#download {
  background-image: url("~@/assets/img/bgx.jpg") !important;
  /* background-attachment: fixed; */
  background-repeat: no-repeat; 
  /* background-size: cover; */
  /* background-position: center; */

}

  .centered-text {
    color: #037682;

  }

</style>

