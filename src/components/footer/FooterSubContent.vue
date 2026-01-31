<template>
    <div 
        class="footer-sub-content"
    >
        <p 
            class="footer-sub-title"
        >
            Stay tuned
        </p>
        <form action="" class="footer-sub-content-form">
            <div class="footer-sub-content-form-email-ctn">
                <label 
                    for="email" 
                    class="footer-sub-content-form-email-label"
                >
                    Email*:
                </label>
                <input 
                    type="email" 
                    class="footer-sub-content-form-email-input"
                    required
                >
            </div>
            <div class="footer-sub-content-form-checkbox-ctn">
                <input 
                    type="checkbox" 
                    class="footer-sub-content-form-checkbox-input"
                    required
                >
                <label 
                    for="email" 
                    class="footer-sub-content-form-checkbox-label"
                >
                    Yes, subscribe me to your newsletter. 
                </label>
            </div>
            <div 
                class="footer-form-btn-ctn"
            >
                <a 
                    href="" 
                    target="_blank" 
                    rel="noopener noreferrer" 
                    id="footer-form-btn-link"
                >
                    <button 
                        class="footer-form-btn"
                    >
                        Submit
                    </button>
                </a>
            </div>
        </form>
    </div>
</template>

<style scoped>
.footer-sub-content{
    width:40%;
    display: flex;
    flex-direction: column;
    gap:2vh;
}
.footer-sub-title{
    font-size: 2.5vh;
    font-family: "Cormorant Unicase", serif;
    font-optical-sizing: auto;
    font-weight: 400;
    text-transform: capitalize;
}
.footer-sub-content-form-email-ctn{
    display: flex;
    flex-direction: column;
}
.footer-sub-content-form-email-input{
    margin: 1vh 0;
    border: 0;
    background: transparent;
    border-bottom: 0.2vh solid #000000;
    padding: 1vh 1vw;
    font-size: 1.6vh;
}
.footer-sub-content-form-email-label, .footer-sub-content-form-checkbox-label{
    font-size: 1.6vh;
    font-family: "Roboto Condensed", sans-serif;
}
.footer-form-btn{
    width: 100%;
    margin-top: 2vh;
    background-color: #000000;
    font-family: "Cormorant Unicase", serif;
    color: #ffffff;
    padding: 1vh 1vw;
    font-size: 1.8vh;
    border-radius: 20vh;
}
.footer-form-btn:hover{
    cursor: pointer;
    transform: scale(0.98);
    transition: all .4s;
}

@media screen and (max-width:990px) {
    .footer-sub-content{
        width: 100%;
    }
    .footer-sub-content-form-checkbox-label{
        font-size: 1.6vh;
    }
}
</style>