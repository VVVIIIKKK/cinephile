<template>
    <div>

    </div>
</template>

<script setup>
import { Swiper, SwiperSlide } from 'swiper/vue';
import { Navigation } from 'swiper'
// import 'swaper/scss'
// import 'swaper/scss/navigation'
import { onMounted } from 'vue'
import { usePopular } from '@/stores/popular'


const props = defineProps(['type'])
const popular = usePopular()




onMounted(() => {
    popular.getPopular({ type: props.type })
})
</script>

<style lang="scss" scoped></style>