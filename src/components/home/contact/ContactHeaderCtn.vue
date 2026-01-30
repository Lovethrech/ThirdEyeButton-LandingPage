<template>
    <div 
        class="contact-header-ctn"
    >
        <h3 
            class="contact-header-title"
        >
            Contact Us
        </h3>
        <p 
            class="contact-header-subtitle"
        >
            Reach Out to ThirdEyeButton
        </p>
        <p 
            class="contact-header-desc"
        >
            Have questions or interested in learning more about our
            <br/>
            default website interface for exam scheduling? Contact us
            <br/>
            today to explore how ThirdEyeButton can elevate you
            <br/>
            university's exam management
        </p>
    </div>
</template>

<style scoped>
.contact-header-ctn{
    display:flex;
    flex-direction: column;
    text-align: center;
}
.contact-header-title{
    font-size: 5vh;
    font-family: "Old Standard TT", serif;
    font-optical-sizing: auto;
    font-weight: 600;
}
.contact-header-subtitle, .contact-header-desc{
    font-size: 1.6vh;
}
.contact-header-subtitle{
    font-family: "Cormorant Unicase", serif;
    letter-spacing: 0.3vh;
    margin:2vh 0;
}
.contact-header-desc{
    font-family: "Roboto Condensed", sans-serif;
    line-height: 4vh;
}

@media screen and (max-width:990px) {

}
</style>