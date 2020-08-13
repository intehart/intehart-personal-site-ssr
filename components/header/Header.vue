<template>
  <header class="menu page">
    <div class="menu__box page__wrap">
      <div class="menu__logo">
        <nuxt-link exact active-class="link--active" class="link" to="/">
          <icon-template class-name="icon icon--nav-svg" view-box="0 0 576 512">
            <icon-home />
          </icon-template>
          INTEHART
        </nuxt-link>
      </div>
      <Nav />
      <!--<button class="menu__button" :class="{ 'menu__button&#45;&#45;active': isActive.default }" @click="openMenu">Go</button>-->
    </div>
    <!--<Nav :is-active="isActive.default" />-->
  </header>
</template>

<script>
import Nav from '~/components/header/Nav'
import IconTemplate from '@/components/icons/IconTemplate'
import IconHome from '@/components/icons/icon/IconHome'

export default {
  components: {
    Nav,
    IconHome,
    IconTemplate
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
