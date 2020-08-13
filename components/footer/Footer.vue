<template>
  <footer class="footer page">
    <div class="footer__content page__wrap">
      <div class="footer__other-page">
        <ul>
          <li class="footer__link">
            <a href="https://github.com/intehart" class="link link--default">
              <icon-template view-box="0 0 496 512" class-name="icon icon--github">
                <icon-git-hub />
              </icon-template>
              GitHub
            </a>
          </li>
          <li class="footer__link">
            <a href="https://github.com/intehart" class="link link--default">
              <icon-template view-box="0 0 448 512" class-name="icon icon--inst">
                <icon-instagram />
              </icon-template>
              Instagram
            </a>
          </li>
          <li class="footer__link">
            <a href="https://github.com/intehart" class="link link--default">
              <icon-template view-box="0 0 512 512" class-name="icon icon--twitter">
                <icon-twitter />
              </icon-template>
              Twitter
            </a>
          </li>
        </ul>
      </div>
      <div class="footer__info">
        <p>&#169; Все права защищены 2020</p>
      </div>
    </div>
  </footer>
</template>
<script>

import IconTemplate from '@/components/icons/IconTemplate'
import IconGitHub from '@/components/icons/icon/IconGitHub'
import IconTwitter from '@/components/icons/icon/IconTwitter'
import IconInstagram from '@/components/icons/icon/IconInstagram'

export default {
  components: {
    IconTemplate,
    IconGitHub,
    IconTwitter,
    IconInstagram
  }
  // data () {
  // v-bind:key="link.tag"
  // v-bind="{ 'view-box': link.viewBox, 'class-name': link.svgClass, 'v-html': link.tag }"
  //   return {
  //     links: [
  //       { path: 'https://github.com/intehart', svgClass: 'icon icon--github', viewBox: '0 0 496 512', tag: '<icon-twitter />' },
  //       { path: 'https://github.com/intehart', svgClass: 'icon icon--inst', viewBox: '0 0 448 512', tag: '<icon-instagram />' },
  //       { path: 'https://github.com/intehart', svgClass: 'icon icon--twitter', viewBox: '0 0 512 512', tag: '<icon-twitter />' }
  //     ]
  //   }
  // }
}
</script>
