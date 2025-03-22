<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GitHub Stats Slideshow</title>
  <style>
    details {
      display: none;
      transition: all 1s ease;
    }
    details.open {
      display: block;
    }
  </style>
</head>
<body>
  <h1>Hi, I'm Zer0W3b 👾</h1>

  <p align="center">
    <a href="https://github.com/zer0w3b?tab=followers">
      <img alt="followers" title="Follow me on Github" src="https://custom-icon-badges.demolab.com/github/followers/zer0w3b?color=236ad3&labelColor=1155ba&style=for-the-badge&logo=person-add&label=FOLLOW&logoColor=white"/>
    </a>
    <a href="https://github.com/zer0w3b?tab=repositories&sort=stargazers">
      <img alt="stars" title="Total stars on GitHub" src="https://custom-icon-badges.demolab.com/github/stars/zer0w3b?color=54960C&labelColor=468307&style=for-the-badge&logo=star&label=STARS"/>
    </a>
    <a href="https://github.com/zer0w3b">
      <img alt="visitors" title="GitHub profile views" src="http://zer0w3b.42web.io/index.php"/>
    </a>
  </p>

  <details class="slide-show">
    <summary><h2>👤 About Me</h2></summary>
    <ul>
      <li>🕵️‍♂️ Ethical Hacker in the making</li>
      <li>🔐 Cybersecurity enthusiast</li>
      <li>🧩 Data broker researcher</li>
      <li>💻 Python, Networking, OSINT, Automation</li>
      <li>🎯 Focus: learn, exploit, protect, repeat</li>
      <li>⚡ Constantly leveling up — stealth mode active</li>
    </ul>
  </details>

  <details class="slide-show">
    <summary><h2>🚀 GitHub Stats</h2></summary>
    <img src="http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Zer0W3b&theme=graywhite" alt="GitHub Stats">
    <img src="http://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Zer0W3b&theme=graywhite" alt="Repos per Language">
    <img src="http://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Zer0W3b&theme=graywhite" alt="Most Commit Language">
    <img src="http://github-profile-summary-cards.vercel.app/api/cards/stats?username=Zer0W3b&theme=graywhite" alt="GitHub Stats">
    <img src="http://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Zer0W3b&theme=graywhite&utcOffset=8" alt="Productive Time">
  </details>

  <details class="slide-show">
    <summary><h2>🔧 Skills</h2></summary>
    <ul>
      <li>Python</li>
      <li>JavaScript</li>
      <li>Linux</li>
      <li>Docker</li>
      <li>Kubernetes</li>
      <li>Git</li>
    </ul>
  </details>

  <details class="slide-show">
    <summary><h2>🔥 Featured Projects</h2></summary>
    <ul>
      <li>Currently, no projects are being worked on.</li>
    </ul>
  </details>

  <details class="slide-show">
    <summary><h2>📫 How to Reach Me</h2></summary>
    <ul>
      <li>Email: <a href="mailto:zer0w3b@keemail.me">zer0w3b@keemail.me</a></li>
    </ul>
  </details>

  <script>
    const slides = document.querySelectorAll('.slide-show');
    let currentIndex = 0;

    function showNextSlide() {
      slides[currentIndex].classList.add('open');
      currentIndex++;
      if (currentIndex >= slides.length) {
        currentIndex = 0; // Reset to the first slide
      }
    }

    // Show next slide every 3 seconds
    setInterval(showNextSlide, 3000);

    // Initially show the first slide
    slides[0].classList.add('open');
  </script>
</body>
</html>
