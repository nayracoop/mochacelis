<template>
<div id="bottom">
    <hr>
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
</div>
</template>
<script>
export default {
    
}
</script>