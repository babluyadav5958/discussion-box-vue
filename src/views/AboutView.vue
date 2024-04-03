<template>
  <div class="common_title_bg">
    <h3 class="main_heading">About</h3>
  </div>

  <AboutInfoDetails />

  <div class="common_padding about_service_wrapper">
    <div class="bg_anime1">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="-25 -25 250 250" class="bg_anime2_rotate">
        <defs>
          <radialGradient id="rgrad" cx="50%" cy="50%" r="50%">
            <stop offset="0%" style="stop-color:#ad16fe;stop-opacity:1.00" />
            <stop offset="100%" style="stop-color:#7a5cff;stop-opacity:1.00" />
          </radialGradient>
        </defs>
        <path
          d="M189.30481951465487 55.00389781931194 C174.6398989256279 19.11241406069729 69.65570819150616 -0.4998924172648884 37.843345384077956 21.663863466743678 C9.49285890112234 41.41572111418609 3.382839342072634 127.73147784480389 18.952547055258435 158.57738788278203 C28.67469957765863 177.8384201131743 73.81827884265147 205.13310216348006 94.74000252959364 199.861566313629 C136.67727852548106 189.29485311325357 205.6627753190141 95.0389802810336 189.30481951465487 55.00389781931194Z"
          stroke="none" fill="url(#rgrad)" />
      </svg>
    </div>
    <h3 class="title_h3">OPENING DOORS TO THE<br /> RIGHT CONVERSATIONS</h3>
    <h5 class="text_purple purple_sub_heading">Black-woman owned, women-led...</h5>
    <div class="row service_tow_col">
      <div class="col-md-5 position-realtive">
        <div class="service_abo_1">
          <p>The number of women in technology continues to rise and as a woman-owned and run busineu, Discuuion Box
            is
            here to change the narrative and challenge the status quo.</p>
        </div>
        <span class="cube_group_box"><img src="@/assets/images/cube-group-thumb.png" alt="cube"></span>
      </div>
      <div class="col-md-6">
        <div class="service_abo_2">
          <p>We are building a growing community of accomplished female executives, and are uniquely placed to start
            discussions with both male and female leaders across all corners of the world.
          </p>
        </div>
        <div class="service_abo_3">
          <h3 class="title_h3">WHITE-COLLAR?<br /> <b>NO COLLAR!</b></h3>
          <p>We're people first and professionals second. We keep it simple, honest, and straightforward. As people of
            our word, we are deeply committed to delivering value at every turn, creating experiences that build
            enduring trust and respect. We choose to nurture communities, not leads. </p>
        </div>
      </div>
    </div>
    <div class="service_abo_4">
      <h3 class="title_h3">CHANGING THE NARRATIVE.<br /> DISRUPTING NORMS.</h3>
      <p>We firmly believe in breaking boundaries, lowering accessibility barriers and holding space for uncommon
        empathy and integrity, in all our business activities. It's not why we're good, it's why we're
        <span class="text_purple">different</span>!
      </p>
      <div class="bg_anime2">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="-25 -25 220 190" class="bg_anime2_flot">
          <defs>
            <linearGradient id="lgrad" x1="0%" y1="50%" x2="100%" y2="50%">
              <stop offset="0%" style="stop-color:#896fff;stop-opacity:1.00" />
              <stop offset="100%" style="stop-color:#896fff;stop-opacity:1.00" />
            </linearGradient>
          </defs>
          <path
            d="M171.66168315977535 30.25329278949455 C159.7527212286954 12.237139505773932 111.96747225998925 -2.5665185039430907 90.58198594896766 0.44448276798237885 C65.2221336817152 4.015060790946725 7.992431972505621 35.35722103017508 7.932442145713011 60.96713191747858 C7.818560117464194 109.58385163564222 120.34312054566954 197.38408208412463 164.29069031550455 176.5944328182923 C197.40415822573505 160.9299174097155 191.86156749110737 60.812145402578906 171.66168315977535 30.25329278949455Z"
            stroke="none" fill="url(#lgrad)" />
        </svg>
      </div>
    </div>

  </div>

  <TeamMeet />

  <div class="quick_contact_part common_padding ">
    <div class="contact_left_info">
      <h2>DO YOU BELONG WITH US?</h2>
      <p>Feel free to get in touch. If you are truly share the<br /> Discussion Box spirit, let's chat!</p>
    </div>
    <div class="contact_right_info">
      <RouterLink to="/" class="shadow_btn">
        <span class="title">
          Contact our team
        </span>
        <span class="shadow_drop"></span>
      </RouterLink>
    </div>
  </div>
</template>

<script setup>
import AboutInfoDetails from '../components/about/AboutInfoDetails.vue'
import TeamMeet from '../components/about/TeamMeet.vue'
</script>

<style lang="scss">
@import '../assets/scss/aboutPage.scss';
</style>