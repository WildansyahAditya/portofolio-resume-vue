<template>
    <NavbarComponent/>
    <HeroContent/>
    <MainComponent/>
    <SubContent1/>
    <SubContent2/>
    <FooterComponent/>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import NavbarComponent from '@/components/navbarComponent.vue'
import FooterComponent from '@/components/FooterComponent.vue'
import HeroContent from '@/components/heroContent.vue'
import MainComponent from '@/components/mainComponent.vue'
import SubContent1 from '@/components/subContent1.vue'
import SubContent2 from '@/components/subContent2.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
    NavbarComponent,
    FooterComponent,
    HeroContent,
    MainComponent,
    SubContent1,
    SubContent2
}
}
</script>
