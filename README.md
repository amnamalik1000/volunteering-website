<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Bright Future: Volunteer Today</title>
  <!-- Link to Font Awesome for icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
  <style>
    html {
      scroll-behavior: smooth;
    }
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background: #fffaf5;
      color: #333;
    }
    header {
      background: linear-gradient(to right, #ff758c, #ff7eb3);
      color: white;
      padding: 2em;
      text-align: center;
    }
    nav {
      background-color: #111;
      overflow: hidden;
    }
    nav a {
      float: left;
      display: block;
      color: white;
      padding: 14px 20px;
      text-decoration: none;
      transition: 0.3s;
    }
    nav a:hover {
      background-color: #ff7eb3;
      color: white;
    }
    section {
      padding: 2em;
      max-width: 1000px;
      margin: auto;
      animation: fadeIn 1.2s ease-in;
    }
    h2 {
      color: #ff7eb3;
    }
    ul {
      padding-left: 20px;
    }
    img {
      max-width: 100%;
      height: auto;
      margin: 1em 0;
      border-radius: 12px;
    }
    footer {
      background-color: #ff7eb3;
      color: white;
      text-align: center;
      padding: 2em;
      position: relative;
    }
    .cta {
      background-color: #ff758c;
      padding: 1em;
      color: white;
      text-align: center;
      margin: 3em auto;
      border-radius: 8px;
      max-width: 800px;
    }
    .top-button {
      position: fixed;
      bottom: 30px;
      right: 30px;
      background-color: #ff7eb3;
      color: white;
      border: none;
      padding: 10px 15px;
      border-radius: 50%;
      font-size: 18px;
      cursor: pointer;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
      z-index: 1000;
    }
    .top-button:hover {
      background-color: #ff5a92;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <header>
    <h1><i class="fas fa-hands-helping"></i> Bright Future: Volunteer Today</h1>
    <p>Explore fun and meaningful ways to help your community and the world</p>
  </header>
  <nav>
    <a href="#home">Home</a>
    <a href="#organised">Organised Volunteering</a>
    <a href="#local">Local Volunteering</a>
    <a href="#international">International Ideas</a>
  </nav>
  <section id="home">
    <h2>Home Page: Introduction</h2>
    <img src="https://images.unsplash.com/photo-1573497491208-6b1acb260507" alt="Volunteers working together">
    <p>Welcome to Bright Future, your go-to place for everything about volunteering! Discover exciting ways to give back, develop new skills, and meet amazing people. No matter your age or interests, there's something here for you.</p>
  </section>
  <section id="organised">
    <h2>Organised Volunteering</h2>
    <img src="https://images.unsplash.com/photo-1603575448364-44e4f54c3ed7" alt="Organised volunteering team activity">
    <p>Join programs run by schools, non-profits, and youth clubs. These opportunities are structured and perfect for learning responsibility while making an impact.</p>
    <ul>
      <li>Clubs at school or community centers</li>
      <li>NGOs like the Red Crescent</li>
      <li>National campaigns such as <em>Clean Up UAE</em></li>
    </ul>
    <p>These experiences often lead to certifications and open doors to more opportunities.</p>
  </section>
  <section id="local">
    <h2>Local Volunteering</h2>
    <img src="https://images.unsplash.com/photo-1524504388940-b1c1722653e1" alt="Local community cleanup">
    <p>Support causes close to home! Helping locally creates stronger communities and brings neighbors together.</p>
    <ul>
      <li>Tutor students or help with homework</li>
      <li>Volunteer at animal shelters</li>
      <li>Assist elderly citizens</li>
      <li>Clean public spaces or plant trees</li>
    </ul>
  </section>
  <section id="international">
    <h2>International Ideas</h2>
    <img src="https://images.unsplash.com/photo-1509099836639-18ba1795216d" alt="Volunteering abroad">
    <p>Ready to explore the world and give back at the same time? International volunteering builds cultural understanding and global friendships.</p>
    <ul>
      <li>UNICEF or Habitat for Humanity trips</li>
      <li>Online projects via UN Volunteers</li>
      <li>Teach languages, support refugees, or help with sustainability goals</li>
    </ul>
  </section>
  <div class="cta">
    <h2>Start Your Journey Today</h2>
    <p>One small action can make a big difference. Get involved, spread kindness, and create a better world. 🌍</p>
  </div>
  <button onclick="window.scrollTo({top: 0, behavior: 'smooth'})" class="top-button" title="Back to top">
    <i class="fas fa-arrow-up"></i>
  </button>
  <footer>
    <p>"The best way to find yourself is to lose yourself in the service of others." – Mahatma Gandhi</p>
    <p>&copy; 2025 Bright Future Volunteers</p>
  </footer>
</body>
</html>
