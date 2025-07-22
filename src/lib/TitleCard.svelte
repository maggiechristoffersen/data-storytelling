<script>
  let { title, subtitle } = $props();
</script>

<div class="title-card">
  <div class="content">
    <h1>{title}</h1>
    <p>{subtitle}</p>
  </div>
</div>

<style>
  .title-card {
    background-color: #aabd8c;
    background-image: url("header.png");
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 2rem;
    box-sizing: border-box;
    font-family: "Garamond", serif;
    font-style: italic;
  }

  .content {
    max-width: 700px;
    background-color: #362b2e;
    padding: 2rem;
    border: 6px solid #362b2e;
    border-radius: 2rem;
    box-shadow: 16px 16px #221b1d;
  }

  h1 {
    font-size: 3rem;
    margin: 0;
    color: #aabd8c;
    text-shadow: 1px 1px 0 #627543;
  }

  p {
    font-size: 1.1rem;
    color: #e9e3b4;
    text-shadow: #100f05;
    margin-top: 1rem;
  }

  @media (max-width: 600px) {
    h1 {
      font-size: 2.2rem;
    }

    p {
      font-size: 1.1rem;
    }
  }
</style>
