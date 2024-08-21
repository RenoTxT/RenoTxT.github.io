<script setup>
    
</script>

<template>
    <nav class="navbar navbar-expand-lg bg-black fixed-top">
        <div class="container-fluid">
            <a class="navbar-brand me-auto" href="#"><img src="../assets/logo.png" alt="logo" height="70vh" class="a-inline-block align-text-center rnz-text-logo">Kana Group</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                <div class="navbar-nav">
                    <a class="nav-link active" aria-current="page" href="#" id="btnA">Home</a>
                    <a class="nav-link" href="#portofolio" id="btnB">Portofolio</a>
                    <a class="nav-link" href="#about" id="btnC">About</a>
                    <a class="nav-link" href="#contact" id="btnD">Contact</a>
                </div>
            </div>
        </div>
    </nav>
</template>

<style scoped>
    .navbar {
    height: 80px;
    margin: 1vh;
    border-radius: 16px;
    padding: 0.5rem;
}

.navbar-brand{
    padding-left: 5vw;
    font-weight: 500;
    color: rgb(238, 238, 238);
    height: 50;
    transition: 0.3s color;
}

.navbar-brand:hover{
    color: #c647f4;
}

.nav-link.active{
    color: #c647f4;
}

.navbar-toggler{
    border: none;
    font-size: 1.25rem;
}

.navbar-toggler:focus, btn-close:focus{
    box-shadow: none;
    outline: none;
}

.nav-link {
    color: #ffffff;
    font-weight: 500;
    position: relative;
}

.nav-link:hover, .nav-link.active{
    color: #c647f4 !important;
}

#navbarNavAltMarkup{
    justify-content: end;
    background-color: #000000;
    text-align: center;
}

.navbar-brand{
    padding-top: 0;
}

.navbar-nav .nav-link.active {
    color: #c647f4 !important; /* Change the color to red */
}
.navbar-nav .nav-link.active:hover {
    color: #c647f4 !important; /* Ensure hover state also displays red */
}

.nav-link.active {
    color: #c647f4 !important; /* Example color */
}

@media (min-width: 991px){
    .nav-link::before{
        content:"";
        position: absolute;
        bottom: 0;
        left: 50%;
        transform: translateX(-50%);
        width: 0;
        height: 2px;
        background-color: #c647f4;
        visibility: hidden;
        transition: 0.3s ease-in-out;
    }

    .nav-link:hover::before, nav-link.active::before{
        width: 100%;
        visibility: visible;
    }
}

</style>
