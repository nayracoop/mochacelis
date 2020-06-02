<template>
  <div id="cover" class>
    <b-container class="cover-info">
      <b-row>
        <b-col class="col-12">
          <h1 class="sr-only">{{ $t('cover.title') }}</h1>
        </b-col>
      </b-row>
      <b-row class="cover-image">        
        <b-col class="col-12">
          <img
            src="static/img/cover-image-3.png"
            alt="Bachillerato Popular Travesti-Trans Mocha Celis"
          />
        </b-col>
      </b-row>
      <b-row class="cover-buttons">
        <b-col class="col-12 col-md-6">
          <b-button
            class="cover-button b-purple"
            href="mailto: preceptoria@bachilleratomochacelis.edu.ar"
          >{{ $t('cover.btn-text-1') }}</b-button>
        </b-col>
        <b-col class="col-12 col-md-6">
          <b-button class="cover-button b-orange" href="#donations">{{ $t('cover.btn-text-2') }}</b-button>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
export default {};
</script>
