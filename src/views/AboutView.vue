<template>
    <!--Header-->
  <v-container fluid id="container">
    <v-row class="mt-16 mb-16">
      <v-spacer></v-spacer>
        <v-col>
          <span class="font-weight-light text-white text-h1">Welcome to </span>
        <span class="text-white text-h1 font-weight-bold">KalikaShop</span>
        <div class="text-body-3 text-white font-weight-medium">Preserve, Be one with the Nature</div>
        </v-col>
          <v-spacer></v-spacer>
    </v-row>
    <br />
  </v-container>

  <!--Group Image-->
  <v-container fluid>
  <v-img
  src="src\images\group.png"
  contain
  max-height="650"
  max-width="650"
  class="mx-auto"
  ></v-img>
  </v-container>

  <!--About Us-->
  <v-container fluid>
    <v-row>
      <v-spacer></v-spacer>
      <v-col>
        <div class="text-h3 text-center mt-5" fill-height>About Us</div>
        <div class="text-body-3 text-center mt-2">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ea eveniet velit ratione voluptatibus similique quam recusandae at magni. Illum vel dolorem dolor ipsum sint. Illo minima perferendis corporis est doloribus ipsum veniam numquam porro? Debitis quod explicabo dolore in autem velit quam sunt. Delectus explicabo tenetur velit quod nisi dolorem inventore pariatur neque. Sed laudantium voluptate labore tempore quisquam obcaecati ut deleniti illo, quo quia distinctio debitis autem molestias est beatae. Voluptate quia placeat officiis delectus eius provident quos cumque?</div>
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

     <!--Leave a Message-->
     <v-row>
      <v-spacer></v-spacer>
      <v-col>
        <div class="text-h3 text-center mt-5" fill-height>Leave a Massage</div>
        
      </v-col>
      <v-spacer></v-spacer>
    </v-row>
  <v-container fluid>

    <v-row>
        <v-col justify="end" >
    <v-card 
    class="dude"
    >
            <v-container fluid>
  <v-text-field label="Full Name" ></v-text-field>
  <v-text-field label="Email Address" ></v-text-field>
  <v-text-field label="Subject" ></v-text-field>
  <textarea rows="5" placeholder="Please leave a message"></textarea>
  <br />
  <v-btn @click="">Submit</v-btn>
  
</v-container>
    </v-card>
        </v-col>
        <v-col justify="start">
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3861.065908981749!2d120.98578831532507!3d14.595320181117808!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3397c9f618e826d3%3A0xeb7fcfb4bf255def!2sTechnological%20Institute%20of%20the%20Philippines!5e0!3m2!1sen!2sph!4v1662197673369!5m2!1sen!2sph" width="600" height="450" style="border:0;"  loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>  
        </v-col>

    </v-row>
  </v-container>
<!--Contact Us-->
<v-container fluid>
    <v-row>
      <v-spacer></v-spacer>
      <v-col>
        <div class="text-h3 text-center mt-5" fill-height>Contact Us</div>
        
      </v-col>
      <v-spacer></v-spacer>
    </v-row>
    
    <v-row justify="center">
      <v-col cols="auto">
        <div class="text-caption-1 font-weight-medium">E-mail:</div>
        <div class="text-caption-1 font-weight-medium">Contact No.:</div>
        <div class="text-caption-1 font-weight-medium">Address:</div>
      </v-col>
      <v-col cols="auto">
        <div class="text-caption-1 text-green-darken-3 text-left">kalikashop@gmail.com</div>
        <div class="text-caption-1 text-green-darken-3 text-left">(123) 456-7890</div>
        <div class="text-caption-1 text-green-darken-3 text-left">123 Anywhere St. Any City, 
        ST 12345</div>
      </v-col>
    </v-row>
  </v-container>
  <v-footer
    class="bg-green-lighten-1 text-white text-center d-flex flex-column"
  >
   

    <div class="text-white pt-3">
      Phasellus feugiat arcu sapien, et iaculis ipsum elementum sit amet. Mauris cursus commodo interdum. Praesent ut risus eget metus 
    </div>

    <v-divider></v-divider>

    <div class="text-white">
      {{ new Date().getFullYear() }} — <strong>KalikaShop</strong>
    </div>
  </v-footer>
  <v-container>
        <v-row align="center" justify="center">
            <v-col cols="12" sm="20">
                <v-card class="elavation-10 mt-10">
                    <v-window v-model="step">
                        <v-window-item :value="1">
                            <v-row>
                                <v-col cols="12" sm="6">
                                    <v-card-text class="mt-12">
                                        <h4 class="text-center">Login in to Your Account</h4>
                                        <h6 class="text-center grey--text">Log in to your account so you can continue builiding <br>and editing your onboarding flows</h6>
                                        <v-row align="center" justify="center">
                                            <v-col cols="12" sm="8">
                                                <v-text-field label="Email" variant="outlined" color="green-lighten-1" class="mt-16"></v-text-field>
                                                <v-text-field label="Password" type="password" variant="outlined" color="green-lighten-1" class=""></v-text-field>
                                                <v-row>
                                                    <v-col cols="12" sm="7">
                                                        <v-checkbox label="Remember me" v-model="checkbox" color="green-lighten-1"></v-checkbox>
                                                    </v-col>
                                                    <v-col cols="12" sm="5" class="mt-5">
                                                        <span><a class="forgot-text" href="">Forgot Password</a></span>
                                                    </v-col>
                                                </v-row> 
                                                  <v-btn color="green-lighten-1" class="text-white" dark block tile>Login</v-btn> 
                                                  <h5 class="text-center text-grey mt-4 mb-3">Or Log in using</h5>
                                                  <div class="d-flex  justify-space-between align-center mx-5 mb-16">
                                                    <v-btn variant="outlined" color="green-lighten-1" class="mx-5">
                                                        <v-icon color="red">mdi-google</v-icon>
                                                    </v-btn>
                                                    <v-btn variant="outlined" color="green-lighten-1" class="mx-5">
                                                        <v-icon color="blue-lighten-1">mdi-facebook</v-icon>
                                                    </v-btn>
                                                    <v-btn variant="outlined" color="green-lighten-1" class="mx-5">
                                                        <v-icon color="blue-lighten-2">mdi-twitter</v-icon>
                                                    </v-btn>
                                                  </div>                                       
                                            </v-col>
                                        </v-row>
                                    </v-card-text>
                                </v-col>
                                <v-col cols="12" sm="6" class="background1">
                                    <div style="text-align:center; padding: 180px 0;">
                                        <v-card-text class="text-white">
                                            <h3 class="text-center">Don't Have an Account yet?</h3>
                                            <h6>Let's get you all set up so you can start creating your first<br>
                                                onboarding experience
                                            </h6>
                                        </v-card-text>
                                        <div class="text-center">
                                            <v-btn variant="outlined" color="white" @click="step++">SIGN UP</v-btn>
                                        </div>
                                    </div>
                                </v-col>
                            </v-row>
                        </v-window-item>
                        <v-window-item :value="2">
                            <v-row>
                                <v-col cols="12" sm="6" class="background2">
                                    <div style="text-align:center; padding:180px 0;">
                                        <v-card-text class="text-white">
                                            <h3 class="text-center">Already Signed up?</h3>
                                            <h6>Login to your account so you can continue buying our products<br>
                                                and have a great day
                                            </h6>
                                        </v-card-text>
                                        <div class="text-center">
                                            <v-btn variant="outlined" color="white" @click="step--">LOG IN</v-btn>
                                        </div>
                                    </div>
                                </v-col>
                                <v-col cols="12" sm="6">
                                    <v-card-text class="mt-12">
                                        <h4 class="text-center">Sign up for an Account</h4>
                                        <h6 class="text-center grey--text">Let's get you all set up so you can start creating your first<br>
                                            onboarding experience
                                        </h6>
                                        <v-row align="center" justify="center">
                                            <v-col cols="12" sm="8">
                                                <v-row>
                                                    <v-col cols="12" sm="6">
                                                        <v-text-field label="First Name" variant="outlined" color="green-lighten-1" class="mt-4"></v-text-field>
                                                    </v-col>
                                                    <v-col cols="12" sm="6">
                                                        <v-text-field label="Last Name" variant="outlined" color="green-lighten-1" class="mt-4"></v-text-field>
                                                    </v-col>
                                                </v-row>
                                                <v-text-field label="Email" variant="outlined" color="green-lighten-1" class=""></v-text-field>
                                                <v-text-field label="Password" type="password" variant="outlined" color="green-lighten-1" class=""></v-text-field>
                                                <v-row>
                                                    <v-col cols="12" sm="7">
                                                        <v-checkbox label="I accept the " v-model="checkbox" color="green-lighten-1"></v-checkbox>
                                                    </v-col>
                                                    <v-col cols="12" sm="5" class="mt-5">
                                                        <span><a class="forgot-text" href="">Terms & Conditions</a></span>
                                                    </v-col>
                                                </v-row>
                                                <v-btn color="green-lighten-1" class="text-white" dark block tile>Sign Up</v-btn>
                                                <h5 class="text-center text-grey mt-4 mb-3">Or Sign Up using</h5>
                                                  <div class="d-flex  justify-space-between align-center mx-5 mb-16">
                                                    <v-btn variant="outlined" color="green-lighten-1" class="mx-5">
                                                        <v-icon color="red">mdi-google</v-icon>
                                                    </v-btn>
                                                    <v-btn variant="outlined" color="green-lighten-1" class="mx-5">
                                                        <v-icon color="blue-lighten-1">mdi-facebook</v-icon>
                                                    </v-btn>
                                                    <v-btn variant="outlined" color="green-lighten-1" class="mx-5">
                                                        <v-icon color="blue-lighten-2">mdi-twitter</v-icon>
                                                    </v-btn>
                                                  </div>   
                                            </v-col>
                                        </v-row>
                                    </v-card-text>
                                </v-col>
                            </v-row>
                        </v-window-item>
                    </v-window>
                </v-card>
            </v-col>
        </v-row>
    </v-container>  
</template>

<script>

  export default {
  data () {
    return {
      checkbox: true,
    }
  },

   data: () => ({
    step: 1
  }),
  props: {  
    source: String,
    
  },

}
</script>


<style scoped>
    #container{
      background: url('src/images/home-bg2.png');
      background-position: center;
      background-size: cover;
      background-repeat: no-repeat;
      height:20%;   
    }
    textarea{
      border:1px solid #999999;
      width:100%;
      margin:5px 0;
      padding:3px;
        }
    .dude{
        margin-left: 50%;
    }
    .v-application .background1 {
      border-bottom-left-radius: 300px !important;
      background-color: green;
      opacity: 75%;
  }
  .v-application .background2 {
      border-bottom-right-radius: 300px !important;
      background-color: green;
      opacity: 75%;
  }
  .forgot-text{
    color: green;
    text-decoration: none;
  }
  .text-white{
    letter-spacing: 2px;
  }
    </style>
    
