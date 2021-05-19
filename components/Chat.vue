<template></template>
<script>
export default {
  created () {
    window.converse.initialize({
        bosh_service_url: 'https://conversejs.org/http-bind/',
        show_controlbox_by_default: true
    })
  }
}
</script>
