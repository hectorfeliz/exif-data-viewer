<template>
  <section class="intro">
    <div class="container">
      <div class="row">
        <div class="col-md-12 intro-content">
          <div class="intro-logo">
            <img alt="Image logo" src="../assets/svg/file.svg" />
            <h1>EXIF Data Viewer</h1>
          </div>

          <p>
            EXIF is short for Exchangeable Image File, a format that is
            a standard for storing interchange information in digital photography image
            files using JPEG compression. Almost all new digital cameras use the EXIF annotation,
            storing information on the image such as shutter speed, exposure compensation, F number,
            what metering system was used, if a flash was used, ISO number, date and time the image was
            taken, whitebalance, auxiliary lenses that were used and resolution. Some images may even store
            GPS information so you can easily see where the images were taken!
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "intro"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
