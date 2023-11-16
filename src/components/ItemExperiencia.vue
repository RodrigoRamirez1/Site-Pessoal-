<template>
    <div class="mx-6">
            <v-icon>mdi-check-decagram</v-icon>
            <h3>{{ nome }}</h3>
            <p>{{ descricao }}</p>
    </div>
</template>

<script>
export default {
    props: {
        nome: String,
        descricao: String,
    }
}

</script>