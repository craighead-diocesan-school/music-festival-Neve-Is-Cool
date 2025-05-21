<script>
  export let src = ""
  export let alt = ""
  export let caption = ""
</script>

<figure>
  <img {src} {alt} />
  <figcaption>{caption}</figcaption>
</figure>

<style>
  figcaption {
    font-family: "Belanosima", sans-serif;
    color: #a34f04;
  }

  figure {
    margin-left: 5%;
    margin-right: 5%;
    width: 100%;
  }
</style>
