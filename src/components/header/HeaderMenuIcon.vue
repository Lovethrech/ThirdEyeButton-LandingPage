<template>
    <div 
        class="header-menu-icon"
    >
        <i 
            class="ri-menu-4-line"
        >
        </i>
        <!-- <i class="ri-close-large-line"></i> -->
    </div>
</template>

<style scoped>
.header-menu-icon{
    font-size: 4vh;
    display: flex;
    place-items: center;
    display: none;
}
@media screen and (max-width:990px) {
    .header-menu-icon{
        display:flex;
    }
}

@media screen and (width: 1024px) and (min-height:1360px) {
    .header-menu-icon{
        display:flex;
    }
}
</style>