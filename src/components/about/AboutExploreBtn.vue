<template>
    <div class="about-explore-btn-ctn">
        <RouterLink to="">
            <button id="about-explore-btn">
                explore features
            </button>
        </RouterLink>
    </div>
</template>

<style scoped>
.about-explore-btn-ctn{
}
#about-explore-btn{
    background-color: #000000;
    color: #ffffff;
    font-size:1.6vh;
    font-family: "Roboto Condensed", sans-serif;
    font-weight: 400;
    padding: 0.2vh 3vh;
    text-transform: capitalize;
    border: 0.2vh solid #000000;
    border-radius: 20vh;
}
#about-explore-btn:hover{
    cursor: pointer;

}
</style>