<template>
    <div class="footer">
        <div class="d-flex justify-content-between">
            <p class="m-0"><b-icon icon="envelope"></b-icon>
            email: moralesk765@gmail.com</p>
            <p class="m-0"><b-icon icon="phone"></b-icon>
            Phone: 09665388712</p>
            <p class="m-0"><b-icon icon="github"></b-icon>
            github: <a href="https://github.com/Kev1118">Kev1118</a> </p>
        </div>
       
    </div>
</template>

<script>
export default {
    name: 'footer-component'
}
</script>

<style scoped>
.footer{
    position: relative;
    width: 100%;
    height: 50px;
    background-color: #111111;
    padding: 1rem 1.5rem;
    color: #60be86;
}
@media only screen and (max-width: 400px){
    .footer p:nth-child(1){
        font-size: 10px;
    }
    .footer p:nth-child(2){
        font-size: 10px;
    }
    .footer p:nth-child(3){
        font-size: 10px;
    }
}
</style>