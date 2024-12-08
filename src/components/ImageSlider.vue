<template lang="">

</template>

<script>

</script>

<style scoped lang="scss">



    header{
        height: 160px;
        background-color: white;
        // color: black;

        .upper-header{
            display: flex;
            justify-content: space-between;
            max-width: 996px;
            // background-color: red;
            margin: 0 auto;

            img.header-logo{
                height: 80px
            }

            div.upper-items{
                display: flex;
                height: 80px;
                align-items: center;

                div{
                    margin-right: 2rem;

                    a{
                        color: #2f2f2f;
                    }
                }

            }
        }

        .lower-header{
            height: 80px;
            background-color: #2f2f2f;
            // width: 996px;
            color: white;
            margin: 0 auto;
            text-align: center;

            ul{
                display: flex;
                align-items: center;
                height: 100%;
                justify-content: space-evenly;
                padding-right: 2rem;
                width: 100%;
                color: white !important; 


                li{
                    list-style-type: none;

                    a{
                        color: white;

                        &:hover{
                            border-bottom: 2px solid #22684f;
                        }
                    }
                }
            }
        }

    }
</style>