<script>
export default {
  name: 'EjemploVuetify',

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
  <v-container class="mt-6">
    <v-row justify="center">
      <v-col cols="12" md="6">

        <v-card class="pa-6" elevation="4">

          <v-card-title class="text-center">
            Formulario de saludo
          </v-card-title>

          <v-text-field
            v-model="nombre"
            label="Escribe tu nombre"
            variant="outlined"
            class="mb-4"
          />

          <v-btn
            color="primary"
            @click="saludar"
          >
            Saludar
          </v-btn>

          <v-divider class="my-4"></v-divider>

          <p
            class="text-center"
            v-if="mensaje"
          >
            {{ mensaje }}
          </p>

        </v-card>

      </v-col>
    </v-row>
  </v-container>
</template>