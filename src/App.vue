<script setup>
  import Products from './components/Products.vue';
  
</script>

<template>
  <!--Nav bar section-->
  <section id="navbar">
    <nav class="nav_navbar">
      <ul class="navbar_links">
        <li class="nav_links"><a href="#">HOME</a></li>
        <li class="nav_links"><a href="#product">PRODUCT</a></li>
        <div class="nav_logo">
          <a href="#">JEWELLERY</a>
          <img src="public/diamond.png" alt="img_logo" class="img_logo" />
        </div>
        <li class="nav_links"><a href="#">SERVICES</a></li>
        <li class="nav_links"><a href="#">CONTACT</a></li>
      </ul>
    </nav>
  </section>

  <!--Slider section-->
  
  <div class="Slider"><!--Slider section-->
    <div class="fullslider">
    <div class="slider-model">
      <img src="public/slider-model.jpg" alt="Jewellery girl" class="model">
    </div>
    <div class="slider-content">
      <div class="slider-content-head">
        <h1>PREMIUM HANDMADE<br/>JEWELLERY ON EVERY<br/>OCCASION</h1>
      </div>
      <div class="slider-content-description">
        <p>In publishing and graphic design, Lorem ipsum
          is a placeholder text commonly used to
          demonstrate the visual form of a document
          or a typeface without relying.
        </p>
        <button class="btn">FIND OUT MORE</button>
      </div>
      
    </div>
    <div class="slider-diamond">
      <img src="public/diamond.png" alt="img_logo" class="slider-diamond-logo" />
    </div>
  </div>
</div>

  <section class="hero_section">
    <div class="hero-section">
      <div class="hero-product">
        <p class="hero-head">3000</p>
        <p class="hero-subhead">exclusive products</p>
        <div class="hero-icons-container">
          <div class="hero-icon">
            <div class="circle">
              <img src="public/ring-icon.png" alt="ring" class="hero-icon-inside">
            </div>
            <p class="hero-icon-description">Rings</p>
          </div>
          <div class="hero-icon">
            <div class="circle">
              <img src="public/bracelet.png" alt="ring" class="hero-icon-inside">
            </div>
            <p class="hero-icon-description">Bracelets</p>
          </div>
          <div class="hero-icon">
            <div class="circle">
              <img src="public/necklace.png" alt="ring" class="hero-icon-inside">
            </div>
            <p class="hero-icon-description">Necklace</p>
          </div>
          <div class="hero-icon">
            <div class="circle">
              <img src="public/earings.png" alt="ring" class="hero-icon-inside">
            </div>
            <p class="hero-icon-description">Earrings</p>
          </div>
          <div class="hero-icon">
            <div class="circle">
              <img src="public/tarias.png" alt="ring" class="hero-icon-inside">
            </div>
            <p class="hero-icon-description">Tiaras</p>
          </div>
          <div class="hero-icon">
            <div class="circle">
              <img src="watch.png" alt="ring" class="hero-icon-inside">
            </div>
            <p class="hero-icon-description">Watches</p>
          </div>
        </div>
      </div>
      <div class="hero-banner">
        <div class="lefthero-banner">
          <img src="leftbanner.jpg" alt="" id="leftmodel">
          <div class="banner-ad-left">
          <p id="leftbanner-description">NEW <br />SPRING<br /> COLLECTION</p>
          </div>
        </div>
        <div class="righthero-banner">
          <img src="rightnbanner.jpg" alt="" id="rightmodel">
          <div class="rightbanner-texts">
            <div banner-ad-right>
            <p id="rightbanner-head">20%<br />OFF</p>
            <p id="rightbanner-description">In publishing and <br /> graphic design,<br />Lorem ipsum is a
              <br />placeholder</p>
            <a href="#" style="letter-spacing: 2px; color: red;">Products</a>
          </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <Products />

  <section class="Gallery">
    <div class="gallery">
      <div class="ribbon-picture">
        <img src="ribbon-6.jpg" alt="jewellery girl" class="ribbon-model">
      </div>
      <div class="ribbon-picture">
        <img src="ribbon-6.jpg" alt="jewellery girl" class="ribbon-model">
      </div>
      <div class="ribbon-picture">
        <img src="ribbon-6.jpg" alt="jewellery girl" class="ribbon-model">
      </div>
      <div class="ribbon-picture">
        <img src="ribbon-6.jpg" alt="jewellery girl" class="ribbon-model">
      </div>
      <div class="ribbon-picture">
        <img src="ribbon-6.jpg" alt="jewellery girl" class="ribbon-model">
      </div>
      <div class="ribbon-picture">
        <img src="ribbon-6.jpg" alt="jewellery girl" class="ribbon-model">
      </div>
    </div>

  </section>

  <section class="FOOTER">
    <div class="footer">
      <div class="footer-1">
        <div class="footer_logo">
          <div class="text">
            <a href="#">JEWELLERY</a>
          </div>
          <img src="public/diamond.png" alt="img_logo" class="footer-diamond" />
        </div>
        <div class="footer-1-description">
          <p>Quam pulvinar leo euismod id eu <br/>ultricies, Placerat proin rhoncus sit.</p>
        </div>
        <div class="footer-1-ContactUs"><a href="#">Contact Us</a></div>
        <div class="footer-1-logo-collection">
          <div class="footer-1-logo"><img src="icon _Visa_.png" alt="">
          </div>
          <div class="footer-1-logo"><img src="icon _PayPal_.png" alt="">
          </div>
          <div class="footer-1-logo"><img src="icon _MasterCard_.png" alt="">
          </div>
          <div class="footer-1-logo"><img src="icon _maestro_.png" alt="">
          </div>
        </div>
      </div>
      <div class="footer-2">
        <p class="footer-headers">Useful links</p>
        <a href="#" class="foooter-link">Contact us</a>
        <a href="#" class="foooter-link">Help and About us</a>
        <a href="#" class="foooter-link">Shipping and Returns</a>
        <a href="#" class="foooter-link">Refund Policy</a>
        <p class="footer-headers">Delivery</p>
        <a href="#" class="foooter-link">How it works</a>
        <a href="#" class="foooter-link">Free delivery</a>
        <a href="#" class="foooter-link">FAQ</a>
      </div>
      <div class="footer-3">
        <p class="footer-headers">Customer Service</p>
        <a href="#" class="footer-link">Orders</a>
        <a href="#" class="footer-link">Downloads</a>
        <a href="#" class="footer-link">Adresses</a>
        <a href="#" class="footer-link">Account Details</a>
        <a href="#" class="footer-link">Lost password</a>
      </div>
      <div class="footer-4">
        <p class="footer-headers">Customer Service</p>
        <a href="#" class="footer-header">+61 (0) 383 766 284</a>
        <a href="#" class="footer-header">+61 (0) 383 766 284</a>
        <p class="#" :class="footer-link">Monday-Friday</p>
        <p class="#" :class="footer-link">8am-5pm</p>
        <p class="#" :class="footer-link">Monday-Friday</p>
        <p class="#" :class="footer-link">6am-5pm</p>

      </div>
    </div>
  </section>
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
  margin-top: 8rem;
  display: grid;
  grid-template-columns: repeat(4, auto);
  justify-content: space-between;
  padding: 0 8rem;


}
.footer_logo{

  display: flex;
  justify-content: center;
}
.footer-1 .text{
  position: relative;
}

.footer-diamond {
  z-index: 2;
  left: 0;
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

</style>