# Ex.07 Software Product Company Website
## Date:

## AIM:
To develop a static company website to display the softwares and services provided by the company.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
## index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Software product development company</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="slider.css">
</head>
<body>
    <header>
        <ul>
            <li><a href="AboutUs.html">About Us</a></li>
            <li><a href="Products.html">Products</a></li>
            <li><a href="Resources.html">Resources</a></li>
            <li><a href="ContactUs.html">Contact Us</a></li>
        </ul>
    </header>
    <!-- Slideshow container -->
<div class="slideshow-container">

    <!-- Full-width images with number and caption text -->
    <div class="mySlides fade">
      <div class="numbertext">1 / 3</div>
      <img src="DS-1.png" style="width:100%">
    </div>
  
    <div class="mySlides fade">
      <div class="numbertext">2 / 3</div>
      <img src="DS-2.png" style="width:100%">
    </div>
  
    <div class="mySlides fade">
      <div class="numbertext">3 / 3</div>
      <img src="DS-3.png" style="width:100%">
    </div>
  
    <!-- Next and previous buttons -->
    <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
    <a class="next" onclick="plusSlides(1)">&#10095;</a>
  </div>
  <br>
  
  <!-- The dots/circles -->
  <div style="text-align:center">
    <span class="dot" onclick="currentSlide(1)"></span>
    <span class="dot" onclick="currentSlide(2)"></span>
    <span class="dot" onclick="currentSlide(3)"></span>
  </div>
  <footer>
    <p>&copy;2024 THANGA DEEPIKA R. All rights reserved.</p>
  </footer>
    <script src="slider.js"></script>
</body>
</html>
```
## AboutUs.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us</title>
</head>
<body>
    h1>About Us</h1>
<img src="AboutUs-1.png" alt="">
<p>The world is evolving rapidly with transformative technological advancements, dynamic changes in economies, and a shifting global landscape. These changes make it challenging for our people, clients, partners, and communities to navigate the evolving landscape. At RTR, we constantly push the boundaries of what’s possible by leveraging our expertise, experience, and innovative ecosystem to empower enterprises, people, and communities to build a better Future, Faster. Together. To achieve this, we drive business transformation using what we are good at—technology, talent, and a robust ecosystem of partners—to eliminate all barriers to progress. Our commitment is to a singular goal: to relentlessly ensure our clients become their future sustainable selves ahead of schedule.

    We want to use technology to build intimacy, warmth, and empathy through the experiences we create. Our purpose is to unleash new possibilities and impact every human we touch. Our net-zero pledge leverages renewable energy, waste management, and a focus on the practices of a circular economy to ensure a healthier, safer, and more sustainable business.
    
    Our vision lets us be as ambitious as we want to be. It allows us to think beyond what we did until yesterday. Today, we have become the catalyst that takes all our stakeholders to the future, faster. Together.</p>
    <footer>
        <p>&copy;2024 THANGA DEEPIKA R. All rights reserved.</p>
      </footer>
</body>
</html>
```
## Products.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Data Science Software Products - Company Name</title>
<style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        background-color: #f4f4f4;
    }
    .container {
        max-width: 1200px;
        margin: 0 auto;
        padding: 20px;
    }
    header {
        background-color: #333;
        color: #fff;
        padding: 10px 20px;
        text-align: center;
    }
    h1, h2 {
        margin: 20px 0;
    }
</style>
</head>
<body>

<header>
    <h1>Data Science Software Products</h1>
</header>

<div class="container">
    <div class="product">
        <h2>REDaxis</h2>
        <img src="Products-1.png" alt="Product 1">
        <div class="product-details">
            <p>Description: A Design Thinking approach to problem-solving and identification of the most lucrative business opportunities. Powered by Fosfor , solutions developed for ERP customers, specializing in streamlined data sourcing and simplification of data development.</p>
            <p>Features:</p>
            <ul>
                <li>Context / Role-based Analytics Insights through Dashboards/Reports.</li>
                <li>Enhanced User Experience through advanced visualizations and Mobile BI.</li>
                <li>Executive Insights highlighting priorities among the Business As Usuals.</li>
            </ul>
            <a href="#" class="btn">Learn More</a>
        </div>
    </div>

    <div class="product">
        <h2>Unitrax</h2>
        <img src="Products-2.png" alt="Product 2">
        <img src="Products-3.png" alt="">
        <div class="product-details">
            <p>Description: Single version system auto-switching and household assettiering capabilities. Built-in, robust indexing capabilities, to extract records for a user-defined date, promptly upon request.</p>
            <p>Features:</p>
            <ul>
                <li>Built for 360o administration of insurance wealth products.</li>
                <li>Streamlines administration of a wide range of investment vehicles.</li>
                <li>Supports all Canadian registration types (e.g. RDSP, RESP, TFSA, RRIF, LIF, RRSP, IPP).</li>
            </ul>
            <a href="#" class="btn">Learn More</a>
        </div>
    </div>
</div>
<footer>
    <p>&copy;2024 THANGA DEEPIKA R. All rights reserved.</p>
  </footer>

</body>
</html>
```
## Resources.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Grid Layout</title>
<style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
    }
    .grid-container {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        grid-gap: 20px;
        padding: 20px;
    }
    .person {
        text-align: center;
    }
    .person img {
        max-width: 100%;
        height: auto;
        border-radius: 50%;
    }
    .designation {
        margin-top: 10px;
        font-size: 14px;
    }
</style>
</head>
<body>
<div class="grid-container">
    <div class="person">
        <img src="Ravi.jpg" alt="Person 1">
        <div class="designation">CEO</div>
    </div>
    <div class="person">
        <img src="Suji.jpg" alt="Person 2">
        <div class="designation">Managing Director</div>
    </div>
    <div class="person">
        <img src="Shalini.jpg" alt="Person 3">
        <div class="designation">Chairwoman</div>
    </div>
    <div class="person">
        <img src="Vino.jpg" alt="Person 4">
        <div class="designation">SCRUM Master</div>
    </div>
    <div class="person">
        <img src="Yohan.jpg" alt="Person 5">
        <div class="designation">Software Developer</div>
    </div>
    <div class="person">
        <img src="Deepi.jpg" alt="Person 6">
        <div class="designation">Tester</div>
    </div>
</div>
<footer>
    <p>&copy;2024 THANGA DEEPIKA R. All rights reserved.</p>
  </footer>

</body>
</html>
```
## ContactUs.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Contact Us</title>
<style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
    }
    .container {
        max-width: 600px;
        margin: 20px auto;
        padding: 20px;
        border: 1px solid #ccc;
        border-radius: 5px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }
    h2 {
        margin-bottom: 20px;
        text-align: center;
    }
    label {
        display: block;
        margin-bottom: 5px;
    }  
</style>
</head>
<body>

<div class="container">
    <h2>Contact Us</h2>
    <form action="#" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>

        <label for="message">Message:</label>
        <textarea id="message" name="message" required></textarea>

        <input type="submit" value="Submit">
    </form>
</div>
<footer>
    <p>&copy;2024 THANGA DEEPIKA R. All rights reserved.</p>
  </footer>

</body>
</html>
```
## style.css
```
ul{
    list-style-type: none;
    text-align: right;
    
    
}
li{
    display: inline-block;
    margin-right: 4%;
   
}
a{
    text-decoration: none;
    color:white;
    font-weight: bold;
    font-size: 1.2em;
    font-family: 'Gill Sans';
}
body{
    background-color: hsl(247, 87%, 12%);
}

footer{
    background-color: hsla(240, 87%, 32%, 0.616);
    color: papayawhip;
    text-align: center;
    padding: 20px 0;
    position: fixed;
    bottom: 0%;
    width: 100%;
}
```
## slider.css
```
* {box-sizing:border-box}

/* Slideshow container */
.slideshow-container {
  max-width: 70%;
  padding-top: 3% 0%;
  position: relative;
  margin: auto;
  
}

/* Hide the images by default */
.mySlides {
  display: none;
}

/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  margin-top: -22px;
  padding: 16px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
}

/* Caption text */
@keyframes fade {
  from {opacity: .4}
  to {opacity: 1}
}
```
## OUTPUT:
![Screenshot 2024-04-28 232330](https://github.com/ThangaDeepika/softweb/assets/125663099/070a4f40-2f4c-4a86-9e39-b321ff0943a7)
![Screenshot 2024-04-28 232251](https://github.com/ThangaDeepika/softweb/assets/125663099/99174ce3-2362-4921-af48-b09539eec4f7)
![Screenshot 2024-04-28 232232](https://github.com/ThangaDeepika/softweb/assets/125663099/cef611f7-3bc3-4179-83da-15e7219a0f94)
![Screenshot 2024-04-28 232312](https://github.com/ThangaDeepika/softweb/assets/125663099/49110ea4-243c-422e-b13d-b134a2c476a9)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
