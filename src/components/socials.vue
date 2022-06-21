<template>
<div class="social">
    <div class="social-container">
        <div><p class="name default center">Medium</p></div>
        <div><p class="description default">My main social network.
            All Articles stored here. Everything is free to read.
            You can visit profile by button bottom.</p></div>
        <p class="default center button-container"><a class="button" href="https://medium.com/">Visit</a></p>
    </div>
    <div class="social-container">
        <div><p class="name default center">YouTube</p></div>
        <div><p class="description default">I shoot a lot of
            educational videos on the subject of investing.
            I'm waiting for you on my channe.</p></div>
        <p class="default center button-container"><a class="button" href="https://medium.com/">Visit</a></p>
    </div>
    <div class="social-container">
        <div><p class="name default center">Telegram</p></div>
        <div><p class="description default">Here I make exclusive posts and
            communicate with the audience. Sometimes I do giveaways.</p></div>
        <p class="default center button-container"><a class="button" href="https://medium.com/">Visit</a></p>
    </div>
    <div class="social-container">
        <div><p class="name default center">Discord Server</p></div>
        <div><p class="description default">There is also a place for
            communication only for a wider number of people.</p></div>
        <p class="default center button-container"><a class="button" href="https://medium.com/">Visit</a></p>
    </div>
    <div class="social-container">
        <div><p class="name default center">Twitter</p></div>
        <div><p class="description default">Here I write what is happening
            in my life and my opinion about the news</p></div>
        <p class="default center button-container"><a class="button" href="https://medium.com/">Visit</a></p>
    </div>
    <div class="social-container">
        <div><p class="name default center">Github</p></div>
        <div><p class="description default">You can find my automated
            trading scripts here. </p></div>
        <p class="default center button-container"><a class="button" href="https://medium.com/">Visit</a></p>
    </div>
</div>
</template>

<script>
export default { name: 'socials' }
</script>

<style scoped>
.social {
    display: grid;
    grid-template-columns: 33.333333% 33.333333% 33.333333%;
    background: url(../assets/light.jpg);
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    border-radius: 10px;
    filter: contrast(85%);
}
.social-container {
    margin: 45px;
    color: white;
    padding: 25px;
    border-radius: 15px;
    box-shadow: 0px 10px 0px rgba(0, 0, 0, 0.178);
    background-color: #0000003f;
    backdrop-filter: blur(50px);
    transition: .1s;
}
.social-container:hover {
    transform: translateY(-15px);
}
.name {
    font-family: 'Inria Serif';
    font-size: 40px;
    padding-bottom: 25px;
}
.description { 
    text-align: justify;
    font-family: 'IM FELL Double Pica';
    font-size: 25px;
    margin-left: 40px;
    margin-right: 40px;

}
.button {
    padding: 15px;
    padding-left: 55px;
    padding-right: 55px;
    font-size: 25px;
    font-family: 'Inter';
    text-decoration: none;
    color: white;
    background: linear-gradient(90deg, #00B2FF, #26DAC4);
    border-radius: 25px;
    transition: 0.5s;
}
.button:hover {
    outline: 5px solid rgba(22, 172, 199, 0.11);
}
.button-container {
    margin: 25px;
    margin-top: 40px;
    
}

</style>