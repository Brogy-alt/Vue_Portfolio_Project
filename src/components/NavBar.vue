<template>
    <header class="sticky-top">
        <nav class="navbar navbar-expand-lg bg-light text-light ">
            <div class="container-fluid">
                <a class="navbar-brand" href="index.html">
                    <img class="logo" src="https://i.postimg.cc/VLjZH31V/speakerlogo.png" alt="logo" width="60" height="55">
                </a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                    data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent"
                    aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav ms-auto mb-2 mb-lg-0 ">
                        <li class="nav-item">
                            
                            <a class="nav-link active" aria-current="home-nav" href="/"> <i class="fa-sharp fa-solid fa-house-user"></i> Home</a>
                        </li>
                        <a class="nav-link active" aria-current="aboutme-nav" href="/about"> 
 
 
                            <i class="fa-sharp fa-solid fa-folder"></i>About me</a>
                        
                        <a class="nav-link active" aria-current="contact-nav" href="/contact"> <i class="fa-solid fa-phone"></i>Contact & Socials</a>
                        
                        <li class="nav-item">
                            <a class="nav-link"></a>
                        </li>
                    </ul>
                </div>
            </div>
            </nav>
    </header>
</template>
<script>
export default {
    name : 'NavBar'
}
</script>
<style>

head,
main,
footer header,
body,
footer {
    min-width: 100%;
}
    
</style>