<template>
  <section class="preview">
    <div class="preview__items">
      <div class="preview__item">
        <h1 class="preview__headline">
          Frontend Blog
        </h1>
        <h3 class="preview__subheading">
          const Frontend = ['JavaScript', 'Vue', 'Angular']
        </h3>
        <button class="preview__button" disabled>
          Регистрация
        </button>
      </div>
      <div class="preview__item">
        <icon-template view-box="0 0 448 512" class-name="icon icon--preview-svg icon--js">
          <icon-j-s />
        </icon-template>
        <icon-template view-box="0 0 448 512" class-name="icon icon--preview-svg icon--vue">
          <icon-vue />
        </icon-template>
        <icon-template view-box="0 0 448 512" class-name="icon icon--preview-svg icon--angular">
          <icon-angular />
        </icon-template>
      </div>
    </div>
  </section>
</template>

<script>
import IconTemplate from '@/components/icons/IconTemplate'
import IconVue from '@/components/icons/icon/IconVue'
import IconAngular from '@/components/icons/icon/IconAngular'
import IconJS from '@/components/icons/icon/IconJS'

export default {
  components: {
    IconTemplate,
    IconVue,
    IconAngular,
    IconJS
  }
}
</script>
