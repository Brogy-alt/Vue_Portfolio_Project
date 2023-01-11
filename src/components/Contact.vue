<template>
    
    <section class="container">
        <div class="contact">
            <h2 class="text-light">Contact me</h2>
            <form action="https://formspree.io/f/xbjbywjp" method="POST"><br>
                <div>
                    <label for="#firstname">Name</label>
                    <input id="firstname" name="firstName" type="text" placeholder="Enter your name" required>
                </div>
                <div>
                    <label for="#surname">Surname</label>
                    <input id="surname" name="surname" type="text" placeholder="Enter your surname" required>
                </div>
                <div>
                    <label for="#message">Message</label>
                    <textarea name="message" cols="45" rows="5" placeholder="Enter your message" required></textarea>
                </div>
                <div class="button">
                    <input type="submit" value="submit">
                </div>
                <br>
            </form>
        </div>
    </section>
   
</template>
<script>
export default {
    name : 'Form'
    
}
</script>
<style>

input[type=submit] {
    color: white;
    background-color: #808080;
    padding: 12px 20px;
    border: none;
    border-radius: 4px;
}

input[type=text] {
    width: 100%;
    padding: 10px 20px;
    margin: 8px 0px;
    box-sizing: border-box;
}

input:hover[type=text] {
    border: none;
    border: 4px;
}


textarea {
    width: 100%;
    height: 150px;
    padding: 12px 20px;
    box-sizing: border-box;
    border-radius: 4px;
    resize: none;
}

textarea:hover {
    border: none;
    box-sizing: border-box;
    border-radius: 4px;

}

    
</style>