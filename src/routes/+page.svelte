<script>
  import Header from "$lib/Header.svelte";
  import Footer from "$lib/Footer.svelte";
</script>

<Header />

<main>
  <div class="columns">
    <div class="text">
      <h2 class="center">Lorem Ipsum with Flavour</h2>

      <p>What's Ipsum Bro is a lorem ipsum generator with a twist. Instead of the same old boring lorem ipsum, you can choose from a variety of flavours to spice up your placeholder text.</p>
    </div>
    <div class="boxes">
      <a href="pirate">
        <img class="box" src="pirate.png" alt="Pirate" />
      </a>
      <a href="cheese">
        <img class="box" src="cheese.png" alt="Cheese" />
      </a>
      <a href="cupcake">
        <img class="box" src="cupcake.png" alt="Cupcake" />
      </a>
      <a href="hipster">
        <img class="box" src="hipster.png" alt="Hipster" />
      </a>
    </div>
  </div>
</main>

<Footer />

<style>
  .box {
    width: 125px;
    height: 125px;
    border-radius: 5%;
    padding: 25px;
    background: ivory;
    box-shadow: 15px 15px lightblue;
  }
  .boxes {
    display: flex;
    flex-wrap: wrap;
    gap: 25px;
    justify-content: space-between;
    width: 400px;
  }
  .text {
    font-family: "Patrick Hand", cursive;
    width: 30;
  }
  .center {
    text-align: center;
  }
  .columns {
    display: flex;
    align-items: center;
    justify-content: space-evenly;
    background: lavender;
    padding: 5rem 10rem;
  }
  @media screen and (max-width: 600px) {
    .columns {
      flex-direction: column;
      padding: 2rem 3rem;
    }
    .text {
      width: 100%;
    }
  }
</style>
