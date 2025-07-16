---
layout: home
title: "Home"
---

<style>
.hero {
  background: url('/assets/your-background.jpg') no-repeat center center;
  background-size: cover;
  height: 80vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  color: white;
  text-shadow: 1px 1px 5px rgba(0,0,0,0.7);
  font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
}

.hero h1 {
  font-size: 4rem;
  font-weight: 900;
  margin: 0;
}

.hero p {
  font-size: 1.5rem;
  margin-top: 0.5rem;
  font-weight: 300;
  letter-spacing: 2px;
}

nav {
  position: fixed;
  top: 20px;
  right: 30px;
  font-weight: bold;
  font-family: Arial, sans-serif;
  z-index: 1000;
}

nav a {
  color: white;
  text-decoration: none;
  margin-left: 30px;
  font-size: 1rem;
  text-transform: uppercase;
}

nav a:hover {
  text-decoration: underline;
}
</style>

<nav>
  <a href="/">HOME</a>
  <a href="/about/">ABOUT</a>
  <a href="/projects/">PROJECTS</a>
  <a href="/contact/">CONTACT</a>
</nav>

<div class="hero">
  <h1>Amruta Gandhe</h1>
  <p>Business Analytics Projects</p>
</div>
