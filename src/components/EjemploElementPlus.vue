<script>
export default {
  name: 'EjemploElementPlus',

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
  <div style="max-width: 600px; margin: 40px auto;">

    <el-card shadow="hover">

      <h2 style="text-align:center; margin-bottom: 20px;">
        Formulario de saludo
      </h2>

      <el-input
        v-model="nombre"
        placeholder="Escribe tu nombre"
        clearable
        class="mb-4"
      />

      <el-button
        type="primary"
        @click="saludar"
      >
        Saludar
      </el-button>

      <el-divider></el-divider>

      <p v-if="mensaje" style="text-align:center;">
        {{ mensaje }}
      </p>

    </el-card>

  </div>
</template>

<style>
.mb-4 {
  margin-bottom: 16px;
}
</style>