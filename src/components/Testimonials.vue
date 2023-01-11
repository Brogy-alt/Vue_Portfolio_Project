<template>
     <section class="container">

    
     <!-- Cards -->
     <center>
<!-- <div class="cards pt-5"> -->
    <h2 class="text-center">Testimonial</h2>
            <div style="display: grid; grid-template-columns: repeat(3, 1fr); margin: auto;">
            <div class="card h-100" v-for="list in items" :key="list" style="height: 20rem; grid-column: span 1; margin: auto;">
                <img :src="list.img" class="card-img-top" style="height: 25rem" loading="lazy" alt="Profile img"/>
                <div class="card-body bg-dark">
                    <h5 class="card-title text-center">{{list.Person}}</h5>
                    <p>
                       {{list.Comment}}
                    </p>

                </div>
            </div>
        </div>
        
</center>
</section>



</template>
<script>
export default {
    name : 'Testimonials',

    data(){
        return {
            items : [
                {
                    img : 'https://i.postimg.cc/GhSShNPq/t1.jpg',
                    Person : 'Meezaan',
                    Comment : ' Brogan has a really bright and innovative mind when it comes to the design of his projects. Brogan to the eye is very introverted but once he opens up he is totally the opposite.',

                },
                {
                    img : 'https://i.postimg.cc/T3h9Mgd5/t0.jpg',
                    Person : 'Imraan',
                    Comment : ' Brogan has a good judge of character, he is a very friendly person to be around.He is also very passionate about his music producing, I view him as a smart and knowledgeable guy.',

                },
                {
                    img : '',
                    Person : 'Lazola',
                    Comment : 'Brogan likes learning new stuff, he is a team player and he is someone who is always on time. I can assure you that he can be a great asset to your company',

                },
                {
                    img : '',
                    Person : 'Joel Mukanya (Lecturer)',
                    Comment : 'Brogan is a very creative, go-getter, and well-behaved student. He does He has gained knowledge of web development, including Bootstrap 5',

                },
                {
                    img : '',
                    Person : 'Asandile',
                    Comment : 'Brogan is a sweet guy that knows how to stick to the task at hand and is willing to help where he can. He isreliable and he is full of ambition and drive. He loves his space and he is respectful towards others.',

                }
            ]
            }
        }
}

</script>
<style>
    
</style>