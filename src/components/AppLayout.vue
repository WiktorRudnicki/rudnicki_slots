<template>
    <div class="layout">
        <header class="crazy-diamond"><slot name="header"></slot></header>
        <main class="dogs"><slot></slot></main>
        <footer class="brick-in-the-wall"><slot name="footer"></slot></footer>
    </div>
</template>

<script>
export default {
};
</script>

<style>
.layout {
    display: flex;
};
.crazy-diamond{
    text-align: center;
    padding: 15px;
    background-color: green;
};
.brick-in-the-wall{
    text-align: center;
    padding: 15px;
    background-color: green;
    margin-top: 60%;
};
.dogs{
    height: 20%;
    width: 20%;
    padding: 10px;
    border: 5px solid black;
}
</style>
