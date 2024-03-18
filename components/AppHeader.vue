<!-- components/Header.vue -->
<template>
    <!-- <header>
        <nav>
            <NuxtLink to="/kapcsolat">kapcsolat</NuxtLink>
        </nav>
    </header> -->
    <header class="header">
        <div class="header-content d-flex">
            <div class="logo-box  header-content__logo-box">
                <a href="/" class="header-content__logo-box__link">
                    <img class="header-content__logo-box__link__img" src="/img/header/logo.svg" alt="Biztos Alkuszom">
                </a>
            </div>
            <div class="nav-box header-content__nav-box">
                <div class="hamburger position-relative" id="hamburger">
                    <div class="bar"></div>
                    <div class="bar"></div>
                    <div class="bar"></div>
                </div>
                <nav class="menu">
                    <ul class="menu__list d-flex" id="menu__list">
                        <li class="menu__list__li">
                            <a class="menu__item menu__item--border-left text-color text-transform-uppercase"
                                href="#">Főoldal</a>
                        </li>
                        <li class="menu__list__li">
                            <a class="menu__item text-color text-transform-uppercase" href="#">Partnerek</a>
                        </li>
                        <li class="menu__list__li">
                            <a class="menu__item text-color text-transform-uppercase" href="#">Szolgáltatások</a>
                        </li>
                        <li class="menu__list__li">
                            <a class="menu__item text-color text-transform-uppercase" href="#">Szolgáltatások</a>
                        </li>
                        <li class="menu__list__li">
                            <a class="menu__item text-color text-transform-uppercase" href="#">Ajánlatkérés</a>
                        </li>
                        <li class="menu__list__li">
                            <a class="menu__item text-color text-transform-uppercase" href="#">Kapcsolat</a>
                        </li>
                        <li class="menu__list__li menu__list__li-facebook-link">
                            <a class="menu__item text-color text-transform-uppercase" href="#">
                                <img class="menu__list__li-facebook-link__img" src="/img/header/facebook.svg"
                                    alt="Biztos Alkuszom">
                            </a>
                        </li>
                    </ul>
                </nav>
            </div>
        </div>
        <div class="header-bottom d-flex">
            <div class="header-bottom__div">
                <h1 class="header-bottom__div__h1 text-color-w text-transform-uppercase">ÁGOSTON GÁBOR - <span
                        class="header-bottom__div__span">Az Ön
                        alkusza</span>
                </h1>
            </div>
            <div class="header-bottom__div header-bottom__div-linkbox">
                <a class="header-bottom__div-linkbox__link text-color-w" href="tel:+36302345866">
                    <img class="header-bottom__div-linkbox__link__img position-relative" src="/img/header/mobile.svg"
                        alt="Biztos Alkuszom">06 30 234 5866
                </a>
                <a class="header-bottom__div-linkbox__link text-color-w" href="mailto:biztos@alkuszom.info">
                    <img class="header-bottom__div-linkbox__link__img header-bottom__div-linkbox__link__img--margin-left position-relative"
                        src="/img/header/mail.svg" alt="Biztos Alkuszom">biztos@alkuszom.info
                </a>
            </div>
        </div>
    </header>
</template>
