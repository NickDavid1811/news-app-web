<script>
export default {
  name: "footer-content"
}
</script>

<template>
  <div class=" bg-primary p-2">
    <p>Copyright &copy; 2024. ACME Studios</p>
    <p>
      {{ $t('authoring-phrase.intro') }} <i class="pi pi-heart-fill" />
      {{ $t('authoring-phrase.use') }} <a class="text-white" href="https://primevue.org/" target="_blank">PrimeVue</a>
      {{ $t('authoring-phrase.author', { brand: 'ACME' }) }}
    </p>
  </div>
</template>
