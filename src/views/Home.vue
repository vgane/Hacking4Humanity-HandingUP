<template>
  
    <div class="page" id="app">

        <section class="video">
            <h2>"We help elevate you where you want to be" -HandUp"</h2>
            <br/>
            <iframe width="900" height="500" src="https://www.youtube.com/embed/uemObN8_dcw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </section>

        <div class="gg">
            <div class="container">
                <div class="row">

                    <div class="col">
                        <img src=".\assets\warehouse-brookings.jpg" width="350" height="315"><br />
                        <div class="container">
                            <div class="row">
                                "In charity there is no excess."
                                -Francis Bacon
                                16th Century intellectual and statesman
                            </div>
                        </div>
                    </div>

                    <div class="col">
                        <img src=".\assets\maria-vertkin-workdevel-BU.jpg" width="350" height="315" />
                        <div class="container">
                            <div class="row">
                                "I think it is incumbent on
                                anyone who can to lift human
                                dignity to the highest possible
                                levels, maintaining one's own
                                and helping to raise that of others."
                                -Henry Rollins
                                musician, activist
                            </div>
                        </div>
                    </div>

                    <div class="col">
                        <img src=".\assets\youngProfessional-unsplash.jpg" width="350" height="315" />
                        <div class="container">
                            <div class="row">
                                "No one has ever become poor by giving."
                                Anne Frank
                                -writer, WWII refugee
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>


        <div class="testimonials">
            <div class="container-test">
                <p><span>John</span></p>
                <p>"I love HandUp.  I first used it for a jobseeking profile after I got evicted and didn't have a place to stay.  The online resume and profile got me my current job with Phat Beets, a local food justice non-profit.  I've also told my friend about HandUp, he used it to get a tooth filling, and without it he couldn't find time a low-cost dentist near him."</p>
            </div>

            <div class="container-test">
                <p><span>Sania</span></p>
                <p>
                    "HandUp has helped me make ends meet.  Since I joined, I've gotten more donations from people I've never met.  My disability checks don't go far enough, living in San Jose. Thank you HandUp for your help."
                </p>
            </div>

            <div class="container-test">
                <p><span>Aman</span></p>
                <p>"HandUp has given my kid and I some more spending money.  We used it right away on essentials, my kid got school supplies last month with the $20 we got in total donations. used hand up to help connect to employers."</p>
            </div>
        </div>

        <div class="container" id="createProfilebutton">
            <div class="row">
                <div class="col">

                    <button href="/createProfile" class="btn">
                        Click Here to Make Your Profile
                    </button>
                </div>
            </div>
        </div>


    

        <footer>
            <div class="socialmedia">
                <a href="https://twitter.com"><img src=".\assets\twitter.png" alt="twitter" title="twitter" />   |    </a>

                <a href="https://www.facebook.com"><img src=".\assets\facebook.png" alt="facebook" title="facebook" />  |   </a>
                <a href="https://www.instagram.com"><img src=".\assets\ig.png" alt="instagram" title="instagram" />  |   </a>
                <p>&copy; 2019 HandUp</p>
            </div>
        </footer>


    </div>
</template>

<script>

//import axios from 'axios';
    export default {
        name: 'Home',
        components: {
        }
           
        }

</script>

<style>
   
    .testimonials{
        padding-top:10px;
        background-color:#1F2041;
    }
    .gg{
        background-color:#5F6062;        
        padding-right:100px;
        padding-left:100px;
        color:white;
        text-shadow:0.5px 2px #000000;   

    }
  body {
    font-family: Arial, Helvetica, sans-serif;
    line-height: 1.4;
  }
  .video{
      padding-top:10px;
      padding-left:15%;
      margin: auto;  
      background-color: #5Ec4BB;
      border:solid 20px white;
      padding-bottom:10px;
      background-size:contain;

  }


  .btn {

    border: initial;
    background-color: #CA2E55;
    color: white;   
    vertical-align: middle;
  }

  #createProfilebutton{
      padding-bottom:30px;
  }


    .container-test img {
    margin: auto;
    float: none;
    display: block;
  }

    p {
     font-family: 'Montserrat', sans-serif;
	text-align: center;
}

.socialmedia {
	display: inline;
	font-family: 'Montserrat', sans-serif;
}

footer img {
	height: 25px;
}

footer {
	background: black;
    font-family: 'Oswald', sans-serif;
    padding-bottom:10px;
    color:white;
}

.row{
     font-family: 'Oswald', sans-serif;
}

body {
	font-family: 'Archivo Narrow', sans-serif;
}

.container {
	margin: 0 auto;
	text-align: center;
  padding-top: 20px ;
}

aside, article {
  text-shadow: 1px 1px 1px grey;
}
.quotes{

font-family: 'Montserrat', sans-serif;
}

h2 {
	
    font-family: 'Montserrat', sans-serif;
}

.qsection {
display: flex;
}

.qsection img {
	width: 100%;
  height: 260px;
  max-width: 600px;
}


    #button-font{
        color:white;
    }
.container-test {
  border: 2px solid #ccc;
  background-color: #eee;
  border-radius: 5px;
  padding: 16px;
  margin: 16px 0;
}

/* Clear floats after containers */
.container-test::after {
  content: "";
  clear: both;
  display: table;
}

/* Float images inside the container to the left. Add a right margin, and style the image as a circle */
.container-test img {
  float: left;
  margin-right: 20px;
  border-radius: 50%;
}

/* Increase the font-size of a span element */
.container-test span {
  font-size: 20px;
  margin-right: 15px;
}

.container-test img {

    float: none;
    display: block;
  }

.page{
    background-color:white;
}

iframe{
    border-radius:20px;
    border-color:white;
    border:5px solid white ;

}


</style>

