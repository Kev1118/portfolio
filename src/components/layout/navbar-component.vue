<template>
    <div >
        <b-navbar toggleable="sm" type="light" variant="light">
            <div class="container">
                <b-navbar-toggle target="nav-text-collapse"></b-navbar-toggle>
                <b-navbar-brand ref="topview">KEVIN MORALES</b-navbar-brand >
                <b-collapse id="nav-text-collapse" is-nav>
                <b-navbar-nav class="ml-auto">
                    <b-nav-item @click="scrollTo('info-section')">About</b-nav-item>
                    <b-nav-item @click="scrollTo('services-section')">Projects</b-nav-item>
                    <b-nav-item @click="scrollTo('footer-section')">Contact</b-nav-item>
                </b-navbar-nav>
                </b-collapse>
            </div>
        </b-navbar>
        <aboutSection></aboutSection>
        <div ref="info-section"> 
            <infoSection></infoSection>
        </div>
        <skillsSection></skillsSection>
        <div ref="services-section">
            <projectSection></projectSection>
        </div>
        
        <div class="footer-section" ref="footer-section">
            <footerSection></footerSection>
            <div class="scrollTotop">
                <span @click="scrollTo('topview')"> <b-icon icon="arrow-up-circle-fill"></b-icon></span>
            </div>
        </div>
        
    </div>
</template>

<script>
import aboutSection from '../pages/about-section.vue'
import infoSection from '../pages/info-section.vue';
import skillsSection from '../pages/skills-section.vue';
import projectSection from '../pages/project-section.vue';
import footerSection from '../pages/footer-section.vue';
export default {
  name: 'Nav-component',
  components:{
    aboutSection,
    infoSection,
    skillsSection,
    projectSection,
    footerSection
  },
  methods:{
    scrollTo(div){
        this.$refs[div].scrollIntoView({behavior: "smooth"})
    }
  }

}
</script>

<style scoped>
.ml-auto{
    margin-left: auto;
}
.footer-section{
    position: relative;
}
.footer-section .scrollTotop{
    cursor: pointer;
    font-size: 2em;
    color: #60be86;
    position: absolute;
    top: -25px;
    right: 35px;
    /* bottom: 0; */
}
</style>