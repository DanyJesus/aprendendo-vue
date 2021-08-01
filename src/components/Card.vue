<template>
  <div>
    <b-col >
      <b-card
      :title="nome"
        header="Primary"       
        img-src="https://picsum.photos/id/237/200/300"
        img-alt="Curso de Vue.JS"
        img-top
        tag="article"
        style="max-width:20rem;"
        class="mb-5"
        border-variant="primary"
        header-bg-variant="primary"
        header-text-variant="white"
        align="center"
         >
        <b-card-text>"Honra teu pai e tua mãe, a fim de que tenhas vida longa na terra que o Senhor,o teu Deus, te dá.</b-card-text>
        <b-button variant="primary">Comprar</b-button>
      </b-card>
    </b-col>
  </div>
</template>

<script>
export default {
    props: {
        nome: {
            type: String,
            required: true,
        }
    },

};
</script>