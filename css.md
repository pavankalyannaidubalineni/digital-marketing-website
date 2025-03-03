/* General Styling */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

header {
  background-color: #333;
  padding: 10px;
  position: fixed;
  width: 100%;
  top: 0;
  left: 0;
}

header nav ul {
  display: flex;
  justify-content: center;
  list-style-type: none;
}

header nav ul li {
  margin: 0 20px;
}

header nav ul li a {
  color: white;
  text-decoration: none;
  font-size: 18px;
}

header nav ul li a:hover {
  color: #f39c12;
}

.hero {
  height: 100vh;
  background-color: #1abc9c;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  color: white;
  text-align: center;
}

.hero h1 {
  font-size: 4em;
  margin-bottom: 20px;
}

.hero p {
  font-size: 1.5em;
  margin-bottom: 30px;
}

.cta-button {
  background-color: #f39c12;
  color: white;
  padding: 15px 30px;
  text-decoration: none;
  font-size: 18px;
  border-radius: 5px;
}

.cta-button:hover {
  background-color: #e67e22;
}

#services {
  padding: 50px 0;
  background-color: #ecf0f1;
  text-align: center;
}

#services h2 {
  font-size: 2.5em;
  margin-bottom: 20px;
}

.service-cards {
  display: flex;
  justify-content: center;
  gap: 30px;
}

.service-cards .card {
  background-color: white;
  padding: 20px;
  width: 250px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  border-radius: 8px;
}

.service-cards .card h3 {
  font-size: 1.8em;
  margin-bottom: 15px;
}

.service-cards .card p {
  font-size: 1em;
}

#testimonials {
  padding: 50px 0;
  background-color: #fff;
  text-align: center;
}

.testimonial {
  margin-bottom: 20px;
  font-style: italic;
}

#contact {
  padding: 50px 20px;
  background-color: #f1c40f;
  text-align: center;
}

#contact h2 {
  font-size: 2.5em;
  margin-bottom: 20px;
}

form {
  max-width: 600px;
  margin: 0 auto;
  background-color: white;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

form label {
  display: block;
  margin: 10px 0 5px;
}

form input, form textarea {
  width: 100%;
  padding: 10px;
  margin-bottom: 15px;
  border-radius: 4px;
  border: 1px solid #ccc;
}

form button {
  background-color: #2ecc71;
  color: white;
  padding: 10px 20px;
  border: none;
  font-size: 16px;
  border-radius: 5px;
}

form button:hover {
  background-color: #27ae60;
}

footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 10px 0;
  position: fixed;
  bottom: 0;
  width: 100%;
}
