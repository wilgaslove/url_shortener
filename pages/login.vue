<template>
  <div class="prose m_form bg-white p-6 rounded-lg shadow-lg mt-10">
    <h1>Connexion</h1> 
    <FormKit type="form" submit-label="Se connecter"  default="{value}" class="m_form">
      <FormKit
      type="email" label="Email" nema="email"  placeholder="Votre adresse email"
      />
      <FormKit
      type="password" label="mot de passe" name="password" placeholder="Votre mot de passe"
      />
    </FormKit>

    <p class="text-red-600">
      Pas de compte ?
      <NuxtLink class="uderline text-lime-600" to="/login">Inscrivez-Vous !</NuxtLink>
    </p>
  </div>
</template>

<script lang="ts" setup>

</script>

<style >
.m_form{
  margin-inline: auto;
}
</style>