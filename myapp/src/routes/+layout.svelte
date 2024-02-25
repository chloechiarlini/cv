<script>
  import Header from "./Header.svelte";
  import "./output.css";
</script>

<div class="bg-red-400">
  <p>test</p>
  <main>
    <slot />
  </main>

  <footer></footer>
</div>
