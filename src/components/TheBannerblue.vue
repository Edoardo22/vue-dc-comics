<template>
    <div>
        <div class="fluid-container bg-primary py-5">
            <div class="container d-flex">
                <div class="d-flex justify-content-between d-flex align-items-center gap-3"
                    v-for="(icon, i) in blueIcon" :key="i">
                    <img class="blue-icon " :src="icon.src" alt="">
                    <div class="text-white pe-4">{{ icon.name }}</div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'TheBannerblue',
    data() {
        return {
            blueIcon: [
                {
                    name: 'DIGITAL COMICS',
                    src: 'img/buy-comics-digital-comics.png',
                },
                {
                    name: 'DC MERCHANDIES',
                    src: 'img/buy-comics-merchandise.png'
                },
                {
                    name: 'SUBSCRIPTION',
                    src: 'img/buy-comics-shop-locator.png'
                },
                {
                    name: 'COMIC SHOP LOCATOR',
                    src: 'img/buy-comics-subscriptions.png'
                },
                {
                    name: 'PC POWER VISA',
                    src: 'img/buy-dc-power-visa.svg'
                },

            ]
        }
    }
};
</script>

<style>
.blue-icon {
    height: 85px;
    width: 70px;
}
</style>