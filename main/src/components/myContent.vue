<template>
    <div class="content">
        <div class="wrapper">
            <div class="logo">
                <img src="../assets/img/google.png">
            </div>
            <div class="search-bar">
                <img src="../assets/img/magnifying_glass.jpg">
                <input type="text" id="search-input" @keyup.enter="addMessage" v-model="txtInput">
                <img src="../assets/img/mic.png">
            </div>
            <div class="buttons" id="search">
                <button class="button" v-on:click="addMessage()">
                    Google Search
                </button>
                <button class="button" onclick="location.href='https://www.google.com/doodles'">
                    I'm Feeling Lucky
                </button>
            </div>
            <div class="language">
                Google offered in:
                <a href="">
                    Română
                </a>
                <a href="">
                    Magyar
                </a>
                <a href="">
                    Deutsch
                </a>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'my-content',
//   props: {
//     msg: String
//   }
    data() {
        return {
            txtInput: ''
        }
    },
    methods: {
        addMessage() {
            if(this.txtInput != '')
                window.location.href = 'https://www.google.com/search?q=' + this.txtInput;
        }
    }
}
</script>

<style>
  @import '../styles/content.css';
</style>