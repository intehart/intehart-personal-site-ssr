<template>
  <header class="menu">
    <div class="menu__box wrap">
      <div class="menu__logo">
        <nuxt-link exact active-class="links--active" class="links" to="/">
          Home Page
        </nuxt-link>
      </div>
      <!--<button class="menu__button" :class="{ 'menu__button&#45;&#45;active': isActive.default }" @click="openMenu">-->
      <!--Go-->
      <!--</button>-->
      <Nav/>
    </div>
    <!--<Nav :is-active="isActive"/>-->
  </header>
</template>

<script>
import Nav from '~/components/header/Nav'

export default {
  components: {
    Nav
  }
  // data () {
  //   return {
  //     isActive: {
  //       type: Boolean,
  //       default: false
  //     }
  //   }
  // },
  // methods: {
  //   openMenu () {
  //     this.isActive.default = !this.isActive.default
  //   }
  // }
}
</script>
