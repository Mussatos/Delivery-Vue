<script setup>
import Button from "@/components/utils/Button.vue"
import SecondButton from "@/components/utils/SecondButton.vue"
import { RouterLink } from 'vue-router'


</script>


<template>

    <main>
        <img class="logo-img" src="../assets/img/logo.png" alt="logo">

        <div class="cta-container">
            <img class="splash-img" src="../assets/img/box.png" alt="">
            <h1>Non-Contact Deliveries</h1>
            <p>When placing an order, select the option “Contactless delivery” and the courier will leave your order at the door.
</p>

            <div class="action-container">
                <RouterLink to="/home">
                <Button title="order now"></Button>
                </RouterLink>
            </div>

            <div class="button2">
                <RouterLink to="/home">
                <SecondButton title="dismiss"></SecondButton>
                </RouterLink>
            </div>
            
            

        </div>

    </main>

</template>


<style scoped>

main{
    background: url("../assets/img/bg-img.png");
    height: 100vh;
    background-color: #a259ff;
}

.splash-img{
    height: 104px;
    width: 104px;
}

.logo-img{
    padding-top: 2rem;
}

.cta-container{
    background-color: #F6F5F5;
    padding: 2rem;
    border-radius: 24px 24px 0 0;
    height: calc(100vh - 145px);
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;

}

h1{
    margin-top: 24px;
    text-align: center;
    font-size: 34px;
    font-weight: bold;
    color: #2D0C57;
    line-height: 40px;
}

p{
    text-align: center;
    color: #9586A8;
    font-size: 16px;
    margin-top: 12px;

}

.action-container{
    margin-top: 8px;
    width: 100%;
}

</style>