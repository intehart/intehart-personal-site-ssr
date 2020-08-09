<template>
  <svg
    xmlns="http://www.w3.org/2000/svg"
    :viewBox="viewBox"
    :class="className"
  >
    <slot />
  </svg>
</template>

<script>
export default {
  props: {
    viewBox: {
      type: [Number, String],
      default: Number
    },
    className: {
      type: String,
      default: 'icon'
    },
    iconName: {
      type: String,
      default: 'box'
    },
    iconColor: {
      type: String,
      default: '#000'
    }
  }
}
</script>
