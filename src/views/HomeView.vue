<template>
  <NavBar/>
  <!--Header-->
  <v-container fluid id="container">
    <v-row class="mt-16 mb-16">
      <v-spacer></v-spacer>
        <v-col>
          <div class="text-body-2 text-green font-weight-black">Lorem ipsum dolor sit amet consectetur adipisicing.</div>
          <div class="text-white text-h1">Welcome to KalikaShop</div>
          <div class="text-caption text-white">Lorem ipsum dolor sit amet consectetur adipisicing elit. Minima iure quos adipisci itaque? Et, incidunt! Animi error numquam quae omnis!</div>
          <v-btn rounded="0" color="green-lighten-1 text-white mt-4" href="/store">Shop Now</v-btn></v-col>
          <v-spacer></v-spacer>
    </v-row>
  </v-container>

  <!--What we do-->
  <v-container fluid>
    <v-row>
      <v-spacer></v-spacer>
      <v-col>
        <div class="text-h3 text-center mt-5" fill-height>What We Do</div>
        <div class="text-body-1 text-center mt-3">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ea eveniet velit ratione voluptatibus similique quam recusandae at magni. Illum vel dolorem dolor ipsum sint. Illo minima perferendis corporis est doloribus ipsum veniam numquam porro? Debitis quod explicabo dolore in autem velit quam sunt. Delectus explicabo tenetur velit quod nisi dolorem inventore pariatur neque. Sed laudantium voluptate labore tempore quisquam obcaecati ut deleniti illo, quo quia distinctio debitis autem molestias est beatae. Voluptate quia placeat officiis delectus eius provident quos cumque?</div>
      </v-col>
      <v-spacer></v-spacer>
    </v-row>
    <v-row>
    <v-spacer></v-spacer>
      <v-col cols="auto">
        <v-btn variant="outlined" href="/about" rounded="0">Learn More</v-btn>
      </v-col>
      <v-spacer></v-spacer>
    </v-row>
  </v-container>

  <v-divider class="mx-6 mt-5"></v-divider>
  <!--Featured Products-->
  <v-container fluid>
    <v-row>
      <v-spacer></v-spacer>
      <v-col>
        <div class="text-h3 text-center mt-5" fill-height>Featured Products</div>
      </v-col>
      <v-spacer></v-spacer>
    </v-row>
    <v-row justify="center">
    <v-col cols="auto">
      <v-card
          class="mx-auto"
          max-width="300"
        >
          <v-img
            class="align-end text-white"
            height="200"
            src="src\images\product2.webp"
            cover
          >
            <v-card-title class="text-green">Eco Shirt</v-card-title>
          </v-img>

          <v-card-subtitle class="pt-4">
            ₱ 250.00
          </v-card-subtitle>

          <v-card-text>
           <div class="text-caption">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nam, blanditiis.</div>
          </v-card-text>
        </v-card>
    </v-col>

    <v-col cols="auto">
        <v-card
          class="mx-auto"
          max-width="300"
        >
          <v-img
            class="align-end text-white"
            height="200"
            src="src/images/product1.webp"
            cover
          >
            <v-card-title class="text-green">Sustainable Design</v-card-title>
          </v-img>

          <v-card-subtitle class="pt-4">
            ₱ 450.00
          </v-card-subtitle>

          <v-card-text>
            <div class="text-caption">Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolor, deleniti.</div>
          </v-card-text>
        </v-card>
      </v-col>

      <v-col cols="auto">
      <v-card
          class="mx-auto"
          max-width="300"
        >
          <v-img
            class="align-end text-white"
            height="200"
            src="src/images/product3.webp"
            cover
          >
            <v-card-title class="text-green">TOM'S Shoes</v-card-title>
          </v-img>

          <v-card-subtitle class="pt-4">
            ₱ 2,450.00
          </v-card-subtitle>

          <v-card-text>
            <div class="text-caption">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Culpa, dolores.</div>
          </v-card-text>
        </v-card>
    </v-col>
    </v-row>
    <v-row>
    <v-spacer></v-spacer>
      <v-col cols="auto">
        <v-btn rounded="0" color="green-lighten-1 text-white" href="/store">Shop Now</v-btn>
      </v-col>
      <v-spacer></v-spacer>
    </v-row>
    <v-divider class="mx-6 mt-5"></v-divider>
  </v-container>
</template>

<script setup>
  import NavBar from '@/components/NavBar.vue'
</script>

<style scoped>
#container{
  background: url('src/images/home-bg2.png');
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;
  height:35%;   
}
</style>


