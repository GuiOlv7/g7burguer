<template>
    <div id="main-banner">
        <h1>Monte Seu Lanche</h1>
    </div>
</template>

<script>
export default {
    name: 'Banner'
}
</script>

<style scoped>
    #main-banner {
        background-image: url('/public/img/burger.jpg');
        background-position: 0 -250px;
        background-size: cover;
        height: 500px;
        display: flex;
        align-items: center;
        justify-content: flex-start;
    }

    #main-banner h1 {
        background: #2222225c;
        color: #fff;
        text-align: center;
        font-size: 60px;
        padding: 20px 40px;
        border-radius: 7.5px;
        letter-spacing: 3px;
    }
</style>