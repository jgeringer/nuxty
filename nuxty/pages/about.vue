<template>
  <section class="container">
    <h1>about vue!</h1>
    <p>more stuff</p>
    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quam debitis laboriosam temporibus atque consectetur fugiat, cum cupiditate facilis incidunt unde minus laborum exercitationem animi molestias, voluptatum ducimus quod repudiandae eaque!</p>
  </section>
</template>

<script>
export default {
    // transition: 'bounce',
    head(){
        return {
            title: 'About Nuxt',
            meta: [
                {
                    name: 'description', 
                    content: 'This is my about description here.'
                },
                {
                    name: 'keywords', 
                    content: 'keywords go here here.'
                }
            ]
        }
    }
}
</script>

<style>

</style>
