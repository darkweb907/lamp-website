<script>
  import logo from "../assets/download.svg";
  import lamp from "../assets/lamp.png";
  import log from "../assets/app.svg";
</script>

<footer class="mt-5 col-12  col-lg-12 mx-auto">
  <div class="container">
    <div class="row align-center ">
      <div class="col-12 col-md-5 col-lg-6 text-center">
        <img class="img-fluid" src={lamp} alt="" />
        <div class="join my-5">
          <button type="button" class="btn btn-labeled btn-lg fw-bold">
            <span class="btn-label me-2 "><img src={logo} alt="hello" /></span
            >Download The App</button
          >
        </div>
        <img class="img-fluid log" src={log} alt="log" />
      </div>
      <div class="col-12 col-md-7 col-lg-6 align-self-center">
        <form class="border p-4 mt-5 border-3 border-dark ">
          <h2 class="fw-bold">Contact Us</h2>
          <div class="form-group mt-4">
            <label class="mb-3 fw-bold" for="name">Name</label>
            <input
              type="text"
              class="form-control"
              id="name"
              placeholder="Enter name"
            />
          </div>
          <div class="form-group my-4">
            <label class="mb-3 fw-bold" for="email">Email</label>
            <input
              type="email"
              class="form-control"
              id="email"
              placeholder="Enter email"
            />
          </div>
          <div class="form-group">
            <label class="mb-3 fw-bold" for="message">Message</label>
            <textarea class="form-control" id="message" rows="5" />
          </div>
        </form>
      </div>
    </div>
  </div>
</footer>

<style>
  .log {
    border-radius: 31px 29px 0 0;
    object-fit: cover;
    width: 59%;
    height: 39vh;
  }
  button {
    background-color: #ca8a04;
  }
  form {
    border-radius: 0.9rem;
  }
  input,
  textarea {
    border: 2px solid #ca8a04 !important;
  }
</style>
