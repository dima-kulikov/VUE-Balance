<template>
    <div class="budget-list-wrap">
        <ElCard :header ="header">

        </ElCard>
    </div>
</template>

<script>
export default {
    name: 'BudgetList',
    props: {
        list: {
            type: Object,
            default: () => ({})
        },
    },
    data: ()=> ({
        header: 'Budget Lisr'
    })
}
</script>

<style scoped>

</style>