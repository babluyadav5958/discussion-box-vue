<template>
    <div class="common_padding about_info_sec">
        <div class="hero_heading2">
            <div class="style1">The</div>
            <h2 class="style2">Spotlight<br /> Experience</h2>
            <div class="author_group">
                by <div class="style3">discussi<span class="square_ico"></span>n b<span class="square_ico"></span>x
                </div>
            </div>
        </div>
        <div class="about_story_sec">
            <h4>Our story</h4>
            <div class="row">
                <div class="col-md-4" v-for="(content, index) in contents" :key="index">
                    <div class="stroy_info_box">
                        <p>{{ content.text }}</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <AboutMarqueeMain />
</template>

<script setup>
import AboutMarqueeMain from '../about/AboutMarquee.vue';

const contents = [
    {
        key: 1,
        text: "Discussion Box was born and raised in the Digital era, which saw (and still sees!) increasing demand for business expansion beyond traditional means."
    },
    {
        key: 2,
        text: "Founded by serial entrepreneur and mum of 3 Lisa-Marie Carter, The Spotlight Experience aims to connect important decision-makers and leading global bra., through meaningful online discussions."
    },
    {
        key: 3,
        text: "Driven by the goal to reduce unnecessary world-travel and improve accessibility in the events space, Discussion Box was built to be different. "
    }
]
</script>

<style lang="scss">

</style>