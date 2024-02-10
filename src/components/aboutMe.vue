<template>
    <div class="about">
        <div class="top">
            <div class="get">
            <div class="small">
                Get to know more
            </div>
            <div class="larger">
                About me
            </div>
        </div>
        </div>
        <div class="main">
            <div class="image">
                <img src="https://spikree.github.io/my-portfolio/assets/about-pic.png" alt="toji aka me">
            </div>
            <div class="content">
            <div class="experience">
                <h4 style="justify-content: center; display: flex;">Experience</h4>
                <p>3+ months as an intern</p>
                <p>Front end developement</p>
            </div>
            <div class="edu">
                <h4 style="display: flex; justify-content: center;">education</h4>
                <p>currently in third year of my computer science bachlors degree</p>
            </div>
        </div>
        </div>
    </div>
</template>

<script>
        const About = {
       
    };
</script>

<style scoped>
    .about {
        display: flex;
        gap: 100px;
        flex-direction: column;
    }

    .main {
        display: flex;
        gap: 70px;
        justify-content: center;
        align-content: center;
    }

    img {
        height: 350px;
    }

    .top {
        display: flex;
        justify-content: center;
        align-content: center;
    }

    .content {
        display: flex;
        gap: 100px;
        margin-top: 90px;
    }
    
    .larger {
        display: flex;
        justify-content: center;
    }
</style>