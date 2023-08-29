<template>
    <div class="hero">
        <div class="container-xxl">
            <div class="hero-text">
                <div class="primary-text">
                    The CRM Platform <br />
                    Your Whole Business <br />
                    Will Love
                </div>
                <div class="secondary-text">
                    Provide Excellent Customer Service. Answer More <br />
                    Tickets All-In-One Primarily Software.
                </div>
                <button class="primary-btn btn d-none d-lg-block">
                    Get Started
                </button>
            </div>
        </div>
    </div>
</template>
<script>
    export default {};
</script>
<style lang="scss" scoped>
    .hero {
        background-image: url("/images/Background.svg");
        position: relative;
        background-repeat: no-repeat;
        background-size: cover;
        margin-top: -170px;
        z-index: -1;

        .hero-text {
            padding-top: 250px;
            padding-bottom: 180px;
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
        }
    }
</style>
