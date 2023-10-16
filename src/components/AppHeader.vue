<template lang="">
    <header>

            <!--UPPER HEADER-->
        <div class="upper-header">
            <img class="header-logo" src="https://logos-world.net/wp-content/uploads/2020/12/Nespresso-Logo-700x394.png" alt="Logo Of Nespresso">
            <div class="upper-items">
                <div>
                    <a href="">
                        CERCA
                    </a>
                </div>
                <div>
                    <a href="">
                        ACCEDI
                    </a>
                </div>
                <div>
                    <a href="">
                        CARRELLO
                    </a>
                </div>

            </div>
        </div>

        <!--LOWER HEADER-->
        <nav class="lower-header">
            <ul>
                <li>
                    <a href="">
                        Caffè
                    </a>
                </li>
                <li>
                    <a href="">
                        Macchine
                    </a>
                </li>
                <li>
                    <a href="">
                        Accessori
                    </a>
                </li>
                <li>
                    <a href="">
                        Easy
                    </a>
                </li>
                <li>
                    <a href="">
                        Promozioni
                    </a>
                </li>
                <li>
                    <a href="">
                        Ricette
                    </a>
                </li>
                <li>
                    <a href="">
                        Sostenibilità
                    </a>
                </li>
                <li>
                    <a href="">
                        Assistenza
                    </a>
                </li>
                <li>
                    <a href="">
                        Dove siamo
                    </a>
                </li>
                <li>
                    <a href="">
                        Professional
                    </a>
                </li>


            </ul>
        </nav>
    </header>
</template>

<script>
export default {
    data() {
        return {
            links: [
                {
                    route: 'caffè',
                    name: 'Caffè'
                },
                {
                    route: 'macchine',
                    name: 'Macchine'
                },
                {
                    route: 'accessori',
                    name: 'Accessori'
                },
                {
                    route: 'easy',
                    name: 'Easy'
                },
                {
                    route: 'promozioni',
                    name: 'Promozioni'
                },
                {
                    route: 'ricette',
                    name: 'Ricette'
                },
                {
                    route: 'sostenibilità',
                    name: 'Sostenibilità'
                },
                {
                    route: 'assistenza',
                    name: 'Assistenza'
                },
                {
                    route: 'dove',
                    name: 'Dove siamo'
                },
                {
                    route: 'professional',
                    name: 'Professional'
                },
            ]
        }
    },
}
</script>

<style scoped lang="scss">
@use '../styles/general.scss' as*;


    header{
        height: 160px;
        background-color: white;
        color: black;

        .upper-header{
            display: flex;
            justify-content: space-between;
            width: 996px;
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
                }

            }
        }

        .lower-header{
            height: 80px;
            // background-color: blue;
            width: 996px;
            margin: 0 auto;
            text-align: center;

            ul{
                display: flex;
                align-items: center;
                height: 100%;
                justify-content: space-evenly;
                width: 100%;
                padding-right: 2rem;

                li{
                    list-style-type: none;
                }
            }
        }

    }
</style>