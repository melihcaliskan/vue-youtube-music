<script setup>
import SongInfo from "./PlayerItems/SongInfo.vue";
import SeekBar from "./PlayerItems/SeekBar.vue";
import PlayerControl from "./PlayerItems/PlayerControl.vue";
import ExtraControls from "./PlayerItems/ExtraControls.vue";
</script>

<template>
  <div class="player-container">
    <SeekBar />
    <div class="content">
      <PlayerControl />
      <SongInfo />
      <ExtraControls />
    </div>
  </div>
</template>

<style scoped>
.player-container {
  position: absolute;
  bottom: 0;
  width: 100%;
  background-color: var(--yt-player-bg-dark);
}

.content {
  display: flex;
  justify-content: space-between;
  padding: 6px 12px;
}
</style>
