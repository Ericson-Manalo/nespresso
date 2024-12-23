<template lang="">

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
</template>

<script>
export default {
};
</script>

<style scoped lang="scss">

// ========COMPANY SERVICES SECTION========= //

div.services{
    max-width: 1200px;
    margin: 3.2rem auto;

    div.card-container{
        border-right: 1px solid #ececec;
        border-left: 1px solid #ececec;

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
</style>
