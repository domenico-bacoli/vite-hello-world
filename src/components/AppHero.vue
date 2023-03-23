<script>

export default {
    data() {
        return {

        }
    }
}
</script>

<template>
    <header>
        <div class="jumbotron">
            <img src="/images/coding-image.jpg" alt="jumbotron image">
            <h2>Let's Start Coding</h2>
        </div>
    </header>
</template>



<style scoped>
.jumbotron {
    display: flex;
    flex-direction: column;
    align-items: center;
    max-width: 100%;
}

h2 {
    font-size: 32px;
}

.jumbotron img {
    width: 700px;
    border-radius: 30px;
}
</style>