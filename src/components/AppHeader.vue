<template lang="">
    <header>
        <div class="header-container">
            <img class="header-logo" src="https://logos-world.net/wp-content/uploads/2020/12/Nespresso-Logo-700x394.png" alt="Logo Of Nespresso">
            <div class="upper-items">
                <div>1</div>
                <div>2</div>
                <div>3</div>
            </div>
        </div>
    </header>
</template>

<script>
export default {
    
}
</script>

<style scoped lang="scss">
    header{
        height: 200px;
        background-color: white;
        color: black;

        .header-container{
            display: flex;

            img.header-logo{
                height: 90px
            }

            div.upper-items{
                display: flex;
                height: 90px;
                align-items: center
            }

            
        }
    }
</style>