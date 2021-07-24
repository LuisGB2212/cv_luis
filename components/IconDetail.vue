<template>
    <div class="mb-0 text-white row mt-4">
        <b-icon class="h1 mr-4 align-self-end" :icon="icon"></b-icon>
        <div class="col align-self-center">
            <h5> {{title}} </h5>
            <div v-if="description">
                <small>{{description}}</small>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    props:['icon','title', 'description']
}
</script>