<template>
    <div>
        {{msg}}<br>
        <a-button type="danger">
            Danger
        </a-button>
        <a-pagination :defaultCurrent="2" :defaultPageSize="5" :total="50" show-less-items @change="onchange"/>
    </div>
</template>

<script>
    export default {
        name: "Content",
        data(){
            return{
                msg:"这是内容"
            }
        },
        methods:{
            onchange(page,pageSize){
                console.log(page,pageSize)
            }
        }
    }
</script>

<style scoped>

</style>