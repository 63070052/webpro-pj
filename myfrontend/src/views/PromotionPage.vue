<template>
    <div class="headbody">
        <div>
          <img :src="require('../assets/shark1.jpg')" class="shark">
        </div>

  <div class="promo">
    โปรโมชั่น
  </div>

  <div class="promo promo2">
    ซื้อตั๋วออนไลน์ถูกกว่า
  </div>

  <div class="flex-container cardpromotion">

    <div class="card">
      <div class="card-image">
        <figure class="image is-4by3">
          <img src="https://bulma.io/images/placeholders/1280x960.png" alt="Placeholder image">
        </figure>
      </div>
      <div class="card-content">
        <div class="content">
          บัตรเดี่ยวเที่ยวชม
         
        </div>
        <button class="button is-danger">BUY NOW</button>
        <p style="margin-left: 3px;">฿650</p>
      </div>
      
    </div>

    <div class="card">
      <div class="card-image">
        <figure class="image is-4by3">
          <img src="https://bulma.io/images/placeholders/1280x960.png" alt="Placeholder image">
        </figure>
      </div>
      <div class="card-content">
        <div class="content">
          บัตรเดี่ยวเที่ยวชม<br>

          
        </div>
      </div>
    </div>

    <div class="card">
      <div class="card-image">
        <figure class="image is-4by3">
          <img src="https://bulma.io/images/placeholders/1280x960.png" alt="Placeholder image">
        </figure>
      </div>
      <div class="card-content">
        <div class="content">
          บัตรเดี่ยวเที่ยวชม
        </div>
      </div>
    </div>

    <div class="card">
      <div class="card-image">
        <figure class="image is-4by3">
          <img src="https://bulma.io/images/placeholders/1280x960.png" alt="Placeholder image">
        </figure>
      </div>
      <div class="card-content">
        <div class="content">
          บัตรเดี่ยวเที่ยวชม
        </div>
      </div>
    </div>

    <div class="card">
      <div class="card-image">
        <figure class="image is-4by3">
          <img src="https://bulma.io/images/placeholders/1280x960.png" alt="Placeholder image">
        </figure>
      </div>
      <div class="card-content">
        <div class="content">
          บัตรเดี่ยวเที่ยวชม
        </div>
      </div>
    </div>


  </div>
    </div>
</template>
<script>
export default {
    data() {
      return {}
    }
  }
</script>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Prompt:wght@300&family=Sarabun:wght@300&display=swap');
    *{
        font-family: 'Prompt', sans-serif;
        font-family: 'Sarabun', sans-serif;  
    }
    .headbody {
    font-size: 18px;
    line-height: 2.5;
  }

  .shark {
    width: 100%;
    position: absolute;
  }

  .promo {
    font-size: 40px;
    padding-left: 5%;
    padding-top: 5%;
    position: relative;
    color: #FFF;
  }

  .promo2 {
    font-size: 30px;
    padding-top: 0%;
    color: #FFF;
    line-height: 1;
  }

  .cardpromotion {
    display: flex;
    flex-wrap: wrap;
    margin-left: 4%;
   margin-top: 8%;
  }
  .card{
    width: 20%;
    margin: 2%;
    position: relative;
  }

  /* .image{
    width: 300px;
    height: 200px;
  } */
</style>