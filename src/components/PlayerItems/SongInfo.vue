<script>
const ALBUM_ART = "https://cdns-images.dzcdn.net/images/cover/fce6fe4cf02a3c78cedb8eb32fa4fa31/350x350.jpg";
const ALBUM_ART_DIMENSION = 40;
const ICON_COLOR = "grey-darken-1";

export default {
    data() {
        return {
            ALBUM_ART,
            ALBUM_ART_DIMENSION,
            ICON_COLOR
        }
    }
}
</script>

<template>
    <div class="song-info-container">
        <img class="album-art" :src="ALBUM_ART" :width="ALBUM_ART_DIMENSION" :height="ALBUM_ART_DIMENSION" />
        <div>
            <p class="song-title">
                Awake and Alive (Live from iTunes Sessions)
            </p>
            <p>
                Skillet • iTunes Session (Live) • 2010
            </p>
        </div>

        <div>
            <v-btn variant="text" icon="mdi-thumb-down-outline" :color="ICON_COLOR" />
            <v-btn variant="text" icon="mdi-thumb-up-outline" :color="ICON_COLOR" />
            <v-btn variant="text" icon="mdi-dots-vertical" :color="ICON_COLOR" />
        </div>
    </div>
</template>

<style scoped>
.song-info-container {
    display: flex;
    align-items: center;
    gap: 16px;
}

p {
    font-size: 16px;
    line-height: 19px;
}

.song-title {
    color: var(--vt-c-white);
    font-weight: 600;
}

.album-art {
    border-radius: 2px;
}
</style>
