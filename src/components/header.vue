<script setup>
    const headerr = {
       
};
</script>

<template>
    <header>
        <div class="header">
            <div class="logo">Avi</div>
        </div>
        <div class="options">
            <ul>
                <li>
                    <a href="#">About</a>
                </li>
                <li>
                    <a href="#">Experience</a>
                </li>
                <li>
                    <a href="#">Contact</a>
                </li>
                <li>
                    <a href="#">Project</a>
                </li>
            </ul>
        </div>
    </header>
</template>

<style scoped>
    header {
        display: flex;
        justify-content: space-evenly;
        padding-top: 30px;
    }

    ul {
        display: flex;
        gap: 30px;
        list-style: none;
        margin-top: 0;
        padding-top: 0;
    }

    a{
        text-decoration: none;
        color: black;
    }

    li:hover {
        text-decoration: underline;
        color: gray;
    }
</style>
