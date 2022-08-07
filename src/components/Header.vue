
<script>
const LOGO_URL = "https://music.youtube.com/img/on_platform_logo_dark.svg";

export default {
    data() {
        return {
            LOGO_URL
        }
    }
}
</script>

<template>
    <div class="container">
        <img :src="LOGO_URL" width="80" />
    </div>
</template>

<style scoped>
.container {
    display: flex;
    align-items: center;
    padding: 18px;
}
</style>
