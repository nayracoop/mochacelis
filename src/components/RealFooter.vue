<template>
<div id="bottom">
    <hr>
    <b-container>
      <b-row>
        <b-col class="col-12">
          <div class="real-footer text-center">
            <small class="made-with mt-3"><a target="_blank" href="https://nayra.coop" v-html="$t('footer.signature')"></a></small>
            <div class="licence-cont mt-2">
              <small class="licence">{{ $t('footer.licence') }} <a target="_blank" href="http://creativecommons.org/licenses/by-sa/4.0/">{{ $t('footer.licenceLinkTitle') }}.</a></small>
              <a target="_blank" rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">
                <img class="mt-3" alt="Licencia Creative Commons" src="static/img/licence.png">
              </a>
            </div>
          </div>
        </b-col>
      </b-row>
    </b-container>
</div>
</template>
<script>
export default {
    
}
</script>