<template>
  <router-tab :lang="'en'" />
</template>

<script>
export default {
  name: 'Language',
  data() {
    return {
      lang: {
        tab: {
          untitled: 'Untitled Page'
        },

        contextmenu: {
          refresh: 'Refresh This',
          refreshAll: 'Refresh All',
          close: 'Close This',
          closeLefts: 'Close to the Left',
          closeRights: 'Close to the Right',
          closeOthers: 'Close Others',
          pin: 'Pin',
          unpin: 'Unpin'
        },

        msg: {
          keepLastTab: 'Keep at least 1 tab'
        }
      }
    }
  }
}
</script>
