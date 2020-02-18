<template>
    <div>
        <v-list>
        <v-list-item v-for="(da, index) in datas " :key="index">
            <v-list-item-action>
                <v-icon v-bind:class="`${color}--text`">{{da.icon}}</v-icon>
            </v-list-item-action>
            <v-list-item-content>
                <v-list-item-title class="white--text">
                    {{da.name}}
                </v-list-item-title>
            </v-list-item-content>
        </v-list-item>
    </v-list>
    </div>
</template>
<style>
</style>
<script>
    export default {
        name: "Lists",
        data: ()=> ({
            color: 'white',
            datas: [{
                name: 'Dashboard',
                icon: 'dashboard',
                route: '/'
            },{
                name: 'My Projects',
                icon: 'folder',
                route: '/'
            },{
                name: 'Team',
                icon: 'person',
                route: '/'
            }]
        })
    }
</script>