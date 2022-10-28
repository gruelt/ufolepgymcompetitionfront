<template>

  <div>

    <b-form @submit="" @reset="" v-if="1">
      <b-form-group
        id="input-group-1"
        label="Adresse Mail:"
        label-for="email"
        description="We'll never share your email with anyone else."
      >
        <b-form-input
          id="email"
          v-model="email"
          type="email"
          placeholder="Enter email"
          required
        ></b-form-input>
      </b-form-group>

      <b-form-group id="input-group-2" label="Mot de passe:" label-for="mot de passe">
        <b-form-input
          id="mot de passe"
          v-model="password"
          placeholder="mot de passe"
          required
        ></b-form-input>
      </b-form-group>


      <b-button type="submit" variant="primary">Envoyer</b-button>
      <b-button type="reset" variant="danger">Effacer</b-button>
    </b-form>


  </div>

</template>

<script>
export default {
  name: "loginForm",
  data() {
    return {
      email: '',
      password: 'gne'
    }
  }
}
</script>

<style scoped>

</style>
