<template>
  <footer id="footer" class="bg-grey">
    <b-container>
      <b-row>
        <b-col class="col-12 col-md-6 section-heading">
          <h2 class="pb-2">
            <span class="initial">
              {{$t('contact.title')[0]}}</span>{{ $t('contact.title').substr(1)}}
          </h2>
        </b-col>
      </b-row>
      <b-row>
        <b-col class="col-12 col-md-4 contact-data">
          <div class="contact-info">
            <p>Bachillerato Popular Trans Mocha Celis</p>
            <p>Av. Federico Lacroze 4181, 5to piso.</p>
            <p>Buenos Aires, Bs. As.</p>
            <p>C1427EDG ARGENTINA</p>
            <p>Tel: +54 (011) 4554-9048</p>
          </div>
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
             <li class="mt-1 mb-1">
              <a
                target="_blank"
                href="#"
                title="Mail"
              ><font-awesome-icon :icon="['fas','envelope']" /><span class="sr-only">Mail</span></a>
            </li>
          </ul>
        </b-col>
        <b-col class="col-12 col-md-8 map">
          <iframe width="600" height="450" frameborder="0" style="border:0" src="https://www.google.com/maps/embed/v1/place?q=Bachillerato%20Popular%20Trans%20Mocha%20Celis&key=AIzaSyCLVhr-tpYjB_FRMDqefWyvrOLXO9-Oq9g" allowfullscreen></iframe> 
        </b-col>
      </b-row>
      <b-row>
        <b-col class="col-12">
          <div class="real-footer text-center">
            <small class="mb-3 made-with mt-3" v-html="$t('footer.signature')"></small>
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
          </div>
        </b-col>
      </b-row>
    </b-container>
  </footer>
</template>

<script>
export default {}
</script>
