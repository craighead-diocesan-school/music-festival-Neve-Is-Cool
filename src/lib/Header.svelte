<script>
  export let heading
  export let subheading
</script>

<header>
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
    padding: 12%;
    height: 100vh;
  }

  .heading-container {
    background-color: #a34f04;
    padding-top: 100px;
    padding-bottom: 100px;
    margin-right: 45%;
    align-items: center;
  }

  h1 {
    color: #ede6c6;
    font-family: "Sniglet", system-ui;
    font-size: 415%;
    text-align: center;
  }

  h2 {
    color: #ede6c6;
    font-family: "Belanosima", sans-serif;
    font-size: 200%;
    text-align: center;
    margin-top: 20px;
  }
</style>
