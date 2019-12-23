<template>
    <div class="icons">
        <swiper :options="swiperOption">
                <swiper-slide v-for='(page, index) of page' :key='index'>
                    <div class="icon" v-for="item of page" :key="item.id">
                            <div class="icon-img">
                                <img class="con-img-content" :src="item.imgUrl">
                            </div>
                            <p class="icon">
                    </div>
                </swiper-slide>
        </swiper>
    </div>
</template>