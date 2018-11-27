<template>
  <section>
    <div class="row">
      <h1>Events.</h1>
    </div>

    <div class="row" v-for="i in events">
      <div class="event">
        <a v-if="i.website" :href="i.website"><h3>{{ i.title }}</h3></a><h3 v-else>{{ i.title }}</h3>, <span class="event-date">{{ i.date }}</span>
        <p v-html="i.description" />
        <hr/>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
        events: [
          {title: 'HackSurrey Mk2',
           date: '9-10th February 2019',
           description: 'Our second hackathon at the University of Surrey: 150 students, 24 hours, what will <b>you</b> build?',
           website: 'https://mk2.hacksurrey.uk'},
          {title: 'HackSurrey Beta',
           date: '5-6th May 2018',
           description: 'Our first 24 hour hackathon at the University of Surrey! 🎉',
           website: 'https://beta.hacksurrey.uk'},
          {title: 'MLH Local Hack Day 2017',
           date: '2nd December 2017',
           description: 'MLH Local Hack Day hosted by HackSurrey! 12 hour hackathon with workshops, food, and prizes',
           website: 'https://www.facebook.com/events/151976128870688'}
        ]
    }
  }
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
  .event
    flex-direction: column
    width: 100%
    a
      text-decoration: underline
      color: inherit
    h3
      display: inline
      padding: 0
      font-weight: 500
    span
      display: inline
    hr
      margin-top: 2em;
      border: .8px solid #AAA;
      
.row:last-child
  margin-bottom: -2em

.center
  justify-content: center
</style>
