<template>
  <div class="person-image-main">
    <person-image-table />
  </div>
</template>

<script>
import PersonImageTable from '@/views/search/component/person-image-table'

export default {
  name: 'PersonImage',
  components: { PersonImageTable },
  data() {
    return {

    }
  }
}
</script>

<style lang="scss" scoped>
  @import "~@/assets/styles/base";

  .person-image-main {
    box-sizing: border-box;
    height: 100%;
    padding: 32px 56px;
    position: relative;
  }
</style>
