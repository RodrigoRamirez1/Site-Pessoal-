<template>
  <div>
    <pagina-principal/>
    <sobre-mim/>
    <my-experiencia/>
    <projetos-portifolio/>
    <my-contato/>
  </div>
</template>

<script>
  import PaginaPrincipal from '../components/PaginaPrincipal'
  import SobreMim from '../components/SobreMim'
  import MyExperiencia from '../components/MyExperiencia'
  import ProjetosPortifolio from '../components/ProjetosPortifolio'
  import MyContato from '../components/MyContato'

  export default {
    name: 'Home',

    components: {
      PaginaPrincipal, SobreMim, MyExperiencia, ProjetosPortifolio, MyContato
    },
  }
</script>
