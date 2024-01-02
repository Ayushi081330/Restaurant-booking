# Restaurant-booking


<!DOCTYPE html>
<html lang="en">
<head>
 <link rel="stylesheet" href="vansh1.css">
 <link rel="stylesheet" href="styles.css">
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>Delicious Bites Restaurant</title>
</head>
<body background="C:\Users\Hp\OneDrive\Desktop\1b71d8b8-c986-4458-8dd5-
d68b78e2723a.jpeg">
 
 <nav class="navbar" id="home">
 
 <div class="logo"><img src="C:\Users\Hp\OneDrive\Desktop\f9a737d0-d10e-41ce-9674-
0f3b15c3de6e.jpeg" alt="Delicious Bites Logo"></div>
 <div class="h2">Delicious Bites</div>
 <ul class="nav-list">
 <li><a href="#">Home</a></li>
 <li><a href="#about">About</a></li>
 <li><a href="#menu">Menu</a></li>
 <li><a href="#contact">Contact</a></li>
 </ul>
 </nav>
 <form id="restaurantForm">
 <div class="options">
 <label for="restaurantType">Select a restaurant type:</label>
 <select id="restaurantType" name="restaurantType">
 <option value="choose your type">select your type</option>
 <option value="Vegetarian">Vegetarian</option>
 <option value="Non-Vegetarian">Non-Vegetarian</option>
 <option value="Italian">Italian</option>
 <option value="Chinese">Chinese</option>
 </select>
 </div>
 <button type="submit" class="button">Submit</button>
 </form>
 <section class="background firstsection">
 <div class="box-main">
 <div class="firsthalf">
 <h1 class="text-big1">welcome to our website , here you get best meals of day</h1>
 <p class="text-small">Experience a world of flavors and aromas that will tantalize your taste 
buds.</p>
 <div class="button">
 <a href="#menu" class="btn">View Menu</a>
 <a href="#contact" class="btn">Make a Reservation</a>
 </div>
 </div>
 <div class="secondhalf">
 
 </div>
 </div>
 </section>
 <section class="section" id="about">
 <div class="paras">
 <h2 class="sectiontag text-big">Our Story</h2>
 <p class="sectionsubtag text-small">
 At Delicious Bites Restaurant, we believe in crafting exceptional dining experiences. Our 
passion for food, combined with our commitment to quality ingredients, results in dishes that are a 
true culinary delight. From traditional favorites to innovative creations, our diverse menu caters to 
every palate.
 </p>
 </div>
 <div class="thumbnail">
 
 </div>
 </section>
 <section class="section section-left" id="menu">
 <div class="paras">
 <h2 class="sectiontag text-big">Explore Our Menu</h2>
 <p class="sectionsubtag text-small">
 Our menu is a symphony of flavors, bringing together the finest ingredients and expert 
craftsmanship. From appetizers to desserts, each dish is a masterpiece that reflects our dedication to 
culinary excellence.
 </p>
 </div>
 <div class="thumbnail">
 
 </div>
 </section>
</div>
 <section class="contact" id="contact">
 <h2 class="text-center">BOOK YOUR RESERVATION</h2>
 <div class="form">
 <input class="form-input" type="text" name="name" id="name" placeholder="Full Name" 
required>
 <input class="form-input" type="tel" name="phone" id="phone" placeholder="Phone Number" 
required>
 <input class="form-input" type="email" name="email" id="email" placeholder="Email Address" 
required>
 <textarea class="form-input" id="message" cols="30" rows="6" placeholder="Your Message" 
required></textarea>
 <button class="btn-dark" id="submitBtn">Submit</button>
 <p id="confirmationMessage"></p>
 </div>
 </section>
 <footer class="">
 <p class="text-footer">
 &copy; 2023 Delicious Bites Restaurant - All rights reserved.
 </p>
 </footer>
 
 <script>
 document.getElementById("restaurantForm").addEventListener("submit", function(event) {
 event.preventDefault(); // Prevent form submission
 
 const selectedOption = document.getElementById("restaurantType").value;
 
 if (selectedOption === "Italian") {
 window.open("https://www.zomato.com/chandigarh/best-italian-restaurants", "_blank");
 } else if (selectedOption === "Chinese") {
 window.open("https://www.zomato.com/chandigarh/best-chinese-restaurants", "_blank");
 } else if (selectedOption === "Vegetarian") {
 window.open("https://www.zomato.com/chandigarh/best-chandigarh-city￾restaurants?veg=1", "_blank");
 } else if (selectedOption === "Non-Vegetarian") {
 window.open("https://crazymasalafood.com/20-best-non-veg-restaurants-chandigarh/", 
"_blank");
 }
 
 
 });
 function generateRandomTableNumber() {
 return Math.floor(Math.random() * 50) + 1; // Change the range as needed
 }
 // Function to update the confirmation message
 function updateConfirmationMessage(name, tableNumber) {
 const confirmationMessage = document.getElementById('confirmationMessage');
 confirmationMessage.textContent = `Thanks for booking, ${name}! Your table number is 
${tableNumber}.`;
 }
 // Event listener for the submit button
 const submitBtn = document.getElementById('submitBtn');
 submitBtn.addEventListener('click', function() {
 const nameInput = document.getElementById('name');
 const phoneInput = document.getElementById('phone');
 const emailInput = document.getElementById('email');
 const name = nameInput.value.trim();
 const phone = phoneInput.value.trim();
 const email = emailInput.value.trim();
 if (name === '' || phone === '' || email === '') {
 alert('Please fill in all fields before submitting.');
 return;
 }
 const randomTableNumber = generateRandomTableNumber();
 updateConfirmationMessage(name, randomTableNumber);
 });
 
 </script>
 
</body>
</html>
<style>
* {
 margin: 0;
 padding: 0;
 box-sizing: border-box;
}
.h2{
 font-size:1.5rem ;
 
 font-family:cursive;
 text-align: center;
 font-weight: 800;
 
 
 
}
.h2::first-letter{
 color:#3498db;
font-size: 2.1rem;
font-weight: 800;
 
}
/* Set default font and color for the body */
body {
 font-family: Arial, sans-serif;
 color: #333;
 background-color: #f8f8f8;
}
/* Style the navigation bar */
.navbar {
 display: flex;
 align-items: center;
 justify-content: space-between;
 background-color: #fff;
 padding: 10px 20px;
 box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
position: sticky;
 top:0;
}
.nav-list {
 list-style: none;
 display: flex;
}
.nav-list li {
 margin-right: 20px;
}
.nav-list li a {
 text-decoration: none;
 color: #333;
 font-weight: bold;
 transition: color 0.3s ease;
}
.nav-list li a:hover {
 color: #007bff;
}
/* Style the header section */
.firstsection {
 background-color: rgba(0,0,0,0.7);
 color: #fff;
 padding: 80px 0;
 text-align: center;
 position: relative;
}
.firsthalf {
 width: 50%;
 padding: 0 20px;
}
.text-big {
 font-size: 36px;
 margin-bottom: 15px;
}
.text-small {
 font-size: 28px;
font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, 
Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
font-weight:600;
color:white;
}
.button {
 margin-top: 30px;
}
.btn {
 display:flex;
 padding: 10px 20px;
 background-color: transparent;
 color: white;
 border: none;
 border-radius:6px;
 text-decoration: none;
 font-weight: bold;
 transition: background-color 0.3s ease;
}
.btn:hover {
 background-color: #0056b3;
display:flex;
 padding: 10px 20px;
color: white;
 border: none;
 border-radius:6px;
 text-decoration: none;
 font-weight: bold;
 transition: background-color 0.3s ease;
}
/* Style the about and menu sections */
.section {
 padding: 80px 0;
 display: flex;
 align-items: center;
 justify-content: space-between;
 
}
.sectiontag {
 font-size: 32px;
 margin-bottom: 15px;
color:black;
 font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
.sectionsubtag {
 font-size: 18px;
}
.thumbnail img {
 max-width: 100%;
 border-radius: 10px;
 box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}
/* Style the contact section */
.contact {
 background-color: #f7f7f7;
 padding: 80px 0;
 text-align: center;
}
.form-input {
 width: 100%;
 padding: 10px;
 margin: 10px 0;
 border: 1px solid #ccc;
 border-radius: 5px;
}
.btn-dark {
 padding: 10px 20px;
 background-color: #333;
 color: #fff;
 border: none;
 border-radius: 5px;
 font-weight: bold;
 cursor: pointer;
 transition: background-color 0.3s ease;
}
.btn-dark:hover {
 background-color: #000;
}
/* Style the footer */
.text-footer {
 font-size: 16px;
 text-align: center;
 padding: 20px 0;
 background-color: #333;
 color: #fff;
}
/* Add your custom CSS for the restaurant type selection here */
.restaurant-form-container {
 display: flex;
 justify-content: center;
 align-items: center;
 background-color: #f8f8f8;
 padding: 20px 0;
 border-bottom: 1px solid #ccc;
}
#restaurantForm {
 display: flex;
 align-items: center;
 justify-content: center;
 flex-direction: column;
 width: 100%;
 max-width: 400px;
 margin: 0 auto;
}
.options {
 display: flex;
 align-items: center;
 margin-bottom: 20px;
}
.options label {
 font-size: 18px;
 margin-right: 10px;
}
#restaurantType {
 padding: 8px;
 font-size: 16px;
 border: 1px solid #ccc;
 border-radius: 6px;
 flex: 1;
}
.button {
 width: 100%;
 max-width: 200px;
 height: 40px;
 font-size: 16px;
 text-transform: capitalize;
 font-weight: 600;
 border: none;
 border-radius: 6px;
 background-color: #3498db;
 color: white;
 cursor: pointer;
 transition: background-color 0.3s;
 font-family: Arial, Helvetica, sans-serif;
}
.button:hover {
 background-color: #2980b9;
}
.logo img{
width:4.9rem;
height:4.1rem;
border-radius:50%;
outline:1px solid rgba(0,0,0,0.5);
}
body{
background-size:cover;
background-blend-mode:darker;
background-repeat:no-repeat;
}
label{
color:rgb(35, 23, 23);
font-size:1.9rem;
font-weight:800;
}
@keyframes bounce {
 0%, 100% {
 transform: translateY(0);
 }
 
 50% {
 transform: translateY(-10px);
 }
}
.text-big1{
 animation: bounce 2s infinite;
font-size:1.3rem;
}
</style>
