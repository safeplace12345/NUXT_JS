<template>
<div class="container-fluid bg-dark" style="height:100vh">
 <mainNav></mainNav>
    <Nuxt />
</div>
</template>

<style>

/* custom styles for layouts-blog */

.gradient-layout{
  font-weight: bold;
  color: black;
  background: linear-gradient(to bottom , gray, salmon);
}

</style>

<script>

  import mainNav from '../components/mainNav'
  export default{
    components : {
      mainNav
    }
  }
  </script>