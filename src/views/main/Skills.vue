<template>
    <section class="section section-components pb-0" id="section-components">
       <div class="container">
            <div class="row">
                <div class="col-sm-3 col-6">
                    <h3 class="h4 text-success font-weight-bold mb-4">Skills</h3>
                </div>
                <div class="col-sm-9 col-6">
                    <base-progress type="primary" :value="80" label="HTML5"></base-progress>
                    <base-progress type="default" :value="80" label="REACTJS"></base-progress>
                    <base-progress type="info" :value="80" label="JAVASCRIPT"></base-progress>
                    <base-progress type="success" :value="80" label="JAVA"></base-progress>
                    <base-progress type="warning" :value="80" label="PYTHON"></base-progress>
                    <base-progress type="danger" :value="80" label="NODEJS"></base-progress>
                </div>
            </div>
        </div>
    </section>

</template>
<script>
export default {};
</script>
<style>
</style>
