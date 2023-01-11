<template>
     <!-- Cards -->
     <center>

<section class="cards pt-5">
    <h2 class="text-center">Testimonial</h2>
    <div class="row row-cols-1 row-cols-md-2 g-4 pt-5">
        <div class="card-item col">
            <div class="card w-50 h-50" v-for="list in items" :key="list">
                <img src="/Assets/Images/Meezaan.JPG" class="card-img-top" loading="lazy" alt="Profile img" />
                <div class="card-body bg-dark">
                    <h5 class="card-title text-center">{{list.Person}}</h5>
                    <p>
                       {{ list.Comment }}
                    </p>
                </div>
            </div>
        </div>
        <div class="col">
            <div class="card w-50 h-50">
                <img src="/Assets/Images/Imraan.jpg" class="card-img-top" loading="lazy" alt="Profile img" />
                <div class="card-body bg-dark">
                    <h5 class="card-title text-center">Imraan</h5>
                    <p class="card-text">
                        Brogan has a good judge of character, he is a very friendly person to be
                        around.
                        He is also very passionate about his music producing, I view him as a smart
                        and knowledgeable guy.
                    </p>
                </div>
            </div>
        </div>
        <div class="col">
            <div class="card w-50 h-50">
                <img src="/Assets/Images/Lazola.JPG" class="card-img-top" loading="lazy" alt="Profile img" />
                <div class="card-body bg-dark">
                    <h5 class="card-title text-center">Lazola</h5>
                    <p class="card-text">Brogan likes learning new stuff, he is a team player and he is someone
                        who
                        is always on time. I can assure you that he can be a great asset to your
                        company</p>
                </div>
            </div>
        </div>
        <div class="col">
            <div class="card w-50 h-50">
                <img src="/Assets/Images/JoelProfile.jpg" class="card-img-top" loading="lazy"
                    alt="Profile img" />
                <div class="card-body bg-dark">
                    <h5 class="card-title text-center">Joel Mukanya (Lecturer)</h5>
                    <p class="card-text">Brogan is a very creative, go-getter, and well-behaved student. He does
                        enjoy working with his classmates and works well on his project.
                        He has gained knowledge of web development, including Bootstrap 5.</p>
                </div>
            </div>
        </div>
        <div class="col">
            <div class="card w-50 h-50">
                <img src="/Assets/Images/Asandile.JPG" class="card-img-top" loading="lazy" alt="Profile img" />
                <div class="card-body bg-dark">
                    <h5 class="card-title text-center">Asandile</h5>
                    <p class="card-text">
                        Brogan is a sweet guy that knows how to stick to the task at hand and is willing to help
                        where
                        he can. He is
                        reliable and he is full of ambition and drive. He loves his space and
                        he is respectful towards others.

                    </p>
                </div>
            </div>
        </div>
    </div>
</section>
</center>

</template>
<script>
export default {
    name : 'Testimonials'
    
    
    data(){
        return {
            items : [
                {
                    img : '',
                    Person : 'Meezaan',
                    Comment : ' Brogan has a really bright and innovative mind when it comes to the design of his projects. Brogan to the eye is very introverted but once he opens up he is totally the opposite.',

                }


            ]
            }
        }
}

</script>
<style lang="">
    
</style>