<template>
    <nav class="nav">
        <div class="logo"></div>
        <div class="links">
            <g-link
                class="nav__link"
                to="/"
            >
                Home</g-link>
            <g-link
                class="nav__link"
                to="/about/"
            >
                About</g-link>
        </div>
    </nav>
</template>

<style>
.nav {
    display: flex;
    justify-content: space-between;
    /* padding: 20px; */
    position: fixed;
    z-index: 1;
    width: 100%;
    max-width: 1500px;
    background: rgba(255, 255, 255, 0.35);
    padding: 20px 0;
}
.links {
}

.nav__link {
    margin: 20px;
    font-size: 24px;
    text-decoration: none;
    color: black;
}

@media screen and (max-width: 425px) {
    .nav {
        display: none;
    }
}
</style>