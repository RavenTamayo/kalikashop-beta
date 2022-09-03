<template>
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
    <v-row justify="center">
    <v-spacer></v-spacer>
      <v-col cols="auto">
        <v-btn variant="outlined" href="/about" rounded="0">Learn More</v-btn>
      </v-col>
      <v-spacer></v-spacer>
    </v-row>
  </v-container>

  <!--Featured Products-->
  <v-container fluid>
    <v-row>
      <v-spacer></v-spacer>
      <v-col>
        <div class="text-h3 text-center mt-5" fill-height>Featured Products</div>
        <div class="text-body-1 text-center mt-3">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ea eveniet velit ratione voluptatibus similique quam recusandae at magni. Illum vel dolorem dolor ipsum sint. Illo minima perferendis corporis est doloribus ipsum veniam numquam porro? Debitis quod explicabo dolore in autem velit quam sunt. Delectus explicabo tenetur velit quod nisi dolorem inventore pariatur neque. Sed laudantium voluptate labore tempore quisquam obcaecati ut deleniti illo, quo quia distinctio debitis autem molestias est beatae. Voluptate quia placeat officiis delectus eius provident quos cumque?</div>
      </v-col>
      <v-spacer></v-spacer>
    </v-row>
    <v-row justify="center">
    <v-spacer></v-spacer>
      <v-col cols="auto">
        <v-btn rounded="0" color="green-lighten-1 text-white" href="/store">Shop Now</v-btn>
      </v-col>
      <v-spacer></v-spacer>
    </v-row>
  </v-container>
</template>

<script setup>
</script>

<style scoped>
#container{
  background: url('src/images/home-bg2.png');
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;
  height:60%;
   
}
</style>


