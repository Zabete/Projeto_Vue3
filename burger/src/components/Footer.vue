<template>
    <div>
        <footer id="footer">
            <p>Burger &copy; 09/2023</p>
        </footer>
    </div>
</template>

<script>
export default {
    name: "Footer"
}
</script>

<style scoped>
    #footer {
        height: 300px;
        background-color: #222;
        border-top: 4px solid #111;
        color: #fcba03;
        display: flex;
        align-items: center;
        justify-content: center;
        bottom: 0;
        width: 100%;
    }
</style>