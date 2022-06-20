<template>
    <div class="welcome">
      <div class="welcome-container">
        <div><h1 class="main-welcome default center">My Blog</h1></div>
        <div><p class="description-welcome default center">
          Here I will tell you what happened to me new. 
          About me and my life. About news and my opinion about it. 
          About investing and my successful in this sphere.</p></div>
        <div class="description-welcome-parts default">
          <div><p class="description-welcome-part description-welcome-part-1 default">Lorem Ipsum is simply dummy text of the printing
            and typesetting industry. Lorem Ipsum has been the industry's
            standard dummy text ever since the 150</p></div>
          <div><p class="description-welcome-part description-welcome-part-2 default">It is a long established fact that a reader will be distracted by the readable content
            of a page when looking at its layout. The point...</p></div>
        </div>
      </div>
    </div>
</template>

<script>
export default { name: 'welcome' }
</script>

<style scoped>
.welcome {
    min-width: 100%;
    padding-top: 80px;
    padding-bottom: 80px;
    background: url(../assets/sea.jpg);
    border-radius: 0px 0px 10px 10px;
    
}
.welcome-container {
    margin: 0px auto;
    max-width: 40%;
    max-height: 730px;
    padding: 50px;
    background-color: #ffffff31;
    backdrop-filter: blur(15px);
    background-repeat: no-repeat;
    background-attachment: fixed;
    border-radius: 9.5px;
    border: 1px solid white;
}
.main-welcome {
    font-family: 'Inria Serif';
    font-size: 65px;
    padding: 0px;
    padding-bottom: 20px;
}
.description-welcome {
    font-family: 'IM FELL Double Pica';
    font-size: 22px;
    padding: 26px;
}
.description-welcome-part {
    text-align: justify;
    font-family: 'IM FELL Double Pica';
    font-size: 20px;
    padding: 16px;
}
.description-welcome-parts {
    display: grid;
    grid-template-columns: 50% 50%;
}
</style>