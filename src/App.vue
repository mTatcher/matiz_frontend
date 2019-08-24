<template>
    <div id="app">
        <b-navbar toggleable="lg" type="dark" variant="info">
            <b-container>
                <b-navbar-brand href="#">Матиз-сервис Краснодар</b-navbar-brand>
                <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
                <b-collapse id="nav-collapse" is-nav>
                    <b-navbar-nav class="ml-auto">
                        <b-nav-item href="#about">О нас</b-nav-item>
                        <b-nav-item href="#services">Виды работ</b-nav-item>
                        <b-nav-item href="#grands">Преимущества</b-nav-item>
                        <b-nav-item href="#teh">Техобслуживание</b-nav-item>
                        <b-nav-item href="#otziv">Отзывы</b-nav-item>
                        <b-nav-item href="#contact">Контакты</b-nav-item>
                    </b-navbar-nav>
                </b-collapse>
            </b-container>
        </b-navbar>
        <b-container fluid class="text-center header">
            <b-row align-v="center">
                <b-col sm="12">
                    <h1>Рады Вас приветствовать</h1>
                </b-col>
            </b-row>
            <b-row align-v="center">
                <b-col sm="12">
                    <p class="lead">В лучшем сервисе специализирующемся на обслуживании Daewoo Matiz</p>
                </b-col>
            </b-row>
        </b-container>
        <b-container fluid class="section" id="about">
            <About/>
        </b-container>
        <b-container fluid class="section bg-light" id="services">
            <Services/>
        </b-container>
        <b-container fluid class="section" id="grands">
            <Grands/>
        </b-container>
        <b-container fluid class="section bg-light" id="teh">
            <Teh/>
        </b-container>
        <b-container fluid class="section" id="otziv">
            <Otziv/>
        </b-container>
        <b-container fluid class="section bg-light" id="contact">
            <Contact/>
        </b-container>
        <b-container fluid class="footer bg-dark">
            <b-container>
                <p class="text-center text-white">
                    Copyright © матиз-сервис.рф 2019
                </p>
            </b-container>
        </b-container>
    </div>
</template>

<script>
    import About from './components/About.vue';
    import Services from './components/services.vue';
    import Grands from './components/grands.vue';
    import Teh from './components/teh.vue';
    import Otziv from './components/otziv.vue';
    import Contact from './components/contact.vue';
    export default {
        components: {
            About,
            Services,
            Grands,
            Teh,
            Otziv,
            Contact,
        },
        name: 'app',
    };
</script>

<style>
    h2, .h2 {
        font-size: 2rem;
    }
    h1, .h1 {
        font-size: 2.5rem;
    }
    h1, h2, h3, h4, h5, h6, .h1, .h2, .h3, .h4, .h5, .h6 {
        margin-bottom: 0.5rem;
        font-family: inherit;
        font-weight: 500;
        line-height: 1.2;
        color: inherit;
    }
    .header{
        padding: 154px 0 100px;
        height: 600px;
        background: url(img/matiz-top.jpg);
        background-position: center;
        background-repeat: no-repeat;
        background-size: auto;
        background-color: white;
        color: white;
        text-shadow: 1px 1px 2px black;
    }
    .lead {
        font-size: 1.25rem;
        font-weight: 300;
    }
    .section {
        padding: 150px 0;
    }
    .footer {
        padding: 30px 0;
    }
</style>
