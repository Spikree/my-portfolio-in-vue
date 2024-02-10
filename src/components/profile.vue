<template>
       <section id="profile">
    <div class="section__pic-container">
        <img src="../assets/profile-pic.png" alt="Avi profile picture">
    </div>
    <div class="section__text">
        <p class="section__text__p1">Hello, I'm</p>
        <h1 class="title">Avi ★</h1>
        <p class="section__text__p2">Fullstack web and flutter developer</p>
        <div class="btn-container">
            <button class="btn btn-color-2" onclick="window.open('./assets/resume-example.pdf')">Download cv</button>
            <button class="btn btn-color-1" onclick="location.href ='./#contact'">Contact</button>
        </div>
        <div id="socials-container">
            <a href="boohoo.html"><img src="../assets/linkedin.png" alt="Linkedin logo/profile" class="icon"></a>
            <a href="https://github.com/Spikree"><img src="../assets/github.png" alt="github logo/profile" class="icon"></a>
        </div>
    </div>
   </section>
</template>

<script>
    const profile = {
       
};
</script>

<style  scoped>

</style>