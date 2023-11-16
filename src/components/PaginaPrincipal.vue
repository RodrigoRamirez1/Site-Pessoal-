<template>
  <v-container>
    <v-row class="text-center">
      <v-col cols="12">
        <v-row>
          <v-col cols="6">
            <v-img max-height="100" max-width="350" src="../assets/logo-perfil.jpeg">
            </v-img>
          </v-col>
          <div class="mt-5"> 
            <v-col >
            <v-btn text rounded large>Sobre</v-btn>
            <v-btn text rounded large>Experiência</v-btn>
            <v-btn text rounded large>Projetos</v-btn>
            <v-btn text rounded large>Contato</v-btn>
          </v-col>
          </div>
        </v-row>
      </v-col>
      
      <v-col cols="12" class="mt-12">
        <v-row>
          <v-col cols="6" class="d-flex justify-end pr-8 mt-12">
            <v-avatar size="350"> <img src="../assets/rodrigo.jpeg" alt=""></v-avatar>
          </v-col>
          <v-col class="d-flex justify-start pl-5 margin-t">
            <div>
              <p id="font" >Olá, Eu sou</p>
              <h1>Rodrigo Ramirez</h1>
              <h2>Desenvolvedor Front-End</h2><br>
              <v-col>
                <a :href="dow" target="_blank"><v-btn class="mx-2" elevation="2" outlined rounded>Curriculo</v-btn></a>
                <v-btn class="mx-2 " dark elevation="2" rounded >Contato</v-btn>
              </v-col>
              <a href="https://www.linkedin.com/in/rodrigo-pinheiro-ramirez-30482a231/" target="_blank">
                <v-avatar class=" mt-3  mx-2" size="40">
                  <img src="../assets/linkedin.png" alt="perfil linkedin">
                </v-avatar>
              </a>
              <a href="https://github.com/RodrigoRamirez1" target="_blank">
                <v-avatar class="mt-3 mx-2" size="40">
                  <img src="../assets/github.png" alt="perfil github">
                </v-avatar></a>
            </div>
            
          </v-col>
        </v-row>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
  export default {
    name: 'PaginaPrincipal',

    data() {
      return {
        dow: '/curriculum.pdf',
      }
    },
    
  }
</script>

<style scoped>
.margin-t {
  margin-top: 8%;
}

#font {
  font-size: 1rem;
}

h1 {
    font-size: 3rem;
}

</style>