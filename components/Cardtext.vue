<template>
<div class="leading-7 p-4">
 <slot></slot>
</div> 
</template>
 
<script>
  export default {
    props: ['title', 'category', 'text']
  }
</script>