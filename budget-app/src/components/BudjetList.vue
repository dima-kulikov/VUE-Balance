<template>
    <div class="budget-list-wrap">dsadsad
        <!-- <el-card :header="header"></el-card > -->
        <h2>sdfdf</h2>
    </div>
</template>

<script>
export default {
    name: 'BudjetList',
    props: {
        list: {
            type: Object,
            default: () => ({})
        },
    },
    data: () => ({
        header: 'Budget List'
    })
}
</script>

<style scoped>

</style>