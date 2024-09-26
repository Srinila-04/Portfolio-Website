/* General styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

h1, h2, h3 {
    color: #2c3e50;
}

a {
    text-decoration: none;
    color: #2980b9;
}

/* Navbar styles */
nav {
    background-color: #34495e;
    padding: 10px;
    text-align: center;
}

nav a {
    color: white;
    margin: 0 15px;
    font-size: 18px;
}

nav a:hover {
    color: #1abc9c;
}

/* Home page styles */
.home {
    text-align: center;
    padding: 50px;
}

.home h1 {
    font-size: 48px;
}

.home p {
    font-size: 18px;
    line-height: 1.6;
    max-width: 600px;
    margin: 20px auto;
}

/* Contact page styles */
.contact {
    text-align: center;
    padding: 50px;
}

.contact form {
    display: inline-block;
    text-align: left;
    max-width: 400px;
    width: 100%;
}

.contact label {
    font-size: 16px;
}

.contact input, 
.contact textarea {
    width: 100%;
    padding: 10px;
    margin: 10px 0;
    border: 1px solid #ccc;
    border-radius: 4px;
}

.contact input[type="submit"] {
    background-color: #2980b9;
    color: white;
    border: none;
    cursor: pointer;
}

.contact input[type="submit"]:hover {
    background-color: #1abc9c;
}
