<template>
<!--  <nav class="nav" :class="{ 'nav&#45;&#45;active': isActive.default }">-->
    <nav class="nav">
    <ul class="nav__items">
      <li class="nav__item">
        <nuxt-link to="/contacts" active-class="links--active" class="links">
          Contacts
        </nuxt-link>
      </li>
    </ul>
  </nav>
</template>

<script>
export default {
  // props: ['isActive']
}
</script>
