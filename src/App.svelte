<script>
  let name = "Revangga";
  let points = 100;
</script>

<style>
  main {
    text-align: center;
    padding: 1em;
    max-width: 240px;
    margin: 0 auto;
  }

  h1 {
    color: purple;
    text-transform: uppercase;
    font-size: 4em;
    font-weight: 100;
  }

  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>

<main>
  <div class="container">
    <h1>Hello {name}!</h1>
    <h3>{points}</h3>
    <button class="btn btn-primary">Button</button>
  </div>
</main>
