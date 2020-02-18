<template>
    <nav>
     <v-toolbar dark flat >
         <v-btn fab @click="()=>openCloseDrawer()">
             <v-icon>menu</v-icon>
         </v-btn>
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
     
     <v-navigation-drawer  app class="success" v-model="drawer">
         <List />
     </v-navigation-drawer>
    </nav>
</template>
<style>
</style>
<script>
    import List from './06.Lists'

    export default {
        name: "ToolBars",
        data: ()=> ({
            drawer: false
        }),
        components: {
            List
        },
        methods: {
            openCloseDrawer (){
                this.drawer = !this.drawer
            }
        },
    }
</script>