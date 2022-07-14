<template>
  <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/line-awesome/1.3.0/line-awesome/css/line-awesome.min.css"
  />
  <div class="app">
    <Header />
    <div class="flex">
      <Profile />
      <Project />

      <Activity />
    </div>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Profile from "./components/Profile.vue";
import Project from "./components/Project.vue";
import Activity from "./components/Activity.vue";


export default {
  name: "App",
  components: {
    Header,
    Profile,
    Project,
    
    Activity,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Rubik:wght@400;500;600;700&display=swap");
*,
*::before,
*::after {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  list-style: none;
  list-style-type: none;
  text-decoration: none;
}
body {
  font-family: "Rubik", ui-sans-serif, system-ui, -apple-system, sans-serif;
  font-weight: 400;
  line-height: 1.5;
}
#app {
  /* width: 100%; */
  display: flex;
  align-items: center;
  justify-content: center;
}
.setting {
        display: ;
  }
@media only screen and (min-width: 1440px) {
  #app {
   
  }
  .app {
  
    width: 100%;
  }
  .flex {
    display: flex;
  }
 
}
 
</style>
