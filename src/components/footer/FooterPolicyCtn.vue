<script setup>
const policies=[
    {
        "id":"1",
        "name":"Terms and Conditions"
    },
    {
        "id":"2",
        "name":"privacy policy"
    },
    {
        "id":"3",
        "name":"refund policy"
    },
    {
        "id":"4",
        "name":"accessibility statement"
    }
]
</script>

<template>
    <div class="footer-policy-ctn">
        <div class="footer-policy-mini-ctn" v-for="policy in policies" :key="policy.id">
            <div class="footer-policy-major-ctn">
                <RouterLink to="">
                    <p class="footer-policy">
                        {{ policy.name }}
                    </p>
                </RouterLink>
            </div>
        </div>
    </div>
</template>

<style scoped>
.footer-policy-mini-ctn{
    margin-bottom: 1vh;
}
.footer-policy{
    text-transform: capitalize;
}

@media screen and (max-width:990px) {
    .footer-policy-ctn{
        text-align: center;
    }
}
</style>