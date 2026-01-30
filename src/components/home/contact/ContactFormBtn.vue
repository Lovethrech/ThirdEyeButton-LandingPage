<template>
    <div 
        class="contact-form-btn-ctn"
    >
        <a 
            href="" 
            target="_blank" 
            rel="noopener noreferrer" 
            id="contact-form-btn-link"
        >
            <button 
                class="contact-form-btn"
            >
                Submit
            </button>
        </a>
    </div>
</template>

<style scoped>
.contact-form-btn-ctn{
    width: 100%;    
}
.contact-form-btn{
    width: 100%;
    background-color: #000000;
    font-family: "Cormorant Unicase", serif;
    letter-spacing:1vh;
    color: #ffffff;
    padding: 1vh 1vw;
    font-size: 1.8vh;
    border-radius: 20vh;
}
.contact-form-btn:hover{
    cursor: pointer;
    transform: scale(0.98);
    transition: all .4s;
}
</style>