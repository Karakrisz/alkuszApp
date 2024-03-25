<!-- components/Footer.vue -->
<template>
    <footer>
        <div class="footer-content">
            <div class="footer-content__form bg-color-w">
                <h5 class="text-transform-uppercase text-center">VEGYÜK FEL A KAPCSOLATOT!</h5>
            </div>
            <div class="footer-content__link-box text-center">
                <img src="/img/footer/logo.svg" alt="Biztos Alkuszom" class="footer-content__link-box__img">
                <div class="footer-content__link-box__links">
                    <NuxtLink v-for="link in footerLinks" :key="link.path" :to="link.path" class="footer-link">
                        {{ link.name }}
                    </NuxtLink>
                </div>
                <div class="footer-content__link-box__DigitalSeed bg-color-w">
                    <NuxtLink class="footer-content__link-box__DigitalSeed__Nuxtlink text-transform-uppercase" to="/">DIGITAL SEED STUDIO - 2024</NuxtLink>
                </div>
            </div>
        </div>
    </footer>
</template>


<script>
import { Footerlinks } from '~/utils/js/links';

export default {
    data() {
        return {
            footerLinks: Footerlinks,
        };
    },
};
</script>
