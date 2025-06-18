# stunning-enigma

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Links</title>
  <style>
    :root {
      --bg-color: #f9f9f9;
      --text-color: #333;
      --link-bg: #ffffff;
      --link-hover-bg: #e6f0ff;
      --link-color: #0066cc;
    }

    [data-theme="dark"] {
      --bg-color: #1e1e1e;
      --text-color: #e0e0e0;
      --link-bg: #2c2c2c;
      --link-hover-bg: #444;
      --link-color: #66aaff;
    }

    * {
      box-sizing: border-box;
    }

    body {
      font-family: system-ui, sans-serif;
      background: var(--bg-color);
      color: var(--text-color);
      margin: 0;
      padding: 40px 20px;
      display: flex;
      flex-direction: column;
      align-items: center;
      transition: background 0.3s, color 0.3s;
    }

    h1 {
      margin-bottom: 10px;
    }

    .theme-toggle {
      margin-bottom: 30px;
      cursor: pointer;
      background: none;
      border: 1px solid #ccc;
      padding: 8px 16px;
      border-radius: 6px;
      font-size: 14px;
    }

    h2 {
      margin-top: 30px;
      padding-bottom: 5px;
      border-bottom: 1px solid #ccc;
      width: 100%;
      max-width: 500px;
    }

    ul.link-list {
      list-style-type: none;
      padding: 0;
      margin: 10px 0 30px 0;
      width: 100%;
      max-width: 500px;
    }

    .link-list li {
      margin: 10px 0;
    }

    .link-list a {
      display: block;
      background: var(--link-bg);
      border: 1px solid #ddd;
      padding: 12px 20px;
      text-decoration: none;
      color: var(--link-color);
      border-radius: 8px;
      transition: background 0.3s, color 0.3s;
    }

    .link-list a:hover {
      background: var(--link-hover-bg);
    }
  </style>
</head>
<body data-theme="light">
  <h1>My Useful Links</h1>
  <button class="theme-toggle" onclick="toggleTheme()">🌙 Toggle Dark Mode</button>

  <h2>Work Tools</h2>
  <ul class="link-list">
    <li><a href="https://github.com" target="_blank">GitHub</a></li>
    <li><a href="https://stackoverflow.com" target="_blank">Stack Overflow</a></li>
  </ul>

  <h2>AI & Learning</h2>
  <ul class="link-list">
    <li><a href="https://openai.com" target="_blank">OpenAI</a></li>
    <li><a href="https://www.khanacademy.org" target="_blank">Khan Academy</a></li>
  </ul>

  <h2>General</h2>
  <ul class="link-list">
    <li><a href="https://example.com" target="_blank">Example Website</a></li>
    <li><a href="https://wikipedia.org" target="_blank">Wikipedia</a></li>
  </ul>

  <script>
    function toggleTheme() {
      const current = document.body.getAttribute('data-theme');
      document.body.setAttribute('data-theme', current === 'light' ? 'dark' : 'light');
    }
  </script>
</body>
</html>
