<template>
  <header>
    <ul>
      <li><router-link to="/">Home</router-link></li>
      <li><router-link to="/about">About</router-link></li>
    </ul>

    <h1>{{ message }}</h1>
  </header>
</template>

<script>
export default {
  props: {
    message: String
  }
}
</script>

<style>
  header{
    background-image: url('../../static/media/header-bg.jpeg');
    color: #fff;
    overflow: hidden;
    text-align: center;
  }
  header ul{
    display: flex;
    flex-direction: row;
    justify-content: flex-end;
  }
  header ul li a{
    font-size: 0.8rem;
    padding: 1rem;
    opacity: 1;
    transition: opacity .4s;
    display: block;
    color: #fff;
    text-decoration: none;
  }
  header h1{
    font-size: 3rem;
    font-weight: 400;
    padding: 5rem 0;
  }

</style>
