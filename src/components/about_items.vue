<template>
<div class="about_items">
    <div class="about_item">
        <div class="logo_item" id="logo_item_1"></div>
        <div class="text-container">
            <div><p class="about-name default">About traveling</p></div>
            <div><p class="about-description default">I am writing about nature. You can my articles about nature <a href="https://medium.com/" class="link">here</a></p></div>
        </div>
    </div>
    <div class="about_item">
        <div class="logo_item" id="logo_item_2"></div>
        <div class="text-container">
            <div><p class="about-name default">About news</p></div>
            <div><p class="about-description default">This is block about news. I write very frequently on this topic. You can my articles <a href="https://medium.com/" class="link">here</a></p></div>
        </div>
    </div>
    <div class="about_item">
        <div class="logo_item" id="logo_item_3"></div>
        <div class="text-container">
            <div><p class="about-name default">About investing</p></div>
            <div><p class="about-description default">I have already written a lot of useful information about investing in the cryptosphere. Watch <a href="https://medium.com/" class="link">here</a></p></div>
        </div>
    </div>

</div>
</template>

<script>
export default { name: 'about_items' }
</script>

<style scoped>
.link { text-decoration: underline; color: blue; }
.about_item {
    margin-bottom: 25px;
    margin-top: 25px;
    margin-left: 15%;
    margin-right: 15%;
    outline: 2px solid white;
    box-shadow: 0px 6px 0px white;
    border-radius: 19px; 
    color: white;
    display: flex;
    padding: 15px;
    transition: .05s;
    box-shadow: 0px 6px 0px white;
}
.about_item:hover { outline: 4px solid white; }
.logo_item {
    padding: 128px;
    border-radius: 6px;
}
#logo_item_1 { background: linear-gradient(240deg, #3C87CC, #37E472) }
#logo_item_2 { background: linear-gradient(240deg, #CC3C70, #E49537) }
#logo_item_3 { background: linear-gradient(240deg, #C8CB48, #37BBE4) }
.text-container {
    margin-top: auto;
    margin-bottom: auto;
    margin-left: 5%;
}
.about-name {
    font-family: 'Inria Serif';
    font-size: 35px;
    margin-bottom: 25px;
}
.about-description {
    font-family: 'Inria Serif';
    font-size: 25px;
}
</style>