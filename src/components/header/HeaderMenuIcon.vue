<template>
    <div class="header-menu-icon">
        <i class="ri-menu-4-line"></i>
        <!-- <i class="ri-close-large-line"></i> -->
    </div>
</template>

<style scoped>
.header-menu-icon{
    font-size: 5vh;
    display: flex;
    place-items: center;
    display: none;
}
@media screen and (max-width:990px) {
    .header-menu-icon{
        display:flex;
    }
}
</style>