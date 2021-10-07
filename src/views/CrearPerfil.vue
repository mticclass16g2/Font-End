<template>
  <v-app>
    <v-content>
      <v-card width="550" class="mx-auto mt-9">
        <v-img
          contain
          max-height="80"
          src="https://i.ibb.co/x15GLkz/react-vate-logo-transp-929x172.png"
        ></v-img>
        <v-card-title class="justify-center"> Crear Mi Perfil </v-card-title>
        <v-card-text>
          <v-text-field
            label="Correo electrónico"
          />

          <v-text-field
            label="Contraseña:"
          />

          <v-text-field
            label="Confirma tu contraseña:"
          />

          <v-text-field label="Documento identidad:" />

          <v-text-field label="Tipo documento:" />

          <v-text-field label="Nombre completo:" />

          <v-text-field label="Apellido completo:" />

          <v-text-field label="Teléfono móvil:" />

          <v-text-field label="Ciudad de residencia:" />

          Acepto los términos, condiciones y políticas de privacidad de este
          sitio.
        </v-card-text>

        <v-card-actions>
          <v-btn rounded color="#364c63" dark class="mb-6">Registrarme</v-btn>
        </v-card-actions>
      </v-card>
    </v-content>
  </v-app>
</template>

<script>
export default {
  data() {
    return {
      showPassword: false,
    };
  },
};
</script>
