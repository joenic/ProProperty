<template>
  <v-container>
    <v-row justify="space-around">
      <v-card class="ma-2" width="400">
        <v-img
          height="200px"
          src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTQDcdlt2oAwhMxEqQ-wi4SKQ6oWd6XAk1xDg&usqp=CAU"
        >
          <v-app-bar
            flat
            color="rgba(0, 0, 0, 0)"
          >

            <v-toolbar-title class="text-h6 white--text pl-0">
              Main Menu
            </v-toolbar-title>

            <v-spacer></v-spacer>

            <v-btn
              color="white"
              icon
            >
              <v-icon>mdi-dots-vertical</v-icon>
            </v-btn>
          </v-app-bar>

        </v-img>

        <v-card-text>

          <router-link to="/login">
            <v-btn block class="ma-2" outlined >Sign In</v-btn>
          </router-link>

          <v-spacer></v-spacer>

          <router-link to="/signup">
            <v-btn block class="ma-2" outlined >Sign Up</v-btn>
          </router-link>

          <v-spacer></v-spacer>

          <v-btn disabled block class="ma-2" >Run the Numbers like a Pro</v-btn>
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