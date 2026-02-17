<script setup>
const headers = [
    { title: 'Plant', align: 'start', sortable: false, key: 'name' },
    { title: 'Light', align: 'end', key: 'light' },
    { title: 'Height', align: 'end', key: 'height' },
    { title: 'Pet Friendly', align: 'end', key: 'petFriendly' },
    { title: 'Price ($)', align: 'end', key: 'price' },
]

const plants = [
    {
        name: 'Fern',
        light: 'Low',
        height: '20cm',
        petFriendly: 'Yes',
        price: 20,
    },
    {
        name: 'Snake Plant',
        light: 'Low',
        height: '50cm',
        petFriendly: 'No',
        price: 35,
    },
    {
        name: 'Monstera',
        light: 'Medium',
        height: '60cm',
        petFriendly: 'No',
        price: 50,
    },
    {
        name: 'Pothos',
        light: 'Low to medium',
        height: '40cm',
        petFriendly: 'Yes',
        price: 25,
    },
    {
        name: 'ZZ Plant',
        light: 'Low to medium',
        height: '90cm',
        petFriendly: 'Yes',
        price: 30,
    },
    {
        name: 'Spider Plant',
        light: 'Bright, indirect',
        height: '30cm',
        petFriendly: 'Yes',
        price: 15,
    },
    {
        name: 'Air Plant',
        light: 'Bright, indirect',
        height: '15cm',
        petFriendly: 'Yes',
        price: 10,
    },
    {
        name: 'Peperomia',
        light: 'Bright, indirect',
        height: '25cm',
        petFriendly: 'Yes',
        price: 20,
    },
    {
        name: 'Aloe Vera',
        light: 'Bright, direct',
        height: '30cm',
        petFriendly: 'Yes',
        price: 15,
    },
    {
        name: 'Jade Plant',
        light: 'Bright, direct',
        height: '40cm',
        petFriendly: 'Yes',
        price: 25,
    },
]
</script>

<template>
<h1>HOla desde index Students</h1>

<!--    <v-container>-->
<!--        <v-btn color="primary">Botón Vuetify</v-btn>-->
<!--    </v-container>-->

<!--    <v-card-->
<!--        class="mx-auto"-->
<!--        color="surface-variant"-->
<!--        image="https://cdn.vuetifyjs.com/docs/images/cards/dark-beach.jpg"-->
<!--        max-width="340"-->
<!--        subtitle="Take a walk down the beach"-->
<!--        title="Evening sunset"-->
<!--    >-->
<!--        < v-slot:actions>-->
<!--            <v-btn-->
<!--                append-icon="mdi-chevron-right"-->
<!--                color="red-lighten-2"-->
<!--                text="Book Activity"-->
<!--                variant="outlined"-->
<!--                block-->
<!--            ></v-btn>-->
<!--    </v-card>-->


<!--    <div class="text-center">-->
<!--        <v-chip-->
<!--            class="ma-2"-->
<!--            label-->
<!--            size="large"-->
<!--        >-->
<!--            Label-->
<!--        </v-chip>-->

<!--        <v-chip-->
<!--            class="ma-2"-->
<!--            color="pink"-->
<!--            label-->
<!--        >-->
<!--            <v-icon icon="mdi-label" start></v-icon>-->
<!--            Tags-->
<!--        </v-chip>-->

<!--        <v-chip-->
<!--            class="ma-2"-->
<!--            color="primary"-->
<!--            label-->
<!--        >-->
<!--            <v-icon icon="mdi-account-circle-outline" start></v-icon>-->
<!--            John Leider-->
<!--        </v-chip>-->

<!--        <v-chip-->
<!--            class="ma-2"-->
<!--            color="cyan"-->
<!--            closable-->
<!--            label-->
<!--        >-->
<!--            <v-icon icon="mdi-twitter" start></v-icon>-->
<!--            New Tweets-->
<!--        </v-chip>-->
<!--    </div>-->

    <v-data-table
        :headers="headers"
        :items="plants"
        density="compact"
        item-key="name"
    ></v-data-table>

</template>



<style scoped>

</style>
