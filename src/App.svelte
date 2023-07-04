<script lang="ts">
  import svelteLogo from './assets/svelte.svg'
  import viteLogo from '/vite.svg'
  import Counter from './lib/Counter.svelte'
</script>

<main>
<div class="container">
    <div class="item">アイテム1</div>
    <div class="item">アイテム2</div>
    <div class="item">アイテム3</div>
    <div class="item">アイテム4</div>
</div>
</main>

<style>
.container {
    display: flex;
}

.item {
    margin: 5px;
    border: solid 1px #00ff7f;
    background-color: #87c3fa;
}
</style>
