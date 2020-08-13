<template>
  <nav class="nav">
    <ul class="nav__items">
      <li class="nav__item">
        <nuxt-link to="/contacts" active-class="link--active" class="link">
          <icon-template class-name="icon icon--nav-svg" view-box="0 0 576 512">
            <icon-blog />
          </icon-template>
          Блог
        </nuxt-link>
      </li>
      <li class="nav__item">
        <nuxt-link to="/contacts" active-class="link--active" class="link">
          <icon-template class-name="icon icon--nav-svg" view-box="0 0 512 512">
            <icon-contact />
          </icon-template>
          Контакты
        </nuxt-link>
      </li>
    </ul>
  </nav>
</template>

<script>
import IconTemplate from '~/components/icons/IconTemplate'
import IconContact from '@/components/icons/icon/IconContact'
import IconBlog from '@/components/icons/icon/IconBlog'

export default {
  components: {
    IconTemplate,
    IconContact,
    IconBlog
  }
  // props: {
  //   isActive: Boolean
  // }
  // :class="{ 'nav--active': isActive }"
}
</script>
