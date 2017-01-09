<template>
    <nav class="ts horizontally scrollable large fluid borderless pure basic menu">
        <div class="ts narrow container">
            <router-link class="item" to="/">Tocas UI</router-link>
            <router-link class="item" to="/getting-started/">Getting Started</router-link>
            <router-link class="item" to="/elements/">Elements</router-link>
            <router-link class="item" to="/collections/">Collections</router-link>
            <router-link class="item" to="/modules/">Modules</router-link>
            <router-link class="item" to="/views/">Views</router-link>
            <!--<router-link class="item" to="/animation/">動畫</router-link>-->
            <router-link class="item" to="/rwd/">Responsive</router-link>
            <div class="right menu">
                <a class="item" href="//patreon.com/yamiodymel">Donate</a>
                <a class="item" href="//github.com/TeaMeow/TocasUI/">Github</a>
            </div>
        </div>
    </nav>
</template>

<script>
export default
{
    name: 'DocNav'
}
</script>