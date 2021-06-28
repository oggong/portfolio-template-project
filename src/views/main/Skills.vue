<template>
    <section class="section section-components pb-0" id="section-components">
       <div class="container">
            <div class="row">
                <div class="col-sm-3 col-6">
                    <h3 class="h4 text-success font-weight-bold mb-4">Skills</h3>
                </div>
                <div class="col-sm-9 col-6">
                    <h5 class="h5 text-primary font-weight-bold mb-4">WEB DEVELOP</h5>
                    <base-progress type="info" :value="90" label="JAVASCRIPT"></base-progress>
                    <base-progress type="primary" :value="90" label="VUEJS"></base-progress>
                    <base-progress type="default" :value="80" label="REACTJS"></base-progress>
                    <base-progress type="success" :value="60" label="NODEJS"></base-progress>
                    <hr/>
                </div>
                <div class="col-sm-3 col-6">
                    <!-- <h3 class="h4 text-success font-weight-bold mb-4">Skills</h3> -->
                </div>
                <div class="col-sm-9 col-6">
                    <h5 class="h5 text-primary font-weight-bold mb-4">APP DEVELOP</h5>
                    <base-progress type="warning" :value="80" label="REACTNATIVE"></base-progress>
                    <base-progress type="danger" :value="80" label="JAVA"></base-progress>
                </div>
            </div>
            <hr/>
        </div>
    </section>

</template>
<script>
export default {};
</script>
<style>
</style>
