<template>
    <footer id="footer">
        <p>G7Burger &copy; 2023</p>
        <div>
            <a href="" target="_blank">Instagram</a>
            <a href="" target="_blank">Facebook</a>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style scoped>
    #footer {
        display: flex;
        flex-direction: column;
        width: 100%;
        height: 100px;
        background: #222;
        border-top: 4px solid #111;
        color: #fcba03;
        display: flex;
        align-items: center;
        justify-content: center;
        bottom: 0;
    }

    #footer p {
        margin-bottom: .5rem;
    }

    #footer a {
        text-decoration: none;
        color: #fff;
        margin: auto .5rem;
    }
</style>