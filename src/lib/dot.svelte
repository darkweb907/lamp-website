<script>
  import logo from "../assets/dot.svg";
  import key from "../assets/key.svg";
  import pop from "../assets/pop.svg";
  import light from "../assets/light.svg";
</script>

<section>
  <div class="d-flex justify-content-between my-5 align-items-center">
    <div class="dot1 d-none d-xl-block">
      <img class="jab" src={logo} alt="hello" />
    </div>
    <div
      class="dance d-flex flex-column flex-md-row justify-content-center mx-auto gap-2  px-5"
    >
      <div class="safe text-center px-4">
        <img src={key} alt="hello" />
        <h2 class="fw-bold fs-3 mb-4">Safe</h2>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Nihil,
          facilis?
        </p>
      </div>
      <div class="anytime text-center px-4">
        <img src={pop} alt="hello" />
        <h2 class="fw-bold fs-3 mb-4 text-nowrap">Easy Payments</h2>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Nihil,
          facilis?
        </p>
      </div>
      <div class="key text-center px-4">
        <img src={light} alt="hello" />
        <h2 class="fw-bold fs-3 mb-4">Anytime</h2>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Nihil,
          facilis?
        </p>
      </div>
    </div>
    <div class="dot2 d-none d-xl-block">
      <img class="jab" src={logo} alt="hello" />
    </div>
  </div>
</section>

<style>
  .dance img {
    padding: 1.5rem;
    border: 8px solid var(--tw-gradient-from);
    border-radius: 50%;
    margin-bottom: 1.5rem;
  }
  .dance {
    margin-top: 4rem;
  }
  .jab {
    max-height: 47vh;
  }
</style>
