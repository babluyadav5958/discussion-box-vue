<template>
    <div class="home_info_box">
        <div class="row">
            <div class="col-md-4">
                <div class="info_details_box">
                    <p>Grow your industry presence<br /> <a href="#">through meaningful</a><br /> <a
                            href="#">networking.</a></p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="info_details_box">
                    <p>Harness <a href="#">inspiring digital<br /> discussions</a> to drive reliable<br /> business
                        growth.
                    </p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="info_details_box">
                    <div class="triangle_shape"><img src="@/assets/images/dts-shape.png" alt=""></div>
                    <p>Open the door to <a href="#">genuine<br /> relationships</a> with C-Level<br /> executives peers.
                    </p>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>
</script>

<style lang="scss">
.home_info_box {
    padding: 30px 6%;
}
.info_details_box {
    position: relative;
    p {
        margin: 0;
        font-size: 1.1vw;
        a {
            text-decoration: underline;
            &:hover {
                text-decoration: none;
            }
        }
    }
}
.triangle_shape {
    width: 70px;
    position: absolute;
    top: -3vw;
    left: -4vw;
    animation: TriangleMove 3s infinite alternate;
}
@keyframes TriangleMove {
    from {
        transform: translateY(10px);
    }

    to {
        transform: translateY(-10px);
    }
}
</style>
