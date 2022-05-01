<template>
    <div class="body">
        <div class="headbook">
            <div class="mt-5" style="width: 100px;">
                <img :src="require('../assets/fishpng.png')" style="width: 70%;padding-top: 50px;padding-left: 20px;">
            </div>
            <div class="mt-5">
                <div style="font-size: 40px;">
                    จองบัตรเข้าชมออนไลน์
                </div>
                <div style="margin-top:-20px;">จองตอนนี้พร้อมสิทธิพิเศษมากมาย</div>

            </div>
        </div>
        <div class="displayflex blockbig">

            <div class="pic" style="width: 30%;">
                <img :src="require('../assets/01.jpg')" style="width: 100%;">
            </div>

            <div class="detail" >
                <div class="nameoftik">บัตรชมเที่ยวเดียว ออนไลน์ถูกกว่า</div>
                <div class="displayflex" style=" background-color: #F6F6F6; margin-bottom:15px ;width: 500px;">
                    
                    <div style="color: #7E7C7C; margin-left: 20px;margin-top: 4px;"><strike>฿1180</strike></div>&nbsp; &nbsp;
                    <div style="color: #250096; font-size: 20px;">฿550 - ฿650</div>
                </div>

                <div class="displayflex">
                    <div>ตัวเลือก</div>&nbsp; &nbsp;
                    <div>
                        <div class="select is-info" style="margin-left: 6px;">
                            <select>
                                <option>บัตรเด็ก</option>
                                <option>บัตรผู้ใหญ่</option>
                            </select>
                        </div>
                    </div>
                </div>

                <div class="displayflex">
                    <div>วันเข้าชม</div>&nbsp; &nbsp;
                    <div><input class="input is-info" type="date" placeholder="Text input"></div>
                </div>

                <div class="displayflex">
                    <div>จำนวน</div>&nbsp; &nbsp;
                    <div>
                        <button class="button">-</button>
                    </div>&nbsp; 
                    <div>
                        <button class="button">1</button>
                    </div>&nbsp; 
                    <div>
                        <button class="button">+</button>
                    </div>
                </div>

                <div class="displayflex">
                    <div><button class="button is-link is-outlined">เพิ่มไปยังตระกร้า</button></div>&nbsp; &nbsp;
                    <div><button class="button is-link">ซื้อสินค้า</button></div>
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
    .body {
        font-size: 18px;
        color: rgb(0, 0, 0);
        line-height: 2.5;


    }

    .headbook {
        display: flex;
        flex-direction: row;
        padding-top: 3%;
        background-color: #1A132F;
        margin: 0;
        color: #fff;
        padding-left: 130px;
        padding-bottom: 40px;
    }

    .displayflex {
        display: flex;
        flex-direction: row;
        background-color: #fff;
    }
    .blockbig{
        padding-left: 10%;
        align-items: center;
        height: 500px;
    }
    .detail{
        padding-left: 10%;
        line-height: 3;
        padding-top: 0;
    }
</style>