<template>
    <section class="section section-components pb-0" id="section-components">
       <div class="container">
            <div class="row">
                <div class="col-sm-12 col-12">
                    <h3 class="h4 text-success font-weight-bold mb-4">
                        CHECK OUT SOME OF MY WORKS
                    </h3>
                </div>
                <div class="col-sm-12 col-12">
                    <tabs fill class="flex-column flex-md-row w-100 h-100 mb-5">
                       <card shadow slot-scope="{activeTabIndex}">
                    <tab-pane key="tab1">
                        <template slot="title">
                            <i class="ni ni-collection mr-2"></i>First Project
                        </template>

                        <p class="description">첫 번째 프로젝트의 설명 입니다. 저는 이런 프로젝트를 만들었습니다. 짱이죠? </p>
                       
                    </tab-pane>

                    <tab-pane key="tab2">
                        <template slot="title">
                            <i class="ni ni-collection mr-2"></i>Second Project
                        </template>

                        <p class="description">두 번째 프로젝트의 설명 입니다. 저는 이런 프로젝트를 만들었습니다. 짱이죠? </p>
                    </tab-pane>

                    <tab-pane key="tab3">
                        <template slot="title">
                            <i class="ni ni-collection mr-2"></i>Third Project
                        </template>

                        <p class="description">세 번째 프로젝트의 설명 입니다. 저는 이런 프로젝트를 만들었습니다. 짱이죠? </p>
                    </tab-pane>
                </card>
                    </tabs>
                </div>
            </div>
        </div>
    </section>

</template>
<script>
import Tabs from "@/components/Tabs/Tabs.vue";
import TabPane from "@/components/Tabs/TabPane.vue";
export default {
    name: 'Links',
    data(){
        return {

        }
    },
    components: {
        Tabs,
        TabPane
    }
};
</script>
<style>
</style>
