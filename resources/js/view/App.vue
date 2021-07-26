<template>
    <div>
        <router-link :to="{name: 'home'}">Home</router-link>
        <router-link :to="{name: 'hello'}">Hello</router-link>
        <router-link :to="{name: 'example'}">Example</router-link>

        <div class="container">
            <p>LaraVue SPAss - Laravel + Vue</p>
            <router-view></router-view>
        </div>
    </div>
    
</template>

<script>
export default {
    
}
</script>