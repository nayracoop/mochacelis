<template>
  <section id="donations" class="bg-grey">
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
            <b-button class="donate-button b-green">{{ $t('donations.donateOnce') }}</b-button>
            <b-button class="donate-button b-blue">{{ $t('donations.suscripcion') }}</b-button>
          </div>
          <div class="donation-type">
            <h4>Desde el exterior</h4>
            <p><em>via PayPal</em></p>
            <b-button class="donate-button b-purple">{{ $t('donations.donateOnce') }}</b-button>
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

export default {
}
</script>
