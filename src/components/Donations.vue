<template>
  <section id="donations">
    <b-container>
      <b-row>
        <b-col class="col-12 col-md-6 section-heading">
          <h2 class="pb-2">
            <span class="initial">
              {{$t('donations.title')[0]}}</span>{{ $t('donations.title').substr(1)}}
          </h2>
        </b-col>
      </b-row>
      <b-row>
        <b-col class="col-12 col-md-4">
          <div class="donation-type mb-5">
            <h4>Dentro de Argentina</h4>
            <p><em>via MercadoPago</em></p>
            <b-button 
              class="donate-button b-green"
              mp-mode="dftl" 
              href="https://mpago.la/2tvk3dJ" name="MP-payButton"
            >{{ $t('donations.donateButton') }} $500</b-button>
            <b-button 
              class="donate-button b-blue"
              mp-mode="dftl" 
              href="https://mpago.la/32nZJqk" name="MP-payButton"
            >{{ $t('donations.donateButton') }} $750</b-button>
            <b-button 
              class="donate-button b-purple"
              mp-mode="dftl" 
              href="https://mpago.la/26kybgE" name="MP-payButton"
            >{{ $t('donations.donateButton') }} $1000</b-button>
            <b-button 
              class="donate-button b-red"
              mp-mode="dftl" 
              href="https://mpago.la/1uTZrZr" name="MP-payButton"
            >{{ $t('donations.donateButton') }} $2500</b-button>
            
          </div>
          <div class="donation-type">
            <h4>Desde el exterior</h4>
            <p><em>via PayPal</em></p>
            <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
              <input type="hidden" name="cmd" value="_donations" />
              <input type="hidden" name="business" value="mochadocumental@gmail.com" />
              <input type="hidden" name="currency_code" value="USD" />
              <b-button 
                type="submit" 
                class="donate-button b-orange" 
                name="submit" 
                alt="Donate with PayPal button">
                {{ $t('donations.donateButton') }}
                </b-button>
            </form>
          </div>
        </b-col>   
         <b-col class="col-12 col-md-8">
          <p>{{ $t('donations.content[0]') }}</p>
          <p>{{ $t('donations.content[1]') }}</p>
          <p>{{ $t('donations.content[2]') }}</p>
         </b-col>
      </b-row>
    </b-container>
  </section>
</template>

<script>
// (function(){function $MPC_load(){window.$MPC_loaded !== true && (function(){var s = document.createElement("script");s.type = "text/javascript";s.async = true;s.src = document.location.protocol+"//secure.mlstatic.com/mptools/render.js";var x = document.getElementsByTagName('script')[0];x.parentNode.insertBefore(s, x);window.$MPC_loaded = true;})();}window.$MPC_loaded !== true ? (window.attachEvent ?window.attachEvent('onload', $MPC_load) : window.addEventListener('load', $MPC_load, false)) : null;})();
export default {

  
}
</script>
