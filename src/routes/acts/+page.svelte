<script>
  import Header from "$lib/Header.svelte"
  import Nav from "$lib/Nav.svelte"
  import Image from "$lib/Image.svelte"
  import Footer from "$lib/Footer.svelte"
</script>

<Header heading="The Acts" subheading="Sunburst festival entertainment" caption="Danny Howe" />
<Nav />
<main class="content section">
  <div class="img-text-container">
    <article class="text-beside-img">
      <ul>
        <li>Tent sites are $15 per night, or $40 with a tent included.</li>
      </ul>
      <p>The music festival boasts an exciting lineup of talented musicians from a variety of genres, promising a diverse and entertaining experience for all attendees.</p>
    </article>
    <Image src="tony-pham.jpg" alt="Festival stage with colour smoke shells" caption="Tony Pham" />
  </div>
  <div class="img-text-container">
    <Image src="colin-lloyd-2.jpg" alt="Crowd watching main stage" caption="Colin Lloyd" />
    <article class="text-beside-img">
      <p>On the main stage, the headliners are a mix of established and up-and-coming acts, guaranteed to draw in large crowds. The first headliner is a popular rock band, known for their high-energy performances and catchy hooks. They will be followed by a chart-topping pop artist, whose upbeat and infectious hits are sure to get the crowd dancing and singing along. The final headliner is a legendary hip-hop artist, whose iconic rhymes and charismatic stage presence will bring the festival to a thrilling close.</p>

      <p>On the second stage, indie bands and singer-songwriters showcase their unique styles and sounds. The performers on this stage are often the most buzzed-about acts of the festival, with a loyal and passionate following. From dreamy shoegaze bands to alternative rock acts, the second stage offers a more intimate and personal experience for music lovers looking to discover new artists.</p>

      <p>The third stage is dedicated to up-and-coming artists from different genres, providing a platform for emerging talent to showcase their skills and gain exposure. This stage is a great opportunity for attendees to discover new artists and support the next generation of musicians.</p>
    </article>
  </div>
  <div class="img-text-container">
    <Image src="tijs-van-leur.jpg" alt="Crowd cheering and watching stage" caption="Tijs Van Leur" />
    <article class="text-beside-img">
      <p>Throughout the festival, DJs and electronic acts keep the energy up between sets, playing a mix of classic and contemporary dance tracks that will keep the crowd moving and grooving.</p>
      <p>Overall, the music festival offers a diverse and exciting lineup that caters to different tastes and styles. From established headliners to emerging talent, the festival promises a memorable and thrilling musical</p>
    </article>
  </div>
</main>
<Footer />

<style>
  main {
    background-color: #fbf1b2;
  }

  main.content {
    margin-bottom: 0;
    margin-top: 0;
  }

  p {
    font-family: "Belanosima", sans-serif;
    color: #3c1c00;
    font-size: 120%;
    margin-left: 10%;
    margin-right: 10%;
  }

  .img-text-container {
    display: flex;
    align-items: center;
    margin-top: 5%;
    margin-bottom: 5%;
  }

  li {
    font-family: "Belanosima", sans-serif;
    color: #3c1c00;
    font-size: 120%;
    margin-left: 10%;
  }
</style>
