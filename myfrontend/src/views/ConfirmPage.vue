<template>
    <div class="bodyall">
          <div class="container is-max-desktop headtext">
    <h1 class="mt-6">ยืนยันการชำระเงิน</h1>
  </div>


  <div class="container is-max-desktop" style="padding-bottom: 5%; justify-content: center; display: flex;">
    <div class="notification block1">
<!--  -->
    ธนาคาร
    <div class="flex-container" style="display: flex; flex-direction: row;">

          <div class="bank button">
            <img :src="require('../assets/bank01.png')" style="width: 30%; margin-right: 3%;">
              ธนาคารกสิกร  
          </div>
          <div class="button bank">
            <img :src="require('../assets/bank02.png')" style="width: 30%; margin-right: 3%;">
                ธนาคารกรุงเทพ  
            </div>
          <div class="button bank">
            <img :src="require('../assets/bank03.png')" style="width: 30%; margin-right: 3%;">
                ธนาคารกรุงไทย
            </div>

    </div>
<!-- -------------------ชื่อจริงนามสกุล-------------------- -->
      <div class="flex-container" style="display: flex; flex-direction: row;">
          <div style="margin-right: 7%; width: 350px;" >
            ชื่อ
            <input class="input" type="text" placeholder="" >
          </div>
          <div style=" width: 350px;">
            นามสกุล
            <input class="input" type="text" placeholder="">
          </div>
      </div>
<!-- --------------------------------------------------- -->
            ยอดชำระเงิน
        <div style="width: 350px;" >
            <input class="input" type="text" placeholder="baht">
        </div>
       
            หลักฐานการชำระเงิน
            <div class="file has-name">
                <label class="file-label">
                  <input class="file-input" type="file" name="resume">
                  <span class="file-cta">
                    <span class="file-icon">
                      <i class="fas fa-upload"></i>
                    </span>
                    <span class="file-label">
                      Choose a file…
                    </span>
                  </span>
                  <span class="file-name">
                    Screen Shot 2017-07-29 at 15.54.25.png
                  </span>
                </label>
              </div>

           
      
    
     
      <div class="buttons flex-container" style="width: 755px; justify-content: flex-end; margin-top: 5%;">
        <button class="button is-dark">ยกเลิก</button>
        <button class="button is-link">ยืนยัน</button>
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
    .bodyall {
    background-color: #61A4BC;
    font-size: 18px;
    font-family: 'Prompt', sans-serif;
    color: #FFF;
    line-height : 2.5 ;
  }

  .headtext {
    font-size: 40px;
    font-family: 'Prompt', sans-serif;
    text-align: center;
    padding-top: 2%;
  }

  .block1 {
    background-color: #85B8CB;
    height: auto;
    width: 870px;
    margin-top: 2%;
    padding: 5%;
  }
  .bank{
      background-color: #5B7DB1;
      height: auto;
    width: 230px;
    /* margin-top: 2%; */
    margin-right: 5%;
    color: #FFF;
  }
</style>