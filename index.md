<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Pastel Minimalist Portfolio</title>
<style>
  /* Pastel Color Palette */
  :root {
    --color-bg: #f3f0fa; /* pale lavender background */
    --color-primary: #a8dadc;   /* soft cyan */
    --color-secondary: #f4a261; /* pastel orange */
    --color-accent: #b5ead7;    /* light mint */
    --color-text: #333;
    --color-hover-bg: #ffe8d6;  /* soft peach */
  }

  /* Reset */
  * {
    box-sizing: border-box;
  }
  body {
    margin: 0;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-color: var(--color-bg);
    color: var(--color-text);
    scroll-behavior: smooth;
  }

  /* Navigation */
  nav {
    position: fixed;
    top: 0; left: 0; right: 0;
    background-color: var(--color-bg);
    border-bottom: 1px solid var(--color-accent);
    padding: 0.75rem 1.5rem;
    display: flex;
    justify-content: center;
    z-index: 1000;
  }

  nav ul {
    list-style: none;
    display: flex;
    gap: 2.5rem;
    margin: 0;
    padding: 0;
  }

  nav li {
    display: flex;
    align-items: center;
  }

  nav a {
    text-decoration: none;
    color: var(--color-primary);
    display: flex;
    flex-direction: column;
    align-items: center;
    font-size: 0.8rem;
    font-weight: 500;
    transition: color 0.3s ease;
    cursor: pointer;
  }

  nav a:hover,
  nav a:focus {
    color: var(--color-secondary);
  }

  nav svg {
    width: 24px;
    height: 24px;
    stroke: currentColor;
    fill: none;
    stroke-width: 2;
    margin-bottom: 4px;
  }

  /* Section styling */
  section {
    max-width: 900px;
    margin: 0 auto;
    padding: 100px 20px 60px; /* padding top for nav offset */
    min-height: 100vh;
  }

  h1, h2 {
    color: var(--color-primary);
  }

  /* Home Section */
  #home {
    display: flex;
    flex-direction: column;
    justify-content: center;
    text-align: center;
  }
  #home h1 {
    font-size: 3rem;
    margin-bottom: 0.25rem;
  }
  #home p {
    font-size: 1.25rem;
    color: var(--color-secondary);
  }

  /* About Section */
  #about p {
    font-size: 1.1rem;
    line-height: 1.5;
  }

  /* Projects Section */
  #projects ul {
    list-style: none;
    padding: 0;
  }
  #projects li {
    background: var(--color-accent);
    border-radius: 8px;
    margin-bottom: 1rem;
    padding: 1rem;
    color: #2a2a2a;
    box-shadow: 0 2px 6px rgba(0,0,0,0.05);
  }

  /* Contact Section */
  #contact form {
    max-width: 400px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    gap: 1rem;
  }
  #contact input, #contact textarea {
    padding: 0.75rem;
    border: 1px solid var(--color-accent);
    border-radius: 6px;
    font-size: 1rem;
    font-family: inherit;
    resize: vertical;
  }
  #contact button {
    background-color: var(--color-primary);
    border: none;
    color: white;
    padding: 0.75rem;
    font-size: 1rem;
    border-radius: 6px;
    cursor: pointer;
    transition: background-color 0.3s ease;
  }
  #contact button:hover {
    background-color: var(--color-secondary);
  }

  /* Responsive tweaks */
  @media (max-width: 480px) {
    nav ul {
      gap: 1.5rem;
    }
    #home h1 {
      font-size: 2.2rem;
    }
    #home p {
      font-size: 1rem;
    }
  }
</style>
</head>
<body>

<nav>
  <ul>
    <li>
      <a href="#home" title="Home" aria-label="Home">
        <!-- House Icon -->
        <svg viewBox="0 0 24 24" aria-hidden="true" focusable="false">
          <path d="M3 12 L12 3 L21 12 V21 H15 V15 H9 V21 H3 Z" />
        </svg>
        Home
      </a>
    </li>
    <li>
      <a href="#about" title="About" aria-label="About">
        <!-- User Icon -->
        <svg viewBox="0 0 24 24" aria-hidden="true" focusable="false">
          <circle cx="12" cy="8" r="4" />
          <path d="M6 20c0-3.33 5.34-5 6-5s6 1.67 6 5" />
        </svg>
        About
      </a>
    </li>
    <li>
      <a href="#projects" title="Projects" aria-label="Projects">
        <!-- Folder Icon -->
        <svg viewBox="0 0 24 24" aria-hidden="true" focusable="false">
          <path d="M3 7h6l2 3h10v9H3z" />
        </svg>
        Projects
      </a>
    </li>
    <li>
      <a href="#contact" title="Contact Me" aria-label="Contact Me">
        <!-- Envelope Icon -->
        <svg viewBox="0 0 24 24" aria-hidden="true" focusable="false">
          <path d="M3 8l9 6 9-6" />
          <rect x="3" y="8" width="18" height="10" rx="2" ry="2" />
        </svg>
        Contact
      </a>
    </li>
  </ul>
</nav>

<section id="home" tabindex="-1">
  <h1>Hi, I'm Amruta G.</h1>
  <p>Welcome to my portfolio site! I create clean, minimalist web designs with pastel vibes.</p>
</section>

<section id="about" tabindex="-1">
  <h2>About Me</h2>
  <p>
    I am passionate about building beautiful and functional web experiences.
    With a focus on soft pastel colors and minimalist aesthetics, I craft websites that are both
    pleasing to the eye and easy to use.
  </p>
</section>

<section id="projects" tabindex="-1">
  <h2>Projects</h2>
  <ul>
    <li><strong>Project 1:</strong> Minimalist Portfolio Website</li>
    <li><strong>Project 2:</strong> Data Visualization Dashboard</li>
    <li><strong>Project 3:</strong> Interactive Contact Form</li>
  </ul>
</section>

<section id="contact" tabindex="-1">
  <h2>Contact Me</h2>
  <form>
    <label for="name">Name</label>
    <input type="text" id="name" name="name" placeholder="Your full name" required />

    <label for="email">Email</label>
    <input type="email" id="email" name="email" placeholder="you@example.com" required />

    <label for="message">Message</label>
    <textarea id="message" name="message" rows="5" placeholder="Your message here..." required></textarea>

    <button type="submit">Send Message</button>
  </form>
</section>

</body>
</html>
