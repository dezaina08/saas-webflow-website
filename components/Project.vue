<template>
    <div class="project mb-5">
        <div class="container-xxl">
            <div class="row d-flex flex-md-row pt-1 pt-md-5 pb-1 pb-md-5 px-2 flex-column gap-4">
                <div class="col d-flex flex-column justify-content-center">
                    <div class="font-family-jostsemibold primary-color text-3xl text-md-4xl text-center text-md-start mb-2">
                        Ways A Project Management Tool Can Help Your Team
                    </div>
                    <div
                        class="font-family-opensansregular secondary-color text-base text-md-xl text-center text-md-start mb-3 mb-md-5">
                        Unique and powerful suite of software to run your entire business, brought to you by a company with
                        the long term vision to transform the way you work.
                    </div>
                    <div class="d-flex flex-md-row flex-column">
                        <div class="p-2 mb-3 mb-md-5">
                            <div
                                class="font-family-jostsemibold primary-color text-2xl text-md-3xl text-center text-md-start">
                                CRM Security
                            </div>
                            <div
                                class="font-family-opensansregular secondary-color text-base text-md-xl text-center text-md-start">
                                cards and make more sales while chatting
                            </div>
                        </div>
                        <div class="p-2">
                            <div
                                class="font-family-jostsemibold primary-color text-2xl text-md-3xl text-center text-md-start">
                                Marketing Hub
                            </div>
                            <div
                                class="font-family-opensansregular secondary-color text-base text-md-xl text-center text-md-start">
                                Show off your goods in elegant product cards and mak.
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col d-flex justify-content-center">
                    <img src="/images/Project.svg" class="img-fluid" alt="" />
                </div>

            </div>
        </div>
    </div>
</template>
<script>
export default {

}
</script>
<style lang="scss" scoped>
.project {
    background-image: url("/images/ProjectBg.svg");
    background-size: contain;
    background-repeat: no-repeat;
    background-position: right;

    @media screen and (max-width: 768px) {
        background-image: none;
    }
}
</style>