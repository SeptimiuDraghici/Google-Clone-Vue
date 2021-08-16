<template>
    <div class="header">
        <a href="https://www.google.com/gmail/about/#">
            Gmail
        </a>
        <a href="https://www.google.ro/imghp?hl=en&authuser=0&ogbl">
            Images
        </a>
        <div class="img-dots">
            <img src="../assets/img/dots.svg">
        </div>
        <div class="img-avatar">
            <img src="../assets/img/avatar.jpg">
        </div>
    </div>
</template>

<script>
export default {
  name: 'my-header',
//   props: {
//     msg: String
//   }
}
</script>

<style>
  @import '../styles/header.css';
</style>