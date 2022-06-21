<template>
    <div class="container d-flex justify-content-between">
        <img src="/img/dc-logo.png" alt="">

        <ul class="nav">
            <li class="nav-item" v-for="(link, i) in navLinks" :key="i"> 
                <a class="nav-link text-dark fw-bold mt-4" href="">{{link.name}}</a>
            </li>
        </ul>
    </div>
</template>

<script>
export default {
    name: "TheHeader",
    data() {
        return {
            navLinks: [
                {
                    name: "CHARACTERS",
                    href: "#",
                },
                {
                    name: "COMICS",
                    href: "#",
                },
                {
                    name: "MOVIES",
                    href: "#",
                },
                {
                    name: "TV",
                    href: "#",
                },
                {
                    name: "GAMES",
                    href: "#",
                },
                {
                    name: "COLLECTIBLES",
                    href: "#",
                },
                {
                    name: "VIDEOS",
                    href: "#",
                },
                {
                    name: "FANS",
                    href: "#",
                },
                {
                    name: "NEWS",
                    href: "#",
                },
                {
                    name: "SHOP",
                    href: "#",
                },
            ]
        }
    }
}
</script>

<style>
    
</style>