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
            <div class="dropdown">
                <a href="#" id="imageDropdown" data-toggle="dropdown">
                    <img src="../assets/img/avatar.jpg">
                </a>
            <ul class="dropdown-menu" role="menu" aria-labelledby="imageDropdown">
                <li role="presentation"><a role="menuitem" tabindex="-1" href="#">Menu item 1</a></li>
                <li role="presentation"><a role="menuitem" tabindex="-1" href="#">Menu item 2</a></li>
                <li role="presentation"><a role="menuitem" tabindex="-1" href="#">Menu item 3</a></li>
                <li role="presentation" class="divider"></li>
                <li role="presentation"><a role="menuitem" tabindex="-1" href="#">Menu item 4</a></li>
            </ul>
            </div>
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