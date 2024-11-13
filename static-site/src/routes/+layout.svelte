<script lang="ts">
  import '../app.css'
</script>

<div>
  <main>
    <slot />
  </main>

  <footer>
    <a href="https://icc.gg/privacidade" target="_blank">Privacy Policy</a>
    ⭐️
    <a href="https://icc.gg/termos" target="_blank">Terms and Conditions</a>
  </footer>
</div>

<style>
  div {
    margin: 1em auto 1em auto;
    max-width: 800px;
  }

  main {
    background-color: rgb(30 41 59);
    border-radius: 0.6em;
    padding: 1em;
  }

  footer {
    font-size: small;
    text-align: right;
    opacity: 0.5;
    padding: 0.4em;
  }
</style>
