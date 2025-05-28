<script>
  import Header from "$lib/Header.svelte"
  import Nav from "$lib/Nav.svelte"
  import Image from "$lib/Image.svelte"
  import Footer from "$lib/Footer.svelte"
</script>

<Header heading="Sunburst Festival" subheading="General details" caption="Danny Howe" />
<Nav />

<main class="content section">
  <h3>Key Information</h3>
  <div class="img-text-container">
    <article class="text-beside-img">
      <ul>
        <li>Tickets are $200 per person</li>
        <li>Festival goers must be 15 years of age or older</li>
      </ul>
      <p>Welcome to the ultimate music festival experience! Get ready for a day filled with live music, great food, and unforgettable memories.</p>
      <p>Our festival features a diverse lineup of talented musicians from different genres, sure to satisfy every taste in music. With multiple stages set up throughout the venue, you can easily move from one act to the next, discovering new favorites and enjoying classic hits.</p>
    </article>
    <Image src="aditya-chinchure.jpg" alt="Crowd watching dark stage" caption="Aditya Chinchure" />
  </div>
  <p>From up-and-coming artists to established headliners, we have curated an exciting lineup that will keep you dancing and singing along all day long. Our festival is the perfect opportunity to discover new music, see your favorite artists live, and make lasting memories with friends and family.</p>
  <p>But the music is just the beginning. Our festival also boasts an impressive selection of food vendors, offering everything from classic festival fare to more gourmet options. You won't go hungry with the delicious treats and refreshing beverages available throughout the venue.</p>
  <div class="img-text-container">
    <Image src="aranxa-esteve.jpg" alt="Three women sitting at festival" caption="Aranxa Esteve" />
    <article class="text-beside-img">
      <p>In addition to the music and food, our festival also features a variety of activities to keep you entertained throughout the day. From art installations to merchandise booths, there is something for everyone to enjoy. You can even capture the memories with our festival photo booths and snap a selfie with your favorite artists.</p>
      <p>So don't miss out on this one-of-a-kind music festival experience. Get your tickets now and join us for a day of music, fun, and community. We can't wait to see you there!</p>
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
  }

  h3 {
    color: #ede6c6;
    background-color: #3c1c00;
    padding: 12px;
    text-align: center;
    width: 200px;
    font-size: 160%;
    font-family: "Belanosima", sans-serif;
    font-weight: 400;
  }

  p {
    font-family: "Belanosima", sans-serif;
    color: #3c1c00;
    font-size: 120%;
    margin-left: 10%;
    margin-right: 10%;
  }

  li {
    font-family: "Belanosima", sans-serif;
    color: #3c1c00;
    font-size: 120%;
    margin-left: 10%;
  }

  .img-text-container {
    display: flex;
    align-items: center;
    margin-top: 5%;
    margin-bottom: 5%;
  }

  @media (max-width: 800px) {
    .img-text-container {
      flex-direction: column;
      align-items: center;
    }
  }
</style>
