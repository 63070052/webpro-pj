<template>
    <div class="all">
        <div class="container is-max-desktop headtext">
            <h1>Sign up</h1>
        </div>


  <div class="container is-max-desktop p-3" style="padding-bottom: 5%; justify-content: center; display: flex;">
    <div class="notification block">

      <div class="flex-container" style="display: flex; flex-direction: row;">
          <div style="margin-right: 7%; width: 350px;" >
            ชื่อจริง
            <input class="input" type="text" placeholder="" >
          </div>
          <div style=" width: 350px;">
            นามสกุล
            <input class="input" type="text" placeholder="">
          </div>
      </div>

      <div class="flex-container" style="display: flex; flex-direction: row;">
        <div style="margin-right: 7%; width: 350px;" >
          เบอร์โทร
          <input class="input" type="tel" placeholder="" >
        </div>
        <div style=" width: 350px;">
          อีเมล
          <input class="input" type="email" placeholder="">
        </div>
    </div>
    
      รหัสผ่าน
      <input class="input" type="password" placeholder="" style="width: 755px;">
      ยืนยันรหัสผ่าน
      <input class="input" type="password" placeholder="" style="width: 755px;">

      <div class="buttons flex-container" style="width: 755px; justify-content: flex-end; margin-top: 5%;">
        <button class="button is-link"><p>สร้างบัญชีใหม่</p></button>
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
    .all {
    background-color: #61A4BC;
    font-size: 18px;
    font-family: 'Prompt', sans-serif;
    color: #FFF;
    line-height : 2.5 ;
    padding: 3rem;
  }

  .headtext {
    font-size: 40px;
    font-family: 'Prompt', sans-serif;
    text-align: center;
    padding-top: 2%;
  }

  .block {
    background-color: #85B8CB;
    height: auto;
    width: 870px;
    margin-top: 2%;
    padding: 5%;
  }
</style>