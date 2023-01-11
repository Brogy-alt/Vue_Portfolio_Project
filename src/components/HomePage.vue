<template>
    <main>
        
        <!--Home-->
        <section id="home" class="container min-vh-100">
            <div class="row d-flex flex-column flex-md-row ">
                <div class=" home-text col">
                    <h1 class="name lead ">Brogan Gys</h1>
                    <p class="lead">Aspiring developer</p>
                    <p class="lead">Music producer</p>
                </div>
                <div class="col">
                    <img src="https://i.postimg.cc/Zn4hrwKW/C11-Brogan-Gys-3.jpg" style="max-width: 60%; height: 50;"
                        alt="Brogans Profile" class="rounded mx-auto d-block">
                        <div class="pt-3">
                        <center>
                            <a class="btn btn-lg btn-floating border-light text-light" href="https://www.instagram.com/prodbrogy/" target="_blank" role="button"><i class="fab fa-instagram"></i>
                            </a>
                            <a class="btn btn-lg btn-floating border-light text-light" href="https://twitter.com/_Brogy_ " target="_blank" role="button"><i class="fab fa-twitter"></i>
                            </a>
                            <a class="btn btn-lg btn-floating border-light text-light" href="https://www.youtube.com/channel/UC13tr7mMjdQfZRaoI0rbTgQ" target="_blank" role="button"><i class="fab fa-youtube"></i>
                            </a>
                            
                        </center>
                    </div>
                </div>
            </div>
        </section>



    </main>
</template>

<script>
export default {
    name : 'HomePage'
    
}
</script>


<style>

    section {
    padding: 10px 0rem;
}

#home {
    margin: auto;
    width: 73%;
    height: 100vh;
    padding-top: 10%
    /* margin-top: 10rem; */
}

head,
main,
footer header,
body,
footer {
    min-width: 100%;
}

body {
    background-color: rgba(0, 0, 0, 0.8);
    color: #FDF7FF;
    font-size: 19px;
    font-family: 'Hind Vadodara', sans-serif;
    /* padding: 5rem 1rem; */
    overflow-x: hidden;
}

 h1{
    font-weight: 700;
}

.name {
    font-size: 80px;
    color: #FDF7FF;
    display: flex;
    margin-right: 2rem
}

main {

background: linear-gradient(rgba( 0,0,0,.7), rgba( 0,0,0,.7)) , url(https://i.postimg.cc/Vvh9RJq3/Back3.jpg);
background-repeat: no-repeat;
background-size: cover;
background-position: center;

}
section {
    padding: 10px 0rem;
}

</style>