<template>
    <div class="skill-section">
        <div class="container-fluid">
            <div class="row">
                <div class="col-lg-6 col-md-12">
                    <span class="text-white">Current Tech stack:</span>
                    <div class="d-flex flex-row">
                        <span class="skill-icon">
                            <i class="devicon-html5-plain"></i>
                            <small>HTML 5</small>
                        </span>
                        <span class="skill-icon">
                            <i class="devicon-css3-plain"></i>
                            <small>CSS</small>
                        </span>
                        <span class="skill-icon">
                            <i class="devicon-bootstrap-plain"></i>
                            <small>Bootstrap</small>
                        </span>
                        <span class="skill-icon">
                            <i class="devicon-javascript-plain"></i>
                            <small>Javascript</small>
                        </span>
                        <span class="skill-icon">
                            <i class="devicon-jquery-plain"></i>
                            <small>Jquery</small>
                        </span>
                        <span class="skill-icon">
                        <i class="devicon-php-plain"></i>
                        <small>PHP</small>
                    </span>
                    <span class="skill-icon">
                        <i class="devicon-mysql-plain"></i>
                        <small>MySQL</small>
                    </span>
                    <span class="skill-icon">
                        <i class="devicon-postgresql-plain"></i>
                        <small>PostgreSQL</small>
                    </span>
                    </div>
                </div>
                <div class="col-lg-6 col-md-12">
                    <span class="text-white">Current Tech stack learning:</span>
                    <div class="d-flex">
                        <span class="skill-icon">
                            <i class="devicon-laravel-plain"></i>
                            <small>Laravel</small>
                        </span>
                        <span class="skill-icon">
                            <i class="devicon-vuejs-plain"></i>
                            <small>VueJS</small>
                        </span>
                        <span class="skill-icon">
                            <i class="devicon-react-plain"></i>
                            <small>ReactJS</small>
                        </span>
                        <span class="skill-icon">
                            <i class="devicon-angularjs-plain"></i>
                            <small>AngularJS</small>
                        </span>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'skills-component'
}
</script>

<style scoped>
.skill-section{
    height: 300px;
    background-color: #ffffff;
    padding: 2% 10% 0px 10%;
    background: url('../../assets/blackbg.png');
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;
    
}
.skill-icon i{
    font-size: 50px;
    color: #60be86;
}
.skill-icon small{
    color: #60be86;
}
.skill-icon{
    display: flex;
    flex-direction: column;
    /* align-items: center; */
    padding: 0 .5rem;
}
</style>