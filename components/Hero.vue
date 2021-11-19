<template>
    <div class="Hero container">
        <div class="text-container">
            <h1 class="header">Find your Vacuum Cleaner</h1>
            <p class="snippet">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste iusto illum quidem asperiores, cum nisi aperiam eius ipsa sapiente odit!</p>
            <button class="button btn">Start Looking</button>
        </div>
        <span class="circle"></span>
        <img class="image" src="~assets/svg/vacuum-cleaner.svg" alt="fire extinguisher">
    </div>
</template>

<script>
    export default {
    }
</script>

<style scoped>
    .Hero {
        height: 600px;
        position: relative;
        display: flex;
        padding: 5rem 0;
        align-items: flex-start;
        justify-content: space-between;
    }
    .container{}
    .text-container {
        width: 50%;
        margin-top: 4rem;
    }
    .header {
        font-weight: 900;
        font-size: 5rem;
    }
    .snippet {
        color: grey;
        font-size: 1.25rem;
    }
    .image {
        width: 22rem;
        margin-top: 4.8rem;
        z-index: 2;
    }
    .circle {
        border-radius: 50%;
        width: 22rem;
        height: 22rem;
        background-color: rgb(231, 81, 43);
        position: absolute;
        right:70px;
        top:170px;
        z-index: 1;
    }
    .overlay {
        background: rgba(0, 0, 0, 0);
        position: absolute;
        width: 100%;
        height: 100%;
        top: 0;
    }
    .button {
        padding: 1rem 4rem;
        border-radius: 100rem;
        background-color: rgb(231, 81, 43);
        color: white;
        width: 20rem;
        font-weight: 700;
        transition: 0.5s;
    }
    .button:hover {
        width: 21.5rem;
    }
    @media (max-width: 500px) {
        .Hero {
            height: 40vh;
        }
    }
</style>