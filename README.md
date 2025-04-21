<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Lane Talbot</title>
  <link rel="icon" href="favicon.ico" type="image/x-icon">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Inter', sans-serif;
      background: #f9fafb;
      color: #222;
      margin: 0;
      padding: 2rem;
    }

    img {
      display: block;
      margin: 1rem auto;
      max-width: 160px;
      border-radius: 100px;
    }

    a {
      color: #0f62fe;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    h1, h2 {
      text-align: center;
    }

    h2 {
      border-bottom: 1px solid #ddd;
      padding-bottom: 0.25rem;
    }

    nav {
      text-align: center;
      margin: 1rem 0;
    }

    nav a {
      margin: 0 0.75rem;
      font-weight: 600;
      color: #0f62fe;
    }

    section {
      max-width: 600px;
      margin: 2rem auto;
      padding: 1rem 2rem;
      background: white;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.03);
      animation: fadein 0.8s ease-in;
    }

    footer {
      text-align: center;
      font-size: 0.9rem;
      color: #999;
      margin-top: 3rem;
    }

    @keyframes fadein {
      from { opacity: 0; transform: translateY(10px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .subtitle {
      text-align: center;
      margin-top: -1rem;
      font-weight: 500;
      color: #666;
    }

    .centered-bio {
      text-align: center;
      max-width: 600px;
      margin: 1rem auto 2rem auto;
      font-size: 0.95rem;
      color: #444;
    }

    .subscribe-form {
      display: flex;
      justify-content: center;
      gap: 0.5rem;
      margin-top: 1rem;
    }

    .subscribe-form input[type="email"] {
      padding: 0.5rem;
      font-size: 1rem;
      border: 1px solid #ccc;
      border-radius: 5px;
      width: 250px;
    }

    .subscribe-form button {
      background: #0f62fe;
      color: white;
      border: none;
      padding: 0.5rem 1rem;
      border-radius: 5px;
      font-weight: 600;
      cursor: pointer;
    }

    .subscribe-form button:hover {
      background: #0043ce;
    }
  </style>
</head>
<body>

<h1>Lane Talbot</h1>
<p class="subtitle">Fiction Writer | Advertising Strategist | Speaker</p>

<img src="LaneTalbotHeadshot (1).jpeg" alt="Lane Talbot Headshot">

<nav>
  <a href="#about">About</a>
  <a href="#fiction">Fiction</a>
  <a href="#consulting">Consulting</a>
  <a href="#featured">Featured Work</a>
  <a href="#contact">Contact</a>
  <a href="https://darkmidwest.substack.com">Dark Midwest</a>
  <a href="https://www.linkedin.com/in/lanetalbot">LinkedIn</a>
</nav>

<p class="centered-bio">I write fiction about fear, survival, and the strange undercurrents of American life—and consult on brand strategy, storytelling, and advertising effectiveness.</p>

<section id="about">
  <h2>About</h2>
  <p>I'm Lane Talbot—an award-winning fiction writer and advertising strategist at LinkedIn. My work spans short stories published in top literary journals and marketing strategy that drives Fortune 500 growth.</p>
</section>

<section id="fiction">
  <h2>Fiction</h2>
  <p>My fiction is listed in <em>Best American Mystery Stories</em>, and published in <em>Berkeley Fiction Review</em>, and more.</p>
  <p>Read more at <a href="https://darkmidwest.substack.com">Dark Midwest</a>.</p>
</section>

<section>
  <h2>Subscribe</h2>
  <p>Get new stories and essays from the Dark Midwest straight to your inbox.</p>
  <form class="subscribe-form" action="https://darkmidwest.substack.com/subscribe" method="get" target="_blank">
    <input type="email" name="email" placeholder="Your email" required>
    <button type="submit">Subscribe</button>
  </form>
</section>

<section id="consulting">
  <h2>Consulting & Thought Leadership</h2>
  <p>As a Senior Content Solutions Consultant at LinkedIn, I help brands build authority and trust through creative that actually converts. My background spans brand narrative, inbound strategy, and campaign execution.</p>
  <p>I also speak regularly on storytelling, advertising effectiveness, and AI’s evolving role in marketing. Follow my work on <a href="https://www.linkedin.com/in/lanetalbot">LinkedIn</a>.</p>
</section>

<section>
  <h2>What I Do</h2>
  <ul>
    <li>✍️ <strong>Fiction:</strong> Horror, thriller, craft essays.</li>
    <li>🧠 <strong>Consulting:</strong> Lead gen, brand strategy, AI.</li>
    <li>🎤 <strong>Speaking:</strong> Keynotes and talks on advertising, AI, and narrative.</li>
  </ul>
</section>

<section id="featured">
  <h2>Featured Work</h2>
  <ul>
    <li><strong>Short Story:</strong> <a href="#">“Destroyer Comes Home”</a> — listed as Notable Fiction in <em>Best American Mystery Stories</em></li>
    <li><strong>Blog:</strong> <a href="https://darkmidwest.substack.com">DarkMidwest</a></li>
  </ul>
</section>

<section id="contact">
  <h2>Contact</h2>
  <p>Email: <a href="mailto:lane.talbot@outlook.com">lane.talbot@outlook.com</a></p>
  <p>Bluesky: <a href="https://bsky.app/profile/lanetalbot">@lanetalbot</a></p>
  <p>Threads: <a href="https://www.threads.net/@lane_talbot_and_ink">@lane_talbot_and_ink</a></p>
</section>

<footer>
  &copy; 2025 Lane Talbot. All rights reserved.
</footer>

</body>
</html>
