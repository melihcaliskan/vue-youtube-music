<script>
export default {
    data() {
        return {
            playing: true,
            currentSec: "0:02",
            totalSec: "3:40"
        }
    }
}
</script>

<template>
    <div class="container">
        <v-btn icon="mdi-skip-previous" variant="text" />
        <v-icon size="40">
            mdi-play
        </v-icon>
        <v-btn icon="mdi-skip-next" variant="text" />

        <h5 class="text-grey-lighten-1">
            {{ currentSec }} / {{ totalSec }}
        </h5>
    </div>
</template>

<style scoped>
.container {
    display: flex;
    align-items: center;
}

h5 {
    font-size: 12px;
    font-weight: 400;
}
</style>
