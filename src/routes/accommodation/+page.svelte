<script>
  import Header from "$lib/Header.svelte"
  import Nav from "$lib/Nav.svelte"
  import Image from "$lib/Image.svelte"
  import Footer from "$lib/Footer.svelte"
</script>

<Header heading="Accommodation" subheading="Staying at Sunburst Festival" caption="Danny Howe" />
<Nav />
<main class="content section">
  <div class="img-text-container">
    <Image src="krists-luhaers.jpg" alt="Festival goers in tents" caption="Krists Luhaers" />
    <article class="text-beside-img">
      <p>Experience the ultimate music festival adventure with our tent accommodation packages! With our comfortable and convenient tents, you can immerse yourself in the festival atmosphere and stay close to all the action.</p>
      <p>Our tent accommodation packages are designed to provide you with a hassle-free and enjoyable stay. Whether you're attending the festival with friends or family, our tents offer a cozy and secure space to relax after a long day of music and festivities.</p>
    </article>
  </div>
  <p>Our tents are spacious and come equipped with everything you need for a comfortable stay. With comfortable beds, pillows, and blankets, you can get a good night's sleep and wake up feeling refreshed and ready for another day of music and fun.</p>
  <p>Located within the festival grounds, our tents are just a short walk away from all the stages and attractions. You won't have to worry about transportation or navigating crowds to get to the festival – you'll be right in the heart of it all.</p>
  <p>Our tents also come with a range of amenities to make your stay even more comfortable. You'll have access to clean restroom facilities, hot showers, and charging stations for your devices. We also have a dedicated staff available to assist with any needs or questions you may have during your stay.</p>
  <div class="img-text-container">
    <article class="text-beside-img">
      <p>But the best part of our tent accommodation packages is the community. You'll be surrounded by other festival-goers who are just as excited as you are to be a part of the experience. You'll make new friends, share stories, and create memories that will last a lifetime.</p>
      <p>Don't miss out on this opportunity to enhance your music festival experience. Book your tent accommodation package today and get ready for an unforgettable adventure. We can't wait to see you there!</p>
    </article>
    <Image src="jade-masri.jpg" alt="Festival crowd on each others shoulders" caption="Jade Masri" />
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

  @media (max-width: 800px) {
    .img-text-container {
      flex-direction: column;
      align-items: center;
    }
  }
</style>
