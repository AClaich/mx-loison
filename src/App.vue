<script setup lang="ts">
import { RouterView } from 'vue-router'
import NavBarView from './views/NavBarView.vue'
</script>

<template>
  <header class="container position-sticky z-index-sticky top-0 pt-5">
    <NavBarView />
  </header>

  <div class="container h-100">
    <div class="card blur">
      <div class="card-body">
        <RouterView />
      </div>
    </div>
  </div>

  <footer class="blur">
    <div class="container">
      <div class="row row-footer pt-3 justify-content-around">
        <div class="col-6 col-lg-4 d-flex align-items-center">
          Copyright © 2023 Margaux Loison

        </div>
        <div class="col-6 col-lg-4 text-end">
          <a href="/mention">Mentions légales & politiques</a>
        </div>
      </div>
    </div>
  </footer>
</template>

<style scoped>
div>.card {
  margin-top: 20%;
  border-radius: 0.375rem 0.375rem 0 0;
  height: fit-content;
}

footer {
  background-color: white;
  position: absolute;
  bottom: 0;
  width: 100%;
  height: 60px;
  min-height: fit-content;
  line-height: 60px;
  font-size: medium;
  color: black;
}

.row-footer {
  line-height: normal;
}

footer>a {
  color: black
}

.z-index-sticky {
  z-index: 1020;
}

/* nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  margin-top: 2rem;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
} */

@media (min-width: 400px) {
  div>.card {
    margin-top: 8%;
    border-radius: 0.375rem 0.375rem 0 0;
    height: fit-content;
    min-height: 100%;
  }
}

@media (min-width: 1537px) {
  div>.card {
    margin-top: 12%;
    border-radius: 0.375rem 0.375rem 0 0;
    height: fit-content;
  }
}

@media (min-height: 926px) {
  div>.card {
    /* min-height: 620px; */
  }
}

@media (min-width: 1024px) {
  /* header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  } */

  /* nav {
    text-align: left;
    margin-left: -1rem;
    font-size: 1rem;

    padding: 1rem 0;
    margin-top: 1rem;
  } */
}
</style>
