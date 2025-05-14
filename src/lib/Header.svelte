<script>
  export let heading
  export let subheading
</script>

<header>
  <div></div>
  <div class="heading-container">
    <h1>{heading}</h1>
    <h2>{subheading}</h2>
  </div>
</header>

<style>
  header {
    background-image: url("danny-howe.jpg");
    background-size: cover;
    background-position: center;
    height: 100vh;
  }

  .heading-container {
    background-color: #a34f04;
    width: 350px;
    margin-left: 15%;
    height: 300px;
  }

  h1 {
    color: #ede6c6;
    font-family: "Sniglet", system-ui;
    font-size: 500%;
    text-align: center;
  }

  h2 {
    color: #ede6c6;
    font-family: "Belanosima", sans-serif;
    font-size: 200%;
    text-align: center;
  }

  div {
    height: 25%;
  }
</style>
