<script setup>
import reviewCustomerDetails from "@/data/review-customer-details.json";
import ReviewCustomer from './ReviewCustomer.vue';
</script>

<template>
    <div class="review-customer-ctn">
        <div class="review-customer-main-ctn">
            <div 
                v-for="reviewCustomerDetail in reviewCustomerDetails"
                :key="reviewCustomerDetail.id"
                class="review-customer-mini-ctn"
            >
                <ReviewCustomer
                    :name="reviewCustomerDetail.name"
                    :desc="reviewCustomerDetail.desc"
                >
                </ReviewCustomer>
            </div>
        </div>
    </div>
</template>

<style scoped>
.review-customer-ctn{
    display: flex;
    justify-content: right;
    padding: 3vh 0;
}
.review-customer-main-ctn{
    width: 45%;
    display: flex;
    flex-direction: column;
    gap:6vh;
}

@media screen and (max-width:990px) and (min-width:346px){
    .review-customer-main-ctn{
        width: 100%;
        
    }
}
</style>