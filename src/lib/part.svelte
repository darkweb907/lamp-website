<script>
  import logo from "../assets/spotify.svg";
  import key from "../assets/dell.svg";
  import pop from "../assets/cisco.svg";
  import light from "../assets/disney.svg";
  import dezer from "../assets/deezer.svg";
  import verserce from "../assets/verizon.svg";
  import texas from "../assets/texas.svg";
</script>

<section class="part py-5 mt-4 text-center">
  <div class="container">
    <h2 class="h1 fw-bold">Our Partners</h2>
    <p
      class="text-white col-md-8 col-lg-7 fw-bold fs-5 mt-3 lh-base mx-auto mb-5"
    >
      Lorem ipsum dolor sit, amet consectetur adipisicing elit. Magnam atque
      iusto accusamus consequuntur nulla? Dolores quasi nobis aut temporibus
      ipsum?
    </p>
    <div class="par p-2 mt-5 d-flex gap-5 justify-content-center  flex-wrap">
      <div class=" text-center bg-white col-12 col-sm-3 rounded shadow-lg">
        <img class="w-100 h-50" src={logo} alt="" />
      </div>
      <div class="text-center bg-white col-12 col-sm-4 rounded shadow-lg">
        <img class="w-100 h-50" src={key} alt="" />
      </div>
      <div class="text-center bg-white col-12 col-sm-3 rounded shadow-lg">
        <img class="w-100 h-50" src={pop} alt="" />
      </div>
      <div class="text-center bg-white col-12 col-sm-3 rounded shadow-lg">
        <img class="w-100 h-50" src={light} alt="" />
      </div>
      <div class="text-center bg-white col-12 col-sm-3 rounded shadow-lg">
        <img class="w-75 h-50" src={dezer} alt="" />
      </div>
      <div class="text-center bg-white col-12 col-sm-3 rounded shadow-lg">
        <img class="w-75 h-50" src={verserce} alt="" />
      </div>
      <div class="py-5 px-3 bg-white col-12 col-sm-3 rounded shadow-lg">
        <img class="w-100" src={texas} alt="" />
      </div>
    </div>
  </div>
</section>

<style>
  .rounded {
    display: flex;
    height: 101px;
    border-radius: 0.25rem !important;
    justify-content: center;
    align-items: center;
  }
  .par {
    max-width: 60%;
    margin-inline: auto;
  }
  .part {
    background-color: black;
  }
  .part h2 {
    color: var(--tw-gradient-from);
  }
  @media (max-width: 768px) {
    .par {
      max-width: 100%;
    }
    p {
      font-size: 1rem !important;
    }
  }
  @media (min-width: 370px) and (max-width: 768px) {
    .col-12 {
      width: 35% !important;
    }
  }
</style>
