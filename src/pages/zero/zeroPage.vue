<script setup lang="ts">
import ZeroNavbar from './components/navbar/ZeroNavbar.vue'

</script>

<template>
    <div class="zero-page">
        <section class="zero-page__navbar">
            <ZeroNavbar />
        </section>
        <section class="zero-page__first">
            <div class="zero-page__hero-content">
                <div class="first">
                    <div class="first__content">
                        <div class="first__header-tag">
                            Design addicted
                        </div>
                        <h1 class="first__title">
                            A stylish UI Kit
                        </h1>
                        <h2 class="first__title-secondary">
                            for all web creatives
                        </h2>
                        <p class="first__description">Zero is a Webflow Ecommerce and CMS UI kit including several carefully designed page layouts.</p>
                        <div class="first__icons">
                            <div class="icon">
                                <img src="@/assets/images/first_icon1.png" alt="icon-1">
                                <span class="icon__text">smooth</span>
                                <span class="icon__text">interactions</span>
                            </div>
                            <div class="icon">
                                <img src="@/assets/images/first_icon2.png" alt="icon-2">
                                <span class="icon__text">many</span>
                                <span class="icon__text">page layouts</span>
                            </div>
                            <div class="icon">
                                <img src="@/assets/images/first_icon3.png" alt="icon-2">
                                <span class="icon__text">fully</span>
                                <span class="icon__text">responsive</span>
                            </div>
                            <div class="icon">
                                <img src="@/assets/images/first_icon4.png" alt="icon-2">
                                <span class="icon__text">fast</span>
                                <span class="icon__text">customization</span>
                            </div>
                        </div>
                    </div>
                    <div class="first__image">
                        <img src="@/assets/images/first-banner.png" alt="first-image">
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

<style scoped>

</style>
