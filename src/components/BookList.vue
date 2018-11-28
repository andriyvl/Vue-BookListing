<template>
    <div>
        <h1> {{titles}} </h1>
    </div>
</template>

<script>
export default {
    name: 'BookList',
    data() {
        return {
            titles: 'All Books'
        } 
    }    
}
</script>

<style>
h1, h2 {
    font-weight: normal;
}
</style>
