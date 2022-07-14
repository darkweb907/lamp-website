<script>
  import logo from "../assets/download.svg";
  import Dot from "./dot.svelte";
</script>

<section class="first ">
  <div class="join text-center">
    <button type="button" class="btn btn-labeled btn-lg fw-bold">
      <span class="btn-label me-2 "><img src={logo} alt="hello" /></span
      >Download The App</button
    >
  </div>
  <Dot />
</section>

<style>
  .first {
    margin: 8rem 0 6rem 0;
  }
  button {
    background-color: #ca8a04;
  }
</style>
