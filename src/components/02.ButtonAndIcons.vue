<template>
    <div>
       <v-btn class="pink white--text">Click Me</v-btn>
       <v-btn  color="yellow" v-on:click="()=>{click()}">Click Me</v-btn>
       <v-btn text color="pink" >Click Me</v-btn>
       <v-btn  color="green" loading>Click Me</v-btn>
       <v-btn outlined color="green">Click Me</v-btn>
       <v-btn rounded color="blue">Click Me</v-btn>
       <v-btn class="ma-2" dark>
        <v-icon dark left >delete</v-icon>Cancel
      </v-btn>
      <v-btn depressed small>
          Small
      </v-btn>
      <v-btn depressed Large>
          Large
      </v-btn>
    </div>
</template>
<style>
</style>
<script>
    export default {
        name: "ButtonsAndIcons",
        data: ()=> ({

        }),
        methods: {
            click: ()=> {
                console.log("Hasi")
            }
        },
    }
</script>