<template>
  <div class="container">
    <video autoplay muted loop id="bgVdo">
      <source src='~/assets/videos/THA2018_trim.mp4' type="video/mp4">
    </video>
    <div id="cover"></div>  
    <div id="logo">
      <img src="~/assets/images/logo_temp.png" alt="logo" />
    </div>
  </div>
</template>

<script>
export default {
  head () {
    return {
      link: [
        { rel: 'stylesheet', href: 'https://fonts.googleapis.com/css?family=Prompt:500&display=swap' }
      ]
    }
  }
}
</script>

<style scope>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
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

img {
  width: 70%;
  height: auto;
}
#bgVdo {
  z-index: 2000;
  position: absolute;
  height: 100%;
}
#logo {
  z-index: 2001;
}
/* #cover {
  background-color: rgba(0, 0, 0, 0.5);
  height: 1vh;
  width: 1vh;
} */
</style>
