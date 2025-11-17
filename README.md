<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Trivia Stampede</title>

  <!-- Bungee Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Bungee&display=swap" rel="stylesheet">

  <style>
    :root {
      --teal: #008080;
      --coral: #FF6F61;
      --coral-dark: #e05b4e;
      --coral-light: #ffa192;
      --coral-mid: #f88070;
      --white: #ffffff;
      --light: #f0f0f0;
    }

    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: var(--coral);
      color: var(--light);
      scroll-behavior: smooth;
    }

    header, section, footer {
      padding: 60px 20px;
      text-align: center;
    }

    header {
      background-color: var(--coral);
    }

    nav {
      position: sticky;
      top: 0;
      background-color: var(--teal);
      padding: 10px;
      z-index: 1000;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    h1, h2 {
      font-family: 'Bungee', sans-serif;
      color: var(--white);
      letter-spacing: 1px;
      text-shadow: 2px 2px 4px rgba(128, 128, 128, 1);
    }

    .cta-button {
      background-color: var(--teal);
      color: white;
      border: none;
      padding: 12px 24px;
      font-size: 1em;
      border-radius: 5px;
      cursor: pointer;
      margin-top: 20px;
    }

    .cta-button:hover {
      opacity: 0.9;
    }

    section:nth-child(even) {
      background-color: rgba(255, 255, 255, 0.05);
    }

    #about {
      background-color: var(--coral-dark);
    }

    #details {
      background-color: var(--coral);
    }

    #how {
      background-color: var(--coral-dark);
      
    }

    #why {
      background-color: var(--coral);
    }

    #contact {
      background-color: var(--coral-dark);
    }
    
    footer {
      background-color: #008080;
      font-size: 0.9em;
    }

    a {
      color: var(--light);
    }
    
    .features-list {
  text-align: left;
  max-width: 600px;
  margin: 0 auto;
}

.checkmark {
  display: inline-block;
  color: var(--teal);
  border: 2px solid var(--teal);
  border-radius: 50%;
  padding: 4px 8px;
  font-weight: bold;
  margin-right: 10px;
  
.features-list p {
  margin: 10px 0;
  
}

.how-list {
  text-align: left;
}

  </style>
</head>
<body>

  <nav>
    <a href="#about">About</a>
    <a href="#details">What You Get</a>
    <a href="#how">How It Works</a>
    <a href="#why">Why Trivia?</a>
    <a href="#contact">Contact</a>
  </nav>

  <header>
    <img src="https://i.postimg.cc/zvvXyY1d/Trivia-Stampede-Logo.png" alt="Trivia Stampede Logo" width="200" />
    <h1>Weekly trivia brings a stampede to your tables</h1>
  </header>

  <section id="about">
    <h2>What Is Trivia Stampede?</h2>
    <p>Trivia Stampede helps boost interest in your business and customer engagement by providing ready-to-run trivia nights. <br><br>You get a full set of questions. <br>You get fun. <br>You get customers.</p>
  </section>

  <section id="details">
    <h2>What You Get</h2>
    <div class="features-list">
    <p><span class="checkmark">✔</span>Weekly question sets<br><span class="checkmark">✔</span>Variety of trivia subjects so each player has something to look forward to<br><span class="checkmark">✔</span>Varied formats from round-to-round to mix up the fun<br> <span class="checkmark">✔</span>Standard question-answer, multiple choice, music, visual, themed rounds, etc.<br> <span class="checkmark">✔</span>Easy-to-follow hosting guide that will script everything out for you<br> <span class="checkmark">✔</span>Contact info for quick support if needed during your trivia night</p>
  </section>

  <section id="how">
    <h2>How It Works</h2>
    <div class="how-list">
    <p class="how-list">1. Choose a night you want to boost business.<br>2. Choose your person to host.<br>3. Contact us. Support provided and all questions about logistics answered.<br>4. Only $25 for the question set each week.<br>5.You host and your trivia night will be a hit! </p>
  </section>

  <section id="why">
    <h2>Why Add Trivia Nights?</h2>
    <p>🎉 Increase repeat visits<br>💡 Attract new customers <br>🍽️Food & drink sales get boosts on trivia nights<br>👥 Build a sense of commmunity and comfort<br>✅ Trivia Stampede has proven success as a trivia night writer and host</p>
  </section>

  <section id="contact">
    <h2>Get In Touch</h2>
    <button class="cta-button"><p></b>Email: <a href="mailto:triviastampede@gmail.com">triviastampede@gmail.com<br>Phone Contact will be provided</a></p></button>
  </section>

  <footer>
    2025 Trivia Stampede
  </footer>

</body>
</html>
