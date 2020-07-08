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
      <article class="message is-danger">
        <div class="message-body">
        <h2>I know what your all thinking <i>Oh boy,Yet Another ERC20 token</i></h2>
        </div>
      </article>
      <article class="message is-warning">
        <div class="message-body">
          <h3><b> So without reading the technical WP heres all you need to know in neat bundles below</b></h3>
        </div>      
      </article>
      <div class="gap"></div>
      <div class="column">
        <article class="message is-dark">
          <div class="message-header">
            <p>Dark</p>
            <button class="delete" aria-label="delete"></button>
          </div>
          <div class="message-body">
             Lorem ipsum dolor sit amet, consectetur adipiscing elit. <strong>Pellentesque risus mi</strong>, tempus quis placerat ut, porta nec nulla. Vestibulum rhoncus ac ex sit amet fringilla. Nullam gravida purus diam, et dictum <a>felis venenatis</a> efficitur. Aenean ac <em>eleifend lacus</em>, in mollis lectus. Donec sodales, arcu et sollicitudin porttitor, tortor urna tempor ligula, id porttitor mi magna a neque. Donec dui urna, vehicula et sem eget, facilisis sodales sem.
          </div>
        </article>
      </div>
      <div class="column">
        <article class="message is-success">
          <div class="message-header">
            <p>Success</p>
            <button class="delete" aria-label="delete"></button>
          </div>
          <div class="message-body">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. <strong>Pellentesque risus mi</strong>, tempus quis placerat ut, porta nec nulla. Vestibulum rhoncus ac ex sit amet fringilla. Nullam gravida purus diam, et dictum <a>felis venenatis</a> efficitur. Aenean ac <em>eleifend lacus</em>, in mollis lectus. Donec sodales, arcu et sollicitudin porttitor, tortor urna tempor ligula, id porttitor mi magna a neque. Donec dui urna, vehicula et sem eget, facilisis sodales sem.
          </div>
        </article>
      </div>
      <div class="column">
        <article class="message is-primary">
          <div class="message-header">
          <p>Info</p>
          <button class="delete" aria-label="delete"></button>
          </div>
          <div class="message-body">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. <strong>Pellentesque risus mi</strong>, tempus quis placerat ut, porta nec nulla. Vestibulum rhoncus ac ex sit amet fringilla. Nullam gravida purus diam, et dictum <a>felis venenatis</a> efficitur. Aenean ac <em>eleifend lacus</em>, in mollis lectus. Donec sodales, arcu et sollicitudin porttitor, tortor urna tempor ligula, id porttitor mi magna a neque. Donec dui urna, vehicula et sem eget, facilisis sodales sem.
          </div>
        </article>
    </div>
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


