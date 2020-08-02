<template>
    <div id="app">
        <ab-navigation></ab-navigation>
        <ab-home></ab-home>
    </div>
</template>

<script>
import Navigation from "@/components/navigation";
import Home from "@/components/Home";

export default {
    name: 'App',
    components: {
        abHome: Home,
        abNavigation: Navigation
    }
}
</script>

<style>
#app {
    width: 100%;
}
</style>
