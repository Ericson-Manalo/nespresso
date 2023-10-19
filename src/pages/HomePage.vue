<template lang="">
    <!--========JUMBOTRON SECTION=========-->
    <section>
        <div class="col jumbotron">
            <div class="jumbotron-content">
                <h1>
                    "You can plant a dream"
                </h1>
            </div>
        </div>
    </section>

    <!--========COMPANY SERVICES SECTION=========-->

    <section>
        <div class="row text-center services">
                <div class="col-lg-3 col-md-6 col-sm-12 card-container">
                    <div class="card-content">
                        <i class="fa-solid fa-truck-fast"></i>
                        <h2>
                            guaranteed shipping
                        </h2>
                        <p>
                            Our shipping service is effectively fast. the delivery will be taken to its destination within 24 hours.
                        </p>
                    </div>
                </div>
                <div class="col-lg-3 col-md-6 col-sm-12 card-container">
                    <div class="card-content">
                        <i class="fa-solid fa-handshake"></i>
                        <h2>
                            reliability
                        </h2>
                        <p>
                            Our company constantly works to give you the best service. Our support service is available 24 hours a day.
                        </p>
                    </div>
                </div>
                <div class="col-lg-3 col-md-6 col-sm-12 card-container">
                    <div class="card-content">
                        <i class="fa-solid fa-leaf"></i>
                        <h2>
                            eco-friendly packaging
                        </h2>
                        <p>
                            We are working to become a totally plastic free company! We only use 0.5% of our packaging by weight and it is made of (recycled) plastic.
                        </p>
                    </div>
                </div>

                <div class="col-lg-3 col-md-6 col-sm-12 card-container">
                    <div class="card-content">
                        <i class="fa-solid fa-users-line"></i>
                        <h2>
                            earnest company
                        </h2>
                        <p>
                            For over 50 years we have been operating in the floriculture and field gardening sector, offering products of the highest quality
                        </p>
                    </div>
                </div>
        </div>
    </section>

    <!--========PLANTING SECTION=========-->

    <section class="planting-section">
        <div class="row">
            <div class="col planting-content">
                <h1>
                    Let's reforest the planet with you
                </h1>
                <div class="d-flex">
                    <img src="../assets/planting.png" href="">
                    <p>
                        We care about the life of the forest. We will plant 1 tree together every time you place an order over €30
                    </p>

                </div>
            </div>
            <div class="col seeding-img">
                <video controls autoplay>
                    <source src="../assets/video-rainforestation.mp4" type="video/mp4">
                    <source src="movie.ogg" type="video/ogg">
                    Your browser does not support the video tag.
                </video> 
            </div>
        </div>
    </section>

</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>


// ========JUMBOTRON SECTION========= //

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
}

// ========COMPANY SERVICES SECTION========= //


div.services{
    max-width: 1200px;
    margin: 3.2rem auto;

    div.card-container{
        border-right: 1px solid #ececec;
        border-left: 1px solid #ececec;

        // @media only screen and (min-width: 980px) {
        //     .card-container {
        //         all: none;
        //     }
        // }


        div.card-content{
            padding: 2rem;


            i{
                font-size: 3rem;
                color: #22684f;
            }

            h2{
                text-transform: uppercase;
                font-size: 1.4rem;
                letter-spacing: .125rem;
                padding-top: 1.2rem;
            }

            p{
                padding-top: 1rem;
            }
        }
    }
}


// ========PLANTING SECTION========= //

section.planting-section{
    margin-top: 4rem;

    div.seeding-img{
        background-color: #22684f;
        height: 630px;
        display: flex;
        justify-content: center;
        align-items: center;

        video{
            width: 100%;
            height: 550px;
        }
    }

    div.planting-content{
        display: flex;
        flex-direction: column;
        justify-content: center;

        h1{
            font-size: 5rem;
            padding-left: 3rem;
            color: #22684f;
        }
        div.d-flex{
            align-items: center;

                img{
                    height: 200px;
                    width: 250px;
                }
            }
        }
        


}



</style>