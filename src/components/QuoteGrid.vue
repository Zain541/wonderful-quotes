<template>
<div>
    <div class="row" v-for="quote in quotes">
        <app-quote>{{ quote }}</app-quote>
    </div>
</div>
</template>


<script>
import Quote from './Quote.vue';
export default {
    props: ['quotes'],
    components: {
        appQuote: Quote
    }
}
</script>


<style scoped>

</style>