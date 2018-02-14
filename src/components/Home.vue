<template>
  <div class="hero is-fullheight is-white">
    <div class="hero-body">
      <div class="container has-text-centered">
        <h2 class="title">MSHE Internships Portal</h2>
        <h2 class="subtitle">Please choose your option below</h2>
        <div class="columns">
          <div class="column">
            <a>
              <b-icon class="circle-icon" icon="file-account" size="is-large" type="is-white" />
              <p class="title is-5">Internship Site</p>
            </a>
          </div>
          <div class="column">
            <b-icon class="circle-icon" icon="account" size="is-large" type="is-white" />
            <p class="title is-5">Student</p>
          </div>
          <div class="column">
            <b-icon class="circle-icon" icon="account-settings-variant" size="is-large" type="is-white" />
            <p class="title is-5">Admin</p>
          </div>
        </div>
      </div>
    </div>
    <div class="hero-foot">
      <div class="container">
        <div class="level">
          <div class="level-left">
            <img class="image" src="../assets/logo.png">
          </div>
          <div class="level-right">
            <a class="level-item">
              <b-icon icon="information" />
            </a>
            <a class="level-item">
              <b-icon icon="email" />
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.columns {
  margin-top: 40px;
}
.hero-foot {
  padding-bottom: 10px;
}
.circle-icon {
  background-color: #4e2a84;
  border-radius: 50%;
  padding: 4rem;
  margin-bottom: 1rem;
}
.circle-icon:hover {
  background-color: #333;
  box-shadow: 1px 1px 3px 1px #999;
}
.image {
  height: 100px;
}
</style>
