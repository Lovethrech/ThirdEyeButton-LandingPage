<template>
    <div 
        id="about-title-ctn"
    >
        <h2 
            id="about-title-name"
        >
            About
            <br/>
            ThirdEyeButton
        </h2>
    </div>
</template>

<style scoped>
#about-title-name{
    font-size:8vh;
    font-family: "Old Standard TT", serif;
    font-optical-sizing: auto;
    font-weight: 500;
}

@media screen and (max-width:345px) {
    #about-title-name{
        font-size: 8vw;
    }
}
@media screen and (max-width:990px) and (min-width:346px){
    #about-title-name{
        font-size: 4vh;
    }
}
</style>