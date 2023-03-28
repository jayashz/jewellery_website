<script setup>
  import Products from './components/Products.vue';
  import hero from'./components/hero.vue';
  import footers from'./components/footer.vue';
  import ribbon from'./components/ribbon.vue';
  import slider from'./components/slider.vue';
  
  
</script>

<template>
  <!--Nav bar section-->
  <section id="navbar">
    <nav class="nav_navbar">
      <ul class="navbar_links">
        <li class="nav_links"><a href="#">HOME</a></li>
        <li class="nav_links"><a href="#product">PRODUCT</a></li>
        <div class="nav_logo">
          <a href="#" id="logo-text">JEWELLERY</a>
          <img src="public/diamond.svg" alt="img_logo" class="img_logo" />
        </div>
        <li class="nav_links"><a href="#">SERVICES</a></li>
        <li class="nav_links"><a href="#">CONTACT</a></li>
      </ul>
    </nav>f
  </section>


  
  <slider/>

  <hero/>

  <Products />

  <ribbon/>

  <footers/>

</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Heebo&display=swap');

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  text-decoration: none;
  font-family: 'Heebo', sans-serif;

}
html{
  scroll-behavior: smooth;
}

.nav_navbar {
  width: 100%;
  padding: 1.5rem 0;
  background-color: #272727;

}

.navbar_links {

  align-items: center;
  display: flex;
  justify-content: center;
}

ul li {
  list-style: none;
}

.nav_logo {
  margin: 0 19rem;


  display: flex;
  position: relative;
  justify-content: center;

}

.nav_logo a {
  z-index: 2;
  font-size: 16px;
  color: #beb698;
}

.nav_links {
  margin: 0 1.5rem;
}

.nav_links a {
  font-size: 14px;
  color: white;
}
.nav_logo a{
  color: white;
  font-weight: bold;
  padding-top: 0.6rem;
}
.img_logo {
  position: absolute;
  z-index: 0;
  top: -25%;

}

.Slider{

  position: relative;
}

.fullslider{
  width: 100%;
  background-color: black;
  display: flex;
}

.model{
width: 100%;
height: 100%;
}


.slider-content {
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.slider-content-head{
  line-height: 2.5rem;
  margin-bottom: 1rem;
}
.slider-content-head h1 {
  color: #AB9D90;
  font-size: 33px;
}

.slider-content p {
  color: #ffffff;
  font-size: 1rem;
  letter-spacing: 3px;
  line-height: 19px;
  padding-right: 8rem;
  
}
.slider-content-description{
  padding-right: 2rem;
}
.btn{
  color: #AB9D90;
  border: 1px solid #403732;
  background-color: transparent;
  padding: 10px;
  margin-top: 1.5rem;
  width: 8rem;
  cursor: pointer;
}
.slider-diamond {
  width: 50px;
  height: 50px;
  z-index: 3;
  background-color: #ffffff;
  position: absolute;
  transform: rotate(45deg);
  display: flex;
  align-items: center;
  justify-content: center;
  bottom: -25px;
  left: calc(50% - 25px);
}

.slider-diamond-logo {

  transform: rotate(-45deg);


}

.hero-section {
  width: 100%;
  height: 100vh;
  padding: 0 8rem;
  background-color: #403732;
  display: flex;
  flex-direction: column;

}

.hero-product {
  margin-top: 7rem;
  position: relative;
  background-color: #403732;
  text-align: center;

}

.hero-head {
  font-size: 64px;
  color: white;
  text-align: center;
}

.hero-subhead {
  font-size: 32px;
  margin-top: -20px;
  color: white;
}

.hero-icons-container {
  z-index: 2;
  margin: 4rem 0;
  background-color: #403732;
  display: flex;
  justify-content: space-between;
}


.circle {
  height: 100px;
  width: 100px;
  border-radius: 50%;
  border: 1.5px solid white;
}

.hero-icon-description {
  color: white;
  margin-top: 14px;
}

.hero-icon-inside {
  margin-top: 17px;
  margin-left: 4px;
}

.hero-banner {
  width: 100%;
  /* height: 40rem; */
  position: relative;
  display: flex;
  height: 45rem;

}

.lefthero-banner {
  width: 50%;
  height: 100%;
  position: relative;
  z-index: 2;

  overflow: hidden;

}

.righthero-banner {
  width: 50%;
  height: 100%;
  position: relative;
  z-index: 2;

  overflow: hidden;
}

#leftmodel {
  width: 100%;
  height: 90%;
  object-fit: cover;


}

#rightmodel {
  width: 100%;
  height: 90%;
  object-fit: cover;
}

#leftbanner-description {
  z-index: 3;
  font-size: 46px;
  position: absolute;
  top: 30%;

  left: 18%;
  color: #ffffff;
  line-height: 55px;
}

.rightbanner-texts {
  position: absolute;
  z-index: 3;
  top: 20%;
  left: 18%;
  color:  #4E4540;

}

#rightbanner-head {
  font-size: 64px;
  line-height: 4rem;
}

#rightbanner-description {
  font-size: 14px;  
  letter-spacing: 2px;
  margin-bottom: 1rem;
}
.gallery-container{
  width: 100%;
  margin-top: 18%;
  display: flex;
  justify-content: center;
  align-items: center;
}
.product-gallery{
  margin-top: 20rem;
}
.gallery-item {
  background-color: #F9F2EC;
  padding: 3rem 2rem;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
.gallery-header{
padding-left: 8rem;


}
.gallery-item-container {
  position: relative;
  margin-top: 10%;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  padding: 0 8rem;
  gap: 2rem;
}

.gallery-picture {
  width: 80%;

}

.product-price {
  padding-top: 1rem;

}

.gallery {
  margin-top: 10rem;
  display: grid;
  grid-template-columns: repeat(6,1fr);
  padding: 0 8rem;
}

.ribbon-picture {
  width: 100%;

}

.ribbon-model {

  width: 100%;

}

.footer {

  display: grid;
  grid-template-columns: repeat(4, auto);
  justify-content: space-between;
  padding: 8rem 8rem;
  padding-bottom: 1rem;

}
.footer_logo{
  display: flex;
  padding-bottom: 1rem;
}
.footer-diamond{
  position: relative;

}

.footer-1-description{
  font-size: 13px;
  margin-bottom: 1rem;
}
.footer-1 .text{
  position: relative;
  z-index: 2;
  top: 1rem;
  left: 0.7rem;


}
.footer-1-ContactUs{
  margin-bottom: 1.5rem;
}
.footer-diamond {

  position: relative;
  right: 60px;
}

.footer-1-logo-collection {

  display: flex;

}

.footer-2 {
display: flex;
flex-direction: column;

}

.footer-3 {
  display: flex;
  flex-direction: column;

}

.footer-4 {
display: flex;
flex-direction: column;

}
.footer-end{
  margin-top: 6rem;
}

</style>