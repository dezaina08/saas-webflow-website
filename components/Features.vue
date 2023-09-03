<template>
    <div class="container-xxl">
        <div class="features d-flex flex-column align-items-center">
            <div class="text-semibold text-center">
                Explore Premium Features
            </div>
            <div class="text-opensans text-center mb-5" style="max-width: 70%">
                Unique And Powerful Suite Of Software To Run Your Entire
                Business, Brought To You By A Company With The Long Term
                Vision To Transform The Way You Work.
            </div>
            <div class="row d-flex flex-md-row flex-column p-4 gap-4">
                <div class="col feature d-flex flex-column align-items-center align-items-md-start">
                    <div>
                        <img src="/images/FeatureIcon.svg" alt="" />
                    </div>
                    <div class="text-medium text-center text-md-start">
                        Powerful Settings
                    </div>
                    <div class="text-opensans text-center text-md-start">
                        Provide Excellent Customer Service. Answer More
                        Tickets.
                    </div>
                </div>
                <div class="col feature-white d-flex flex-column align-items-center align-items-md-start">
                    <div>
                        <img src="/images/FeatureIcon2.svg" alt="" />
                    </div>
                    <div class="text-medium text-center text-md-start">
                        User Friendly
                    </div>
                    <div class="text-opensans text-center text-md-start">
                        Use Timeline To Plan Projects Right How The Pieces
                        Fit Together.
                    </div>
                </div>
                <div class="col feature d-flex flex-column align-items-center align-items-md-start">
                    <div>
                        <img src="/images/FeatureIcon3.svg" alt="" />
                    </div>
                    <div class="text-medium text-center text-md-start">
                        Integrated Platform
                    </div>
                    <div class="text-opensans text-center text-md-start">
                        Vivamus Massa Eleifend Etiam Neque Odio Feugiat
                        Dolor Est.
                    </div>
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
@import "~/assets/scss/mixins/breakpoints";

.features {
    padding: 100px 0;

    .feature {
        background: #f4f4f4;
        border-radius: 10px;
        padding: 40px 36px;
    }

    .feature-white {
        background: #ffffff;
        border-radius: 10px;
        padding: 40px 36px;
    }

    img {
        size: 55px;
        padding-bottom: 20px;
    }

    @media screen and (max-width: 768px) {
        img {
            padding-bottom: 5px;
        }
    }

    @media screen and (max-width: 768px) {
        .text-semibold {
            font-size: 35px;
            margin-bottom: 0px;
        }

        .text-medium {
            font-size: 25px;
            margin-bottom: 0px;
        }

        .text-opensans {
            font-size: 14px;
            margin-bottom: 0px;
        }
    }

    .text-semibold {
        font-family: JostSemiBold;
        font-size: 40px;
        line-height: normal;
        margin-bottom: 24px;
        color: #303030;
    }

    .text-medium {
        font-family: JostMedium;
        font-size: 30px;
        line-height: normal;
        margin-bottom: 24px;
        color: #303030;
    }

    .text-opensans {
        font-family: OpenSansRegular;
        font-size: 20px;
        line-height: normal;
        color: #303030;
    }
}
</style>