# My 5-Page Website

This project is a simple 5-page website created to demonstrate a multi-page HTML structure with CSS styling and basic interactivity using JavaScript.

## Table of Contents
1. [Home Page](#home-page)
2. [About Page](#about-page)
3. [Services Page](#services-page)
4. [Portfolio Page](#portfolio-page)
5. [Contact Page](#contact-page)
6. [Form Page](#form-page)
7. [Setup Instructions](#setup-instructions)

## Home Page
This is the main landing page of the website. It contains a welcoming header and navigation links to other pages.

### HTML (index.html):
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="about.html">About</a>
            <a href="services.html">Services</a>
            <a href="portfolio.html">Portfolio</a>
            <a href="contact.html">Contact</a>
            <a href="form.html">Form</a>
        </nav>
    </header>
    <main>
        <p>This is the home page of the website.</p>
    </main>
    <footer>
        <p>&copy; 2025 My Website. All rights reserved.</p>
    </footer>
</body>
</html>
```

### CSS (styles.css):
```css
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    background: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}

header h1 {
    margin: 0;
    font-size: 2rem;
}

nav a {
    color: #fff;
    text-decoration: none;
    margin: 0 15px;
}

nav a:hover {
    text-decoration: underline;
}

main {
    padding: 20px;
    background: #f4f4f4;
}

footer {
    text-align: center;
    padding: 10px 0;
    background: #333;
    color: #fff;
    position: absolute;
    width: 100%;
    bottom: 0;
}
form {
    max-width: 600px;
    margin: 20px auto;
    padding: 20px;
    border: 1px solid #ddd;
    border-radius: 5px;
    background-color: #f9f9f9;
}

form label {
    display: block;
    margin-bottom: 8px;
    font-weight: bold;
}

form input, form textarea, form button {
    width: 100%;
    padding: 10px;
    margin-bottom: 15px;
    border: 1px solid #ccc;
    border-radius: 5px;
    font-size: 1rem;
}

form button {
    background-color: #4CAF50;
    color: white;
    border: none;
    cursor: pointer;
    font-size: 1.1rem;
    text-transform: uppercase;
    transition: background-color 0.3s ease;
}

form button:hover {
    background-color: #45a049;
}

```

## About Page
This page gives details about the website or the individual behind it.

### HTML (about.html):
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>About Us</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="about.html">About</a>
            <a href="services.html">Services</a>
            <a href="portfolio.html">Portfolio</a>
            <a href="contact.html">Contact</a>
            <a href="form.html">Form</a>
        </nav>
    </header>
    <main>
        <p>Details about the website or creator go here.</p>
    </main>
    <footer>
        <p>&copy; 2025 My Website. All rights reserved.</p>
    </footer>
</body>
</html>
```

## Services Page
This page outlines the services offered.

### HTML (services.html):
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Services</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Our Services</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="about.html">About</a>
            <a href="services.html">Services</a>
            <a href="portfolio.html">Portfolio</a>
            <a href="contact.html">Contact</a>
            <a href="form.html">Form</a>
        </nav>
    </header>
    <main>
        <p>Information about services offered is listed here.</p>
    </main>
    <footer>
        <p>&copy; 2025 My Website. All rights reserved.</p>
    </footer>
</body>
</html>
```

## Portfolio Page
This page displays a gallery or portfolio items.

### HTML (portfolio.html):
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Our Portfolio</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="about.html">About</a>
            <a href="services.html">Services</a>
            <a href="portfolio.html">Portfolio</a>
            <a href="contact.html">Contact</a>
            <a href="form.html">Form</a>
        </nav>
    </header>
    <main>
        <p>Gallery of work or portfolio items are displayed here.</p>
    </main>
    <footer>
        <p>&copy; 2025 My Website. All rights reserved.</p>
    </footer>
</body>
</html>
```

## Contact Page
This page includes a form for users to reach out.

### HTML (contact.html):
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Contact Us</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="about.html">About</a>
            <a href="services.html">Services</a>
            <a href="portfolio.html">Portfolio</a>
            <a href="contact.html">Contact</a>
            <a href="form.html">Form</a>
        </nav>
    </header>
    <main>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">Submit</button>
        </form>
    </main>
    <footer>
        <p>&copy; 2025 My Website. All rights reserved.</p>
    </footer>
</body>
</html>
```
## Form Page
This page includes a form for users submit.

### HTML (contact.html):
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Submit Your Details</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="about.html">About</a>
            <a href="services.html">Services</a>
            <a href="portfolio.html">Portfolio</a>
            <a href="contact.html">Contact</a>
            <a href="form.html">Form</a>
        </nav>
    </header>
    <main>
        <h2 style="text-align: center;">Contact Form</h2>
        <form action="#" method="POST">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required placeholder="Enter your name">

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required placeholder="Enter your email">

            <label for="subject">Subject:</label>
            <input type="text" id="subject" name="subject" required placeholder="Enter the subject">

            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="4" required placeholder="Enter your message"></textarea>

            <button type="submit">Submit</button>
        </form>
    </main>
    <footer>
        <p>&copy; 2025 My Website. All rights reserved.</p>
    </footer>
</body>
</html>

```

## Setup Instructions
1. Clone the repository:
    ```bash
    git clone <repository-url>
    ```
2. Navigate to the project directory:
    ```bash
    cd <project-directory>
    ```
3. Open the `index.html` file in your browser to view the website.

