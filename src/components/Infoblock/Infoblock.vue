<template>
    <div class="main__info">
        <img src="@/assets/images/close.svg" class="main__info-close" @click="$emit('close')" alt="">
        <div class="main__info-block">
            <img src="@/assets/images/block.jpg" class="main__info-img" alt="">
            <div class="main__info-contetn">
                <div class="main__info-contetn-block">
                    <h2 class="main__info-contetn-title">Ишан-чи</h2>
                    <p class="main__info-contetn-text">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Illum ducimus nam sit exercitationem a rerum delectus quam odit dignissimos iste.
                    </p>
                    <p class="main__info-contetn-date">
                        <span>2023</span>
                        <span >жынры</span>
                    </p>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>
import { imgFull } from '@/static'
const props = defineProps(['current', 'type'])

</script>
