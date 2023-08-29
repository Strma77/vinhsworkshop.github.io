<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" type="text/css" href="css.css" /> 
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Futuristic Website</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <header>
      <h1>Welcome to the Future</h1>
      <nav>
        <ul>
          <li><a href="#about">About</a></li>
          <li><a href="#services">Services</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </header>

    <section id="about">
      <h2>About Us</h2>
      <p>We are a company that specializes in futuristic technology solutions.</p>
    </section>

    <section id="services">
      <h2>Our Services</h2>
      <ul>
        <li>Virtual Reality</li>
        <li>Augmented Reality</li>
        <li>Artificial Intelligence</li>
      </ul>
    </section>

    <section id="contact">
      <h2>Contact Us</h2>
      <form action="#">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name">

        <label for="email">Email:</label>
        <input type="email" id="email" name="email">

        <label for="message">Message:</label>
        <textarea id="message" name="message"></textarea>

        <input type="submit" value="Submit">
      </form>
    </section>

    <footer>
      <p>&copy; 2023 Futuristic Website</p>
    </footer>
  </body>
</html>
