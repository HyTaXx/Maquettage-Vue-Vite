<script setup>
import CardIcon from './CardIcon.vue';

defineProps(['cardtitle','cardtext','cardImg','numberoficon'])
</script>

<template>
    <div class="h-[355px] md:w-[298px] w-[342px] rounded-1 drop-shadow-lg">
        <div class="h-[190px] bg-cover" :style="{'background-image':'url('+cardImg+')'}">

        </div>
        <div class="h-[140] bg-white p-[16px] rounded-lg">
            <h3 class="text-[10px]">{{cardtitle}}</h3>
            <p class="font-bold text-base">{{cardtext}}</p>
            <div class="flex flex-row mt-[24px]">
                <CardIcon/>
            </div>
        </div>
    </div>
</template>

<style scoped>

</style>
