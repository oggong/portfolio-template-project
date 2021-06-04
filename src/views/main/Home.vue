<template>
    <section class="section-hero section-shaped my-0">
        <!-- <div class="shape shape-style-1 shape-primary"> -->
        <div class="shape" :style="cssProps">
            <span class="span-150"></span>
            <span class="span-50"></span>
            <span class="span-50"></span>
            <span class="span-75"></span>
            <span class="span-100"></span>
            <span class="span-75"></span>
            <span class="span-50"></span>
            <span class="span-100"></span>
            <span class="span-50"></span>
            <span class="span-100"></span>
        </div>
        <!-- introduce page -->
        <div class="container shape-container d-flex align-items-center">
            <div class="col px-0">
                <div class="row justify-content-center align-items-center">
                    <div class="col-lg-7 text-center pt-lg">
                    </div>
                </div>
            </div>
        </div>
        <!-- introduce page -->
    </section>
</template>
<script>
export default {
    data() {
      return {
        cssProps: {
        background: `no-repeat center/100% url(${require('@/assets/images/background_two.jpg')})`
        }
      }
    }
};
</script>
<style>
</style>
