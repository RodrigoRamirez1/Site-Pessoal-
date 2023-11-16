<template>
    <v-row >
        <v-col cols="12">
            <p>{{ titulo1 }}</p>
            <h1>{{ titulo2 }}</h1>
        </v-col>
    </v-row>
</template>

<script>
export default {
    props: {
        titulo1: String,
        titulo2: String,
    }
}

</script>

<style scoped>
p {
    font-size: 1rem;
    margin-bottom: 0;
}

h1 {
    font-size: 3rem;
}

</style>