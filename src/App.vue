<template>
<div id="app">

  <section id="nav">



  </section>



  <section id="social-menu">


    <!-- Add font awesome icons -->
    <a href="#" class="fa fa-facebook"></a>
    <a href="#" class="fa fa-twitter"></a>
    <a href="#" class="fa fa-youtube"></a>
    <a href="#" class="fa fa-instagram"></a>

  </section>


  <div class="container">



    <section id="front">
      <div class="row">

        <div class="col-12" style="margin:0px;padding:0px;border:2px solid green;">
          <img src="~@/assets/front-flowers.png" alt="" style="position:relative;min-width:100%;height:100vh;border-bottom:20px solid black;">
          <div class="title-container">
            <p class="title">KYOKA YAMASHITA</p>
            <p class="subTitle">Japanese Supermodel & Entrepreneur</p>

          </div>
        </div>

      </div>
    </section>
  </div>


  <div class="container">
    <div id="biography">
      <div class="row">
        <div class="col-7">

          <p>
            I’m Karlie Kloss, supermodel, entrepreneur and philanthropist. I started my career as a model, and have since discovered my passion for technology, entrepreneurship, & storytelling. When I’m not modeling, I spend my time working on my STEAM
            focused non-profit Kode With Klossy, my YouTube channel, Klossy, & supporting the next generation of designers on Project Runway.</p>
        </div>
      </div>

    </div>
  </div>

  <div id="news" class="container">
    <div class="row">
      <div class="col-12"></div>
    </div>
  </div>

  <div id="projects-campagin" class="container-fluid">
    <div class="row">
      <div class="col-sm-6 col-xs-12 col align-self-start" style="border:1px solid green;text-align:center;height:200px;"></div>
      <div class="col-sm-6 col-xs-12 text-center">
      <h1>Projects</h1>
        <img src="~@/assets/front-flowers.png" alt=""></div>
        <div class="col-sm-6 col-xs-12 " style="border:1px solid green;text-align:center"></div>

    </div>

    <div class="row">
      <div class="col-sm-6 col-xs-12 text-center" style="padding:0px;margin:0px;">
      <h1>Projects</h1>
        <img src="~@/assets/front-flowers.png" alt="" ></div>
        <img src="~@/assets/front-flowers.png" alt="">
    </div>
  </div>


  <div id="gallery">

  </div>
  <div id="follow-me">

  </div>





</div>
</template>

<script>
export default {
  name: "App",
  components: {

  }
};
</script>

<style scoped>
#app {
  font-family: "monserrate", Arial, sans-serif;
  overflow-x: hidden;
}


#social-menu {
  position: fixed;
  top: 50%;
  -webkit-transform: translateY(-50%);
  -ms-transform: translateY(-50%);
  transform: translateY(-50%);

  right: 1%;
  display: grid;
  grid-template: 1;
  z-index: 2;
}

.fa {
  padding: 20px;
  font-size: 20px;
  width: 60px;
  text-align: center;
  text-decoration: none;
  margin: 5px 2px;
  border-radius: 50%;
}

.fa:hover {
  opacity: 0.7;
}

.fa-facebook {
  background: #3B5998;
  color: white;
}

.fa-twitter {
  background: #55ACEE;
  color: white;
}


.fa-youtube {
  background: #bb0000;
  color: white;
}

.fa-instagram {
  background: #125688;
  color: white;
}






#front {
  height: 100vh;

  padding: 0px;
  margin: 0px;
  position: relative;
  border-bottom: 2px solid black;
  overflow: hidden;

}

.title-container {
  padding: 0px;
  margin: 0px;
  position: absolute;

  top: 60%;
  width: 100%;

  text-align: center;
  z-index: 2;
}

.title {
  padding: 0px;
  margin: 0px;

  font-family: Teko, sans-serif;
  font-size: 5em;
  color: white;
  font-weight: 500;
  text-shadow: 2px 2px rgb(29, 32, 32, 0.6);


}

.subTitle {
  padding: 0px;
  margin: 0px;
  color: white;
  position: relative;
  width: 100%;



  font-weight: 700;
  font-size: 1.2em;
  text-shadow: 2px 2px rgb(29, 32, 32, 0.6);

}
.container{
  border:3px solid red;
  padding: 0px;
}

#biography {

  padding:70px 10px;


  font-family: sans-serif, monospace;
  font-size: 1.7em;
  font-weight: 700;

}


@media only screen and (max-width:600px) {
#social-menu{

  top: 90%;
  -webkit-transform: translateY(-50%);
  -ms-transform: translateY(-50%);
  transform: translateY(-50%);


  display: hidden;
  grid-template: 1;

}
}

@media (min-width: 1200px) {
    .container{
        max-width: 1470px;
    }
}
</style>
