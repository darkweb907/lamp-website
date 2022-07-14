<script>
  import Counter from "./lib/Counter.svelte";
  import Footer from "./lib/footer.svelte";
  import Head from "./lib/head.svelte";
  import Part from "./lib/part.svelte";
  import Table from "./lib/table.svelte";
</script>

<main>
  <Counter />
  <Head />
  <Part />
  <Table />
  <Footer />
</main>

<style>
  :root {
    --tw-bg-opacity: 1;
    --tw-gradient-from: #ca8a04;
    --tw-gradient-stops: var(--tw-gradient-from),
      var(--tw-gradient-to, rgba(202, 138, 4, 0));
    --tw-gradient-to: #facc15;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
      Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
  }

  @media (min-width: 480px) {
  }
</style>
