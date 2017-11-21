<template>
  <div class="flex-row" :style="{'justify-content': justifyContent, 'align-items': alignItems}">
    <slot></slot>
  </div>
</template>

<script>
  export default {
    name: 'flex-row',
    props: ['justifyContent', 'alignItems']
  }
</script>
