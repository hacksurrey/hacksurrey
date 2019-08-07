<template>
  <section>
    <div class="row">
      <h1>Committee.</h1>
    </div>
    <div class="row center">
      <div class="item">
        <img src="~resources/avatars/aleks.jpg" />
        <span class="subtitle"><a href="https://www.linkedin.com/in/aleksandra-marevskaia-26a097176/" title="Aleksandra Marevskaia">Aleks</a><br/><span class="subsubtitle">President</span></span>
      </div>
      <div class="item">
        <img src="~resources/avatars/ankur.jpg" />
        <span class="subtitle"><a href="https://www.linkedin.com/in/ankur-mahto-238916127" title="Ankur Mahto">Ankur</a><br/><span class="subsubtitle">Vice President</span></span>
      </div>
      <div class="item">
        <img src="~resources/avatars/uliks.jpg" />
        <span class="subtitle"><a href="https://www.linkedin.com/in/uliks-sekiraqa-438276149/" title="Uliks Seqiraqa">Uliks</a><br/><span class="subsubtitle">Treasurer</span></span>
      </div>
      <div class="item">
        <img src="~resources/avatars/rafail.jpg" />
        <span class="subtitle"><a href="https://www.linkedin.com/in/rafail-giavrimis/" title="Rafail Giavrimis">Rafail</a><br/><span class="subsubtitle">Committee</span></span>
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
    padding: .5em 0
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
        font-weight: 300
        text-decoration: underline
      .subsubtitle
        font-size: .8em

.center
  justify-content: center
</style>
