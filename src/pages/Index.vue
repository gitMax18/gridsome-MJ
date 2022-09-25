<template>
    <Layout>
        <div class="container">
            <g-image class="img" alt="Example image" src="~/assets/default.jpg" />
            <h1>Hello World !</h1>
            <p>
                Bonjour je m'appelle Maxime JEAN je suis apprenti développeur web.
            </p>
            <p class="home-links">
                <a href="https://github.com/gitMax18" target="_blank">Voir mon GitHub</a>
            </p>
        </div>
    </Layout>
</template>

<script>
export default {
    metaInfo: {
        title: "Ma présentation",
        meta: [
            { charset: "utf-8" },
            {
                key: "Présentation, apprenti developpeur",
                name: "Maxime JEAN",
                content: "Ma présentation",
            },
        ],
    },
};
</script>

<style>
.container {
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: center;
}

.img {
    border-radius: 10000px;
    width: 200px;
}
</style>
