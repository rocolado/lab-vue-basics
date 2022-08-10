<template>
    <div>
        <div id="iteration-4">
            <ul v-for="(post, index) in posts" :key="index">
                <li>
                    {{post.title}} - {{post.description}} - {{post.content}}
                </li>
            </ul>
        </div>
    </div>
</template>

<script>
export default {
    name: 'basicExercises',
    data() {
        return {
            posts: [
                {title: "Title post 1", description: "Description post 1", content: "Content post 1"},  
                {title: "Title post 2", description: "Description post 2", content: "Content post 2"},  
                {title: "Title post 3", description: "Description post 3", content: "Content post 3"}  
            ],
        }
    },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
