<template>
  <div class="hello">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bulma@0.9.0/css/bulma.min.css">
    <article class="message is-info">
      <div class="message-body">
        <h1>{{ msg }}</h1>
        <p>
        <i> Careful w/that button link below mate</i> 
        </p>
        <a class="button is-link" href="https://rpubs.com/ProGamerCode/630250">White Paper</a>
      </div>
   </article>
<div class="columns is-primary is-gapless is-multiline">
      <figure class="image is-128x128">
        <img src="../assets/trampstamp.png">
      </figure>
      <article class="message is-danger">
        <div class="message-body">
          <h2>I know what your all thinking <i>Oh boy,Yet Another ERC20 token</i></h2>
        </div>
     </article>
        <figure class="image is-128x128">
          <img src="../assets/trampstamp.png">
        </figure>
      <article class="message is-warning">
        <div class="message-body">
          <h3><b> So without reading the technical WP heres all you need to know in neat bundles below</b></h3>
        </div>      
      </article>
        <figure class="image is-128x128">
          <img src="../assets/trampstamp.png">
        </figure>
      <div class="gap"></div>
      <div class="column">
        <article class="message is-dark">
          <div class="message-header">
            <p class="title has-text-warning">Cannabis Data Incentivised</p>
            <button class="delete" aria-label="delete"></button>
          </div>
          <div class="message-body">
             Record your Marijuana related transactions by weight. Each data entry is also an entry into a weed raffle/lottery payed out monthly automated direct fair with opprotunity to marijuana based businesses and average consumers both to increase their odds and therefore winnings 
          </div>
        </article>
      </div>
      <div class="column">
        <article class="message is-success">
          <div class="message-header">
            <p class="title has-text-dark">A 420Friendly Rideshare</p>
            <button class="delete" aria-label="delete"></button>
          </div>
          <div class="message-body">
           Providing our userbase with the worlds first 420 friendly auction based rideshare Dapp where Drivers can look for customer offering bids riders can in our service enter destination addresses or draw their route on their map location data when submiting offers
          </div>
        </article>
      </div>
      <div class="column">
        <article class="message is-primary">
          <div class="message-header">
          <p class="title has-text-white">Evolving Canna-Culture</p>
          <button class="delete" aria-label="delete"></button>
          </div>
          <div class="message-body">
            Introducing the Mary J Watson smartshop standard(details in the WP). Cannabis culture from Farmer and Trimers to shop Owners and canabis consumers. All can and should benifit from this ecosystems structure. Allowing Hemp based businesses to thrive/grow digitaly    
          </div>
        </article>
    </div>
<iframe width="760" height="515" src="https://www.youtube-nocookie.com/embed/A9i6rgbm40s" frameborder="0" allow="accelerometer; autoplay; encrypted-mediap; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>


