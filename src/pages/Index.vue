<template>
    <Layout>
        <div class="container">
            <g-image class="img" alt="Example image" src="~/assets/default.jpg" />
            <h1>Hello World !</h1>
            <p>
                Bonjour je m'appelle Maxime JEAN je suis apprenti développeur web.
            </p>
            <p class="home-links">
                <a href="https://github.com/gitMax18" target="_blank">
                    <g-image class="github" alt="github" src="~/assets/github.png" />
                </a>
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
            { name: "description", content: "Ma présentation" },
            { name: "viewport", content: "width=device-width, initial-scale=1" },
            { name: "keywords", content: "apprenti, developpeur, web" },
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

.github {
    width: 50px;
}
</style>
