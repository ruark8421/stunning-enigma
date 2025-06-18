# stunning-enigma

<!DOCTYPE html>
<html lang="en">
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
