<template>
    <div class="results-block">
        <h1>Results:</h1>
        <p>Reaction time: {{ score }} ms</p>
    </div>
</template>

<script>
export default {
    props: ['score']
}
</script>

<style>
    .results-block {
        width: 400px;
        border-radius: 20px;
        background-color: crimson;
        color: white;
        text-align: center;
        padding: 100px 0;
        margin: 40px auto;
    }
</style>