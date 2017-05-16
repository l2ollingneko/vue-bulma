<template>
    <div id="app">
        <nav class="nav techsauce-nav">
            <div class="nav-left is-hidden-mobile" style="flex-basis: 1 !important;">
                <a class="nav-item" style="margin: 0px 40px 0px 60px;">
                    <img src="./assets/images/techsauce_logo_sm.png">
                </a>
                <a class="nav-item">
                    Home
                </a>
                <a class="nav-item">
                    for Startup
                </a>
                <a class="nav-item">
                    for Investor
                </a>
                <a class="nav-item">
                    <form>
                        <div class="field">
                        <p class="control has-icons-left">
                            <input class="input search" type="text" placeholder="Search       ">
                            <span class="icon is-small is-left" style="height: 1.9em;">
                                <i class="fa fa-search"></i>
                            </span>
                        </p>
                        </div>
                    </form>
                </a>
            </div>

            <!-- This "nav-toggle" hamburger menu is only visible on mobile -->
            <!-- You need JavaScript to toggle the "is-active" class on "nav-menu" -->
            <span class="nav-toggle">
            <span></span>
            <span></span>
            <span></span>
            </span>

            <div class="nav-left nav-menu is-hidden-tablet">
                <a class="nav-item" style="margin: auto;">
                    <img src="./assets/images/techsauce_logo_sm.png">
                </a>
            </div>
                
            <div class="nav-center is-hidden-tablet">
                <a class="nav-item">
                    <span class="icon">
                        <i class="fa fa-user"></i>
                    </span>
                </a>
            </div>
                
            <!-- This "nav-menu" is hidden on mobile -->
            <!-- Add the modifier "is-active" to display it on mobile -->
            <div class="nav-right is-hidden-mobile">
                <div class="nav-item">
                    <div class="field is-grouped">
                        <p class="control">
                            <a class="nav-item">
                                <span class="icon">
                                    <i class="fa fa-bell-o"></i>
                                </span>
                            </a>
                        </p>
                        <p class="control">
                            <a class="nav-item">
                                <span class="icon">
                                    <i class="fa fa-envelope"></i>
                                </span>
                            </a>
                        </p>
                        <p class="control">
                            <a class="nav-item">
                                <span class="icon">
                                    <i class="fa fa-user"></i>
                                </span>
                            </a>
                        </p>
                    </div>
                </div>
            </div>
        </nav>

        <router-view></router-view>

    </div>
</template>

<script>
    export default {
        name: 'app'
    }
</script>

<style src="./assets/css/bulma.css" rel="stylesheet" type="text/css" />

<style>
    body {
        background-image: url('./assets/images/background/login_regist_bg.png');
        height: 100%;
        position: fixed;
        top: 0px;
        right: 0px;
        bottom: 0px;
        left: 0px;
    }
    input {
        border-color: transparent !important;
        box-shadow: 0 0 0em #719ECE !important;
    }
    .search {
        text-align: center;
        border-radius: 30px;
        height: 30px;
    }
    .techsauce-nav {
        background-color: #252525;
    }
    #app {
        font-family: 'Avenir', Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
    }
</style>
