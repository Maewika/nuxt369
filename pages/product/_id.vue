<template>
  <div id="sup">
    <b-container>
      <b-row class="justify-content-md-center">
        <b-card
          class="card text-dark bg-info "
          :title="this.$route.params.id.title"
          :img-src="this.$route.params.id.image_url"
          :img-alt="url"
          img-top
          tag="article"
          style="max-width: 30rem;"
        >
          <b-card-text>
            synopsis : {{ this.$route.params.id.synopsis }}
            <br>
            score : {{ this.$route.params.id.score }}
            <br>
            rated : {{ this.$route.params.id.rated }}
          </b-card-text>
        </b-card>
      </b-row>
    </b-container>
  </div>
</template>
