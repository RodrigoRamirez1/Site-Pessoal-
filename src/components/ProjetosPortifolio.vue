<template>
    <v-container>
        <v-row class="text-center mt-16">
            <v-col cols="12">
                <titulo-pagina titulo1="Navegar em Meus recentes" titulo2="Projetos"/>
            </v-col> 
            <v-row>
                <v-col cols="4">
                    <card-projetos imagem="../numero-secreto.png" tProjeto="Número Secreto"/> 
                </v-col>
                <v-col cols="4">
                    <card-projetos imagem="../biblioteca-digital.jpg" tProjeto="Biblioteca Digital"/> 
                </v-col>
                <v-col cols="4">
                    <card-projetos imagem="../alura-books.jpg" tProjeto="Alura Books"/> 
                </v-col>
                <v-col cols="4">
                    <card-projetos imagem="../super-mario.png" tProjeto="Divulgação Filme -Mario Bros"/> 
                </v-col>
                <v-col cols="4">
                    <card-projetos imagem="../to-do.jpg" tProjeto="To Do"/> 
                </v-col>
                <v-col cols="4">
                    <card-projetos imagem="../rez-bank.jpg" tProjeto="RezBank"/> 
                </v-col>
                  
            </v-row>
        </v-row>
       
    </v-container>
</template>

<script>
    import TituloPagina from '../components/TituloPagina'
    import CardProjetos from '../components/CardProjetos'

export default {
    components: {
        TituloPagina, CardProjetos,
    }
}

</script>