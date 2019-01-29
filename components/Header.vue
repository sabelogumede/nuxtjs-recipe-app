<template>
    <section>
    
        <header class="header">
            <!-- logo -->
            <div class="logo">
                <h1>Logo</h1>
            </div>
            <!-- nav -->
            
                <ul class="nav-items">
                    <li>
                        <nuxt-link to="/">Intro</nuxt-link>
                    </li>
                    <li>
                        <nuxt-link to="/recipe">Recipe</nuxt-link>
                    </li>
                    <li>
                        <nuxt-link to="/gallery">Gallery</nuxt-link>
                    </li>
                    <li>
                        <nuxt-link to="/contact">Contact</nuxt-link>
                    </li>
                </ul>
            
            
            
        </header>
    </section>
    
</template>

<style scoped>


.header {
    width: 100%;
    height: 60px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.logo {
    width: 25%
}

.nav-items {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: transparent;
    width: 30%;
}

.nav-items a {
    text-decoration: none;
    color: black;
    font-size: 11px;
    padding: 2px;
}

.nav-items a:hover,
.nav-items a:active {
    border-bottom: black solid 1px; 
}

</style>

