<template>
  <section>
    <div class="row">
      <h1>Committee.</h1>
    </div>
    <div class="row center">
      <div class="item">
        <img src="~resources/avatars/rafail.jpg" />
        <span class="subtitle"><a href="https://www.linkedin.com/in/rafail-giavrimis/" title="Rafail Giavrimis">Rafail</a><br/><span class="subsubtitle">President</span>
        <p class="desc" style="height: 110px">I am a 3rd Year Computer Science student, and as the President I aiming to develop a conducive atmosphere within the society, as well as managing the day-to-day running of the society.</p>
        </span>
      </div>
      <div class="item">
        <img src="~resources/avatars/aleks.jpg" />
        <span class="subtitle"><a href="https://www.linkedin.com/in/aleksandra-marevskaia-26a097176/" title="Aleksandra Marevskaia">Aleks</a><br/><span class="subsubtitle">Vice President</span>
        <p class="desc" style="height: 110px">I am a 3rd Year Computer Science student, and as the Vice-President I am involved in running the society steadily, as well as assisting the president in organising engaging events for the members!</p>
        </span>
      </div>
      <div class="item">
        <img src="~resources/avatars/josh.jpg" />
        <span class="subtitle"><a href="https://www.linkedin.com/in/joshasday/" title="Josh Day">Josh</a><br/><span class="subsubtitle">Treasurer</span>
        <p class="desc" style="height: 110px">I'm  a 3rd Year Computer Science student, and as Treasurer I am in charge of managing the funds from our budget and sponsorships in order to host the fun events we have planned this year.</p>
        </span>
      </div>
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
  flex-wrap: wrap;
  flex: 1 1 auto
  h1
    padding: 0
    color: #FF3232
    font-size: 3.5em
    font-weight: 500
    margin: 0 0 5px 0

  .item
    display: flex
    margin: 0 3px
    width: 200px
    padding: .5em 0
    text-align: center
    flex-direction: column
    img
      margin: 0
      width: 200px
    .subtitle
      padding: .35em
      color: #fcfcfc
      font-weight: 300
      font-size: 1.25em
      background-color: #303036
      a
        color: #fcfcfc
        font-weight: 300
        text-decoration: underline
      .subsubtitle
        font-size: .8em
      .desc
        font-size: .6em

.center
  justify-content: center
</style>
