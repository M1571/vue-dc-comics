// -------------------------------
// HTML

<template>
    
    <section id="icons-wrapper">
            <div class="container">
                <ul class="card-wrapper">
                    <li v-for="(el,i) in card" :key="i" class="card-item">
                        <img :src="el.img" alt="">
                        {{ el.text }}
                    </li>
                    <!-- <li>DC MERCHANDISE</li>
                    <li>SUBSCRIPTION</li>
                    <li>COMIC SHOP LOCATOR</li>
                    <li>DC POWER VISA</li> -->
                </ul>
            </div>
        </section>

</template>

// -------------------------------
// JS

<script>
    export default {
        data() {
            return {
                card: [
                    {
                        text: 'DIGITAL COMICS',
                        img: require('../assets/img/buy-comics-digital-comics.png')
                    },
                    {
                        text: 'DC MERCHANDISE',
                        img: require('../assets/img/buy-comics-merchandise.png')
                    },
                    {
                        text: 'SUBSCRIPTION',
                        img: require('../assets/img/buy-comics-subscriptions.png')
                    },
                    {
                        text: 'COMIC SHOP LOCATOR',
                        img: require('../assets/img/buy-comics-shop-locator.png')
                    },
                    {
                        text: 'DC POWER VISA',
                        img: require('../assets/img/buy-dc-power-visa.svg')
                    },
                ]
            }
        }
    }
</script>

// -------------------------------
// CSS

<style lang="scss" scoped>

#icons-wrapper {
    /* border: 3px solid rgb(0, 255, 179); */
    background-color: #0282F9;
    color: white;

    .card-wrapper {
        display: flex;
        align-items: center;
        padding: 30px 0;

        .card-item {
            text-align: center;
            flex-basis: 0;
            flex-grow: 1;
            display: flex;
            align-items: center;
            gap: 15px;

            img {
                height: 55px;
            }
        }
    }
}

</style>