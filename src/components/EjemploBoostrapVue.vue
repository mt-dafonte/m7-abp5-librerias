<script>
export default {
  name: 'EjemploBootstrapVue',
  data() {
    return {
      nombre: '',
      mensaje: '',
    }
  },
  methods: {
    saludar() {
      this.mensaje = `Hola, ${this.nombre || 'visitante'} 👋`
    }
  }
}
</script>

<template>
  <b-container class="mt-4">
    <b-row class="justify-content-center">
      <b-col cols="12" md="6">

        <b-card title="Formulario de saludo" class="text-center">

          <b-form-input
            v-model="nombre"
            placeholder="Escribe tu nombre"
            class="mb-3"
          />

          <b-button variant="primary" @click="saludar">
            Saludar
          </b-button>

          <hr>

          <p class="mt-3" v-if="mensaje">
            {{ mensaje }}
          </p>

        </b-card>

      </b-col>
    </b-row>
  </b-container>
</template>