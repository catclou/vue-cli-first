<template>
    <div>
        <section class="hero">
            <h3>Questo è il jumbotron più brutto di sempre.</h3>
        </section>
    </div>
</template>

<script>
export default {
    name: 'HeroJumbotron'
}
</script>

<style scoped>
    .hero {
        height: 30vh;
        width: 100%;
        background-image: url('https://images.unsplash.com/photo-1553095066-5014bc7b7f2d?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1742&q=80');
        background-size: contain;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-content: center;
    }

    h3 {
        color: lightgray;
        font-size: 4rem;
    }
</style>