<template>
    <section>
        <footer class="footer">
            <!-- logo -->
            <div>
                <li class="logo">Logo</li>
            </div>
            <!-- contact -->
            <div>
                <ul class=nav-items>
                    <li>
                        <a href="#">+27 21 555 5555</a>
                    </li>
                    <li>
                        <a href="#">info@hellocomputer.com</a>
                        
                    </li>
                </ul>
            </div>
            <!-- social Icons -->
            <div>
                <ul class="nav-items">
                    <li><a href="#">Twitter</a></li>
                    <li><a href="#">FB</a></li>
                    <li><a href="#">Instagram</a></li>
                </ul>
            </div>
        </footer>
    </section>
</template>


<style scoped>

    .footer {
        width: 100%;
        height: 60px;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .logo {
    width: 25%;
    list-style: none;
    }

    .nav-items {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: transparent;
    /* width: 80%; */
    }

    .nav-items a {
    text-decoration: none;
    color: black;
    font-size: 10px;
    padding: 2px;
    }


</style>

