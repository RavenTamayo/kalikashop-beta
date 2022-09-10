<template>
    <nav>
        <v-toolbar app class>
         <v-app-bar-nav-icon @click='toggleDrawer'></v-app-bar-nav-icon>
        <v-toolbar-title >
            <v-avatar size="100">
                <v-img
                src="src\images\KalikaShop.png"
                cover
                ></v-img>
            </v-avatar>
        </v-toolbar-title>
        <v-spacer></v-spacer>
        
                <v-btn variant="plain">Login</v-btn>
                <v-btn variant="plain">Signup</v-btn>

        
        </v-toolbar>
        <v-navigation-drawer app v-model="drawer">
        <div class="text-h5 mt-3"> 
            <v-row>
                <v-col></v-col>
                <v-col class="font-weight-medium">Dashboard</v-col>
                <v-col></v-col>
            </v-row>
        </div>
        <v-divider class="mx-4 mt-1 mb-1"></v-divider>
         <v-list-item
            v-for="item in items"
            :key="item.title"
            router 
            :to="item.path" :prepend-icon="item.icon"
            height="100px">
            <v-list-item-title>{{ item.title }}</v-list-item-title>
            
          </v-list-item>
        
       </v-navigation-drawer>
    </nav>
  </template>
  
  <script setup>
    import { ref } from 'vue'
      
    const drawer = ref(false)
  
    const  items =  ref([
             { title: 'Home', icon: 'mdi-home', path: '/' },
             { title: 'Store', icon: 'mdi-store', path: '/store'},
             { title: 'About Us', icon: 'mdi-information', path: '/about'},
          ])
  
   function toggleDrawer(){
    return drawer.value = !drawer.value
   }
  
   
  </script>