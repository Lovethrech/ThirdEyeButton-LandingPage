<template>
    <div 
        class="hero-text-ctn"
    >
        <p 
            id="hero-text-desc"
        >
            Empower Your University Examination with ThirdEyeButton
        </p>
        <h1 
            id="hero-text-title"
        >
            Revolutionizing
            <br/>
            examination 
            <br/>
            scheduling
        </h1>
    </div>
</template>

<style scoped>
.hero-text-ctn{
    text-align: center;
}
#hero-text-desc{
    font-size: 1.4vh;
}
#hero-text-title{
    font-size: 10vh;
    text-transform: capitalize;
}

@media screen and (max-width:345px) {
    #hero-text-desc{
        font-size: 3vw;
    }
    #hero-text-title{
        font-size: 10vw;
    }
}

@media screen and (max-width:990px) and (min-width:346px){
    #hero-text-desc{
        font-size: 1.4vh;
    }
    #hero-text-title{
        font-size: 6vh;
    }
}

@media screen and (min-height:1360px) {
    #hero-text-desc{
        font-size: 1.4vh;
    }
    #hero-text-title{
        font-size: 6vh;
    }
}
</style>