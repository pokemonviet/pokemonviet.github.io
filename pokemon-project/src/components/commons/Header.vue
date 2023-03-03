<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Logo from './Logo.vue'
</script>
<template>
    <!-- ======= Header ======= -->
    <header id="header" class="header fixed-top header-scrolled">
        <div class="container-fluid container-xl d-flex align-items-center justify-content-between">

            <Logo></Logo>
            <nav id="navbar" class="navbar">
                <ul>
                
                    <li><RouterLink to="/">Home</RouterLink></li>
                    <li> <RouterLink to="/about">About</RouterLink></li>
                    <li><a class="nav-link scrollto" href="#about">Elite Four</a></li>
                    <li><a class="nav-link scrollto" href="#services">Gym Leader</a></li>
                <li><a class="nav-link scrollto" href="#portfolio">Idol Sky</a></li>
                <li><a class="nav-link scrollto" href="#team">Pokemon Trainer</a></li>
                <!-- <li class="dropdown"><a href="#"><span>Drop Down</span> <i class="bi bi-chevron-down"></i></a>
            <ul>
              <li><a href="#">Drop Down 1</a></li>
              <li class="dropdown"><a href="#"><span>Deep Drop Down</span> <i class="bi bi-chevron-right"></i></a>
                <ul>
                  <li><a href="#">Deep Drop Down 1</a></li>
                  <li><a href="#">Deep Drop Down 2</a></li>
                  <li><a href="#">Deep Drop Down 3</a></li>
                  <li><a href="#">Deep Drop Down 4</a></li>
                  <li><a href="#">Deep Drop Down 5</a></li>
                </ul>
              </li>
              <li><a href="#">Drop Down 2</a></li>
              <li><a href="#">Drop Down 3</a></li>
                  <li><a href="#">Drop Down 4</a></li>
                </ul>
              </li> -->
                    <li><a class="nav-link scrollto" href="#contact">Hội đồng Gym Leader</a></li>
                    <li><a class="getstarted scrollto" href="#about">Phòng Thí Nghiệm</a></li>
                </ul>
                <i class="bi bi-list mobile-nav-toggle"></i>
            </nav><!-- .navbar -->

        </div>
    </header><!-- End Header -->
    
</template>