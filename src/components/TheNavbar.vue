<template>
    <div>
        <div class="container d-flex justify-content-between d-flex align-items-center pt-3 pb-4">
            <div>
                <img src="img/dc-logo.png" alt="">
            </div>
            <ul class="nav ">
                <li class="nav-item" v-for="(link, i) in navLinks" :key="i">
                    <a class="nav-link text-dark" :href="link.url">{{ link.name }}</a>
                </li>
            </ul>
        </div>
    </div>
</template>

<script>
export default {
    name: 'TheNavbar',
    data() {
        return {
            navLinks: [
                {
                    name: 'CHARACTERS',
                    url: '#'
                },
                {
                    name: 'COMICS',
                    url: '#'
                },
                {
                    name: 'MOVIES',
                    url: '#'
                },
                {
                    name: 'TV',
                    url: '#'
                },
                {
                    name: 'GAMES',
                    url: '#'
                },
                {
                    name: 'COLLECTIBLES',
                    url: '#'
                },
                {
                    name: 'VIDEOS',
                    url: '#'
                },
                {
                    name: 'FANS',
                    url: '#'
                },
                {
                    name: 'NEWS',
                    url: '#'
                },
                {
                    name: 'SHOP',
                    url: '#'
                },

            ]
        }
    }
};
</script>

<style>
</style>