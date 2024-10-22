<template>
  <div class="push"></div>
  <div class="footer center">
    <div>
      <a href="https://app.cellcast.com " target="_blank">GitHub Repository</a>
    </div>
  </div>
</template>
<script>
const d = new Date()
const currentYear = d.getFullYear()
export default {
  data() {
    return {
      year: currentYear
    }
  }
}
</script>
