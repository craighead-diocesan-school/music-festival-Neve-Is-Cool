<script>
  export let heading = ""
  export let subheading = ""
  export let caption = ""
</script>

<header>
  <div class="heading-container">
    <h1>{heading}</h1>
    <h2>{subheading}</h2>
  </div>
  <div class="caption-container">
    <p>Image &copy;{caption}</p>
  </div>
</header>

<style>
  header {
    background-image: url("danny-howe.jpg");
    background-size: cover;
    background-position: center;
    padding: 12%;
    height: 100vh;
  }

  .heading-container {
    background-color: #a34f04;
    padding-top: 100px;
    padding-bottom: 100px;
    margin-right: 40%;
    align-items: center;
  }

  h1 {
    color: #ede6c6;
    font-family: "Sniglet", system-ui;
    font-size: 320%;
    text-align: center;
  }

  h2 {
    color: #ede6c6;
    font-family: "Belanosima", sans-serif;
    font-size: 200%;
    text-align: center;
    margin-top: 20px;
  }

  p {
    font-family: "Belanosima", sans-serif;
    color: #a34f04;
    align-self: baseline;
  }

  @media (max-width: 850px) {
    header {
      padding-top: 25%;
    }

    .heading-container {
      margin-right: 0%;
      padding-top: 80px;
      padding-bottom: 80px;
    }

    h1 {
      font-size: 280%;
    }

    h2 {
      font-size: 160%;
    }
  }

  @media (max-width: 500px) {
    header {
      padding-top: 45%;
    }

    h1 {
      font-size: 240%;
    }

    h2 {
      font-size: 150%;
    }
  }
</style>
