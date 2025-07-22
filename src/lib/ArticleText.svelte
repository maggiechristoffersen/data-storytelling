<script>
  let { children } = $props();
</script>

<div class="article-text">
  <p>
    {@render children()}
  </p>
</div>

<style>
  body {
    background-color: #e9e3b4;
  }
  .article-text {
    margin: 50vh auto;
    width: 50%;
    background-color: #f4a47a;
    color: #381d2a;
    border: solid #2e5339 3px;
    border-radius: 20px;
    padding: 20px;
    box-shadow: 16px 16px #aabd8c;
    font-family: "Garamond", serif;
    font-style: italic;
    font-size: 1.1rem;
  }
</style>
