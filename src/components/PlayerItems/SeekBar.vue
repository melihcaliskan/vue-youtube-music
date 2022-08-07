<script>
export default {
    data() {
        return {
            slider: 0
        }
    }
}
</script>

<template>
    <div class="seekbar-container">
        <v-slider v-model="slider" color="red" label="color"></v-slider>
    </div>
</template>

<style scoped>
.seekbar-container {
    height: 1px;
    margin-top: -16px;
    margin-bottom: 24px;
}
</style>
