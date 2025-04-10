<script setup>
import Widget from './components/Widget.vue'
</script>
<template>
  <Widget/>
</template>

<style>
  *,
  *::before,
  *::after {
    box-sizing: border-box;
  }

  html {
    overflow: hidden;
  }

  body {
    overflow: hidden;
  }
  body,
  h1,
  h2,
  h3,
  h4,
  p,
  ul[class],
  ol[class],
  li,
  figure,
  figcaption,
  blockquote,
  dl,
  dd {
    margin: 0;
  }

  ul[class],
  ol[class],li {
    list-style: none;
  }

  a {
    text-decoration: none;
  }
  button {
    border:none;
    cursor:pointer;
  }

</style>
