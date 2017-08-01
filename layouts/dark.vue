Nuxt
NUXT

    Guide
    API
    Examples
    FAQ
    Ecosystem

Version 0.10.6
Essentials

    Hello world
    SEO HTML Head

Customization

    Cached Components
    Custom Loading
    Custom Routes
    Global CSS
    Layouts
    Middleware
    Nested Routes
    Plugins
    Routes transitions

Advanced

    Async Data
    Auth Routes
    Vuex Store
    i18n
    Testing

Layouts

    Layouts example with Nuxt.js

Source Code
Example Files

    layouts
        dark.vue
        default.vue
        error.vue
    pages
        about.vue
        index.vue
    static
        logo.png
    package.json

/layouts/dark.vue

<template>
  <div class="dark">
    <nuxt/>
  </div>
</template>

<style>
body {
  overflow: hidden;
}
.dark {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  min-height: 100%;
  background: black;
  color: white;
  padding: 10px;
}
.dark a {
  color: white;
}
</style>

Live Demo
Live Edit
Download Documentation
