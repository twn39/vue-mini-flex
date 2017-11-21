<template>
  <div class="flex" :style="{'justify-content': justifyContent, 'align-items': alignItems, flex: flex}">
    <slot></slot>
  </div>
</template>

<script>
  export default {
    name: 'flex',
    props: ['justifyContent', 'alignItems', 'flex']
  }
</script>
