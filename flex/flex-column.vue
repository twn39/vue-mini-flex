<template>
  <div class="flex-column" :style="{'justify-content': justifyContent, 'align-items': alignItems}">
    <slot></slot>
  </div>
</template>

<script>
  export default {
    name: 'flex-column',
    props: ['justifyContent', 'alignItems']
  }
</script>
