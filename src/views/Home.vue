<template>
  <div class="home">
    <Hero/>
	<ShopAdmin/>
	<Refs/>
	<Contact/>
	<Footer/>
  </div>
</template>

<script>
// @ is an alias to /src
import Hero from '@/components/Hero.vue'
import Refs from '@/components/Refs.vue'
import ShopAdmin from '@/components/ShopAdmin.vue'
import Footer from '@/components/Footer.vue'
import Contact from '@/components/Contact.vue'

export default {
  name: 'Home',
  components: {
	Hero,
	Refs,
	ShopAdmin,
	Footer,
	Contact
  }
}
</script>

