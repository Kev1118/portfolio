<template>
    <div class="d-flex justify-content-center">
        <div class="info-container">
            <img src="../../assets/about-img.png" alt="myImage" class="img-fluid">
            <div class="about-text">
                <p>About Me</p>
                <p>PHP Developer</p>
                <p>
                    Hi, I'm Kevin Morales graduate with BS Computer Engineer. I'm currently working in FDTP as an IT Staff (Web Developer) with major responsiblity in HR management system with payroll, i've also responsiblity in our MS Server particulary in System Server.
                    Currently I'm looking to utilize broad knowledge of programming, software engineering lifecycle, and data management to perform programming and software development using various programming languages and related tools and frameworks to solve clients’ business problems as a Programmer.
                </p>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'info-component'
}

</script>

<style scoped>
.info-container{
    width:  80%;
    height: 330px;
    background-color: #ffffff;
    border-radius: 20px;
    box-shadow: 2px 2px 12px rgba(0, 0, 0, 0.2);
    display: flex;
    position: relative;
    justify-content: space-evenly;
    align-items: center;
}
.info-container img{
    height: 250px;
}
.about-text{
    width: 550px;
}
.about-text p:nth-child(1){
    color: #403e3e3e;
    font-family: myriad pro;
    font-weight: bold;
    font-size:  23px;
    line-height: 0px;
}
.about-text p:nth-child(2){
    color: #3e3d3d;
    font-size: 13px;
    font-family: myriad pro;
    font-weight: bold;
    line-height: 5px;
}
.about-text p:nth-child(3),
.about-text p:nth-child(3){
    color: #7e7d7d;
    font-family: calibri;
    font-size: 16px;
}


@media only screen and  (max-width: 900px){
    
    .info-container img{
        height: 200px;
    }
    .about-text p:nth-child(1){
        font-size:  23px;
    }
    .about-text p:nth-child(2){
        font-size:  23px;
    }
    .about-text p:nth-child(3){
        font-size:  15px;
    }
    .info-container{
        padding: 10px;
    }
}
@media only screen and  (max-width: 600px){
    
    
    .info-container img{
        height: 160px;
    }
    .about-text p:nth-child(1){
        font-size:  23px;
    }
    .about-text p:nth-child(2){
        font-size:  23px;
    }
    .about-text p:nth-child(3){
        font-size:  11px;
    }
    .info-container{
        padding: 10px;
    }
}
@media only screen and  (max-width: 400px){
    
    /* .info-container {
        display: flex;
        flex-direction: column;
    }
    . */
    
    .info-container img{
        height: 180px;
    }
    .about-text p:nth-child(1){
        font-size:  23px;
    }
    .about-text p:nth-child(2){
        font-size:  10px;
    }
    .about-text p:nth-child(3){
        font-size:  10px;
    }
    .info-container{
        padding: 10px;
    }
}
</style>