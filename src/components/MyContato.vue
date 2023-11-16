<template>
    <v-container>
        <v-row class="text-center mt-16" justify="center">
            <v-col cols="12">
                <titulo-pagina titulo1="Entrar em Contato" titulo2="Contate-Me"/>
            </v-col>
            <v-col cols="12">
                <v-row class="text-center mt-4">
                    <v-col>
                        <span  class="text-center borda pa-8">
                            <v-avatar class="mx-3" size="50">
                                <img src="../assets/email.png" alt="Email icon"/>
                            </v-avatar>
                                <a class="hover mr-3" href="mailto:rodrigopinheiroramirez@gmail.com" target="_blank">rodrigopinheiroramirez@gmail.com</a>
                            <v-avatar class=" mx-3" size="40">
                                <img src="../assets/linkedin.png" alt="Linkedin icon"/>
                            </v-avatar>
                                <a class="hover mr-3" href="https://www.linkedin.com/in/rodrigo-pinheiro-ramirez-30482a231/" target="_blank">Linkedin</a>
                        </span>
                    </v-col>
                </v-row>
            </v-col>
            <v-row class="mt-8">
                <v-col col="12" >
                    <v-btn text rounded large>Sobre</v-btn>
                    <v-btn text rounded large>Experiência</v-btn>
                    <v-btn text rounded large>Projetos</v-btn>
                    <v-btn text rounded large>Contato</v-btn>
                </v-col>
                <v-col class="mt-5" cols="12">
                    <p id="rodape">Copyright &#169; 2023 Rodrigo Pinheiro Ramirez. Todos os direitos reservados.</p>
                </v-col>
            </v-row>
        </v-row>
        
    </v-container>
</template>

<script>
    import TituloPagina from '../components/TituloPagina.vue'

export default {
    components: { TituloPagina,
    }
}

</script>

<style scoped>
.borda {
    border: 1px solid gray;
    border-radius: 30px;
}
.hover {
    color: black;
    text-decoration: none;
}
.hover:hover {
    color: gray;
}

#rodape {
    color: grey;
}
</style>