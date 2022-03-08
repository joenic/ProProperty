<template>
  <v-container>
    <v-row justify="space-around">
      <v-card width="400">
        <v-img
          height="200px"
          src="data:image/jpeg;base64,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"
        >
          <v-app-bar
            flat
            color="rgba(0, 0, 0, 0)"
          >

            <v-toolbar-title class="text-h6 white--text pl-0">
              Sign In
            </v-toolbar-title>

            <v-spacer></v-spacer>

            <router-link to="/">
              <v-btn
                color="white"
                icon
              >
                <v-icon>mdi-dots-vertical</v-icon>
              </v-btn>
            </router-link>
          </v-app-bar>

          <v-row justify="space-around" align="center">
              <v-avatar size="120" color="indigo">
                <v-icon dark size="120">
                    mdi-account-circle
                </v-icon>
              </v-avatar>
          </v-row>
        </v-img>

        <v-card-text>
          <v-text-field block class="ma-2" outlined label="Email">Sign In</v-text-field>

          <v-spacer></v-spacer>

          <v-text-field block class="ma-2" outlined label="Password"></v-text-field>

          <v-spacer></v-spacer>

          <v-btn block class="pa-1" outlined> Login</v-btn>

          <v-spacer></v-spacer>

          <router-link to="/signup">
            <v-btn block class="pa-1" outlined> Create Account</v-btn>
          </router-link>
        </v-card-text>
      </v-card>
    </v-row>
  </v-container>
</template>

<script>
export default {

}
</script>

<style>

</style>