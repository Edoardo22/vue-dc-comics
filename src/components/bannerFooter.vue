<template>
    <div>
        <div class="fluid-container py-3 bg-dark-grey">
            <div class="container d-flex justify-content-between">
                <button class="btn text-light  bg-dark-grey border border-primary p-3 align-items-center">SING-UP
                    NOW!</button>
                <div class="d-flex align-items-center">
                    <h4 class="text-primary pe-3">FOLLOW US</h4>
                    <div class="d-flex px-2" v-for="(icon, i) in socialIcons" :key="i">
                        <img :src="icon.src" alt="">
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'bannerFooter',
    data() {
        return {
            socialIcons: [
                {
                    src: 'img/footer-facebook.png',
                },
                {
                    src: 'img/footer-twitter.png',

                },
                {
                    src: 'img/footer-youtube.png',

                },
                {
                    src: 'img/footer-pinterest.png',

                },
                {
                    src: 'img/footer-periscope.png',

                },
            ]
        }
    }
};
</script>

<style>
.bg-dark-grey {
    background-color: rgb(48, 48, 48);
    z-index: 10;
}
</style>