<template>
    <div>
        <nuxt-link to="/">Home</nuxt-link>
        <nuxt-link to="/about">About</nuxt-link>
        
        <nuxt-link to="/users/1">User 1</nuxt-link>
        <nuxt-link to="/users/2">User 2</nuxt-link>
        
        <nuxt-link to="/this-is-slug/comment/">Comments</nuxt-link> 

        <nuxt-link to="/food">Category</nuxt-link> 
        <nuxt-link to="/food/is-category">Sub Category</nuxt-link> 
        <nuxt-link to="/food/this-is-category/this-is-sub-category">Dynamic Route</nuxt-link> 
        <nuxt-link to="/people">People</nuxt-link> 

        <nuxt-link to="/asfasfasf/asdas/asd/asdasd/as/da/sd/as/das/d/asd/as">Unknown Dynamic nested Route</nuxt-link> 
        <Nuxt />
    </div>
</template>
 