<template lang="">
    <header>

            <!--UPPER HEADER-->
        <div class="upper-header">
            <img class="header-logo" src="https://logos-world.net/wp-content/uploads/2020/12/Nespresso-Logo-700x394.png" alt="Logo Of Nespresso">
            <div class="upper-items">
                <div>
                    <a href="">
                        1
                    </a>
                </div>
                <div>
                    <a href="">
                        2
                    </a>
                </div>
                <div>
                    <a href="">
                        3
                    </a>
                </div>

            </div>
        </div>

        <!--LOWER HEADER-->
        <div class="lower-header">
        </div>
    </header>
</template>

<script>
export default {
    data() {
        return {
            links: [

            ]
        }
    },
}
</script>

<style scoped lang="scss">
    header{
        height: 160px;
        background-color: white;
        color: black;

        .upper-header{
            display: flex;
            justify-content: space-between;
            width: 996px;
            background-color: red;
            margin: 0 auto;

            img.header-logo{
                height: 80px
            }

            div.upper-items{
                display: flex;
                height: 80px;
                align-items: center

            }
        }

    }
</style>