<template>
    <div class="m-navigator">
        <div>
            <i class="el-icon-edit"></i>
            <i class="el-icon-share"></i>
            <i class="el-icon-delete"></i>
        </div>

        <el-row gutter="20">
            <el-col span="6">Col</el-col>
            <el-col span="6">Col</el-col>
            <el-col span="6">Col</el-col>
            <el-col span="6">Col</el-col>
        </el-row>

        NAVI: {{ title }}

        <el-button type="primary" size="small">MyButton</el-button>

    </div>
</template>

<script>
  import ElButton from 'element-ui'
  import ElCol from 'element-ui/packages/col/src/col'
  import ElRow from '../../../../node_modules/element-ui/packages/row/src/row'
  export default {
    components: {
      ElRow,
      ElCol,
      ElButton
    },
    name: 'navigator',

    data () {
      return {
        title: 'This is navigator',
        autoCommit: true
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
