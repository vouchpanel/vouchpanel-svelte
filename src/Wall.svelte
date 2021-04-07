<script lang="ts">
  export let darkMode: "on" | "off";
  export let id: string;
</script>

<svelte:head>
  <script src="https://app.vouchpanel.com/js/embed.js" defer></script>
</svelte:head>

<div class="vouchpanel-publish" dark-mode="{darkMode}" data-wall="{id}"></div>