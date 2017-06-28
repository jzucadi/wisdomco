<template>
  <section class="container">
    <div>
      
      <h1 class="title">
        
      </h1>
      <h2 class="subtitle">
       Hello, what is your name?
      </h2>





      <nuxt-link class="navi" to="/email">
            next ->
          </nuxt-link>
      <nuxt-link class="navi" to="/location">
            location ->
          </nuxt-link>
      <nuxt-link class="navi" to="/loan">
            loan ->
          </nuxt-link>
      <nuxt-link class="navi" to="/loandetail">
            loandetail ->
          </nuxt-link>
      <nuxt-link class="navi" to="/propertyvalue">
            propertyvalue ->
          </nuxt-link>
      <nuxt-link class="navi" to="/second">
            secondmortgage ->
          </nuxt-link>
      <nuxt-link class="navi" to="/credit">
            credit ->
          </nuxt-link>
      <nuxt-link class="navi" to="/submit">
            submit ->
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
.container
{
  max-width: 960px;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  margin: 0 auto;
}
.title
{
  display: block;
  font-weight: 300;
  font-size: 5em;
  color: #35495e;
  letter-spacing: 1px;
}
.subtitle
{
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}
.links
{
  padding-top: 15px;
}
</style>
