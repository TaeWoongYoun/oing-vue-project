<template>
    <header>
        <h1>Vue Web Page</h1>
        <nav>
            <ul>
                <li><a href="/oing-vue-project/src/views/HomePage.vue">Home</a></li>
                <li><a href="/oing-vue-project/src/views/AboutPage.vue">About</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>
</template>

<style scoped>
    header {
        width: 100%;
        height: 70px;
        background-color: #4CAF50;
        color: white;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    header h1{
        padding-left: 20px;
    }
    nav ul {
        list-style: none;
        padding-left: 0;
    }
    nav ul li {
        display: inline-block;
        margin-right: 20px;
    }
</style>
