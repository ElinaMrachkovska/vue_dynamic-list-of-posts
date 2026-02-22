<script setup lang="ts">
const emit = defineEmits<{
  (e: 'click'): void
}>();
</script>

<template>
  <button
    type="button"
    class="button is-link"
    data-cy="WriteCommentButton"
    @click="emit('click')"
  >
    Write a comment
  </button>
</template>