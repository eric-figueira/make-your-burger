<template>
    <footer id="footer">
        <p>Make Your Burger &copy; 2021</p>
    </footer>
</template>

<script>

    export default {
        name: 'Footer'
    }
</script>

<style scoped> 

    #footer {
        height: 200px;
        background: #222;
        border-top: 4px solid #111;
        color: #FCBA03;
        display: flex;
        justify-content: center;
        align-items: center;
        bottom: 0;
        width: 100%
    }

</style>