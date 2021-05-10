<template>
     <header class="s-header">

        <div class="header-logo">
            <nuxt-link class="site-logo" to="/">
                <img src="~/assets/images/logo.png" alt="Homepage">
            </nuxt-link>
        </div>

        <nav class="header-nav-wrap">
            <ul class="header-nav">
                <li><nuxt-link to="/" title="Home">Home</nuxt-link></li>
                <li><nuxt-link to="/about" title="About">About</nuxt-link></li>
                <li><nuxt-link to="/events" title="Services">Events</nuxt-link></li>
                <li><nuxt-link to="/contact" title="Contact us">Contact</nuxt-link></li>	
            </ul>
        </nav>

        <a class="header-menu-toggle" href="#0"><span>Menu</span></a>

    </header>
   
</template>