<template>
    <div id="hero-sign-up-btn-ctn">
        <RouterLink to="/">
            <button id="hero-sign-up-btn">
                Get started now
            </button>
        </RouterLink>
    </div>
</template>

<style scoped>
#hero-sign-up-btn-ctn{
    background-color: transparent;
    display: flex;
    justify-content: center;
}
#hero-sign-up-btn{
    background-color: rgb(0, 0, 0);
    color:#ffffff;
    text-transform:capitalize;
    padding: 1vh 2vh;
    border: 0.2vh solid #000000;
    border-radius:20vh;
}
</style>