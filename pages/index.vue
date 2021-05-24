<template>
  <div class="container">
    <div class="text-center">
      <Logo />
      <h1 class="mt-4">
        welcome!
      </h1>
      <p class="text-center"><a href="https://github.com/kazumawada">github</a></p>
      <p class="text-center"><a href="https://kazumawada.hateblo.jp/">技術ブログ</a></p>
      <p class="text-center"><a href="https://qiita.com/kazumawada">qiita</a></p>
      <p class="text-center"><a href="https://kazumawada.hashnode.dev/">hashnode</a></p>
      <p class="text-center"></p>
      <p class="text-center"></p>
      <p class="text-center"></p>
      <p class="text-center"></p>
      <v-divider></v-divider>
      <h5>
        checkout my profile! → <NuxtLink to="/profile"><v-btn>Profile</v-btn></NuxtLink> 
      </h5>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
/* .container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
} */

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
