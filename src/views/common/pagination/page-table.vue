/*
*该组件实现表格翻页功能
*/
<style>
    @import './style/page.less'
</style>
<template>
    <div class="page-list">
        <Page :total="count" show-total show-elevator show-sizer @on-change="changePage" @on-page-size-change="pageSizeChange"></Page>
    </div>
</template>

<script>
    export default {
        name: 'pageTable',
        props: {
            count: Number
        },
        methods: {
            changePage (current) {
                this.$emit('on-change', current);
            },
            pageSizeChange (page_size) {
                this.$emit('on-page-size-change', page_size);
            }
        }
    }
</script>