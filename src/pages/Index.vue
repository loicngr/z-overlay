<template>
  <q-page class="scroll">
    <h1 class="full-width text-center">Sources</h1>
    <div class="flex flex-center">
      <sources />
    </div>
  </q-page>
</template>

<script>
import Sources from 'components/Sources'

export default {
  name: 'PageIndex',
  components: {
    sources: Sources
  }
}
</script>
