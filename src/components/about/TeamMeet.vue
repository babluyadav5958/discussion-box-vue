<template>
    <div class="common_padding team_meet_sec">
        <h3 class="title_h3">Meet the team</h3>
        <p class="team_desc">With our hearts and headquarters in Bristol, we are powered by diversity and committed to
            creating a more inclusive world, one discussion at a time. </p>
        <div class="team_grid_bg">
            <div class="row">
                <div class="col-md-4" v-for="(content, index) in teamContents" :key="index">
                    <div class="team_col_box">
                        <span class="avatar"><img :src="content.image" alt=""></span>
                        <h4 class="team_name">{{ content.name }}</h4>
                        <h6 class="team_gender">{{ content.gender }}</h6>
                        <p class="designation">{{ content.designation }}</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>
import profilePic1 from '@/assets/images/team/profile-pic1.png';
import profilePic2 from '@/assets/images/team/profile-pic2.png';
import profilePic3 from '@/assets/images/team/profile-pic3.png';
import profilePic4 from '@/assets/images/team/profile-pic4.png';
import profilePic5 from '@/assets/images/team/profile-pic5.png';
import profilePic6 from '@/assets/images/team/profile-pic6.png';

const teamContents = [
    {
        key: 1,
        name: 'Lisa marie carter',
        gender: 'She/Her',
        designation: 'CEO & FOUNDER She/He',
        image: profilePic1,
    },
    {
        key: 2,
        name: 'JEMMA CHARLES',
        gender: 'She/Her',
        designation: 'Chief Revenue Officer (CRO) Queer Woman Bsuiness Leader',
        image: profilePic2,
    },
    {
        key: 3,
        name: 'LEANNE S.',
        gender: 'She/Her',
        designation: 'Events & Sales Professional Championing Diversity in Bsuiness',
        image: profilePic3,
    },
    {
        key: 4,
        name: 'SHILAH PEPPERALL',
        gender: 'She/Her',
        designation: 'Woman in Technology Audience Acquisition Manager',
        image: profilePic4,
    },
    {
        key: 5,
        name: 'PARICE OLU',
        gender: 'She/Her',
        designation: 'Audience Development Executive Supporting Woman in Bsuinesses',
        image: profilePic5,
    },
    {
        key: 6,
        name: 'JAKE SHAW',
        gender: 'She/Her',
        designation: 'Audience Acquisition Manager',
        image: profilePic6,
    },
]
</script>

<style lang="scss">

</style>