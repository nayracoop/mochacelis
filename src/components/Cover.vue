<template>
  <div
    id="cover"
    class="min-vh-100 d-flex flex-column align-items-center align-content-center"
  >
    <b-container>
      <b-row class="min-vh-100 w-100">
        <b-col class="col-12 col-md-6 cover-logo">
          <img
            src="static/img/logo.png"
            alt="Bachillerato Popular Travesti - Trans Mocha Celis"
            id="logo"
          >
        </b-col>
        <b-col class="col-12 col-md-6 cover-info">
          <h2 class="mb-4">
            {{ $t('cover.title') }}
          </h2>
          <h1 class="mb-4">
            {{ $t('cover.subtitle') }}
          </h1>
          <p>
            {{$t('cover.content[0]')}}
          </p>
          <p>
            {{$t('cover.content[1]')}}
          </p>
          <b-button href="#contact">
            {{ $t('cover.btn-text') }}
          </b-button>
          <b-button href="#donations">
            {{ $t('donations.donate') }}
          </b-button>
          <ul class="social-links">
            <li>
              <a
                target="_blank"
                href="https://www.facebook.com/BachiTransMocha/"
                title="Facebook"
              ><font-awesome-icon :icon="['fab', 'facebook-square']" /></a>
            </li>
            <li>
              <a
                target="_blank"
                href="https://www.instagram.com/mochacelis/"
                title="Instagram"
              ><font-awesome-icon :icon="['fab', 'instagram']" /></a>
            </li>
            <li>
              <a
                target="_blank"
                href="https://twitter.com/mochacelis"
                title="Twitter"
              ><font-awesome-icon :icon="['fab', 'twitter']" /></a>
            </li>
          </ul>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>

export default {

}
</script>
