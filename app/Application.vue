<template>
  <div class="content">
    <hero>
      <a class="scroller" v-scroll-to="'#committee'">
        <i class="material-icons">keyboard_arrow_down</i>
      </a>
    </hero>
    <team id="committee"/>
    <contact/>

    <footer>
      <p>
        Coded in {{ new Date().getFullYear() }} with lots of <i class="material-icons">favorite</i> by the <a href="https://github.com/hacksurrey/hacksurrey">@hacksurrey</a> team
      </p>
    </footer>
  </div>
</template>

<script>
import Hero from '../components/Hero.vue'
import Team from '../components/Team.vue'
import Contact from '../components/Contact.vue'

export default {
  name: 'app',
  components: {
    hero: Hero,
    team: Team,
    contact: Contact
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
