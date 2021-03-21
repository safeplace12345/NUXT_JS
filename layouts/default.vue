<template>
<div class="container-fluid">

 <!-- custom components -->
 <mainNav></mainNav>
    <Nuxt />
</div>
</template>

<style>

/* custom styles for blog-post-four */
.nav.nuxt-link-active{
  text-decoration: underline;
  color: whitesmoke;
}
.gradient{
  font-weight: bold;
}
.gradient-one{
  color: White;
  background: linear-gradient(to bottom , gray, saddlebrown);
}
.gradient-two{
  color:black;
  background: linear-gradient(to bottom , powderblue, plum);
}
.gradient-three{
  color: black;
  background: linear-gradient(to bottom , gray, saddlebrown);
}
.gradient-four{
  color: White;
  background: linear-gradient(to bottom , indigo, blue);
}

</style>
<script>
  import mainNav from '../components/mainNav'
  // Must export it
  export default {
    components : {
      mainNav
    }
  }
</script>
