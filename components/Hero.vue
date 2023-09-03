<template>
    <div class="hero">
        <NavBar />
        <div class="container-xxl">
            <div class="hero-text">
                <div class="primary-text text-center text-md-start">
                    The CRM Platform <br />
                    Your Whole Business <br />
                    Will Love
                </div>
                <div class="secondary-text text-center text-md-start">
                    Provide Excellent Customer Service. Answer More <br />
                    Tickets All-In-One Primarily Software.
                </div>
                <div
                    class="d-flex justify-content-center justify-content-md-start"
                >
                    <a href="#" class="primary-btn btn d-lg-block"
                        >Get Started</a
                    >
                    <a href="#" class="secondary-btn btn d-lg-block"
                        >How It Work</a
                    >
                </div>
            </div>
        </div>
    </div>
</template>
<script>
    export default {};
</script>
<style lang="scss" scoped>
    @import "~/assets/scss/mixins/breakpoints";
    .hero {
        background-image: url("/images/Background.svg");
        background-size: contain;
        background-repeat: no-repeat;
        background-position: top right;

        @media screen and (max-width: 768px) {
            background-image: none;
        }

        .hero-text {
            padding-top: 100px;

            .primary-text {
                font-family: JostSemiBold;
                font-size: 60px;
                line-height: normal;
                margin-bottom: 24px;
                color: #303030;
            }

            .secondary-text {
                font-family: OpenSansRegular;
                font-size: 24px;
                line-height: normal;
                margin-bottom: 48px;
                color: #4e4e4e;
            }

            .primary-btn {
                border-radius: 5px;
                background: #303030;
                color: #fff;
                text-align: center;
                font-family: JostSemiBold;
                font-size: 20px;
                line-height: normal;
                padding: 12px 38px;
            }

            .secondary-btn {
                border-radius: 5px;
                background: #ffffff;
                color: #303030;
                text-align: center;
                font-family: JostSemiBold;
                font-size: 20px;
                line-height: normal;
                padding: 12px 38px;
            }

            @media screen and (max-width: 768px) {
                padding-top: 30px 0;
                .primary-text {
                    font-size: 35px;
                }
                .secondary-text {
                    font-size: 18px;
                }
            }
        }
    }
</style>
