<template>
<div class="navbar__wrapper">
    <section>
            <nav class="navbar fixed-top navbar-expand-lg navbar-light header">
            <div class="container">
                <a class="navbar-brand" href="https://www.linkedin.com/in/viktor-shostak-617b0b155/"><Logo/></a>
                <button
                    class="navbar-toggler"
                    type="button"
                    data-bs-toggle="collapse"
                    data-bs-target="#navbarNavAltMarkup"
                    aria-controls="navbarNavAltMarkup"
                    aria-expanded="false"
                    aria-label="Toggle navigation"
                >
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                    <div class="navbar-nav">
                        <NuxtLink class="nav-link" :to="'/'">Home</NuxtLink>
                        <NuxtLink class="nav-link" :to="'/carpet'">Carpets</NuxtLink>
                        <NuxtLink class="nav-link" :to="'/realty'">Realty</NuxtLink>
                        <NuxtLink class="nav-link" :to="'/technic'">Technic</NuxtLink>
                        <NuxtLink class="nav-link" :to="'/about'">About</NuxtLink>
                    </div>
                </div>
            </div>
        </nav>
    </section>
<Nuxt/>
</div>
    
</template>