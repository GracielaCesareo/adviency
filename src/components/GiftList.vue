<template>
    <div v-for="item in list" :key="item.id">
        {{ item.name }}
    </div>
</template>

<script>
export default {
    data(){
        return{
            list:[
                {
                    name: 'Earphones',
                    id:1,
                    desc: 'Lorem Ipsum is simply dummy text of the printing and typesetting industry.'
                },
                {
                    name: 'Jacket',
                    id:2,
                    desc: 'Lorem Ipsum is simply dummy text of the printing and typesetting industry.'
                },
                {
                    name: 'Backpack',
                    id:3,
                    desc: 'Lorem Ipsum is simply dummy text of the printing and typesetting industry.'
                },

            ]
        }
    }

}
</script>

<style>

</style>