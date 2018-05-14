<template>
  <section>
    <header>
      <img src="~resources/logo.svg" />
    </header>

    <vue-particles class="background" color="#FF3232" :particleOpacity="0.75" :particlesNumber="125" shapeType="circle" :particleSize="2"
    linesColor="#FF3232" :linesWidth="0.55" :lineLinked="true" :lineOpacity="0.75" :linesDistance="75"
    :moveSpeed="3" :hoverEffect="false" :clickEffect="false" />
  </section>
</template>

<script>
export default {
}
</script>

<style lang="sass" scoped>
section
  width: 100vw
  display: flex
  max-width: 100%
  min-height: 100vh
  align-items: center
  vertical-align: bottom
  justify-content: center

.background
  z-index: 0
  width: 100%
  min-height: 100%
  max-height: 100vh
  position: absolute

h1
  margin: 0
  color: #FF3232
  display: block
  line-height: 1
  font-weight: 300
  text-align: center

img
  width: 42vw
  max-height: 20vh
  min-width: 400px
  max-width: 850px
</style>

<style lang="sass">
.particles-js-canvas-el
  vertical-align: top !important
  height:100vh !important
</style>
