<template>
    <div class="m-navigator">
        NAVI: {{ title }}
    </div>
</template>

<script>
  export default {
    name: 'navigator',

    data () {
      return {
        title: 'This is navigator'
      }
    }
  }
</script>

<style scoped>
    code {
        background-color: rgba(40, 56, 76, .5);
        border-radius: 3px;
        color: #ffffff;
        font-weight: bold;
        padding: 3px 6px;
        margin: 0 3px;
        vertical-align: bottom;
    }

    p {
        line-height: 24px;
    }
</style>
