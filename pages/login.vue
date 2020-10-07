<template lang="pug">
  div
    h1 Login
    v-container
      v-row(
        align="center"
        justify="center"
      )
        v-col(
          cols="12"
          sm="8"
          md="6"
        )
          v-card(
            class="elevation-12"
          )
            v-toolbar
              v-toolbar-title Inicio de sesión
            v-card-text
              v-form
                v-text-field(
                  label="Correo"
                  type="email"
                )
                v-text-field(
                  label="Contraseña"
                  type="password" 
                )
            v-card-actions
              v-spacer
              v-btn( @click="iniciarSesion()" ) Iniciar sesión          
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  methods: {
    iniciarSesion() {
      console.log("inició sesión")
    }
  }
})
</script>