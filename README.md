<style>
  body {
    background: #0d1117;
    color: #c9d1d9;
    font-family: 'Courier New', monospace;
  }
  #particles-js {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    z-index: -1;
  }
  .project-card {
    background: #1c2526;
    padding: 15px;
    border-radius: 10px;
    margin: 10px 0;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }
  .project-card:hover {
    transform: translateY(-5px) rotateX(10deg) rotateY(10deg);
    box-shadow: 0 10px 20px rgba(0, 255, 128, 0.5);
  }
  .language-badges, .framework-badges {
    display: flex;
    flex-wrap: wrap;
    gap: 0;
    justify-content: left;
    align-items: center;
  }
  .skills-radar {
    width: 200px;
    height: 200px;
    margin: 20px auto;
    position: relative;
    background: radial-gradient(circle, rgba(0, 255, 128, 0.3) 0%, transparent 70%);
    animation: radar-spin 10s linear infinite;
  }
  .skills-radar::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: 2px solid #00FF80;
    border-radius: 50%;
    animation: pulse 2s ease-in-out infinite;
  }
  @keyframes radar-spin {
    0% { transform: rotate(0deg); }
    100% { transform: rotate(360deg); }
  }
  @keyframes pulse {
    0% { transform: scale(1); opacity: 0.7; }
    50% { transform: scale(1.2); opacity: 0.3; }
    100% { transform: scale(1); opacity: 0.7; }
  }
</style>

<div id="particles-js"></div>
<script src="https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>
<script>
  particlesJS("particles-js", {
    particles: {
      number: { value: 80, density: { enable: true, value_area: 800 } },
      color: { value: "#00FF80" },
      shape: { type: "circle" },
      opacity: { value: 0.5, random: true },
      size: { value: 3, random: true },
      line_linked: { enable: true, distance: 150, color: "#00FF80", opacity: 0.4, width: 1 },
      move: { enable: true, speed: 2, direction: "none", random: false }
    },
    interactivity: {
      detect_on: "canvas",
      events: { onhover: { enable: true, mode: "repulse" }, onclick: { enable: true, mode: "push" } },
      modes: { repulse: { distance: 100, duration: 0.4 }, push: { particles_nb: 4 } }
    }
  });
</script>



# Hi, I'm Om Take! 👨‍💻
### <span id="typewriter" style="color: #00FF80;"></span>
Passionate about building slick apps and mastering new tech stacks. Let's hack the world together! 🚀

![Profile Banner](https://github.com/OmTake27/OmTake27/blob/main/github-header-image.png)

<p align="left">
  <img src="https://komarev.com/ghpvc/?username=omtake27&label=Profile%20views&color=0e75b6&style=flat" alt="omtake27" />
</p>

<script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.12"></script>
<script>
  var typed = new Typed('#typewriter', {
    strings: ['Software Engineer', 'Code Hacker', 'Tech Enthusiast', 'Problem Solver', 'GitHub Rockstar'],
    typeSpeed: 50,
    backSpeed: 30,
    loop: true
  });
</script>

---

## My Tech Arsenal 🛠️
### Languages
<div class="language-badges">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
</div>

### Frameworks & Tools
<div class="framework-badges">
  <img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge&logo=spring&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="VS Code" />
</div>

<div class="skills-radar"></div>

---

## Featured Projects 🚀
<div class="project-card">
  <h3><a href="https://github.com/OmTake27/portfolio">Portfolio Website</a></h3>
  A sleek personal website showcasing my projects and skills.<br>
  🛠️ <b>Tech</b>: HTML, CSS, JavaScript, React<br>
  ⭐ <b>Impact</b>: My digital calling card to the world!
</div>

<div class="project-card">
  <h3><a href="https://github.com/OmTake27/task-manager">Java Task Manager</a></h3>
  A task management app built with Spring Boot and Java.<br>
  🛠️ <b>Tech</b>: Java, Spring Boot, SQL<br>
  ⭐ <b>Impact</b>: Streamlines task organization for teams.
</div>

<div class="project-card">
  <h3><a href="https://github.com/OmTake27/leetcode-solutions">LeetCode Solutions</a></h3>
  My collection of problem-solving solutions from LeetCode.<br>
  🛠️ <b>Tech</b>: Python, Java, C++<br>
  ⭐ <b>Impact</b>: Sharpening my coding skills daily.
</div>

---

## Connect with Me 🌐
<p align="left">
  <a href="https://linkedin.com/in/omtake" target="_blank">
    <img align="center" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://leetcode.com/omtake" target="_blank">
    <img align="center" src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" />
  </a>
  <a href="https://x.com/omtake27" target="_blank">
    <img align="center" src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" />
  </a>
</p>

---

## 🏆 GitHub Trophies
<p align="left">
  <img src="https://github-profile-trophy.vercel.app/?username=omtake27&theme=radical&no-frame=true&margin-w=10" alt="GitHub Trophies" />
</p>

---

## 🌍 Visitors Around the Globe
<p align="left">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=omtake27.omtake27&left_color=black&right_color=00FF80" alt="Visitor Badge" />
</p>

---

## 📅 Daily Tasks / Learning
<p>
  <!--START_SECTION:daily-tasks-->
  <img src="https://img.shields.io/badge/Practice%20LeetCode%20Problems-Ongoing-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Learn%20Spring%20Boot%20Security-In%20Progress-orange?style=for-the-badge" />
  <!--END_SECTION:daily-tasks-->
</p>

---

## 📊 GitHub Vibes
<p>
  <img align="left" src="https://github-readme-stats.vercel.app/api?username=omtake27&show_icons=true&hide_border=false&theme=radical&count_private=true" alt="GitHub Stats" />
  <img align="left" src="https://github-readme-stats.vercel.app/api/top-langs/?username=omtake27&layout=compact&hide_border=false&theme=radical" alt="Top Languages" />
</p>

<p>
  <img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=omtake27&theme=radical" alt="GitHub Streak" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=omtake27&theme=radical" alt="GitHub Activity Graph" />
</p>
