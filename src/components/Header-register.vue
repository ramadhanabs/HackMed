<template>
    

    <nav class="navbar fixed-top navbar-expand-lg navbar-dark bg-dark" data-scroll-header>
        <div class="container-fluid">
            <RouterLink class="navbar-brand" to="/">
                <img src="../frontend/assets/logo/logo-mit-light.svg" style="height: 42px;" alt="Canvas Logo">
            </RouterLink>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav mb-2 mb-lg-0 ms-auto">
                    <li class="nav-item">
                        <RouterLink class="nav-link" to="/">Home</RouterLink>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            Speakers
                        </a>
                        <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                            <li>
                                <RouterLink class="dropdown-item" to="/speakers">Conference Speakers</RouterLink>
                            </li>
                            <li>
                                <RouterLink class="dropdown-item" to="/judges">Judges</RouterLink>
                            </li>
                            <li>
                                <RouterLink class="dropdown-item" to="/mentors">Mentors</RouterLink>
                            </li>
                        </ul>
                    </li>
                    <li class="nav-item">
                        <RouterLink class="nav-link" to="/sponsorship">Sponsorship</RouterLink>
                    </li>
                    <li class="nav-item">
                        <RouterLink class="nav-link" to="/contact">Contact</RouterLink>
                    </li>
                    <li class="nav-item">
                        <RouterLink class="nav-link" to="/faq">FAQ</RouterLink>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
</template>

<script setup>
import { RouterLink } from 'vue-router'
</script>