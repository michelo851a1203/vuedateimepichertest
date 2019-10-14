<template>
    <div>
        <input @click="testclick" type="button" value="testclick">

    </div>
</template>

<script>
export default {
    methods:{
        testclick(){
            console.log('OKOK');
        }
    }
}
</script>

<style scoped lang="scss">

</style>
