<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Michael Terrazi | Gameplay Engineer</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Segoe UI', sans-serif;
    background-color: #0a0a0f;
    color: #e6e6e6;
    line-height: 1.6;
}

nav a {
    color: #F5C542;
    text-decoration: none;
    font-weight: 600;
}

nav a:hover {
    color: #FFD95A;
}

.container {
    max-width: 1100px;
    margin: auto;
    padding: 40px 20px;
}

header {
    text-align: center;
    padding: 100px 20px 80px 20px;
    background: linear-gradient(to bottom, #0b0c10, #111218);
}

h1 {
    font-size: 52px;
    font-weight: 600;
    letter-spacing: 2px;
}

.subtitle {
    font-size: 18px;
    color: #9aa0a6;
    margin-top: 10px;
}

.links {
    margin-top: 25px;
}

.links a { margin: 0 15px; color: #F5C542; 
text-decoration: none; font-weight: 500; } 
.links a:hover { color: white; }

section {
    margin-top: 80px;
}

h2 {
    font-size: 28px;
    margin-bottom: 20px;
    border-left: 4px solid #F5C542;
    padding-left: 10px;
}

.project {
    background-color: #111218;
    padding: 30px;
    margin-bottom: 30px;
    border-radius: 8px;
    transition: 0.3s ease;
}

.project:hover {
    transform: translateY(-5px);
}

.project h3 {
    font-size: 22px;
    margin-bottom: 10px;
}

.project p {
    color: #b8b8b8;
}

.tech {
    margin-top: 15px;
}

.tech span {
    display: inline-block;
    background-color: #1f2230;
    padding: 6px 10px;
    margin: 5px 5px 0 0;
    border-radius: 4px;
    font-size: 13px;
}

.button { display: inline-block; margin-top: 20px; padding: 10px 18px; 
background-color: #F5C542; color: #000; border-radius: 4px; font-weight: 
bold; text-decoration: none; } .button:hover { background-color: #89d1ff; }

.skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
}

.skill-box {
    background-color: #111218;
    padding: 20px;
    border-radius: 8px;
}

footer {
    text-align: center;
    margin-top: 100px;
    padding: 40px 20px;
    color: #777;
    font-size: 14px;
}
</style>
</head>

<body>

<header>
    <h1>Michael Terrazi</h1>
    <div class="subtitle">Unreal Engine C++ Gameplay Developer | AI Systems | Freelance & Tutoring</div>
    <div class="links">
        <a href="mailto:mterrazi2@gmail.com">Email</a>
        <a href="https://github.com/Mterrazi2" target="_blank">GitHub</a>
        <a href="https://www.linkedin.com/in/michael-t-01813b239/" target="_blank">LinkedIn</a>
        <a href="https://mterrazi2.itch.io/" target="_blank">itch.io</a>
    </div>
</header>

<div class="container">

<section>
<h2>Professional Summary</h2>
<p>
Gameplay Engineer specializing in systemic gameplay development using Unreal Engine and C++.
Focused on responsive player mechanics, AI behavior systems, combat design, and performance optimization.
Passionate about building polished, scalable gameplay systems that enhance player immersion and mechanical depth.
</p>
</section>

<section>
<h2>Selected Gameplay Systems</h2>

<div class="project">
<h3>Night at the Museum — Stealth Systems Architecture</h3>
<p>
Designed and implemented a modular stealth framework including AI perception systems,
player visibility detection, alert state transitions, and patrol behaviors.
Focused on scalable state logic and performance-conscious C++ implementation.
</p>
<div class="tech">
<span>Unreal Engine</span>
<span>C++</span>
<span>AI Perception</span>
<span>State Machines</span>
<span>Optimization</span>
</div>
<a class="button" href="https://mterrazi2.github.io/NightAtMuseum/" target="_blank">View Gameplay</a>
</div>

<div class="project">
<h3>Downtown Fort Myers — Combat & AI Systems</h3>
<p>
Developed first-person shooter combat systems including weapon firing logic,
damage processing, enemy AI behaviors, and encounter balancing.
Implemented modular enemy behavior trees and responsive player feedback systems.
</p>
<div class="tech">
<span>Unreal Engine</span>
<span>C++</span>
<span>Behavior Trees</span>
<span>Combat Systems</span>
<span>Game Balancing</span>
</div>
<a class="button" href="https://mterrazi2.github.io/DowntownFortMyers/" target="_blank">View Gameplay</a>
</div>

<div class="project">
<h3>Robin Hood — Camera & Spatial Audio Systems</h3>
<p>
Engineered adjustable dynamic camera systems and implemented precise spatial audio
to enhance player feedback and environmental awareness.
Completed full gameplay loop implementation within a two-week sprint cycle.
</p>
<div class="tech">
<span>Unreal Engine</span>
<span>Camera Systems</span>
<span>Spatial Audio</span>
<span>Gameplay Loop</span>
</div>
<a class="button" href="https://mterrazi2.github.io/RobinHood/" target="_blank">View Gameplay</a>
</div>

<div class="project">
<h3>The Flash — Story & Combat Systems</h3>
<p>
Focuses heavily on core systems such as super-speed movement, Free-Flow-style combat, 
and a speed-force ultimate, all built and tuned from scratch.
</p>
<div class="tech">
<span>Unreal Engine</span>
<span>Combat Systems</span>
<span>Cutscenes</span>
<span>Gameplay Loop</span>
</div>
<a class="button" href="https://mterrazi2.github.io/TheFlash/" target="_blank">View Gameplay</a>
</div>

</section>

<section>
<h2>Core Technical Expertise</h2>

<div class="skills-grid">
<div class="skill-box">
<strong>Languages</strong><br><br>
C++<br>
C<br>
Java<br>
HTML
</div>

<div class="skill-box">
<strong>Game Development</strong><br><br>
Gameplay Systems<br>
AI Architecture<br>
Combat Mechanics<br>
Player Movement<br>
Optimization
</div>

<div class="skill-box">
<strong>Tools & Engines</strong><br><br>
Unreal Engine<br>
Blender<br>
Maya<br>
Git
</div>
</div>
</section>

</div>

<footer>
© 2026 Michael Terrazi — Gameplay Engineer Portfolio
</footer>

</body>
</html>
