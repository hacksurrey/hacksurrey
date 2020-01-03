<template>
  <section>
    <div class="item">
      <h1>Contact us.</h1>
    </div>
    <div class="item">
      <h1><a class="button" href="https://www.ussu.co.uk/activity/Pages/GetMemberships.aspx">Sign up here</a></h1>
    </div>
    <div class="item">
      <a href="http://facebook.com/hacksurrey"><i class="fa fa-facebook-square fa-2x" aria-hidden="true"></i></a>
    </div>
    <div class="item">
      <a href="http://twitter.com/hacksurrey"><i class="fa fa-twitter-square fa-2x" aria-hidden="true"></i></a>
    </div>
    <div class="item">
      <a href="https://github.com/hacksurrey"><i class="fa fa-github-square fa-2x" aria-hidden="true"></i></a>
    </div>
    <div class="item">
      <a href="mailto:ussu.hacksurrey@surrey.ac.uk"><i class="fa fa-envelope-square fa-2x" aria-hidden="true"></i></a>
    </div>
  </section>
</template>

<script>
export default {
}
</script>

<style lang="sass" scoped>
section
  display: flex
  min-width: 96%
  padding: 1.5em 4em
  flex-direction: row
  flex-wrap: wrap
  justify-content: center

.item:first-child
  margin: .5em
  flex: 1 1 auto
  padding: .5em 1.5em
  flex-basis: 100%
  min-width: 300px
  border-radius: 2px
  break-inside: avoid-column
  h1
    padding: 0
    color: #FF3232
    font-size: 3.5em
    font-weight: 500
    margin: 0 0 5px 0

.item:nth-child(2)
  flex-basis: 100%
  h1
    padding: 0
    font-weight: 500
    margin: .1em 0 1em 0

.item:not(:first-child)
  display: flex
  margin: 0 12px
  padding: .5em 0
  font-size: 24px
  text-align: center
  flex-direction: column
  img
    margin: 0
    width: 150px
  .subtitle
    padding: .35em
    color: #fcfcfc
    font-weight: 300
    font-size: 1.25em
    background-color: #303036
    a
      color: #fcfcfc
</style>
