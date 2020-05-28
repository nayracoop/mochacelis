<template>
  <div
    id="cover"
    class="min-vh-60 d-flex flex-column align-items-center align-content-center"
  >
    <b-container class="min-vh-100 w-100 cover-info">
      <b-row>
        <b-col class="col-12" >
          <h1> {{ $t('cover.title') }} </h1>
        </b-col>
      </b-row>
      <b-row>
        <b-col class="col-12 col-md-6">
          <img
            src="static/img/cover-image.png"
            alt="Bachillerato Popular Travesti-Trans Mocha Celis"
            class="col-12 cover-image"
          >
          <b-button class="cover-button" href="mailto: preceptoria@bachilleratomochacelis.edu.ar">
            {{ $t('cover.btn-text-1') }}
          </b-button>
        </b-col>
        <b-col class="col-12 col-md-6">
          <img
            src="static/img/cover-image.png"
            alt="Bachillerato Popular Travesti-Trans Mocha Celis"
            class="col-12 cover-image"
          >
          <b-button class="cover-button" href="#donations">
            {{ $t('cover.btn-text-2') }}
          </b-button>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>

export default {

}
</script>
