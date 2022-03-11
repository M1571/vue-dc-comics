// -------------------------------
// HTML

<template>

    <main>

        <!-- ------------------------------- -->

        <section id="content-wrapper">
            <div class="container">
                --> Content goes here 
            </div>
        </section>

        <!-- ------------------------------- -->

        <ContentSection />

    </main>

</template>

// -------------------------------
// JS

<script>

import ContentSection from './ContentSection.vue';

export default {
    components: {
        ContentSection,
    }
};

</script>

// -------------------------------
// CSS

<style _lang_="scss" _scoped_>

#content-wrapper {
    /* border: 3px solid rgb(255, 145, 0); */
    background-color: #1C1C1C;
    color: white;
    /* border: 5px solid red; */
}

/* ------------------------------- */

</style>