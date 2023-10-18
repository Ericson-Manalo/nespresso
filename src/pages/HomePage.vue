<template lang="">
    <section>
        <div class="col jumbotron">
            <div class="jumbotron-content">
                <h1>
                    "You can plant a dream"
                </h1>
            </div>
        </div>
        <div class="row text-center">
            <div class="col-lg-3 col-md-6 col-sm-12">
                <div class="">
                    <i class="fa-solid fa-truck-fast"></i>
                    <h2>
                        guaranteed shipping
                    </h2>
                </div>
            </div>
            <div class="col-lg-3 col-md-6 col-sm-12">
                <div>
                    <i class="fa-solid fa-handshake"></i>
                </div>
                <h2>
                    reliability
                </h2>
            </div>
            <div class="col-lg-3 col-md-6 col-sm-12">
                <div>
                    <i class="fa-solid fa-leaf"></i>
                </div>
                <h2>
                    eco-friendly packaging
                </h2>
            </div>
            <div class="col-lg-3 col-md-6 col-sm-12">
                <div>
                    <i class="fa-solid fa-users-line"></i>
                </div>
                <h2>
                    earnest company
                </h2>
                
            </div>
        </div>
    </section>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>

section{
    width: 100%;

    div.jumbotron{
        background-image: url('https://media.architecturaldigest.com/photos/5dcde00380598800086215f6/16:9/w_2560%2Cc_limit/Osofsky_Oct19-5.jpg');
        height: 700px;
        background-position: 50%;
        background-size: cover;
        width: 100%;
        position: relative;
        filter: grayscale(40%);


        div.jumbotron-content{
            position: absolute;
            width: 650px;
            // background-color: red;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            text-align: center;
            color: white;

            h1{
                font-size: 5rem;
                letter-spacing: .125rem;
                text-shadow: #2d531e 1px 0 10px;
            }
        }

        
    }

    div.row{
        margin-top: 3rem;
        
    }


}




</style>