<template>
    <header>

        <div class="top-bar">
            <nav class="navbar ">
                <div class="container-fluid">
                    <div class="left-nav  ">
                        <a class="nav-item" href="/">About</a>
                        <a class="nav-item" href="/">Contact</a>

                        <div class=" nav-item nav-menu">
                            <a class=" nav-item menu-item " href="/">Full width Page</a>
                            <ul class="dropdown-brand">
                                <li><a class="dropdown-item" href="#">Sub Menu 1</a></li>
                                <li><a class="dropdown-item" href="#">Sub menu 2</a></li>
                                <li><a class="dropdown-item" href="#">Sub Menu 3</a></li>
                            </ul>

                        </div>
                        <a class=" nav-item menu-item " href="/">Submit Article</a>
                        <a class=" nav-item menu-item " href="/">Buy Theme</a>

                    </div>
                    <div class="nav-item menu-icon">
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
                            class="bi bi-list" viewBox="0 0 16 16">
                            <path fill-rule="evenodd"
                                d="M2.5 12a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5z" />
                        </svg>
                    </div>


                    <div class="right-nav d-flex logged ">
                        <ul class="icon">
                            <li>
                                <TwitterIcon />
                            </li>
                            <li>
                                <FacebookIcon />
                            </li>
                            <li>
                                <YoutubeIcon />
                            </li>
                            <li>
                                <LinkedinIcon />
                            </li>
                            <li>
                                <DribbbleIcon />
                            </li>
                            <li>
                                <InstagramIcon />
                            </li>

                        </ul>
                    </div>

                </div>

            </nav>

        </div>

    </header>
</template>

<script setup >

import DribbbleIcon from "../../components/svgs/DribbbleIcon.vue";
import FacebookIcon from "../../components/svgs/FacebookIcon.vue";
import InstagramIcon from "../../components/svgs/InstagramIcon.vue";
import LinkedinIcon from "../../components/svgs/LinkedinIcon.vue";
import TwitterIcon from "../../components/svgs/TwitterIcon.vue";
import YoutubeIcon from "../../components/svgs/YoutubeIcon.vue";
</script>

<style scoped>
/* Style for screens smaller than 760px */


@media (min-width: 1200px) {
    .left-nav {
        display: flex;

    }

    .menu-icon {
        display: none;
    }

    .top-bar {
        background: linear-gradient(to right, #0797ea,#0797ea, #a252cd 90%);
        transition: background-color 0.5s;
        height: 36.8px;
    }

    .navbar {
        margin: 0px 139.60px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 0px;
    }


    .container-fluid {
        padding: 0px;
    }



    .nav-item {
        margin-right: 20px;
        color: #f9f9f9;
        font-size: small;
       
    }

    .nav-item:hover {
        color: #990099;
        text-decoration: none;
    }



    .dropdown-brand {

        display: none;
        position: absolute;
        background-color: #f9f9f9;
        min-width: 200px;
        font-size: 15px;
        box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
        list-style: none;
    }

    .nav-menu:hover .dropdown-brand {
        display: block;
        z-index: 1;

    }

    .dropdown-brand>li>a:hover {

        text-decoration: none;
        color: #990099;
    }

    .icon {

        padding: 8px 0px;
    }



}

@media (max-width: 760px) {
    .top-bar {
        background: linear-gradient(to right, #256fc9, #7464a2 30%);
        transition: background-color 0.5s;
        height: 36.8px;
        width: 100%;
    }

    .left-nav {
        display: none;

    }

    .menu-icon {
        display: block;
        flex: left;
    }



    .nav-bar {
        margin: 0px 0px;
    }



}
</style>