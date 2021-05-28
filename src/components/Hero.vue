<template>
  <div id="hero">
    <div id="hero_text">
      <h2>Jumbotron Title</h2>
      <h3>jumbotron info Lorem, ipsum dolor sit amet consectetur adipisicing elit. Optio amet culpa sunt magni corporis explicabo, quos quo nesciunt quae aspernatur nulla vel iusto unde autem dicta ratione deleniti excepturi expedita.</h3>
      </div>
  </div>
</template>

<script>
export default {
    name: 'Hero'
}
</script>

<style>
    #hero {
        width: 100%;
        height: 500px;
        margin: auto;
        background-color: blue;
    }
    #hero_text {
        width: 50%;
    }
    #hero_text h2 {
        font-size: 100px;
        color: white;
    }
</style>