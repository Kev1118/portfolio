<template>
    <div>
    <div class="container">
        <div class="row">
            <div class="col-lg-6 col-md-12 col-sm-12 d-flex align-items-center">
                <div class="text-container">
                    <p>Hello,</p>
                    <p>I'M KEVIN</p>
                    <p>I am I.T. Staff (PHP developer)</p>
                    <button class="hire-btn">Hire Me</button>
                    <button class="down-cv-btn" @click.prevent="downloadCV">Download CV</button>
                </div>
            </div>
            <div class="col-lg-6 col-md-12 col-sm-12">
                <img src="../../assets/PHP_developer.png" alt="model" class="img-fluid">
            </div>
        </div>
    </div>
        
    </div>
    
</template>

<script>

export default {
  name: 'about-section',
    methods:{
        downloadCV(){
            const url = '/files/kevin-morales-CV.pdf';
            window.open(url,"_blank")
            
           
        }
    }
}
</script>

<style scoped>
.text-container{
   /* margin-top: 2rem; */
}
.text-container p:nth-child(1){
    font-family: calibri;
    font-weight: bold;
    color: #6d6d6d;
    font-size: 22px;
}
.text-container p:nth-child(2){
    font-family: calibri;
    font-weight: bold;
    letter-spacing:  1px;
    color: #1a1a1a;
    font-size: 60px;
}
.text-container p:nth-child(3){
    font-family: myriad pro regular;
    color: #403e3e;
    font-size: 30px;
    line-height: 30px;
}
.text-container p {
    line-height: 0px;
    margin: 45px 0px 25px;
}
/* .text-container{
    position: absolute;
    left: 13%;
    top: 42%;
    transform: translate(-13%, -42%);

} */

.text-container button{
    width: 130px;
    height: 42px;
    border-radius: 10px;
    font-family: calibri;
    font-weight: bold;
    font-size: 14px;
    outline: none;
    margin: 0px 10px;
}
.text-container .hire-btn{
    border: 2px solid #373636;
    color: #373737;
}
.text-container .down-cv-btn{
    background-color: #0b0b0b;
    color: #ffffff;
    border: none;
}
button:hover{
    transform: scale(1.1);
}
/* .model{
    height: 560px;
    position: absolute;
    bottom: 0%;
    left: 70%;
    transform: translateX(-70%);
} */
</style>