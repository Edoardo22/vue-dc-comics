<template>
    <div>
        <footer class="d-flex position-relative">
            <div class="d-flex container pt-5">
                <div class="d-flex flex-column">
                    <div class="pe-4">
                        <h3 class="text-white pb-2">DC COMICS</h3>
                        <ul class="list-unstyled" v-for="(link, i) in dcComicsList" :key="i">
                            <li class="text-light"><a :href="link.url" class="nav-link">{{ link.name }}</a></li>
                        </ul>
                    </div>
                    <div class="">
                        <h3 class="text-white pb-2">SHOP</h3>
                        <ul class="list-unstyled" v-for="(link, i) in shoplist" :key="i">
                            <li class="text-light"><a :href="link.url" class="nav-link">{{ link.name }}</a></li>
                        </ul>
                    </div>
                </div>
                <div class="px-4">
                    <h3 class="text-white pb-2">DC</h3>
                    <ul class="list-unstyled" v-for="(link, i) in dcList" :key="i">
                        <li class="text-light"><a :href="link.url" class="nav-link">{{ link.name }}</a></li>
                    </ul>
                </div>
                <div>
                    <h3 class="text-white pb-2">SITES</h3>
                    <ul class="list-unstyled" v-for="(link, i) in sitesList" :key="i">
                        <li class="text-light"><a class="nav-link" :href="link.url">{{ link.name }}</a></li>
                    </ul>
                </div>
            </div>
            <div class="">
                <img src="img/dc-logo-bg.png" alt="">
            </div>
        </footer>
    </div>
</template>

<script>
export default {
    name: 'TheFooter',
    data() {
        return {
            dcComicsList: [
                {
                    name: 'Characters',
                    url: '#'
                },
                {
                    name: 'Comics',
                    url: '#'
                },
                {
                    name: 'Movies',
                    url: '#'
                },
                {
                    name: 'TV',
                    url: '#'
                },
                {
                    name: 'Games',
                    url: '#'
                },
                {
                    name: 'Videos',
                    url: '#'
                },
                {
                    name: 'News',
                    url: '#'
                },

            ],
            dcList: [
                {
                    name: 'therm Of Use',
                    url: '#'
                },
                {
                    name: 'Privacy policy',
                    url: '#'
                },
                {
                    name: 'Ad choices',
                    url: '#'
                },
                {
                    name: 'Advertising',
                    url: '#'
                },
                {
                    name: 'Jobs',
                    url: '#'
                },
                {
                    name: 'Subscription',
                    url: '#'
                },
                {
                    name: 'Talent Workshop',
                    url: '#'
                },
                {
                    name: 'CPSC certifications',
                    url: '#'
                },
                {
                    name: 'Ratings',
                    url: '#'
                },
                {
                    name: 'Shop help',
                    url: '#'
                },
                {
                    name: 'Contact Us',
                    url: '#'
                },

            ],
            shoplist: [
                {
                    name: 'Shop DC',
                    url: '#'
                },
                {
                    name: 'Shop DC Collectibles',
                    url: '#'
                },
            ],
            sitesList: [
                {
                    name: 'DC',
                    url: '#'
                },
                {
                    name: 'MAD Magazine',
                    url: '#'
                },
                {
                    name: 'DC Kids',
                    url: '#'
                },
                {
                    name: 'DC Universe',
                    url: '#'
                },
                {
                    name: 'DC Power Visa',
                    url: '#'
                },
            ]
        }
    }
};
</script>

<style>
footer {
    background-image: url('../../public/img/footer-bg.jpg');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
}
</style>