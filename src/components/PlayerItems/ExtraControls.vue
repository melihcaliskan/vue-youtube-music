<script>
export default {
    data() {
        return {
            playing: true
        }
    }
}
</script>

<template>
    <div class="container">
        <v-btn icon="mdi-volume-high" color="grey-darken-1" variant="text" />
        <v-btn icon="mdi-repeat" color="grey-darken-1" variant="text" />
        <v-btn icon="mdi-shuffle-variant" color="grey-darken-1" variant="text" />
        <v-btn icon="mdi-menu-up" color="grey-lighten-1" variant="text"  />
    </div>
</template>