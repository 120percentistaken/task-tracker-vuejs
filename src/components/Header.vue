<template>
    <header>
        <h1>{{title}}</h1>
        <Button text="Add Task" color="#39a275"/>
        <Button text="Update Task" color="#194a8d"/>
        <Button text="Delete Task" color="#df1c44"/>
    </header>
</template>

<script>
import Button from './Button';
export default{
    name: 'Header',
    props: {
        title:String,
    },
    components: {
        Button
    }
}
</script>

<style scoped>
header{
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 20px;
}
</style>