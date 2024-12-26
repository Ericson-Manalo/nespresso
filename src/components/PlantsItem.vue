<template lang="">
 <!-- //fare 3 card
    //1.piante interno
    //2. piante esterno
    //3. vasi e arredi -->

    <h2 class="spacing-class">
        Scopri i nostri prodotti!
    </h2>

    <div class="row item-card spacing-class">
        <div class="single-card col-12 col-md-6 col-lg-3">1</div>
        <div class="single-card col-12 col-md-6 col-lg-3">2</div>
        <div class="single-card col-12 col-md-6 col-lg-3">3</div>
        <div class="single-card col-12 col-md-6 col-lg-3">4</div>
    </div>

</template>
    
<script>
    export default {
    };
</script>
    
<style scoped lang="scss">

h2{
    text-transform: uppercase;
}

div.item-card{
    display: flex;
    justify-content: center;
    text-align: center;
    gap: 10px;

    div.single-card{
        height: 350px;
        border: 1px solid #f2f2f2;
        width: 250px;
    }
}

</style>
    