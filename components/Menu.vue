<template>
    <b-navbar toggleable="md" variant="faded" type="light" fixed=top id="menu" v-scroll="handleScroll">
        <b-container>
            <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>

            <b-navbar-brand to="/" tag="h1" class="mb-0">
                <img src="~/assets/logo.png" class="logo" width=60 height=60 :class="{hide: !scrolling}">
            </b-navbar-brand>

            <b-collapse is-nav id="nav_collapse">

                <b-navbar-nav>

                    <b-nav-item to="/assistance">Assistance</b-nav-item>
                    <b-nav-item to="/content">Content</b-nav-item>
                    <b-nav-item to="/marketing">Marketing</b-nav-item>
                    <b-nav-item to="/development">Development</b-nav-item>
                    <b-nav-item to="/events">Events</b-nav-item>
                </b-navbar-nav>

                <b-navbar-nav class="ml-auto align-items-center">
                    <b-nav-item to="/blog">Blog</b-nav-item>
                    <b-nav-item to="/contact">
                        <b-button variant="success" ><fa icon="phone" /> Get in touch</b-button>
                    </b-nav-item>
                </b-navbar-nav>
            </b-collapse>
        </b-container>


    </b-navbar>
</template>
<script>

    function isScrolling() {
        return typeof window !== 'undefined' ? window.scrollY > 0 : false;
    }

    export default {


        data() {
          return {
            scrolling: false
          };
        },

        methods: {
            handleScroll() {
                this.scrolling = isScrolling();
            }
        }
    }
</script>
<style lang=less>

  .logo {
    transition: opacity 0 2s ease;
    opacity: 1;

    &.hide {
      opacity: 0;
    }
  }
</style>
