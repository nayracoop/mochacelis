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
        <b-col class="col-12 col-md-4">
          <div class="donation-type">
            <h4>Donación única (dentro de Argentina)</h4>
            <b-button>{{ $t('donations.donate') }}</b-button>
            <b-button>{{ $t('donations.donate') }}</b-button>
            <b-button>{{ $t('donations.donate') }}</b-button>
          </div>
          <div class="donation-type">
            <h4>Donación única (dentro de Argentina)</h4>
            <b-button>{{ $t('donations.donate') }}</b-button>
            <b-button>{{ $t('donations.donate') }}</b-button>
            <b-button>{{ $t('donations.donate') }}</b-button>
          </div>
          <div class="donation-type">
            <h4>Donar desde el exterior de Argentina</h4>
            <b-button>{{ $t('donations.donate') }}</b-button>
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
