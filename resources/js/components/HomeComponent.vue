<template>
    <div>
        <b-card title="Amigo secreto" sub-title="Como funciona">
            <b-card-text>
            Some quick example text to build on the <em>card title</em> and make up the bulk of the card's
            content.
            </b-card-text>

            <b-card-text>A second paragraph of text in the card.</b-card-text>

            <!-- <a href="#" class="card-link">Criar amigo secreto</a>
            <b-link href="#" class="card-link">Ver amigo secreto</b-link> -->
            <router-link to="/sorteio" class="card-link">Criar amigo secreto</router-link>
            <router-link to="/login" class="card-link">Ver amigo secreto</router-link>
        </b-card>
    </div>
</template>

<script>
    export default {
        // mounted() {
        //     console.log('Component mounted.')
        // }
    }
</script>