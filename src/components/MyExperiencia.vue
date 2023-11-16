<template>
    <v-container>
        <v-row class="text-center mt-16">
            <v-col cols="12">
                <titulo-pagina titulo1="Exprore Minhas" titulo2="Experiências"/>
            </v-col>
            <v-row class="mt-5">
                <v-col cols="12" class="borda mr-2" >
                    <h2>Desenvolvimento Front-End</h2>
                    <v-row class="mt-8">
                        <v-col cols="3" v-for="habilidade in habilidades" :key="habilidade.nome">
                            <item-experiencia :nome="habilidade.nome" :descricao="habilidade.descricao"/>
                        </v-col>
                    </v-row>
                </v-col>
            </v-row>
        </v-row>
    </v-container>
</template>

<script>
    import TituloPagina from '../components/TituloPagina.vue'
    import ItemExperiencia from '../components/ItemExperiencia.vue'

export default {
    components: {
        ItemExperiencia, TituloPagina,
    },
    data: () => {
        let b = 'Básico'
        let i =  'Intermediário'

        return {
            habilidades: [
                {nome:'HTML', descricao:i},
                {nome:'CSS', descricao:i},
                {nome:'JavaScript', descricao:i},
                {nome:'Vue.js', descricao:i},
                {nome:'Vuetify', descricao:b},
                {nome:'Bootstrap', descricao:b},
                {nome:'Figma', descricao:b},
                {nome:'C', descricao:b},
                {nome:'Python', descricao:i},
                {nome:'SQLite', descricao:i},
                {nome:'Git', descricao:b},
                {nome:'GitHub', descricao:i},

            ],
        }
        
    }

}

</script>

<style scoped>
.borda {
    border: 1px solid grey ;
    border-radius: 50px;
}
</style>