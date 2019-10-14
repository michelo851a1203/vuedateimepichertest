<template>
    <div>
        <input @click="testclick" type="button" value="testclick">

    </div>
</template>

<script>
export default {
    data(){
        return {
            time:{
                year:'',
                month:'',
                week:'',
                day:'',
            }
        }
    },
    mounted(){
        const vm = this
        const now = new Date()
        
    },
    methods:{
        testclick(){
            console.log('OKOK');
        }
    }
}
// 用 vue 建立一個萬年曆，
// 需要建立，年月日，星期
// 現在的時間，
// 以及要顯示的時間。
// 頁面起來時，要計算今天日期
// 
</script>

<style scoped lang="scss">

</style>
