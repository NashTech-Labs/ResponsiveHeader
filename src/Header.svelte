<script>
  export let title;
</script>

<header>
  <h1>{title}</h1>
</header>

<style>
  header {
    background-color: #333;
    color: #fff;
    padding: 1rem;
    text-align: center;
  }

  h1 {
    margin: 0;
  }

  @media (max-width: 600px) {
    header {
      padding: 0.5rem;
    }
  }
</style>
