<template>
    <div class="services">
        <div class="container">
          <h4>Projects</h4>
            <div class="row">
                <div class="col-lg-3 col-md-6 col-sm-12 mb-3">
                    <div class="card" style="width: 18rem;">
                        <img src="../../assets/projects/Weather.png" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Weather site (new)</h5>
                                <p class="card-text">This project was created using <strong>Vue JS</strong> and api from <a href="https://www.weatherapi.com/">Weather API</a></p>
                                <a href="https://kev-weather-api.netlify.app/" target="_blank" class="btn btn-primary">Visit site</a>
                        </div>
                    </div>
                </div>
                <div class="col-lg-3 col-md-6 col-sm-12 mb-3">
                    <div class="card" style="width: 18rem;">
                        <img src="../../assets/projects/old_porfolio.png" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Portfolio v1</h5>
                                <p class="card-text">This is my portfolio when I was not yet working as web developer back on 2020, this is created in <strong>Angular JS</strong></p>
                                <a href="https://kev1118.github.io/MyPortfolio/" target="_blank" class="btn btn-primary">Visit site</a>
                        </div>
                    </div>
                
                </div>
                <div class="col-lg-3 col-md-6 col-sm-12 mb-3">
                    <div class="card" style="width: 18rem;">
                        <img src="../../assets/projects/web_template.png" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Clone website</h5>
                                <p class="card-text">I tried to clone a construction website back in 2020 but before i finish the project someone told me I might get a problem in copyright therefor I stop before adding images, this is created in <strong>Angular JS</strong></p>
                                <a href="https://kev1118.github.io/webTemplate/" target="_blank" class="btn btn-primary">Visit site</a>
                        </div>
                    </div>
                </div>

                <div class="col-lg-3 col-md-6 col-sm-12 mb-3">
                    <div class="card" style="width: 18rem;">
                        <video controls>
                            <source src="../../assets/projects/online-shop.mp4" type="video/mp4">
                        </video>
                        <div class="card-body">
                            <h5 class="card-title">Online shop</h5>
                                <p class="card-text">This project was created <strong>Angular JS</strong> back on 2020, I tried to clone the online shop from youtube it was created using ReactJS.</p>
                                <a href="https://kev1118.github.io/webTemplate/" target="_blank" class="btn btn-primary">Visit site</a>
                        </div>
                    </div>
                </div>
            </div>
                <div class="row">
                    <div class="col-lg-3 col-md-6 col-sm-12 mb-3">
                    <b-card
                        title="Admin-template Clone"
                        img-src="https://picsum.photos/600/300/?image=25"
                        img-alt="Image"
                        img-top
                        tag="article"
                        style="max-width: 20rem;"
                        class="mb-2"
                    >
                        <b-card-text>
                        Comming soon.
                        </b-card-text>

                        <b-button href="#" variant="danger" disabled>Visit Project</b-button>
                    </b-card>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name: 'project-component', 

   
   
}
</script>

<style scoped>

</style>