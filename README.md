<!DOCTYPE html>
<html>
<head>
  <title>Bana's Travel Blog</title>
  <link href="https://fonts.googleapis.com/css?family=Roboto:300,400" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css?family=Merriweather:300,400" rel="stylesheet">
  <link rel="stylesheet" type="text/css" href="reset.css">
  <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
  <div id="banner">
    <h1>Bana's Travel Blog</h1>
  </div>
  <div id="blog">
    <div class="post">
      <h2>Saturday Market</h2>
      <h3>January 7th</h3>
      <strong class="opening-line">On Saturday, Dilara took us to the market.</strong>
      <p>It is a wonderfully eclectic mix of goods from all over the world - delightfully random. I dusted off my bargaining skills to buy a metal bracelet with camels on it, and Maggie bought a lapis lazuli necklace from Afghanistan. In the evening, we walked along Gulf Road towards the marina, passed through Marina Mall, and ate dinner at a wonderful little cafe that we will definitely be frequenting. I’ve developed a slight obsession with lentil soul... maybe it’s because I miss Foco’s Indian lentil chili.</p>
      <div class="image-container">
        <img src="market.jpg" />
      </div>
      <p>We took a catamaran from the marina to Failaka Island, where we got to explore a bit, relax on the beach, and go swimming. The water in the Gulf is incredibly still; I haven’t seen a wave yet, and when you look out on the horizon it seems to go forever. Something about the color of the water and maybe the dust in the air make it seem hazier than the Atlantic coast. I have some cool pictures of the city skyline as we returned on the boat.</p>
      <p>That night, I hung out in a cafe with two friends, drinking traditional lemonade with mint. It’s delicious; maybe I should send in a flavor suggestion to Morano Gelato? Then we drove around the city for a while. Cruising around is a really valid way to spend the time when a tank of gas costs about seven bucks. </p>
    </div>
    <div class="images">
      <div class="image-container">
        <img src="camel.jpg" />
      </div><!--
      Adding comment to ensure no whitespace between inline-block div elements from HTML file.
      --><div class="image-container">
        <img src="map.png" />
      </div>
    </div>
  </div>
  <footer>
    <span>&copy; Bana’s Travel Blog</span>
  </footer>
</body>
</html>


css.

/* Universal Styles */

html {
font-size: 16px;
}

body {
  background-color: white;
}

.image-container {
  overflow: hidden;
  
}

.image-container img {
  max-width: 100%;
  height: auto;
  display: block;
}

/* Banner Section */

p {
  min-width: 200px;
  min-height: 200px;
}

#banner {
  height: 46rem;
  background-image: url('camel-background.png');
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

#banner h1 {
  font-size: 3.75rem;
  font-family: 'Roboto', sans-serif;
  font-weight: 300;
  color: white;
}

/* Blog Post */

#blog {
  width: 86%;
  margin: auto;
  display: flex;
  flex-direction: column;
  align-items: center;
}

#blog .post {
 margin-top: 12.5%;
 margin-bottom: 7.5%;
  
width: 52%;
  display: flex;
  flex-direction: column;
  align-items: center;
  font-family: 'Merriweather', serif;
  font-weight: 300;
  font-size: 1rem;
  text-align: center;
  line-height: 1.8;
  color: #444444;
}

.post h2 {
  font-size: 1.875rem;
  
}

.post h3 {
  font-size: 1.125rem;
  color: #999999;
}

.post .opening-line {
  margin-top: 4.1875rem;
  margin-bottom: 1.5rem;
  color: black;
  font-weight: bold;
}

.post .image-container {
  width: 100%;
  min-width: 200px;
}

/* Blog Images */

.images {
  width: 50%;
  margin-bottom: 20%;
}

.images .image-container {
  display: inline-block;
  width: 50%;
}

/* Footer */

footer {
  padding: 4rem 0;
  border-top: 1px solid #999999;
  font-family: 'Roboto', sans-serif;
  font-size: 1.125rem;
  color: #999999;
  text-align: center;
}
