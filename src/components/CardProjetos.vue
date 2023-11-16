<template>
    <v-row class="mt-5">
        <v-col cols="12">
            <v-card class="text-center" light shaped elevation="5">
                    <v-img v-bind:src="imagem" alt=""></v-img>
                <h2 class="mt-2">{{ tProjeto }}</h2>
                <v-row  dense>
                    <v-col >
                        <a href=""><v-btn class=" mx-6 mb-6" elevation="2" outlined rounded>GitHub</v-btn></a>
                        <a href=""><v-btn class=" mx-6 mb-6" elevation="2" outlined rounded>Acesse</v-btn></a>
                    </v-col>
                </v-row>
            </v-card>
        </v-col>
    </v-row>
</template>

<script>

export default {
    props: {
        imagem: String,
        tProjeto: String,
    },
    computed: {
        imagemProcessada() {
            return this.imagem
        }
    },
    data:() => {
        return {
            
        }
    }
}
</script>

<style scoped>
.fonte-linguagem {
    font-weight: bold;
    size: 1.5rem;
}


</style>