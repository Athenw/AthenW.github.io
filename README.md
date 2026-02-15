<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Athen Wilkinson — Creative / Technical Sound Designer</title>
  <meta name="description" content="Athen Wilkinson — Creative and technical sound designer specializing in immersive audio, game sound, film, experimental soundscapes."/>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Playfair+Display:wght@700;900&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg: #0f0f0f;
      --text: #e0e0e0;
      --accent: #00d4ff;
      --accent-dark: #0099bb;
      --card: #1a1a1a;
      --border: #333;
    }
    body {
      margin: 0;
      font-family: 'Inter', system-ui, sans-serif;
      background: var(--bg);
      color: var(--text);
      line-height: 1.6;
    }
    h1, h2, h3 {
      font-family: 'Playfair Display', serif;
      font-weight: 700;
    }
    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 0 1.5rem;
    }
    header {
      position: fixed;
      top: 0;
      width: 100%;
      z-index: 100;
      background: rgba(15,15,15,0.85);
      backdrop-filter: blur(12px);
      border-bottom: 1px solid var(--border);
    }
    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1.25rem 0;
    }
    .logo {
      font-size: 1.5rem;
      font-weight: 700;
      color: var(--accent);
      letter-spacing: -1px;
    }
    .nav-links a {
      margin-left: 2rem;
      color: var(--text);
      text-decoration: none;
      font-weight: 500;
      transition: color 0.3s;
    }
    .nav-links a:hover {
      color: var(--accent);
    }
    #hero {
      min-height: 100vh;
      display: flex;
      align-items: center;
      padding-top: 6rem;
      background: linear-gradient(to bottom, #0f0f0f, #0a1a22);
    }
    #hero .content {
      max-width: 800px;
    }
    #hero h1 {
      font-size: clamp(3.5rem, 8vw, 7rem);
      margin: 0;
      line-height: 0.95;
      letter-spacing: -3px;
      color: white;
    }
    #hero .subtitle {
      font-size: 1.5rem;
      margin: 1.5rem 0 2.5rem;
      color: #aaa;
      max-width: 600px;
    }
    .btn {
      display: inline-block;
      background: var(--accent);
      color: #000;
      padding: 0.9rem 2.2rem;
      border-radius: 50px;
      text-decoration: none;
      font-weight: 600;
      transition: all 0.3s;
    }
    .btn:hover {
      background: var(--accent-dark);
      transform: translateY(-3px);
      box-shadow: 0 10px 30px rgba(0,212,255,0.25);
    }
    section {
      padding: 8rem 0;
    }
    h2 {
      font-size: 3.5rem;
      text-align: center;
      margin-bottom: 4rem;
      background: linear-gradient(90deg, #00d4ff, #ff00aa);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(360px, 1fr));
      gap: 2.5rem;
    }
    .card {
      background: var(--card);
      border: 1px solid var(--border);
      border-radius: 16px;
      overflow: hidden;
      transition: transform 0.4s, box-shadow 0.4s;
    }
    .card:hover {
      transform: translateY(-12px);
      box-shadow: 0 30px 60px rgba(0,0,0,0.6);
    }
    .card audio {
      width: 100%;
      padding: 1rem;
      background: #111;
    }
    .card-content {
      padding: 1.8rem;
    }
    .card h3 {
      margin: 0 0 1rem;
      font-size: 1.6rem;
    }
    .tags {
      display: flex;
      flex-wrap: wrap;
      gap: 0.6rem;
      margin-top: 1rem;
    }
    .tag {
      background: #222;
      color: #aaa;
      padding: 0.4rem 1rem;
      border-radius: 50px;
      font-size: 0.85rem;
    }
    #about p {
      max-width: 700px;
      margin: 0 auto 2rem;
      font-size: 1.2rem;
      text-align: center;
      color: #ccc;
    }
    footer {
      text-align: center;
      padding: 4rem 0 2rem;
      border-top: 1px solid var(--border);
      color: #777;
    }
    .social a {
      color: var(--text);
      margin: 0 1rem;
      font-size: 1.8rem;
      text-decoration: none;
      transition: color 0.3s;
    }
    .social a:hover { color: var(--accent); }
    @media (max-width: 768px)
