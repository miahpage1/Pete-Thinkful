<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pete Thinkful</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/8.0.1/normalize.min.css">
  <link href="style.css" rel="stylesheet" type="text/css">
</head>

<body>
  <header>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#portfolio">Portfolio</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>


  <main>
    <div>
      <section id="about">
        <h2>About</h2>
        <article>
          <h3>Hi! I'm Pete Thinkful</h3>
          <p>Pete's image can be found in the <code>images/</code> folder, titled <code>pete-thinkful.png</code>. You should set the alt text of the image element to Pete Thinkful.</p>
          <img class="image-circle" src="images/pete-thinkful.png" alt="Pete Thinkful">
          <h3>Pete's Background</h3>
          <p>Producing abstract art</p>
          <p>Creating street graffiti art</p>
          <p>Connecting with like-minded artists</p>
          <p>Please feel free to take a look at my website and feel free to <a href="#contact">contact me</a>.</p>
        </article>
      </section>
      
      <article>
        <div>
          <img class="image-circle" src="images/pete-thinkful.png" alt="Pete Thinkful">
        </div>
      </article> 

      <hr>

      <section id="portfolio">
        <h2>Portfolio</h2>
        <article>
          <h3>Abstract Red</h3>
          <img src="images/abstract-red.png" alt="Abstract Red">
          <p>Vaporware wayfarers heirloom neutra disrupt. Activated charcoal waistcoat scenester hell of.</p>
        </article>
        <article>
          <h3>Spiral Zany</h3>
          <img src="images/spiral-zany.png" alt="Spiral Zany">
          <p>Sriracha portland taxidermy cronut messenger bag, vegan distillery. Vaporware kickstarter air plant mumblecore food truck.</p>
        </article>
        <article>
          <h3>Melted Rainbow</h3>
          <img src="images/melted-rainbow.png" alt="Melted Rainbow">
          <p>Edison bulb single-origin coffee snackwave, actually ennui locavore shabby chic forage.</p>
        </article>
      </section>
        </article> 
        <div>
          <img src="images/abstract-red.png" alt="Abstract Red">
        </div>
        <div>
          <img src="images/spiral-zany.png" alt="Spiral Zany">
        </div>
        <div>
          <img src="images/melted-rainbow.png" alt="Melted Rainbow">
        </div>
      </article>

      <hr>

      <section id="contact">
        <h2>Contact</h2>
        <p>I'd love to hear from you! Please feel free to contact or follow me:</p>
        <ul>
          <li><a href="#">LinkedIn</a></li>
          <li><a href="#">Instagram</a></li>
          <li><a href="#">Pinterest</a></li>
        </ul>
      </section>
      
    </div>
  </main>

  <!-- Footer section -->
  <footer>
    <p>© Pete Thinkful. All rights reserved.</p>
  </footer>
</body>

</html>

/* The @import rule below imports the Playfair Display and Source Sans Pro fonts into the stylesheet. You don't have to edit this line.*/
@import url("https://fonts.googleapis.com/css2?family=Playfair+Display&family=Source+Sans+Pro:wght@400&display=swap");

body {
  color: #003049;
  font-family: "Source Sans Pro", Tahoma, Geneva, Verdana, sans-serif;
  padding: 40px;
  background-color: #eae2b7; /* Set the background color of the page */
  text-align: center; /* Center align contents of header and footer */
}

/* Set the font family for any h1, h2, or h3 heading */
h1,
h2,
h3 {
  font-family: "Playfair Display", Times, serif;
}

article {
  padding: 50px 0;
}

article div {
  text-align: center;
  width: 100%;
}

p {
  line-height: 1.5;
}

/* The div container constrains the content width within the main container to 600px */
div {
  margin: auto;
  width: 600px;
}

img {
  width: 100%;
  max-width: 200px;
  height: auto;
}

hr {
  border: 1px solid black;
}

/* Add your solution below */

.image-circle {
  display: block;
  margin: 0 auto;
  width: 200px; /* Set width to match max-width of images */
  height: 200px; /* Ensure it's a square */
  border-radius: 50%; /* Make the image round */
  border: 2px solid #003049; /* Add a 2px solid border with color #003049 */
}

h2 {
  font-size: 32px; /* Larger font size for h2 (Portfolio and About headings) */
}

h3 {
  font-size: 24px; /* Smaller font size for h3 (subheadings) */
}

/* Center align headings and images in Portfolio section */
.portfolio-heading,
.project-name,
.project-image {
  text-align: center;
}

/* Anchor tag styling */
a:link {
  color: #d62828; /* Set link color */
}

a:hover {
  color: #f77f00; /* Change link color on hover */
}

/* Center align Contact heading */
.contact-heading {
  text-align: center;
}


[Pete-Thinkful-Portfolio-1.zip](https://github.com/user-attachments/files/16054710/Pete-Thinkful-Portfolio-1.zip)
