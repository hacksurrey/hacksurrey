<template>
  <section>
    <div class="row">
      <h1>About us.</h1>
    </div>
    <div class="row">
      <p>HackSurrey is a student-run society organising hackathons at the University of Surrey. We aim to create great experiences for students of every background of study, by hosting inclusive events where people can learn, and grow.</p>
    </div>
    <div class="row">
      <h2>What is a hackathon?</h2>
    </div>
    <div class="row">
      <p>A hackathon is best described as an "invention marathon". Anyone who has an interest in technology attends a hackathon to learn, build & share their creations over the course of a weekend in a relaxed and welcoming atmosphere. You don’t have to be a programmer and you certainly don’t have to be majoring in Computer Science. You can find more info <a href="https://mlh.io/faq">here</a>.</p>
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
  flex-direction: column
  flex-wrap: wrap
  justify-content: center

.row
  padding: .5em 1.5em
  margin: .5em .75em
  display: flex
  flex: 1 1 auto
  h1
    padding: 0
    color: #FF3232
    font-size: 3.5em
    font-weight: 500
    margin: 0 0 5px 0
  h2
    padding: 0
    color: #FF3232
    font-size: 2.4em
    font-weight: 500
    margin: 0 0 5px 0
  p
    margin: -2em 3px .6em 3px
    padding: .5em 0
    flex-direction: column
    a
      text-decoration: underline
.row:last-child
  margin-bottom: -2em

.center
  justify-content: center
</style>
