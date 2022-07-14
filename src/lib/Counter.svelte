<script>
  import { fly } from "svelte/transition";
  import logo from "../assets/app.svg";
  import slogo from "../assets/logo.svg";
  import chair from "../assets/couch.png";
  import menu from "../assets/menu.svg";
  import exist from "../assets/exit.svg";
  let show = false;

  // open hamburger
  const display = () => {
    show = !show;
  };

  // hide hamburger
  const hide = () => {
    show = false;
  };
</script>

<header>
  <nav class="">
    <div
      class="container-md d-flex justify-content-between  align-items-center"
    >
      <ul
        class="list-unstyled d-none d-lg-flex gap-3 text-uppercase fw-bold align-self-center"
      >
        <li>
          <a href="/" class="text-decoration-none text-dark fs-5">Home</a>
        </li>
        <li>
          <a href="/" class="text-decoration-none text-dark fs-5">Contact</a>
        </li>
      </ul>
      <img class="img-fluid log" src={slogo} alt="logo" />
      <img
        on:click={display}
        class="d-block d-lg-none img-fluid"
        src={menu}
        alt="logo"
      />
      <ul class="boot d-none d-lg-flex gap-3">
        <button class="btn btn-lg btn-danger text-uppercase fw-bold"
          >Login</button
        >
        <button class="btn btn-lg btn-dark text-uppercase fw-bold"
          >Sign up</button
        >
      </ul>
      {#if show}
        <div
          transition:fly={{ y: -500, duration: 900 }}
          class="small d-block d-lg-none"
        >
          <ul
            class="list-unstyled d-flex flex-column  d-lg-none gap-4 text-uppercase fw-bold align-self-center"
          >
            <li on:click={hide} class="align-self-end mt-5">
              <img src={exist} alt="exit" />
            </li>
            <li>
              <a href="/" class="text-decoration-none text-dark fs-5">Home</a>
            </li>
            <li>
              <a href="/" class="text-decoration-none text-dark fs-5">Contact</a
              >
            </li>
            <button class="btn btn-lg btn-danger text-uppercase fw-bold"
              >Login</button
            >
            <button class="btn btn-lg btn-dark text-uppercase fw-bold"
              >Sign up</button
            >
          </ul>
        </div>
      {/if}
    </div>
  </nav>
  <div class="chair pt-5 bg-info">
    <div class="container-md  d-flex justify-content-center cheap">
      <img src={chair} alt="" class="img-fluid" />
      <img src={logo} alt="" class="img-fluid clap " />
    </div>
  </div>
</header>

<style>
  .chair {
    background-image: linear-gradient(to bottom, var(--tw-gradient-stops));
  }
  nav {
    background-color: rgb(202 138 4/1);
    padding: 1.3rem;
  }
  .cheap {
    position: relative;
    min-height: 89vh;
    padding: 1.3rem;
  }
  .chair img {
    position: absolute;
    bottom: -75px;
  }
  .clap {
    width: 18rem;
  }
  @media (max-width: 480px) {
    ul {
      display: block;
    }
    .cheap {
      min-height: 70vh;
    }
    .log {
      width: 55%;
    }
    .clap {
      width: 15rem;
    }
  }
  .small {
    padding-inline: 23px;
    top: 0;
    z-index: 1;
    min-height: 100vh;
    position: fixed;
    text-align: center;
    background-color: rgb(202 138 4 / var(--tw-bg-opacity));
    left: 0;
    width: 100%;
  }
</style>
