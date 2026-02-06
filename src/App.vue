<script>

  import BannerComponent from "./components/BannerComponent.vue"
  import NavbarComponent from "./components/NavbarComponent.vue"
  import HighlightsComponent from "./components/HighlightsComponent.vue"
  import HomePage from "./pages/HomePage.vue"
  import CoursesPage from "./pages/CoursesPage.vue"

  export default{
    components:{
      NavbarComponent,
      BannerComponent,
      HighlightsComponent,
      CoursesPage
      
    }
  }


</script>


<template>

    <NavbarComponent />
    <BannerComponent />
    <HighlightsComponent />
    <HomePage />
    <CoursesPage />

</template>



<style scoped></style>


