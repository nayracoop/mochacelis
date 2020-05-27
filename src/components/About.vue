<template>
  <section id="about">
    <b-container>
      <b-row class="about">
        <b-col class="col-12 col-md-6 mb-1">
          <h2 class="pb-2">
            <span class="initial">
              {{$t('about.title')[0]}}</span>{{ $t('about.title').substr(1)}}
          </h2>
        </b-col>
      </b-row>
       <b-row class="about-info">
        <b-col class="col-12 col-md-8 mb-1">
          <h4 class="pb-2 color-orange">
            {{ $t('about.content[0].subtitle') }}
          </h4>
          <p>{{ $t('about.content[0].text') }}</p>
          <p class="mb-2 comment" v-if="$t('about.content[0].comment')">{{$t('about.content[0].comment')}}</p>
        </b-col>
      </b-row>
      <b-row class="about-info">
        <b-col class="col-12 col-md-8 mb-1">
          <h4 class="pb-2 color-red">
            {{ $t('about.content[1].subtitle') }}
          </h4>
          <p>{{ $t('about.content[1].text') }}</p>
        </b-col>
      </b-row>
      <b-row class="about-info">
        <b-col class="col-12 col-md-8 mb-1">
          <h4 class="pb-2 color-purple">
            {{ $t('about.content[2].subtitle') }}
          </h4>
          <p>{{ $t('about.content[2].text') }}</p>
        </b-col>
      </b-row>
      <b-row class="about-info">
        <b-col class="col-12 col-md-8 mb-1">
          <h4 class="pb-2 color-blue">
            {{ $t('about.content[3].subtitle') }}
          </h4>
          <p>{{ $t('about.content[3].text') }}</p>
        </b-col>
      </b-row>
      <b-row class="about-info">
        <b-col class="col-12 col-md-8 mb-1">
          <h4 class="pb-2 color-green">
            {{ $t('about.content[4].subtitle') }}
          </h4>
          <p>{{ $t('about.content[4].text') }}</p>
        </b-col>
      </b-row>
      <b-row class="about-info">
        <b-col class="col-12 col-md-8 mb-1">
          <h4 class="pb-2 color-orange">
            {{ $t('about.content[5].subtitle') }}
          </h4>
          <p>{{ $t('about.content[5].text') }}</p>
        </b-col>
      </b-row>
      <b-row class="about-info">
        <b-col class="col-12 col-md-8 mb-1">
          <h4 class="pb-2 color-red">
            {{ $t('about.content[6].subtitle') }}
          </h4>
          <p>{{ $t('about.content[6].text') }}</p>
        </b-col>
      </b-row>
    </b-container>
  </section>
</template>

<script>

export default {
}
</script>
