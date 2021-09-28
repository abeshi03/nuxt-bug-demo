<template>
  <div>
    <div v-if="hasUserNotSignedIn">
      <div v-if="hasNewestImportantNotificationNotBeenRetrievedYet"></div>
    </div>
  </div>
</template>

<script>
import Vue from 'vue'

export default Vue.extend({
  data() {
    return {
      hasUserNotSignedIn: false,
      hasNewestImportantNotificationNotBeenRetrievedYet: false
    }
  }
})
</script>
