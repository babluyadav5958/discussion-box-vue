<template>
    <div class="marquee_scroll">
        <div class="item" v-for="(content, index) in contents" :key="index" v-html="content">
        </div>
    </div>
</template>

<script setup>
const contents = [
    "<span>VIRTUAL EVENTS WITH A</span> HUMAN TOUCH.",
    "<span>VIRTUAL EVENTS WITH A</span> HUMAN TOUCH.",
    "<span>VIRTUAL EVENTS WITH A</span> HUMAN TOUCH.",
];
</script>

<style lang="scss">
@import '../../assets/scss/base/variables';
@import '../../assets/scss/base/mixins';
@import '../../assets/scss/components/fonts';

.marquee_scroll {
    border-top: 1px solid $black;
    border-bottom: 1px solid $black;
    padding: 12px 0;
    white-space: nowrap;
    overflow-x: auto;
    background: $black;

    .item {
        color: #ddd;
        font-family: $font-chivo;
        font-size: 1.2vw;
        display: inline-block;
        margin: 0 3.2vw;
        animation-name: MarqueeMove;
        animation-duration: 10s;
        animation-timing-function: linear;
        animation-iteration-count: infinite;
        font-weight: 200;

        span {
            font-weight: 600;
            color: $white;
        }
    }

    &::-webkit-scrollbar {
        display: none;
    }
}

@keyframes MarqueeMove {
    from {
        transform: translateX(0);
    }

    to {
        transform: translateX(-100%);
    }
}
</style>