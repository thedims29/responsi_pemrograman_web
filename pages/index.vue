<template>

  <div>
    <NavbarSection />
  </div>

  <div>
      <AboutSection />
  </div>

  <div>
    <HeroSection />
  </div>
  
  <div>
    <ProjectsSection />
  </div>

  <div>
    <ContactSection />
  </div>

</template>

<script>
import NavbarSection from '~/components/NavbarSection.vue';
import HeroSection from '~/components/HeroSection.vue';
import AboutSection from '~/components/AboutSection.vue';
import ProjectsSection from '~/components/ProjectsSection.vue';
import ContactSection from '~/components/ContactSection.vue';

export default {
  components: {
    HeroSection,
  }
}
</script>./Index.vue
