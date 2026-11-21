# kelvin26633-source.github
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Kelvin Kipkoech | Cyber Security &amp; Cloud Engineer</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:wght@500;700;800&family=Instrument+Sans:wght@400;500;600&display=swap" rel="stylesheet">
<style>
:root{
  --bg:#f4f6fa; --surface:#ffffff; --ink:#14213d; --muted:#4b5a78; --line:#d5dbe8;
  --accent:#0b6e8a; --accent-ink:#ffffff; --signal:#c2410c;
  --head:"Bricolage Grotesque","Trebuchet MS",system-ui,sans-serif;
  --body:"Instrument Sans","Segoe UI",system-ui,sans-serif;
  box-sizing:border-box; padding-top:env(safe-area-inset-top,0px); padding-bottom:env(safe-area-inset-bottom,0px);
  color-scheme:light;
}
@media (prefers-color-scheme:dark){
  :root:not([data-theme="light"]){--bg:#0f1a2e;--surface:#17243d;--ink:#eaf0fb;--muted:#a3b2cc;--line:#2a3a5a;--accent:#4cc3e0;--accent-ink:#0f1a2e;--signal:#fb923c;color-scheme:dark}
}
:root[data-theme="dark"]{--bg:#0f1a2e;--surface:#17243d;--ink:#eaf0fb;--muted:#a3b2cc;--line:#2a3a5a;--accent:#4cc3e0;--accent-ink:#0f1a2e;--signal:#fb923c;color-scheme:dark}
html{scroll-padding-top:env(safe-area-inset-top,0px);scroll-behavior:smooth}
*,*::before,*::after{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--ink);font:400 1.05rem/1.6 var(--body)}
a{color:inherit}
:focus-visible{outline:3px solid var(--accent);outline-offset:3px}
.wrap{max-width:1000px;margin:0 auto;padding:0 1.25rem}
header.nav{position:sticky;top:env(safe-area-inset-top,0px);background:var(--bg);border-bottom:1px solid var(--line);z-index:5}
.nav .wrap{display:flex;justify-content:space-between;align-items:center;padding-top:.8rem;padding-bottom:.8rem;gap:1rem;flex-wrap:wrap}
.nav b{font-family:var(--head);font-size:1.1rem}
.nav nav{display:flex;gap:1.1rem;flex-wrap:wrap}
.nav nav a{text-decoration:none;color:var(--muted);font-weight:500}
.nav nav a:hover{color:var(--accent)}
.hero{padding:4.5rem 0 3.5rem;position:relative;overflow:hidden}
.hero h1{font-family:var(--head);font-weight:800;font-size:clamp(2.8rem,9vw,6rem);line-height:.98;margin:0 0 1.2rem;letter-spacing:-.03em;position:relative;display:inline-block}
.hero h1::after{content:"";position:absolute;top:-6%;bottom:-6%;left:0;width:3px;background:var(--signal);box-shadow:0 0 14px var(--signal);animation:scan 2.2s ease-out 1 forwards;opacity:0}
@keyframes scan{0%{left:0;opacity:1}90%{opacity:1}100%{left:100%;opacity:0}}
.role{font-family:var(--head);font-size:clamp(1.15rem,3vw,1.6rem);font-weight:500;color:var(--accent);margin:0 0 1rem}
.hero p.lead{max-width:60ch;color:var(--muted);margin:0 0 1.8rem}
.btns{display:flex;gap:.8rem;flex-wrap:wrap}
.btn{display:inline-block;padding:.75rem 1.3rem;border-radius:6px;font-weight:600;text-decoration:none;border:2px solid var(--accent)}
.btn.primary{background:var(--accent);color:var(--accent-ink)}
.btn.ghost{color:var(--accent)}
.btn:hover{filter:brightness(1.08)}
section{padding:3.2rem 0;border-top:1px solid var(--line)}
h2{font-family:var(--head);font-size:clamp(1.7rem,4vw,2.3rem);margin:0 0 1.4rem;letter-spacing:-.02em}
.grid{display:grid;gap:1rem;grid-template-columns:repeat(auto-fit,minmax(250px,1fr))}
.box{background:var(--surface);border:1px solid var(--line);border-radius:8px;padding:1.3rem}
.box h3{font-family:var(--head);margin:0 0 .5rem;font-size:1.2rem}
.box p{margin:0;color:var(--muted)}
.about{display:grid;gap:1.5rem;grid-template-columns:1fr}
@media(min-width:760px){.about{grid-template-columns:1.4fr 1fr}}
dl{margin:0;display:grid;grid-template-columns:auto 1fr;gap:.5rem 1rem}
dt{font-weight:600}
dd{margin:0;color:var(--muted)}
.chips{display:flex;flex-wrap:wrap;gap:.5rem;margin-top:1rem}
.chips span{border:1px solid var(--line);background:var(--surface);padding:.3rem .8rem;border-radius:99px;font-size:.92rem}
.project{background:var(--surface);border:1px solid var(--line);border-left:6px solid var(--signal);border-radius:8px;padding:1.6rem}
.project h3{font-family:var(--head);font-size:1.6rem;margin:0 0 .6rem}
.project p{color:var(--muted);max-width:68ch}
.project ul{color:var(--muted);padding-left:1.2rem;margin:.8rem 0 0}
.contact-list{list-style:none;margin:0;padding:0;display:grid;gap:.8rem;grid-template-columns:repeat(auto-fit,minmax(260px,1fr))}
.contact-list li{background:var(--surface);border:1px solid var(--line);border-radius:8px;padding:1rem 1.2rem}
.contact-list small{display:block;color:var(--muted)}
.contact-list a{font-weight:600;color:var(--accent);word-break:break-word}
footer{border-top:1px solid var(--line);padding:1.8rem 0;color:var(--muted);text-align:center;font-size:.95rem}
@media (prefers-reduced-motion:reduce){.hero h1::after{animation:none}html{scroll-behavior:auto}}
</style>
</head>
<body>
<header class="nav"><div class="wrap">
  <b>Kelvin Kipkoech</b>
  <nav aria-label="Main"><a href="#about">About</a><a href="#skills">Skills</a><a href="#project">Project</a><a href="#contact">Contact</a></nav>
</div></header>

<main>
<div class="hero"><div class="wrap">
  <h1>Kelvin Kipkoech</h1>
  <p class="role">Cyber security and cloud engineer</p>
  <p class="lead">I’m a computer science student at KYU who builds secure systems and cloud infrastructure, and I’m developing an AI detector to tell human-made content from machine-made content.</p>
  <div class="btns">
    <a class="btn primary" href="#project">See my project</a>
    <a class="btn ghost" href="#contact">Contact me</a>
  </div>
</div></div>

<section id="about"><div class="wrap">
  <h2>About me</h2>
  <div class="about">
    <p>I study computer science at KYU and focus on protecting systems and running them in the cloud. I like finding weak points before attackers do, then designing setups that are hard to break and easy to maintain. My current work combines this security mindset with AI.</p>
    <dl>
      <dt>Name</dt><dd>Kelvin Kipkoech</dd>
      <dt>School</dt><dd>KYU</dd>
      <dt>Course</dt><dd>Computer Science</dd>
      <dt>Focus</dt><dd>Cyber security, cloud</dd>
    </dl>
  </div>
</div></section>

<section id="skills"><div class="wrap">
  <h2>What I do</h2>
  <div class="grid">
    <div class="box"><h3>Cyber security</h3><p>Securing networks, applications and accounts, and checking for vulnerabilities and risks.</p></div>
    <div class="box"><h3>Cloud engineering</h3><p>Setting up and managing cloud services with a focus on safe access and reliable uptime.</p></div>
    <div class="box"><h3>AI and software</h3><p>Building tools that use machine learning, taught through my computer science degree.</p></div>
  </div>
  <div class="chips" aria-label="Topics">
    <span>Network security</span><span>Cloud infrastructure</span><span>Threat awareness</span><span>Access control</span><span>Programming</span><span>Machine learning</span>
  </div>
</div></section>

<section id="project"><div class="wrap">
  <h2>Featured project</h2>
  <article class="project">
    <h3>AI detector</h3>
    <p>A tool that analyses content and estimates whether it was written by a person or generated by AI. It supports honesty in schools, workplaces and online spaces.</p>
    <ul>
      <li>Built as part of my computer science studies at KYU</li>
      <li>Combines security thinking with machine learning</li>
      <li>Aims to give clear, easy-to-read results</li>
    </ul>
  </article>
</div></section>

<section id="contact"><div class="wrap">
  <h2>Get in touch</h2>
  <ul class="contact-list">
    <li><small>Phone</small><a href="tel:+254769560407">0769 560 407</a></li>
    <li><small>WhatsApp</small><a href="https://wa.me/254769560407">Message 0769 560 407</a></li>
    <li><small>Email</small><a href="mailto:nizzyliam@gmail.com">nizzyliam@gmail.com</a></li>
    <li><small>Instagram</small><a href="https://instagram.com/Nizzyliam">@Nizzyliam</a></li>
    <li><small>X (Twitter)</small><a href="https://x.com/Nizzyliam">@Nizzyliam</a></li>
    <li><small>TikTok</small><a href="https://tiktok.com/@Nizzyliam">@Nizzyliam</a></li>
    <li><small>GitHub</small><a href="https://github.com/Nizzyliam">@Nizzyliam</a></li>
    <li><small>Facebook</small><a href="https://facebook.com/Nizzyliam">@Nizzyliam</a></li>
  </ul>
</div></section>
</main>

<footer><div class="wrap">© 2026 Kelvin Kipkoech. All rights reserved.</div></footer>
</body>
</html>
