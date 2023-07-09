<template>
    <div class="main">
        <Header />
        <slot />
        <Footer />
    </div>
</template>

<script>
import Header from '@/components/common/Header/Header.vue';
import Footer from '@/components/common/Footer/Footer.vue';

export default {
    components: {
        Header, Footer,
    },
}

</script>