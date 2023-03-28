<script setup>
  var products = [
    {
      name: 'Hello',
      price: '$10 - $20',
      image: 'localhost/jewelry/image.png'
    },
    {
      name: 'Dark earings',
      price: '$10 - $20',
      image: 'localhost/jewelry/image.png'
    }

    

]
</script>

<template>
    <div class="gallery-container" id="product">  <!--Gallery section-->
    <div class="product-gallery">
      <h1 class="gallery-header"> Products</h1>
      <div class="gallery-item-container">
      <div class="gallery-item" v-for="product in products">
        <img src="1.png" alt="" class="gallery-picture">
        <div class="product-price">
          <p>{{ product.name }}</p>
          <p>$10.00-&20.00</p>
        </div>
      </div>
      <div class="gallery-item">
        <img src="2.png" alt="" class="gallery-picture">
        <div class="product-price">
          <p>Dark earings</p>
          <p>$10.00-&20.00</p>
        </div>
      </div>
      <div class="gallery-item">
        <img src="3.png" alt="" class="gallery-picture">
        <div class="product-price">
          <p>Dark earings</p>
          <p>$10.00-&20.00</p>
        </div>

      </div>
      <div class="gallery-item">
        <img src="4.png" alt="" class="gallery-picture">
        <div class="product-price">
          <p>Dark earings</p>
          <p>$10.00-&20.00</p>
        </div>

      </div>
      <div class="gallery-item">
        <img src="5.png" alt="" class="gallery-picture">
        <div class="product-price">
          <p>Dark earings</p>
          <p>$10.00-&20.00</p>
        </div>

      </div>
      <div class="gallery-item">
        <img src="6.png" alt="" class="gallery-picture">
        <div class="product-price">
          <p>Dark earings</p>
          <p>$10.00-&20.00</p>
        </div>
        </div>
      </div>
    </div>
  </div>
</template>