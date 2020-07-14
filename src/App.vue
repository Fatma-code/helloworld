
<template>
<div id="app">
    <v-card
      color="white"
      flat
      height="600px"
      tile
      >
      <v-toolbar>
        <v-app-bar-nav-icon to="/"></v-app-bar-nav-icon>
        <v-toolbar-title>Title</v-toolbar-title>
        <v-spacer></v-spacer>
        <v-btn flat to="/signup">Sign up</v-btn>
        <v-btn flat to="/login">Log in</v-btn>
        <v-btn flat to="userlist">User List</v-btn>
      </v-toolbar>
       <router-view/>
    </v-card>
  <v-footer clas="pa-3" color="#00000"  fixed>
      <v-spacer></v-spacer>
     <div class="one">© division5 2020</div>
      <v-spacer></v-spacer>  
    </v-footer>
</div>
</template>

 <script>

</script>
<style>

  
</style>