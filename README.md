# practice_one_repo
Jarrett McGlynn First practice RUn.


<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Hammersmith+One&family=Notable&display=swap" rel="stylesheet">

<header>
  <h1>Jake’s Eatery</h1>
  <nav>
    <ul>
      <li><a href="menu.html">Menu</a></li>
      <li><a href="location.html">Our Location</a></li>
      <li><a href="about.html">About Us</a></li>
      <li><a href="text.html">Text Us</a></li>
      <li><a href="order.html">Order Online</a></li>
    </ul>
  </nav>
</header>
<article>
  <h2>Customer Recommendations</h2>
  <p>Our menu is full of delicious dishes and innovative offerings. Try out some of our customer favorites.</p>
  <div class="card-container">
    <div class="card">
      <h3>Porterhouse Steak</h3>
      <img src="https://assets.codepen.io/6306176/jakes-steak.jpg" alt="Sliced Porterhouse steak on a wooden board.">
      <p> Porterhouse features a flavorful strip and filet tenderloin together. Seasoned with our special blend of herbs and spices then seared.</p>
    </div>
    <div class="card">
      <h3>Chicken Tortilla Soup</h3>
      <img src="https://assets.codepen.io/6306176/jakes-soup.jpg" alt="Soup is topped with fried tortilla shreds and avocado chunks.">
      <p>Warm up with a delicious bowl of our chicken tortilla soup. It our #1 bestseller.</p>
    </div>
    <div class="card">
      <h3>Cheesecake</h3>
      <img src="https://assets.codepen.io/6306176/jakes-cheesecake.jpg" alt="Slice of cheesecake with strawberry topping and whipped cream.">
      <p>The perfect end to any meal! What’s better than a classic cheesecake?</p>
    </div>
  </div>
</article>
<section>
  <p>Explore the menu by section:</p>
  <ul>
    <li><a href="breakfast.html">Breakfast</a></li>
    <li><a href="lunch.html">Lunch</a></li>
    <li><a href="appetizers.html">Appetizers</a></li>
    <li><a href="dinner.html">Dinner</a></li>
    <li><a href="dessert.html">Dessert</a></li>
  </ul>
</section>
<footer>
    <p>&copy;2022 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.</p>
  <p><small>This site is operated by Trilogy Education Services for educational purposes only. This is not a restaurant website. This is a fictitious company and scenario intended only for internal academic purposes.</small></p>
  <ul>
    <li>
      <a href="https://facebook.com" target="_blank">
        <span aria-hidden="true" class="fa-brands fa-facebook-square"></span>
        <span class="sr-only">Facebook</span>
      </a>
    </li>
    <li>
      <a href="https://twitter.com" target="_blank">
        <span aria-hidden="true" class="fa-brands fa-twitter-square"></span>
        <span class="sr-only">Twitter</span>
      </a>
    </li>
    <li>
      <a href="https://instagram.com" target="_blank">
        <span aria-hidden="true" class="fa-brands fa-instagram-square"></span>
        <span class="sr-only">Instagram</span>
      </a>
    </li>
  </ul>
</footer>

[class*="col-"] {
  width: 100%;
}{
  box-sizing: border-box;
}body {
    font-family: 'Hammersmith One', sans-serif;
  background-color: #E5DDC8;
  padding: 0;
  margin: 0;
  line-height: 1.5;
}
h1 {
font-family: 'Notable', sans-serif;
  color: #DB1F48;
  text-align: center;
}
img {
  max-width: 100%;
}
nav ul {
  list-style-type: none;
  padding: 0;
  margin: 0;
  background-color: #004369;
  text-align: center;
  border-top: 10px double #01949A;
  border-bottom: 10px double #01949A;
}
nav li {
  display: inline-block;
}
nav a {
  color: #ffffff;
  display: block;
  padding: 0.5rem;
  text-decoration: none;
}
nav a:hover {
  color: #E5DDC8;
}
article {
  padding: 1rem;
}
.card-container {
  display: flex;
  flex-flow: row wrap;
  justify-content: space-between;
}
.card {
  flex-basis: 30%;
  border-radius: 10px;
  border: 2px solid 
#004369;
  background-color: #eeFFFF;
}
.card h3, 
.card  p {
  padding: 0 0.5rem;
}
section {
  padding: 1rem;
}
section ul {
  list-style-type: none;
  padding: 0;
  margin: 0;
}
section li {
  display: inline-block;
}
section a {
  display: block;
  background-color: #DB1F48;
  padding: 0.5rem;
  margin-right: 1rem;
  border-radius: 10px;
  color: #ffffff;
  text-decoration: none;
  /* although the border doesn't show much here, if you only place it on the hover, the button "twitches" with the extra width of the border. Place it here and that "twitch" doesn't happen. */
  border: 1px solid #db1f48;
}
section a:hover {
  background-color: #ffffff;
  color: #db1f48;
  border: 1px solid #db1f48;
}

footer {
  background-color: #004369; 
  color: #ffffff;
  padding: 1rem;
  text-align: center;
  border-top: 10px double #01949A;
  margin-top: 3rem;
}

footer ul {
  list-style-type: none;
  padding: 0;
  margin: 0;
  display: flex;
  flex-flow: row wrap;
  justify-content: center;
}
footer a {
  color: #f2f2f2;
  font-size: 2rem;
  display: block;
  margin: 0 1rem 3rem 1rem;
}
