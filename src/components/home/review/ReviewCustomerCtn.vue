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
                <ReviewCustomer></ReviewCustomer>
            </div>
        </div>
    </div>
</template>