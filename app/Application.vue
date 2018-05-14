<template>
  <div class="content">
    <hero/>
  </div>
</template>

<script>
import Hero from '../components/Hero.vue'

export default {
  name: 'app',
  components: {
    hero: Hero
  }
}
</script>

<style lang="sass" scoped>
.scroller
  color: #FF3232
  position: absolute
  bottom: 25px
  text-align: center
  cursor: pointer

  .material-icons
    font-size: 4em
    position: relative
    animation: pulse 1.3s infinite

footer
  margin-top: 2em
  padding: 1.75em
  text-align: center
  background-color: #FF3232
  p
    margin: 0
    font-size: 1em
    color: #ffffff
    font-weight: 300
    .material-icons
      top: 2px
      position: relative
      font-size: 1em
    a
      color: #ffffff
</style>
