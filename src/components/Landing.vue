<template>
  <div>
      <banner />
      <contact />
  </div>
</template>

<script>
import Banner from './Banner'
import Contact from './Contact'
import styles from '../assets/styles/style.css'

export default {
  name: 'landing',
  components: {
    Banner,
    Contact
  }
}
</script>