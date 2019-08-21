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
  position: fixed;
  right: 0;
  bottom: 0;
  min-width: 100%; 
  min-height: 100%;
}
#logo {
  z-index: 2001;
}

</style>
