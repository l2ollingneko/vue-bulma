<template>
    <section class="hero is-fullheight">
        <div class="hero-body">
            <div class="container">
                <div class="columns">
                    <div class="column is-one-third is-offset-one-third">
                        <div class="field">
                            <p class="control">
                                <input class="input" type="text" placeholder="Username">
                            </p>
                        </div>
                        <div class="field">
                            <p class="control">
                                <input class="input" type="password" placeholder="Password">
                            </p>
                        </div>
                        <br>
                        <div class="field">
                            <p class="control">
                                <a class="button is-dark is-medium full-width-button">Login</a>
                            </p>
                        </div>
                        <div class="field">
                            <p class="control">
                                <a class="button is-info is-medium full-width-button">Login with Facebook</a>
                            </p>
                        </div>
                        <div class="field has-text-centered">
                            <a href="#" style="color: #ffffff; font-size: 0.9rem;">or create an account</a>
                            <br>
                            <a href="#" style="color: #ffffff; font-size: 0.9rem;">Forgot password?</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
    export default {
    
    }
</script>

<style>
    .hero {
        background-image: url(../../src/assets/images/background/login_regist_bg.png);
        margin-top: -52px;
    }
    .full-width-button {
        width: 100%;
        font-size: 1.0rem !important;
    }
</style>
