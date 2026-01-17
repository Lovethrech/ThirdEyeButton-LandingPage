<template>
    <div 
        id="header-client-btn-main-ctn"
    >
        <a 
            href=""
        >
            <button 
                id="header-client-btn"
            >
                log in as client
            </button>
        </a>
    </div>
</template>

<style scoped>
#header-client-btn-main-ctn{
    background-color: transparent;
    margin: auto 0;
    display:flex;
    justify-content: center;
    place-items: center;
}
#header-client-btn{
    font-size: 1.6vh;
    background-color: #000000;
    color:#ffffff;
    text-transform: capitalize;
    padding:1vh 2vh;
    border: 0.2vh solid #000000;
    border-radius:20vh;
}
#header-client-btn:hover{
    cursor: pointer;
    background-color: transparent;
    color: #000000;    
    transition: all .5s;
}
</style>