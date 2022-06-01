<template>
    <v-app-bar
        color="green"
        dense
        elevation="3"
        rounded
    >
    <v-app-bar-nav-icon>
    </v-app-bar-nav-icon>
    <v-spacer></v-spacer>
          <div class="d-flex align-center" style="width:200px">
            <v-img
                alt="mushroom img"
                class="shrink mr-2"
                contain
                src="img/resize.webp"
                transition="scale-transition"
                width="100%"
            />
          </div>
    
    
    </v-app-bar>
</template>

<script>
  export default {
    name: 'NavBar'
  }
</script>