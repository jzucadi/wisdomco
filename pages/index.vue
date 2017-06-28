<template>
  <section class="container">
    <div>
      
      <h1 class="title">
        
      </h1>
      <h2 class="subtitle">
       Hello, what is your name?
      </h2>

     <div class="group">      
      <input type="text" required>
      <span class="highlight"></span>
      <span class="bar"></span>
      <label>Name</label>
    </div>

     <nuxt-link class="navi" to="/email">
            next ->
          </nuxt-link>





    
    </div>
  </section>
</template>

<script>
import Logo from '~components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>
<style>
</style>
