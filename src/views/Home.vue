<template>
  <div class="home">
    <h1>Homepage</h1>
    <div class="my-2">
      <v-btn class="pink white--text">click me</v-btn>
    </div>
    <div class="my-2">
      <v-btn depressed color="pink">click me</v-btn>
    </div>
    <div class="my-2">
      <v-btn flat color="pink">click me</v-btn>
    </div>
    <div class="my-2">
      <v-btn depressed class="pink white--text">
        <v-icon left>mdi-email</v-icon>
        <span>email me</span>
      </v-btn>
    </div>

    <div class="my-2">
      <v-btn small depressed class="pink white--text">
        <v-icon left>mdi-email</v-icon>
        <span>email me</span>
      </v-btn>
    </div>

    <div class="my-2">
      <v-btn depressed class="pink white--text">
        <span>email me</span>
        <v-icon large right>mdi-email</v-icon>
        
      </v-btn>
    </div>

    <div class="my-2">
      <v-btn fab depressed small dark color="purple">
        <v-icon>mdi-cloud-upload</v-icon>
      </v-btn>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {};
</script>
