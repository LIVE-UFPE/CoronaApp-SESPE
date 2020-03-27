<template>
  <v-container fluid class="primary d-flex flex-column justify-center align-center" fill-height>
    <v-card raised color="secondary" max-width="705px" max-height="809px" width="705px" height="809px" fluid class="d-flex round-border px-7 pt-12">
      <v-row class="mx-12 mt-12 accent d-block" align="end" justify="center" > 
        <p class="text-center font-weight-bold pb-12" v-bind:style="{fontSize: '60px',color: '#1E9CF8'}" >Logo</p> <!-- // ! Replacement for logo  -->
        <!-- // TODO usar v-form? -->

        <v-text-field placeholder="Email" outlined full-width class="pt-12" v-bind:style="{borderRadius: '10px'}" height="100px" single-line solo></v-text-field> 
        <!-- // ! style deve ser usado da forma usada acima, ou camelCase ou 'kebab-case' : 'string' -->
      </v-row>
    </v-card>
  </v-container>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Login',
  components: {
    
  }
}
</script>

<style scoped>
.v-text-field {
  font-size: 30px;
  border-radius: 10px;
}
</style>
