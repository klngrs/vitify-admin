<template>
  <v-container fluid>Username: {{ props.id }}</v-container>
</template>

<script setup lang="ts">
const props = defineProps<{ id: string }>()
</script>

<script lang="ts">
export default defineComponent({ name: 'UserDetail' })
</script>

<route lang="json">
{ "meta": { "title": "userDetail", "breadcrumb": "disabled" } }
</route>
