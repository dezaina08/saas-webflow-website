<template>
    <nav class="navbar navbar-expand-lg">
        <div class="container-xxl d-flex justify-content-between">
            <a class="navbar-brand m-0 p-0 d-flex" href="#">
                <img src="/images/logo.svg" alt="" />
                <span class="align-middle"> PrimeCRM </span>
            </a>
            <div class="d-flex align-items-center">
                <ul class="navbar-nav mb-2 mb-lg-0 d-none d-lg-flex li-gap">
                    <li class="nav-item">
                        <nuxt-link to="#" class="nav-link">Home</nuxt-link>
                    </li>
                    <li class="nav-item">
                        <nuxt-link to="#" class="nav-link">About Us</nuxt-link>
                    </li>
                    <li class="nav-item">
                        <nuxt-link to="#" class="nav-link">Services</nuxt-link>
                    </li>
                    <li class="nav-item">
                        <nuxt-link to="#" class="nav-link">Project</nuxt-link>
                    </li>
                    <li class="nav-item">
                        <nuxt-link to="#" class="nav-link">Contact Us</nuxt-link>
                    </li>
                </ul>
                <a href="#" class="login-btn btn d-none d-lg-block"> Login </a>
            </div>
            <button
                class="navbar-toggler"
                type="button"
                data-bs-toggle="offcanvas"
                data-bs-target="#offcanvasNavbar"
                aria-controls="offcanvasNavbar"
                aria-label="Toggle navigation"
            >
                <span class="navbar-toggler-icon"></span>
            </button>
            <div
                class="offcanvas offcanvas-end d-block d-lg-none"
                tabindex="-1"
                id="offcanvasNavbar"
                aria-labelledby="offcanvasNavbarLabel"
            >
                <div class="offcanvas-header">
                    <a class="navbar-brand p-0 d-flex" href="#">
                        <img src="/images/logo.svg" alt="" />
                    </a>
                    <button
                        type="button"
                        class="btn-close"
                        data-bs-dismiss="offcanvas"
                        aria-label="Close"
                    ></button>
                </div>
                <div class="offcanvas-body">
                    <ul
                        class="navbar-nav justify-content-end flex-grow-1 li-gap"
                    >
                        <li class="nav-item">
                            <a class="nav-link" aria-current="page" href="#"
                                >Home</a
                            >
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">About Us</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Services</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Project</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Contact Us</a>
                        </li>
                        <li>
                            <a href="#" class="login-btn btn w-100"> Login </a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </nav>
</template>
<script>
    export default {};
</script>
<style lang="scss" scoped>
    .navbar {
        padding: 56px 0;

        .navbar-brand {
            height: 55px;
            color: #303030;
            font-family: JostBold;
            font-size: 40px;
            // font-style: normal;
            // font-weight: 400;
            line-height: normal;
            gap: 10px;
        }

        .navbar-nav {
            gap: 20px;

            .nav-link {
                color: #303030;
                font-family: JostMedium;
                font-size: 20px;
            }
        }

        .login-btn {
            border-radius: 5px;
            background: #303030;
            color: #fff;
            text-align: center;
            font-family: JostSemiBold;
            font-size: 20px;
            padding: 12px 38px;
            margin-left: 20px;
        }
    }
</style>
