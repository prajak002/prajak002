<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Prajak | Digital Garden</title>
  <link href="https://fonts.googleapis.com/css2?family=Fira+Code&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Fira Code', monospace;
      background: linear-gradient(135deg, #1d1f21, #3a3d40);
      color: #f7f7f7;
      overflow-x: hidden;
    }
    header {
      text-align: center;
      padding: 5rem 1rem 2rem;
    }
    header h1 {
      font-size: 3rem;
      background: linear-gradient(to right, #ff6ec4, #7873f5);
      -webkit-background-clip: text;
      color: transparent;
      animation: pulse 2s ease-in-out infinite alternate;
    }
    header p {
      font-style: italic;
      color: #ccc;
      max-width: 700px;
      margin: 0 auto;
      font-size: 1.2rem;
    }
    .profile-pic {
      width: 180px;
      border-radius: 50%;
      margin-top: 2rem;
      transition: transform 0.3s ease-in-out;
    }
    .profile-pic:hover {
      transform: scale(1.1);
    }
    section {
      padding: 2rem;
      max-width: 900px;
      margin: auto;
    }
    section h2 {
      color: #fca5a5;
      margin-top: 2rem;
    }
    .code-box {
      background-color: #2d2f33;
      padding: 1rem;
      border-radius: 10px;
      margin-top: 1rem;
      font-size: 0.9rem;
      overflow-x: auto;
    }
    .blog-posts a {
      display: block;
      color: #93c5fd;
      margin: 0.5rem 0;
      text-decoration: none;
    }
    .blog-posts a:hover {
      text-decoration: underline;
    }
    footer {
      text-align: center;
      margin-top: 4rem;
      padding: 2rem;
      font-size: 1rem;
      background-color: #111;
      color: #aaa;
    }
    @keyframes pulse {
      from { transform: scale(1); }
      to { transform: scale(1.05); }
    }
  </style>
</head>
<body>
  <header>
    <h1>Hi 👋🏽, I'm Prajak</h1>
    <p>🌌 Exploring the convergence of <strong>Art</strong>, <strong>Nature</strong>, <strong>Science</strong>, and <strong>Technology</strong> — reflecting the eternal human urge to preserve <em>beauty</em>, seek <em>truth</em>, and encode <em>meaning</em> across generations.</p>
    <img class="profile-pic" src="https://github.com/prajak002/prajak002/blob/main/mestyeghibli-removebg-preview.png" alt="Prajak">
  </header>
  
  <section>
    <h2>🚀 About Me</h2>
    <ul>
      <li>🧠 Software Developer & Deep Thinker</li>
      <li>🤝 Open Source & Open Science Enthusiast</li>
      <li>🔬 Curious Research Aspirant</li>
      <li>💭 Currently overthinking about... everything</li>
      <li>📬 Reach me: <a href="mailto:prajaksen.s@gmail.com">prajaksen.s@gmail.com</a></li>
      <li>🌐 Portfolio: <a href="https://prajak-dev.vercel.app/" target="_blank">prajak-dev.vercel.app</a></li>
    </ul>

    <h2>🛠️ Code Playground</h2>
    <div class="code-box">
<pre>
const pra = {
  pronouns: "He" | "Him",
  languages: ["C++", "Python", "JS", "Go", "Java"],
  tools: ["Flask", "Django", "React Native", "Docker", "AWS"],
  databases: ["MongoDB", "MySQL", "PostgreSQL"],
  currentFocus: "crush's heart 💘",
  motto: "Let's explore everything with humble curiosity"
};
</pre>
    </div>

    <h2>📕 Blog Posts</h2>
    <div class="blog-posts">
      <a href="https://blogoverflow.hashnode.dev/unveiling-the-power-of-multi-threading-revolutionizing-scalability-in-single-client-server-design">🔥 Unveiling the Power of Multithreading</a>
      <a href="https://blogoverflow.hashnode.dev/zero-copy-io-for-streaming-sockets-in-c-efficient-data-transfer-with-pre-allocated-buffers">💡 Zero-Copy IO in C for Efficient Streaming</a>
    </div>
  </section>

  <footer>
    🌍 Based in Kolkata | Made with 💙 in Code<br>
    Let's connect and build something beautiful 🌱
  </footer>
</body>
</html>
