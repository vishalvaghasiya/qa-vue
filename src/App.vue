<template>
    <!--<v-main>
        <HelloWorld/>
      </v-main>-->
    <v-app>
        <v-main>
            <HeaderComponent></HeaderComponent>
            <router-view></router-view>
        </v-main>
    </v-app>
</template>

<script>
    // import HelloWorld from './components/HelloWorld';
    import HeaderComponent from "./components/common/HeaderComponent";

    export default {
        name: 'App',

        components: {
            HeaderComponent,
            // HelloWorld,
        },

        data: () => ({
            //
        }),
    };
</script>
