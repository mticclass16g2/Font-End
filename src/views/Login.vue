<template>
  <v-app>
    <v-content>
      <v-card width="550" class="mx-auto mt-9">
        <v-img
          contain
          max-height="80"
          src="https://i.ibb.co/x15GLkz/react-vate-logo-transp-929x172.png"
        ></v-img>
        <v-card-title class="justify-center">
          Ingresa a tu cuenta
        </v-card-title>
        <v-card-text>
          <v-text-field
            label="Correo electrónico"
            prepend-icon="mdi-account-circle"
          />
          <v-text-field
            label="Contraseña"
            :type="showPassword ? 'text' : 'password'"
            prepend-icon="mdi-lock"
            :append-icon="showPassword ? 'mdi-eye' : 'mdi-eye-off'"
            @click:append="showPassword = !showPassword"
          />
        </v-card-text>

        <v-card-actions>
          <v-btn rounded color="#364c63" dark class="mb-6" @click="verlogin"
            >Iniciar Sesión</v-btn
          >
        </v-card-actions>
        <v-card-text>
          <div>Olvidé mi usuario o contraseña</div>
        </v-card-text>

        <v-divider class="mx-4"></v-divider>

        <v-card-title> ¿No tienes una cuenta? Registrate ahora </v-card-title>

        <v-card-actions>
          <v-btn rounded color="success" dark class="mb-6" @click="crearperfil"
            >Registrarme</v-btn
          >
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
  methods: {
    crearperfil() {
      this.$router.push("suscripciones");
      // this.$router.push({name: 'suscripciones', path: '/suscripciones'})
    },
  },
};
</script>
