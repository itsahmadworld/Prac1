<template>
 <header class="header">
    <nav>
        <div class="nav-inner">
            <div class="logo">
                <router-link to="/">
                   LOGO
                </router-link>
            </div>
            <div class="inner-nav">
                <RouterLink to="/Car">Car</RouterLink>
                <RouterLink to="/Bike">Bike</RouterLink>
                <RouterLink to="/Health">Health</RouterLink>
                <RouterLink to="/Travel">Travel</RouterLink>
                <RouterLink to="/Global">Global Travel Insurance</RouterLink>
                <RouterLink to="/Group">Group Health</RouterLink>
                <RouterLink to="/Takaful">Takaful</RouterLink>
            </div>
            <div class="sidenav">
                <RouterLink to="/Contact">1234567890</RouterLink>
            </div>
        </div>
    </nav>
</header>

</template>

<script>
</script>

<style >

.header {
    background-color: #C9DFFF;
}
nav .nav-inner {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    width: 100%;
    margin: auto;
}
.logo {
    padding: 20px;
}
.nav .nav-inner {
    background-color: #C9DFFF;
    position: fixed;
    top: 0;
    left: 0;
    height: 80px;
    display: flex;
    align-items: center;
    cursor: pointer;
}
.inner-nav a {
    text-decoration: none;
    color: #2a3b8f;
    font-size: 20px;
    padding: 0 15px;
}
.sidenav a {
    text-decoration: none;
    color: #2a3b8f;
    font-size: 15px;
    padding-right: 35px;
}

.inner-nav a{
    text-decoration: none; 
    color: #2a3b8f; 
    font-size: 20px;
}
.sidenav a {
    text-decoration: none; 
    color: #2a3b8f;
}
</style>