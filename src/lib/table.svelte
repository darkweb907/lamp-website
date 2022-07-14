<script>
  import logo from "../assets/table.png";
</script>

<section class="pot py-4 position-relative">
  <div class="container">
    <div class="row align-items-center flex-column-reverse flex-lg-row px-lg-5">
      <div class="col-12 col-lg-6  px-0 px-md-5 px-lg-0">
        <h2 class="h1 fw-bold">Relax, You're Home!</h2>
        <p class=" lh-base fs-5 py-4">
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Rerum dolore
          voluptatem dolores optio sed ut rem, libero expedita quam ex. Lorem
          ipsum dolor sit amet consectetur adipisicing elit. Id similique
          tempora minima eaque cum libero voluptatibus ex! Voluptates, corrupti
          ducimus.
        </p>
        <button class="fw-bold btn btn-lg">Sign Up</button>
      </div>
      <div class="col-12 col-lg-6 text-center">
        <img class="img-fluid" src={logo} alt="hello" />
      </div>
    </div>
  </div>
  <div class="circle  d-none d-xl-block" />
</section>

<style>
  .circle {
    top: 307px;
    position: absolute;
    width: 389px;
    height: 389px;
    /* background-color: red; */
    right: 24px;
    /* padding-top: 22rem; */
    border-radius: 49%;
    border: 11px solid #ca8a04;
  }
  button {
    background-color: #ca8a04;
  }
  button:hover {
    background-color: #dc2626;
  }
</style>
