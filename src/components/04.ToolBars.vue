<template>
    <nav>
     <v-toolbar dark flat >
         <v-toolbar-title class="text-uppercase">
             <span class="font-weight-light">Hasi</span>
             <span>Apps</span>
         </v-toolbar-title>
         <v-spacer/>
         <v-btn text color="grey">
         <span>
             Sign Out
             <v-icon right>exit_to_app</v-icon>
         </span>
     </v-btn>
     </v-toolbar>
     
     <h1>Hello World</h1>
    </nav>
</template>
<style>
</style>
<script>
    export default {
        name: "ToolBars",
        data: ()=> ({})
    }
</script>