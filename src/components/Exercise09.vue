<template>
    <ul>
        <li v-for="(data,index) in data" v-bind:key="index">
            <ul>
                <li>ID: {{ data.id }}</li>
                <li>Title: {{ data.title }}</li>
                <li>Content: {{ data.content }}</li>
                <li>Author: {{ data.author }}</li>
            </ul>
        </li>
    </ul>
</template>

<script setup>
    const data = [
        {
            id:1,
            title:"Hello",
            content: "Hello",
            author:"Hello"
        },
        {
            id:2,
            title:"Hello",
            content: "Hello",
            author:"Hello"
        },
        {
            id:3,
            title:"Hello",
            content: "Hello",
            author:"Hello"
        }
    ]
</script>

<style>

</style>