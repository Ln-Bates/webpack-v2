<template>
    <div class="home-page">
        <Loading v-show="showLoading"></Loading>
    </div>
</template>

<script>
    import Loading from '@/components/Loading';

    export default {
        mounted() {
        },
        data() {
            return {
                showLoading: true
            }
        },
        components: {
            Loading
        }
    }
</script>
