<template>
  <section>
    <div class="row">
      <h1>Committee.</h1>
    </div>
    <div class="row center">
      <div class="item">
        <img src="https://avatars2.githubusercontent.com/u/4354770?s=460&v=4" />
        <span class="subtitle"><a href="https://twitter.com/sdaniel55" title="@sdaniel55">Dan</a><br/><span class="subsubtitle">President</span></span>
      </div>
      <div class="item">
        <img src="https://avatars1.githubusercontent.com/u/7229472?s=460&v=4" />
        <span class="subtitle"><a href="https://twitter.com/theomessin" title="@theomessin">Ted</a><br/><span class="subsubtitle">Vice President</span></span>
      </div>
      <div class="item">
        <img src="~resources/avatars/marwan.jpg" />
        <span class="subtitle">Marwan<br/><span class="subsubtitle">Treasurer</span></span>
      </div>
      <div class="item">
        <img src="https://avatars1.githubusercontent.com/u/45294765?s=400&v=4" />
        <span class="subtitle">Alex<br/><span class="subsubtitle">Committee</span></span>
      </div>
      <div class="item">
        <img src="https://avatars2.githubusercontent.com/u/45466951?s=460&v=4" />
        <span class="subtitle">Samantha<br/><span class="subsubtitle">Committee</span></span>
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
