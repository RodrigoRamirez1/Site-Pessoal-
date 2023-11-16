<template>
    <v-container>
        <v-row class="text-center mt-16">
            <v-col cols="12">
                <titulo-pagina titulo1="Conheça Mais" titulo2="Sobre Mim"/>
            </v-col>
                <v-col cols="5" class="mt-8 mr-5">
                    <v-avatar rounded size="400" >
                        <img class="borda-img" src="../assets/sobre-mim.jpeg" alt="">
                    </v-avatar>
                </v-col>
                <v-col>
                    <v-row>
                        <v-col class="borda mt-10 mr-10">
                            <v-avatar class=" mt-3  mx-2" size="40">
                                <img src="../assets/experiencia.png" alt="">
                            </v-avatar><br>
                            <h3>Experiência</h3>
                            <p>1 ano <br>Desenvolvimento Front-End</p>
                        </v-col>
                        <v-col class="borda mt-10 ml-10">
                            <v-avatar class=" mt-3  mx-2" size="40">
                                <img src="../assets/educacao.png" alt="">
                            </v-avatar><br>
                            <h3>Formação</h3>
                            <p>Bacharel em Filosofia <br> Estudante Desenvolvimento web</p>
                        </v-col>
                        <v-col cols="12" class="mt-5">
                            <div>
                                <p>Com uma sólida formação em Filosofia, ao longo da minha trajetória acadêmica, adquiri habilidades interpessoais, que se refletem em minha capacidade de comunicação, resolução de conflitos e trabalho em equipe. No entanto, atualmente, estou passando por uma transição de carreira, direcionando meu foco para a área da tecnologia, especificamente no campo do Desenvolvimento Web.
                                    Como estudante, tenho buscado ativamente aprimorar meu conhecimento em linguagens e lógica de programação. E estou determinado a ingressar no mundo da tecnologia como programador, aplicando meu conjunto de habilidades multidisciplinar e minha capacidade para criar soluções inovadoras.
                                </p>
                            </div>
                        </v-col> 
                    </v-row>
                   
                </v-col>
                
        </v-row>
    </v-container>
</template>

<script>
    import TituloPagina from '../components/TituloPagina.vue'

export default {
    components: {   TituloPagina,

    }
}


</script>

<style scoped>
.borda-img {
    border-radius: 50px;
}

.borda {
    border: 1px solid grey ;
    border-radius: 50px;
}

</style>