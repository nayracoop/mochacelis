<template>
  <footer class="text-center bg-grey">
    <b-container>
      <b-row>
        <b-col>
          <p>Información de contacto</p>
          <ul class="social-links mb-5">
            <li>
              <a
                target="_blank"
                href="https://www.facebook.com/mochacelis/"
                title="Facebook"
              ><font-awesome-icon :icon="['fab', 'facebook-square']" /><span class="sr-only">Facebook</span></a>
            </li>
            <li>
              <a
                target="_blank"
                href="https://www.instagram.com/mochacelis/"
                title="Instagram"
              ><font-awesome-icon :icon="['fab', 'instagram']" /><span class="sr-only">Instagram</span></a>
            </li>
            <li>
              <a
                target="_blank"
                href="https://twitter.com/BachiTransMocha"
                title="Twitter"
              ><font-awesome-icon :icon="['fab', 'twitter']" /><span class="sr-only">Twitter</span></a>
            </li>
          </ul>
          <small class="mb-5 made-with" v-html="$t('footer.signature')"></small>

          <div class="licence-cont">
            <a
              rel="license"
              href="http://creativecommons.org/licenses/by-sa/4.0/"
            >
              <img
                class="mb-2"
                alt="Licencia Creative Commons"
                src="static/img/licence.png"
              >
            </a>
            <small class="licence">{{ $t('footer.licence') }} <a href="http://creativecommons.org/licenses/by-sa/4.0/">{{ $t('footer.licenceLinkTitle') }}</a>.</small>
          </div>
        </b-col>
      </b-row>
    </b-container>
  </footer>
</template>

<script>
export default {}
</script>
