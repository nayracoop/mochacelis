<template>
  <section id="donations" class="bg-grey">
    <b-container>
      <b-row>
        <b-col class="col-12 col-md-6 section-heading">
          <h2 class="pb-2">
            {{ $t('donations.title') }}
          </h2>
        </b-col>
      </b-row>
      <b-row>
         <b-col>
          <p>{{ $t('donations.content[0]') }}</p>
          <p>{{ $t('donations.content[1]') }}</p>
          <p>{{ $t('donations.content[2]') }}</p>
         </b-col>
      </b-row>
      <b-row>
        <b-col>
        <h4>Donación única (dentro de Argentina)</h4>
        <b-button>{{ $t('donations.donate') }}</b-button>
        <b-button>{{ $t('donations.donate') }}</b-button>
        <b-button>{{ $t('donations.donate') }}</b-button>
        </b-col>        
      </b-row>
      <b-row>
        <b-col>
          <h4>Suscripción a débito automático (dentro de Argentina)</h4>
          <b-button>{{ $t('donations.donate') }}</b-button>
          <b-button>{{ $t('donations.donate') }}</b-button>
          <b-button>{{ $t('donations.donate') }}</b-button>
        </b-col>
      </b-row>
      <b-row>
        <b-col>
          <h4>Donar desde el exterior de Argentina</h4>
          <b-button>{{ $t('donations.donate') }}</b-button>
        </b-col>
      </b-row>
    </b-container>
  </section>
</template>

<script>

export default {

}
</script>
