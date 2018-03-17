<template>
    <v-layout  row justify-center>
        <v-flex xs12 sm6 md3>
            <v-card>
                <v-card-media src="https://vuetifyjs.com/static/doc-images/cards/desert.jpg" height="200px">
                </v-card-media>
                <v-card-title primary-title>
                    <div>
                        <h3 class="headline mb-0">Kangaroo Valley Safari</h3>
                        <div>Located two hours south of Sydney in the <br>Southern Highlands of New South Wales, ...</div>
                    </div>
                </v-card-title>
                <v-card-actions>
                    <v-btn flat color="orange">Share</v-btn>
                    <v-btn flat color="orange">Explore</v-btn>
                </v-card-actions>
            </v-card>
        </v-flex>
    </v-layout>
</template>

<script>
    export default {
        name: "cardcomponent"
    }
</script>

<style scoped>
    .layout{
        margin-top: 10px;
    }
    .card {
        box-shadow: none;
    }
</style>