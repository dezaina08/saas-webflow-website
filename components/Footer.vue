<template lang="">
    <div class="footer">
        <div class="container-xxl d-flex flex-column">
            <div class="d-flex flex-md-row flex-column align-items-center justify-content-between">
                <div class="footer-brand">
                    <a class="m-0 p-0" href="#">
                        <img src="/images/logo.svg" alt="" />
                    </a>
                    <span class="align-middle"> PrimeCRM </span>
                </div>
                <div class="footer-socials d-flex align-items-center">
                    <a class="m-0 p-0 d-flex" href="#">
                        <img src="/images/Instagram.svg" alt="" />
                    </a>
                    <a class="m-0 p-0 d-flex" href="#">
                        <img src="/images/Facebook.svg" alt="" />
                    </a>
                    <a class="m-0 p-0 d-flex" href="#">
                        <img src="/images/Twiter.svg" alt="" />
                    </a>
                    <a class="m-0 p-0 d-flex" href="#">
                        <img src="/images/LinkedIn.svg" alt="" />
                    </a>
                    <a class="m-0 p-0 d-flex" href="#">
                        <img src="/images/Youtube.svg" alt="" />
                    </a>
                </div>
            </div>

            <!-- <div class="table-responsive w-100">
                <table class="table">
                    <thead class="align-middle">
                        <tr>
                            <th class="col-sm-1">Usefull Link</th>
                            <th class="col-sm-1">Services</th>
                            <th class="col-sm-1">Contact Us</th>
                            <th class="col-sm-2">
                                <div class="d-flex justify-content-between">
                                    <div>Our Latest News</div>
                                    <div>
                                        <button
                                            class="btn btn-primary"
                                            type="button"
                                            data-bs-toggle="collapse"
                                            data-bs-target="#collapseExample"
                                            aria-expanded="false"
                                            aria-controls="collapseExample"
                                        >
                                            Button with data-bs-target
                                        </button>
                                    </div>
                                </div>
                            </th>
                        </tr>
                    </thead>
                    <tbody class="collapse" id="collapseExample">
                                <tr>
                                    <td>
                                        <div
                                            class="usefull-links d-flex flex-column"
                                        >
                                            <a aria-current="page" href="#"
                                                >Solution</a
                                            >
                                            <a aria-current="page" href="#"
                                                >Industries</a
                                            >
                                            <a aria-current="page" href="#"
                                                >Products</a
                                            >
                                            <a aria-current="page" href="#"
                                                >Resources</a
                                            >
                                            <a aria-current="page" href="#"
                                                >Pricing</a
                                            >
                                        </div>
                                    </td>
                                    <td>
                                        <div
                                            class="services d-flex flex-column"
                                        >
                                            <a aria-current="page" href="#"
                                                >Sale</a
                                            >
                                            <a aria-current="page" href="#"
                                                >Marketing</a
                                            >
                                            <a aria-current="page" href="#"
                                                >Real Estate</a
                                            >
                                            <a aria-current="page" href="#"
                                                >Automotive</a
                                            >
                                            <a aria-current="page" href="#"
                                                >Education</a
                                            >
                                        </div>
                                    </td>
                                    <td>
                                        <div
                                            class="contact-us d-flex flex-column align-items-center"
                                        >
                                            <div class="">
                                                1700 W Blancke St, kiyev
                                                <br />
                                                port south USA, American
                                            </div>
                                            <div>
                                                +3255 456 789
                                                <br />
                                                mail@primarily.com
                                            </div>
                                        </div>
                                    </td>
                                    <td colspan="2">Mark</td>
                                </tr>
                    </tbody>
                </table>
            </div> -->

            <div class="font-family-jost text-xl text-white text-center">
                Copyright © Primarly | Designed by VictorFlow Templates
            </div>
        </div>
    </div>
</template>
<script>
    export default {};
</script>
<style lang="scss" scoped>
    .footer {
        background: #4a4a4a;
        padding: 124px 0;

        .footer-brand {
            height: 55px;
            color: #ffffff;
            font-family: JostBold;
            font-size: 40px;
            line-height: normal;
            gap: 10px;
        }

        table {
            th {
                font-family: JostMedium;
                font-size: 25px;
                font-style: normal;
                font-weight: 500;
                height: 72px;
                color: #ffffff;
                background: none;
            }

            td {
                background: none;
            }

            a {
                color: #ffffff;
                text-decoration: none;
                font-family: JostMedium;
                font-size: 20px;
                font-style: normal;
                font-weight: 500;
            }
        }

        .collapsing {
            -webkit-transition: none;
            transition: none;
            display: none;
        }

        .footer-socials {
            height: 55px;
            gap: 26px;

            img {
                height: 22px;
            }
        }
    }
</style>
