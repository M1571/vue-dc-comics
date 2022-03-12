// -------------------------------
// HTML

<template>
    <div class="comic">
        <figure class="comic__thumb">
             <img :src="srcThumb">
        </figure>
        <h4 class="comic__title">
            {{ title }}
        </h4>
    </div>
</template>

// -------------------------------
// JS

<script>
    export default {
        props: {
            srcThumb: {
                type: String,
                required: true,
            },
            title : {
                type: String,
                required: true,
            }
        }
    }
</script>

// -------------------------------
// CSS

<style lang="scss" scoped>

.comic {

    .comic__thumb {

        margin-bottom: 10px;

        img {
            display: block;
            aspect-ratio: 1/1;
            object-position: center;
            object-fit: cover;
            width: 100%;
        }

    }

    .comic__title {
        text-transform: uppercase;
        font-size: 12px;
        font-weight: 400;
    }

}

</style>