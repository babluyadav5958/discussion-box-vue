<template>
    <nav class="navbar bg-body-tertiary fixed-top">
        <div class="header_left_part">
            <RouterLink class="animate_logo" to="/">
                <div>discussi<span class="square_icon"></span>n b<span class="square_icon"></span>x</div>
            </RouterLink>
            <RouterLink class="logo" to="/">
                The Spotlight Experience
            </RouterLink>
        </div>
        <div class="header_right_part">
            <button class="btn btn-default btn-sm user_login_btn"><i class="bi bi-person"></i> Lise-Marie
                Carter</button>
            <button class="navbar-toggler" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasNavbar"
                aria-controls="offcanvasNavbar" aria-label="Toggle navigation">
                <i class="bi bi-list"></i>
            </button>
        </div>
        <div class="offcanvas offcanvas-end" tabindex="-1" id="offcanvasNavbar" aria-labelledby="offcanvasNavbarLabel">
            <div class="offcanvas-header">
                <h5 class="offcanvas-title" id="offcanvasNavbarLabel">Menu</h5>
                <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
            </div>
            <div class="offcanvas-body">
                <RouterLink to="/">Home</RouterLink>
                <RouterLink to="/about">About Us</RouterLink>
            </div>
        </div>
    </nav>
</template>

<script setup>
import { RouterLink, RouterView } from 'vue-router';
</script>

<style lang="scss">

</style>