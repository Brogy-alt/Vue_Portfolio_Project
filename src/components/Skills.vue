<template>
     <!-- Skills section -->
     <section class="container">
        <div class="skills border border-light border-2">
            <div class="row d-flex flex-column flex-md-row">
                <h2 class="text-center">My Skills</h2>

                <p><i class="fa-brands fa-html5"></i><br>HTML</p>
                <div class>
                    <div class="skills-html">50%</div>
                </div>

                <p><i class="fa-brands fa-css3-alt"></i> <br>CSS</p>
                <div>
                    <div class="skills-css">40%</div>
                </div>

                <p><i class="fa-brands fa-bootstrap"></i> <br>Bootstrap</p>
                <div>
                    <div class="skills-bootstrap">30%</div>
                </div>
            </div>
        </div>

    </section>

</template>
<script>
export default {
    name : 'Skills'
    
}
</script>
<style>

.skills {
    width: 100%;
    height: 20em;
    padding-top: 10px;
    padding-bottom: 10px;
    color: white;
    
}


.skills-html,
.skills-css,
.skills-bootstrap {
    text-align: center;
    
    
}

.skills-html {
    width: 50%;
    background-color: #808080;
    border: solid black;
}

.skills-css {
    width: 30%;
    background-color: #808080;
    border: solid black;
}

.skills-bootstrap {
    width: 40%;
    background-color: #808080;
    border: solid black;
}
    
</style>