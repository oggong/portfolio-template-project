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
                       <card shadow>
                        <!-- slot-scope="{activeTabIndex}" -->
                    <tab-pane key="tab1">
                        <template slot="title">
                            <i class="ni ni-collection mr-2"></i>KEEP FIT PROJECT
                        </template>
                        <div class="row">
                            <div class="col-sm-2 col-2 d-flex flex-column justify-content-center align-items-center">
                                <p class="mb-1" style="font-size:5px;">link icon</p>
                                <a href="https://github.com/minseokoh-dev/project-keepfit">
                                    <img src="img/theme/workout.png" style="width:100px; height: 100px;" v-b-tooltip.hover.top title="keepfit project로 이동"/>
                                </a>
                            </div>
                            <div class="col-sm-10 col-10">
                                <h4>나의 운동스타그램 KEEP FIT</h4>
                                <p class="description">자신의 운동 기록을 남기고 타인과 공유하며 지속적으로 건강한 삶을 체크 할 수 있는 인스타그램식 SNS</p>
                                <p class="description">사용 기술 스택: JAVA(ANDROID), JAVASCRIPT, SPRING, MYBATIS, JQUERY, APACHE TOMCAT, ORACLE DB</p>
                            </div>
                        </div>
                    </tab-pane>

                    <tab-pane key="tab2">
                        <template slot="title">
                            <i class="ni ni-collection mr-2"></i>BALLOON PROJECT
                        </template>
                        <div class="row">
                            <div class="col-sm-2 col-2 d-flex flex-column justify-content-center align-items-center">
                                <p class="mb-1" style="font-size:5px;">link icon</p>
                                <a href="https://github.com/minseokoh-dev/project-balloon">
                                    <img src="img/theme/balloon.png" style="width:100px; height: 100px;" v-b-tooltip.hover.top title="balloon project로 이동"/>
                                </a>
                            </div>
                            <div class="col-sm-10 col-10">
                                <h4>blow your ideas </h4>
                                <p class="description">협업툴에 대한 개념을 잘 모르는 대학생과 취준생을 타겟으로 한 프로젝트 기반 협업 툴</p>
                                <p class="description">사용 기술 스택: JAVASCRIPT, REACTJS, EXPRESSJS, MONGODB, MYSQL, NODEJS, SOCKET.IO</p>
                            </div>
                        </div>
                    </tab-pane>

                    <tab-pane key="tab3">
                        <template slot="title">
                            <i class="ni ni-collection mr-2"></i>BLOG PROJECT
                        </template>
                         <div class="row">
                            <div class="col-sm-2 col-2 d-flex flex-column justify-content-center align-items-center">
                                <p class="mb-1" style="font-size:5px;">link icon</p>
                                <a href="https://github.com/minseokoh-dev/project-blog">
                                    <img src="img/theme/blog.png" style="width:100px; height: 100px;" v-b-tooltip.hover.top title="blog project로 이동"/>
                                </a>
                            </div>
                            <div class="col-sm-10 col-10">
                                <h4>REACT BLOG</h4>
                                <p class="description">책을 보고 공부하면서 만든 프로젝트 입니다.</p>
                                <p class="description">사용 기술 스택: JAVASCRIPT, REACTJS, Koa Framework, MONGODB, MYSQL, NODEJS</p>
                            </div>
                        </div>
                    </tab-pane>
                    <tab-pane key="tab3">
                        <template slot="title">
                            <i class="ni ni-collection mr-2"></i>REACT VERSION PORTFOLIO
                        </template>
                         <div class="row">
                            <div class="col-sm-2 col-2 d-flex flex-column justify-content-center align-items-center">
                                <p class="mb-1" style="font-size:5px;">link icon</p>
                                <a href="https://minseokoh-dev.github.io/resume-site/">
                                    <img src="img/theme/react_icon.png" style="width:100px; height: 100px;" v-b-tooltip.hover.top title="blog project로 이동"/>
                                </a>
                            </div>
                            <div class="col-sm-10 col-10">
                                <h4>REACT BLOG</h4>
                                <p class="description">REACTJS로 구성한 포트폴리오 사이트 입니다.</p>
                                <p class="description">사용 기술 스택: JAVASCRIPT, REACTJS</p>
                            </div>
                        </div>
                    </tab-pane>
                </card>
                    </tabs>
                </div>
            </div>
           <div class="row">
                <div class="col-sm-12 col-12">
                    <h3 class="h4 text-success font-weight-bold mb-4">
                    </h3>
                </div>
                <div class="col-sm-12 col-12">
                    <tabs fill class="flex-column flex-md-row w-100 h-100 mb-5">
                       <card shadow>
                                <!-- slot-scope="{activeTabIndex}" -->
                            <tab-pane key="tab1">
                                <template slot="title">
                                    <i class="ni ni-collection mr-2"></i>NOCODING AI PROJECT
                                </template>
                                <div class="row">
                                    <div class="col-sm-2 col-2 d-flex flex-column justify-content-center align-items-center">
                                        <p class="mb-1" style="font-size:5px;">link icon</p>
                                        <a href="/">
                                            <img src="img/theme/ai_img.png" style="width:100px; height: 100px;"/>
                                        </a>
                                    </div>
                                    <div class="col-sm-10 col-10">
                                        <h4>코딩이 필요 없는 AI/딥러닝 모델 개발 플랫폼</h4>
                                        <p class="description">NOCODING AI 웹 애플리케이션 프로토타입 프론트엔드 개발</p>
                                        <p class="description">사용 기술 스택: JAVASCRIPT, VUEJS, TENSORFLOW.JS, RETE.JS, AWS CLOUD9 </p>
                                    </div>
                                </div>
                            </tab-pane>

                            <tab-pane key="tab2">
                                <template slot="title">
                                    <i class="ni ni-collection mr-2"></i>PADO PROJECT
                                </template>
                                <div class="row">
                                    <div class="col-sm-2 col-2 d-flex flex-column justify-content-center align-items-center">
                                        <p class="mb-1" style="font-size:5px;">link icon</p>
                                        <a href="/">
                                            <img src="img/theme/wave_img.png" style="width:100px; height: 100px;"/>
                                        </a>
                                    </div>
                                    <div class="col-sm-10 col-10">
                                        <h4>pado - 마음에 귀기울이는 ASMR 일기장 </h4>
                                        <p class="description">PADO APP 레거시 코드 수정 및 기능 업데이트 프로젝트</p>
                                        <p class="description">사용 기술 스택: JAVASCRIPT, REACTJS, REACT NATIVE, SQLLITE</p>
                                    </div>
                                </div>
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
