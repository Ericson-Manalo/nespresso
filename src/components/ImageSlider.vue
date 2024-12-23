<template lang="">
    <div class="slider">
        <div class="slider-image">
            <!-- Mostra l'immagine attiva -->
            <img :src="images[currentIndex]" :alt="'Image ' + (currentIndex + 1)" />
        </div>
        <div class="slider-controls">
            <!-- Pulsanti per spostarsi manualmente -->
            <button @click="prevImage">⬅️</button>
            <button @click="nextImage">Next</button>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
        images: [
            '/src/assets/piante-slider.jpg',
            '/src/assets/piante-slider2.jpg', // Sostituisci con i percorsi reali delle immagini
            '/src/assets/piante-slider3.jpg'
        ],
        currentIndex: 0, // Indice dell'immagine attiva
        timer: null // Timer per l'autoplay
        };
    },
    methods: {
        // Cambia immagine al successivo
        nextImage() {
            this.currentIndex = (this.currentIndex + 1) % this.images.length;
        },
        // Cambia immagine al precedente
        prevImage() {
            this.currentIndex = (this.currentIndex - 1 + this.images.length) % this.images.length;
        },
        // Avvia l'autoplay
        startAutoPlay() {
            this.timer = setInterval(this.nextImage, 5000); // Cambia immagine ogni 3 secondi
        },
        // Ferma l'autoplay
        stopAutoPlay() {
            clearInterval(this.timer);
        }
    },
    mounted() {
        // Avvia l'autoplay quando il componente è montato
        this.startAutoPlay();
    },
    beforeUnmount() {
        // Pulisce il timer quando il componente viene smontato
        this.stopAutoPlay();
    }
};
</script>

<style scoped lang="scss">
/* Stili base dello slider */
    .slider {
        position: relative;
        width: 100%;
        max-width: 100%;
        margin: 0 auto;
        overflow: hidden;
    }
    .slider-image img {
        width: 100%;
        display: block;
    }
    .slider-controls {
        display: flex;
        justify-content: space-between;
        position: absolute;
        bottom: 320px;
        left: 50%;
        transform: translateX(-50%);
        width: 80%;
    }
    button {
        background-color: rgba(0, 0, 0, 0.5);
        color: white;
        border: none;
        border-radius: 50%;
        padding: 10px;
        cursor: pointer;
    }
    button:hover {
        background-color: rgba(0, 0, 0, 0.7);
    }
</style>
