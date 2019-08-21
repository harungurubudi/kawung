<template>
  <div class="container siteheader">
      <div class="siteheader__logo">
        <img src="~/static/img/logo.png" />
      </div>
      <nav>
        <ul>
          <li class="active">
            <nuxt-link to="/">
              Home
            </nuxt-link>
          </li>
          <li>
            <nuxt-link to="/products">
              Products
            </nuxt-link>
          </li>
          <li>
            <nuxt-link to="/services">
              Services
            </nuxt-link>
          </li>
          <li>
            <nuxt-link to="/about-us">
              About Us
            </nuxt-link>
          </li>
          <li>
            <nuxt-link to="/contact">
              Contact
            </nuxt-link>
          </li>
        </ul>
      </nav>
  </div>
</template>