<template>
    <div>
        <h1>_category.vue</h1>
        <ul>
            <li>Category: {{$route.params.category}}</li>
            <li>Sub Category :{{$route.params.subCategory}}</li>
            <li>Id : {{$route.params.id}}</li>
        </ul>
    </div>
</template>