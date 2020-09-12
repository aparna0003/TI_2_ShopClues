<template>
  <!--Your App Starts Here -->
  <v-app id="inspire">
    
    <!--Header -->
    <v-app-bar color="blue" dark fixed app>
      <v-toolbar-title>Application</v-toolbar-title>
       <!-- Component Example -->
       <VuetifyLogo/>
       <breadCrumb/>
       <navBar/>
      
    
    </v-app-bar>

    <!-- Body -->
    <v-content light>
     <breadCrumb/>
     <navBar2/>
 
      <nuxt /> 
<navBar/>
    </v-content>

    
    <!-- Footer -->
    <v-footer color="black" app>
     
    </v-footer>

  </v-app>
</template>

<script>
export default {}
</script>

<style> 
  .white--text {
    border: 2px solid;
  }

   #inspire {
    background-color: white;
    color: black;
  }
</style>