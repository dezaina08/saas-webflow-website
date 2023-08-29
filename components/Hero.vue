<template>
    <div class="hero">
        <NavBar />
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
                <div class="d-flex">
                    <a href="#" class="primary-btn btn d-lg-block"
                        >Get Started</a
                    >
                    <a href="#" class="secondary-btn btn d-lg-block"
                        >How It Work</a
                    >
                </div>
            </div>
            <div class="hero-features d-flex flex-column align-items-center">
                <div class="text-semibold">Explore Premium Features</div>
                <div
                    class="text-opensans text-center mb-5"
                    style="max-width: 70%"
                >
                    Unique And Powerful Suite Of Software To Run Your Entire
                    Business, Brought To You By A Company With The Long Term
                    Vision To Transform The Way You Work.
                </div>
                <div class="row d-flex flex-md-row flex-column gap-4">
                    <div
                        class="col feature d-flex flex-column align-items-center align-items-md-start"
                    >
                        <div>
                            <img src="/images/FeatureIcon.svg" alt="" />
                        </div>
                        <div class="text-medium">Powerful Settings</div>
                        <div class="text-opensans">
                            Provide Excellent Customer Service. Answer More
                            Tickets.
                        </div>
                    </div>
                    <div
                        class="col feature d-flex flex-column align-items-center align-items-md-start"
                    >
                        <div>
                            <img src="/images/FeatureIcon2.svg" alt="" />
                        </div>
                        <div class="text-medium">User Friendly</div>
                        <div class="text-opensans">
                            Use Timeline To Plan Projects Right How The Pieces
                            Fit Together.
                        </div>
                    </div>
                    <div
                        class="col feature d-flex flex-column align-items-center align-items-md-start"
                    >
                        <div>
                            <img src="/images/FeatureIcon3.svg" alt="" />
                        </div>
                        <div class="text-medium">Integrated Platform</div>
                        <div class="text-opensans">
                            Vivamus Massa Eleifend Etiam Neque Odio Feugiat
                            Dolor Est.
                        </div>
                    </div>
                </div>
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
        background-size: contain;
        background-repeat: no-repeat;
        background-position: top right;

        @media screen and (max-width: 768px) {
            background-image: none;
        }

        .hero-text {
            padding: 100px 0;

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
                padding: 30px 0;
                .primary-text {
                    font-size: 35px;
                }
                .secondary-text {
                    font-size: 14px;
                }
            }
        }

        .hero-features {
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
    }
</style>
