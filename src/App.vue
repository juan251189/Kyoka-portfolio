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



      <section id="welcome-tour" class="container-fluid">
      <div class="container">
        <div class="row">
          <div class="col-md-6">
          <h3>
          WELCOME TO OUR
          </h3>
          <h1>
            MODELING AGENCY...
          </h1>
        </div>
          <div class="col-md-6">
            <h4>FRINGILLA LACUS ORCI ET NUNC. SED DIGNISSIM, LECTUS NON MATTIS FAUCIBUS, NISL NIBH IACULIS ANTE, SIT AMET FRINGILLA VELIT EST SED DIAM. VESTIBULUM VESTIBULUM.</h4>
            <p>Praesent accumsan ac velit vitae auctor. Proin pharetra consectetur leo, nec porta magna varius nec. Sed vehicula eros neque, a venenatis est lobortis id. Aenean id lectus sit amet odio pellentesque gravida. Suspendisse potenti. Praesent non nunc ac orci facilisis auctor. Cras metus quam, condimentum ut venenatis in, rutrum eget diam. Sed vehicula at risus quis fringilla</p>
          </div>
        </div>
      </div>

      </section>


  <div id="news" class="container">
    <div class="row">
      <div class="col-12"></div>
    </div>
  </div>

  <div id="projects-campagin" class="container">
    <div class="row">
      <div class="col-md-4 projects">
        <img src="~@/assets/front-flowers-nobackground.png" class="img-projects" alt="" style="position:absolute;max-width:400px;height:100%;right:0.1%;">

        <h1 class="title-projects">Products</h1>
      </div>
      <div class="col-md-4 projects">
        <img src="~@/assets/front-flowers-nobackground.png" class="img-projects" alt="" style="position:absolute;max-width:400px;height:100%;right:0.1%;">

        <h1 class="title-projects">Gallery</h1>
      </div>
      <div class="col-md-4 projects">
        <img src="~@/assets/front-flowers-nobackground.png" class="img-projects" alt="" style="position:absolute;max-width:400px;height:100%;right:0.1%;">

        <h1 class="title-projects">Work-out Plans</h1>
      </div>
    </div>


  </div>




  <section id="catalog">
    <div class="container">

      <h2 class="catalog-header">NEW MODELS</h2>
      <div class="row">
        <div class="col-md-3 col-sm-6"><div class="image-section"><img src="~@/assets/front-flowers.png" alt="" class="img-circle"><h4 class="catalog-text-header">Name</h4></div><p class="catalog-text">

SFATI FRINCO
Portugal
pharetra consectetur lnec port magn. Sed vehicula eros nequelectus.</p></div>
        <div class="col-md-3 col-sm-6"><img src="~@/assets/front-flowers.png" alt="" class="img-circle"><h4>Name</h4><p>sub name</p></div>
        <div class="col-md-3 col-sm-6"><img src="~@/assets/front-flowers.png" alt="" class="img-circle"><h4>Name</h4><p>sub name</p></div>
          <div class="col-md-3 col-sm-6"><img src="~@/assets/front-flowers.png" alt="" class="img-circle"><h4>Name</h4><p>sub name</p></div>
      </div>
    </div>
  </section>


https://www.gracethemes.com/demo/modeling/


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
.container{

  padding: 0px;

}
.border{

}
.row{

  padding: 0px;
  margin:0px;
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



#biography {

  padding:70px 10px;


  font-family: sans-serif, monospace;
  font-size: 1.7em;
  font-weight: 700;

}


#projects-campagin {

}

.img-projects:hover{
opacity: 0.5;

}

.projects{

  border: 1px solid green;
  width: 100%;
  height: 450px;

/*  background-image: url('~@/assets/front-flowers-nobackground.png'); /* fallback */
    background-image:/* url('~@/assets/front-flowers-nobackground.png'),*/ linear-gradient(#8c8c8c, #4d5167); /* W3C */

  background-repeat: no-repeat;
  background-position:right;
  background-attachment: fixed;

}

.title-projects{
  position: relative;
  top:60%;
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;


  font-family: sans-serif,'monserrate';
  font-weight: 700;
  color: white;
  text-shadow: 1px 1px rgb(29,27,32,0.6)
}

#welcome-tour{
  background-color: #FAFAFA;
}

#catalog{

}

.catalog-header{
  width: 100%;
  text-align: center;
  padding-bottom: 3%;

  font-weight:bold;
}
.img-circle{
  max-width: 100%;
  max-height: 100%;
  border-radius: 100%;
  margin-bottom: 30px;
}


.image-section:hover .image-circle{
width: 600%;
  background-color: red;


}
.catalog-text-header{
  color:black;
  font-weight: bold;

  text-align: center;
}
.catalog-text{
  font-weight: 700;
  font-family: 'Assistant', sans-serif;

  text-align: center;
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

}
</style>
