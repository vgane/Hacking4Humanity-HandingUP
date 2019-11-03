<template>
    <header class="header">
        <img src="./logoHandup.jpg" max-width="250" height="100" />
        <h1>HandUp</h1>
        <div id="nav">
            <router-link to="/" padding-right="5%">  Home </router-link>|
            <router-link to="/createProfile">Create Profiles</router-link>
        </div>
    </header>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style scoped>
  .header {
    background: #333;
    color: #fff;
    display: flex;
    padding: 10px;
  }

  .header-image{
      padding-right:80%;
  }
  .navPick{
      padding-right:70px;
  }

  h1{
      padding-top:50px;
      padding-left:37%;
  }
  .header a {   
    color: #fff;
    padding-right: 5px;
    text-decoration: none;
  }
 
  #nav{
    display:inline-block;
    padding-left:25%;
    padding-top:70px;
    font-family: 'Oswald', sans-serif;
    font-size:1.5em;
  }
  
</style>


