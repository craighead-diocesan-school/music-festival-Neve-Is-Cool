<script>
  export let src = ""
  export let alt = ""
  export let caption = ""
</script>

<figure>
  <img {src} {alt} />
  <figcaption>Image &copy;{caption}</figcaption>
</figure>

<style>
  figcaption {
    font-family: "Belanosima", sans-serif;
    color: #a34f04;
  }

  figure {
    width: 150%;
  }

  @media (max-width: 800px) {
    figure {
      width: 100%;
      margin-top: 3%;
      margin-bottom: 3%;
    }
  }
</style>
