<style>
/* =========================================================
   CODED HERO + STATS
   These styles are scoped so the rest of the profile is unchanged.
========================================================= */

.sa-profile-top,
.sa-profile-top * {
  box-sizing: border-box;
}

.sa-profile-top {
  width: 100%;
  max-width: 1200px;
  margin: 0 auto;
  font-family: Arial, Helvetica, sans-serif;
}

/* =========================================================
   HERO
========================================================= */

.sa-hero {
  width: 100%;
  height: 360px;
  position: relative;
  overflow: hidden;
  text-align: left;
  background-color: #0c1017;
  background-image:
    radial-gradient(circle, rgba(88, 166, 255, 0.10) 1.2px, transparent 1.4px),
    radial-gradient(
      circle at 83% 43%,
      rgba(35, 134, 54, 0.09) 0%,
      rgba(35, 134, 54, 0.025) 26%,
      transparent 47%
    );
  background-size: 26px 26px, 100% 100%;
  border-top: 1px solid #21262d;
  border-bottom: 1px solid #21262d;
}

.sa-hero-content {
  position: absolute;
  left: 70px;
  top: 86px;
}

.sa-eyebrow {
  height: 18px;
  display: flex;
  align-items: center;
  gap: 8px;
  color: #9ba7b4;
  font-size: 14px;
  line-height: 18px;
  font-weight: 700;
  letter-spacing: 4px;
  text-transform: uppercase;
}

.sa-eyebrow-dots {
  display: flex;
  align-items: center;
  gap: 4px;
}

.sa-eyebrow-dot {
  width: 8px;
  height: 8px;
  border-radius: 50%;
}

.sa-blue-dot { background: #58a6ff; }
.sa-green-dot { background: #39d353; }
.sa-purple-dot { background: #a855f7; }

.sa-hero-title {
  margin: 21px 0 0;
  color: #f6f8fa;
  font-size: 70px;
  line-height: 72px;
  font-weight: 800;
  letter-spacing: 1px;
}

.sa-accent-lines {
  display: flex;
  align-items: center;
  gap: 4px;
  margin-top: 8px;
}

.sa-accent-line {
  width: 50px;
  height: 4px;
}

.sa-line-blue { background: #1f6feb; }
.sa-line-green { background: #39d353; }
.sa-line-purple { background: #a855f7; }

.sa-hero-description {
  width: 560px;
  margin: 21px 0 0;
  color: #d7dee7;
  font-size: 21px;
  line-height: 29px;
  font-weight: 400;
}

/* Right-side network */

.sa-hero-visual {
  position: absolute;
  width: 330px;
  height: 330px;
  right: 75px;
  top: 14px;
}

.sa-orbit {
  position: absolute;
  width: 302px;
  height: 302px;
  left: 14px;
  top: 14px;
  border-radius: 50%;
  border: 1px solid rgba(48, 89, 81, 0.24);
}

.sa-connections {
  position: absolute;
  inset: 0;
  width: 330px;
  height: 330px;
  pointer-events: none;
}

.sa-node-label {
  color: #9ba7b4;
  font-size: 12px;
  line-height: 15px;
  font-weight: 700;
  letter-spacing: 2px;
  text-transform: uppercase;
}

.sa-web-group {
  position: absolute;
  left: 129px;
  top: 29px;
  width: 74px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.sa-web-node {
  width: 40px;
  height: 40px;
  margin-top: 8px;
  border: 2px solid #58a6ff;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  background: #0c1017;
}

.sa-center-node {
  position: absolute;
  left: 134px;
  top: 134px;
  width: 62px;
  height: 62px;
  display: flex;
  align-items: center;
  justify-content: center;
  border: 2px solid #e6edf3;
  border-radius: 50%;
  background: #0c1017;
  color: #f0f6fc;
  font-size: 17px;
  line-height: 20px;
  font-weight: 700;
  z-index: 2;
}

.sa-ai-group {
  position: absolute;
  left: 63px;
  top: 191px;
  width: 70px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.sa-ai-node {
  width: 40px;
  height: 40px;
  border: 2px solid #a855f7;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  background: #0c1017;
}

.sa-ai-group .sa-node-label,
.sa-mobile-group .sa-node-label {
  margin-top: 5px;
}

.sa-mobile-group {
  position: absolute;
  left: 223px;
  top: 191px;
  width: 80px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.sa-mobile-node {
  width: 40px;
  height: 40px;
  border: 2px solid #39d353;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  background: #0c1017;
}

/* =========================================================
   STATS
========================================================= */

.sa-stats-section {
  width: 100%;
  height: 94px;
  display: flex;
  align-items: center;
  gap: 19px;
  padding: 0 29px;
  background: #000000;
}

.sa-stat-card {
  flex: 1 1 0;
  min-width: 0;
  height: 76px;
  border: 2px solid;
  border-radius: 40px;
  display: flex;
  align-items: center;
  padding: 0 16px;
  text-align: left;
}

.sa-stat-card.sa-green {
  border-color: #238637;
  background: linear-gradient(180deg, #0f291a 0%, #0e2518 50%, #0e2217 100%);
}

.sa-stat-card.sa-blue {
  border-color: #1f6feb;
  background: linear-gradient(180deg, #111f34 0%, #111d31 50%, #101c2e 100%);
}

.sa-stat-card.sa-purple {
  border-color: #8857e5;
  background: linear-gradient(180deg, #1f132e 0%, #1d122d 50%, #1b112b 100%);
}

.sa-icon-circle {
  width: 42px;
  height: 42px;
  min-width: 42px;
  border-radius: 50%;
  display: flex;
  justify-content: center;
  align-items: center;
  margin-right: 15px;
  color: #06100a;
}

.sa-green .sa-icon-circle { background: #39d353; }
.sa-blue .sa-icon-circle { background: #58a6ff; }
.sa-purple .sa-icon-circle { background: #a855f7; }

.sa-stat-content {
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.sa-stat-title {
  margin: 0;
  font-size: 16px;
  line-height: 20px;
  font-weight: 700;
  letter-spacing: 1px;
  text-transform: uppercase;
}

.sa-green .sa-stat-title { color: #39d353; }
.sa-blue .sa-stat-title { color: #58a6ff; }
.sa-purple .sa-stat-title { color: #a855f7; }

.sa-stat-description {
  margin: 1px 0 0;
  color: #e6edf3;
  font-size: 14px;
  line-height: 18px;
  font-weight: 400;
}
</style>

<div class="sa-profile-top">

  <!-- HERO: fully coded, no hero image -->
  <section class="sa-hero">

    <div class="sa-hero-content">

      <div class="sa-eyebrow">
        <span class="sa-eyebrow-dots">
          <span class="sa-eyebrow-dot sa-blue-dot"></span>
          <span class="sa-eyebrow-dot sa-green-dot"></span>
          <span class="sa-eyebrow-dot sa-purple-dot"></span>
        </span>
        <span>FULL-STACK SOFTWARE ENGINEER</span>
      </div>

      <h1 class="sa-hero-title">Shiza Asif</h1>

      <div class="sa-accent-lines">
        <span class="sa-accent-line sa-line-blue"></span>
        <span class="sa-accent-line sa-line-green"></span>
        <span class="sa-accent-line sa-line-purple"></span>
      </div>

      <p class="sa-hero-description">
        Building web platforms, Flutter apps, and AI-powered<br>
        products — end to end, for founders and product teams.
      </p>

    </div>

    <div class="sa-hero-visual">

      <div class="sa-orbit"></div>

      <svg class="sa-connections" viewBox="0 0 330 330" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <line x1="165" y1="94" x2="165" y2="134" stroke="#59636E" stroke-opacity=".70" stroke-width="1.5" />
        <line x1="140" y1="178" x2="113" y2="198" stroke="#59636E" stroke-opacity=".70" stroke-width="1.5" />
        <line x1="190" y1="178" x2="241" y2="207" stroke="#59636E" stroke-opacity=".70" stroke-width="1.5" />
      </svg>

      <div class="sa-web-group">
        <div class="sa-node-label">WEB</div>
        <div class="sa-web-node">
          <svg width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
            <path d="M3 7H21" stroke="#58A6FF" stroke-width="2" stroke-linecap="round" />
            <path d="M3 12H21" stroke="#58A6FF" stroke-width="2" stroke-linecap="round" />
            <path d="M3 17H21" stroke="#58A6FF" stroke-width="2" stroke-linecap="round" />
          </svg>
        </div>
      </div>

      <div class="sa-center-node">SA</div>

      <div class="sa-ai-group">
        <div class="sa-ai-node">
          <svg width="25" height="25" viewBox="0 0 26 26" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
            <path d="M7 17L13 8L19 17" stroke="#A855F7" stroke-width="1.4" stroke-linecap="round" />
            <path d="M7 17L19 17" stroke="#A855F7" stroke-width="1.4" stroke-linecap="round" />
            <circle cx="13" cy="7" r="2.2" fill="#A855F7" />
            <circle cx="6" cy="18" r="2.2" fill="#A855F7" />
            <circle cx="20" cy="18" r="2.2" fill="#A855F7" />
          </svg>
        </div>
        <div class="sa-node-label">AI</div>
      </div>

      <div class="sa-mobile-group">
        <div class="sa-mobile-node">
          <svg width="19" height="22" viewBox="0 0 20 24" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
            <rect x="3" y="2" width="14" height="20" rx="2" stroke="#39D353" stroke-width="1.7" />
          </svg>
        </div>
        <div class="sa-node-label">MOBILE</div>
      </div>

    </div>
  </section>

  <br/><br/>

  <div align="center">
    <p>
      <a href="https://shiza-asif-portfolio.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-21262D?style=for-the-badge&logo=vercel&logoColor=white" alt="View Portfolio" /></a>
      <a href="https://www.linkedin.com/in/shiza-asif-web-developerr/"><img src="https://img.shields.io/badge/LinkedIn-0969DA?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Profile" /></a>
      <a href="mailto:shizaasif710@gmail.com"><img src="https://img.shields.io/badge/Email-238636?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Shiza" /></a>
      <!-- Replace with your real Fiverr gig URL -->
      <a href="https://www.fiverr.com/your-fiverr-username"><img src="https://img.shields.io/badge/Fiverr-1DBF73?style=for-the-badge&logo=fiverr&logoColor=white" alt="Hire on Fiverr" /></a>
    </p>
  </div>

  <br/>

  <!-- STATS: fully coded, no stats image -->
  <section class="sa-stats-section">

    <div class="sa-stat-card sa-green">
      <div class="sa-icon-circle">
        <svg width="25" height="25" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <circle cx="12" cy="12" r="9" stroke="currentColor" stroke-width="2" />
          <path d="M12 7V12L15.5 14" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" />
        </svg>
      </div>
      <div class="sa-stat-content">
        <div class="sa-stat-title">4+ YEARS</div>
        <div class="sa-stat-description">Building shipped products</div>
      </div>
    </div>

    <div class="sa-stat-card sa-blue">
      <div class="sa-icon-circle">
        <svg width="27" height="27" viewBox="0 0 28 28" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <path d="M5 15.5C7.4 12.8 10.5 11.5 14 11.5C17.5 11.5 20.6 12.8 23 15.5" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" />
          <path d="M8.6 18C10.1 16.5 12 15.7 14 15.7C16 15.7 17.9 16.5 19.4 18" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" />
          <circle cx="14" cy="19.5" r="1.6" fill="currentColor" />
        </svg>
      </div>
      <div class="sa-stat-content">
        <div class="sa-stat-title">REMOTE READY</div>
        <div class="sa-stat-description">Open to remote work</div>
      </div>
    </div>

    <div class="sa-stat-card sa-purple">
      <div class="sa-icon-circle">
        <svg width="27" height="27" viewBox="0 0 24 24" fill="currentColor" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <circle cx="12" cy="7.3" r="4" />
          <path d="M4.8 20C4.8 15.9 8 12.8 12 12.8C16 12.8 19.2 15.9 19.2 20H4.8Z" />
        </svg>
      </div>
      <div class="sa-stat-content">
        <div class="sa-stat-title">INDEPENDENT</div>
        <div class="sa-stat-description">Freelance developer</div>
      </div>
    </div>

  </section>

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:0D1117,100:0D1117&height=2" alt="" />

<h2 align="center">
<img src="https://api.iconify.design/fa6-solid/toolbox.svg?color=%2339D353" width="24" alt="" />
&nbsp;Technical Expertise
</h2>

<table width="100%" border="1" cellpadding="0" cellspacing="0">
<tr>
<td width="12%" align="center" valign="middle">
<img src="https://api.iconify.design/fa6-solid/display.svg?color=%2358A6FF" width="22" alt="" /><br/><br/>
<strong>Frontend</strong>
</td>
<td width="88%">
<table width="100%">
<tr>
<td align="center" width="14.28%"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg" width="40" alt="HTML5"/><br/><sub><b>HTML5</b></sub></td>
<td align="center" width="14.28%"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-original.svg" width="40" alt="CSS3"/><br/><sub><b>CSS3</b></sub></td>
<td align="center" width="14.28%"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" width="40" alt="JavaScript"/><br/><sub><b>JavaScript</b></sub></td>
<td align="center" width="14.28%"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg" width="40" alt="TypeScript"/><br/><sub><b>TypeScript</b></sub></td>
<td align="center" width="14.28%"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg" width="40" alt="React"/><br/><sub><b>React.js</b></sub></td>
<td align="center" width="14.28%"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nextjs/nextjs-original.svg" width="40" alt="Next.js"/><br/><sub><b>Next.js</b></sub></td>
<td align="center" width="14.28%"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/angularjs/angularjs-original.svg" width="40" alt="Angular"/><br/><sub><b>Angular</b></sub></td>
</tr>
<tr>
<td align="center" width="14.28%"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/ionic/ionic-original.svg" width="40" alt="Ionic"/><br/><sub><b>Ionic</b></sub></td>
<td align="center" width="14.28%"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/tailwindcss/tailwindcss-original.svg" width="40" alt="Tailwind"/><br/><sub><b>Tailwind</b></sub></td>
<td align="center" width="14.28%"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/bootstrap/bootstrap-original.svg" width="40" alt="Bootstrap"/><br/><sub><b>Bootstrap</b></sub></td>
<td align="center" width="14.28%"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/jquery/jquery-original.svg" width="40" alt="jQuery"/><br/><sub><b>jQuery</b></sub></td>
<td align="center" width="14.28%"></td>
<td align="center" width="14.28%"></td>
<td align="center" width="14.28%"></td>
</tr>
</table>
</td>
</tr>
</table>

<table width="100%" border="1" cellpadding="0" cellspacing="0">
<tr>
<td width="12%" align="center" valign="middle">
<img src="https://api.iconify.design/fa6-solid/server.svg?color=%2358A6FF" width="22" alt="" /><br/><br/>
<strong>Backend</strong>
</td>
<td width="88%">
<table width="100%">
<tr>
<td align="center" width="14.28%"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/php/php-original.svg" width="40" alt="PHP"/><br/><sub><b>PHP</b></sub></td>
<td align="center" width="14.28%"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/laravel/laravel-original.svg" width="40" alt="Laravel"/><br/><sub><b>Laravel</b></sub></td>
<td align="center" width="14.28%"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nodejs/nodejs-original.svg" width="40" alt="Node.js"/><br/><sub><b>Node.js</b></sub></td>
<td align="center" width="14.28%"></td>
<td align="center" width="14.28%"></td>
<td align="center" width="14.28%"></td>
<td align="center" width="14.28%"></td>
</tr>
</table>
</td>
</tr>
</table>

<table width="100%" border="1" cellpadding="0" cellspacing="0">
<tr>
<td width="12%" align="center" valign="middle">
<img src="https://api.iconify.design/fa6-solid/database.svg?color=%2358A6FF" width="22" alt="" /><br/><br/>
<strong>Databases<br/>&amp; Cloud</strong>
</td>
<td width="88%">
<table width="100%">
<tr>
<td align="center" width="14.28%"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original.svg" width="40" alt="MySQL"/><br/><sub><b>MySQL</b></sub></td>
<td align="center" width="14.28%"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/sqlite/sqlite-original.svg" width="40" alt="SQLite"/><br/><sub><b>SQLite</b></sub></td>
<td align="center" width="14.28%"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/firebase/firebase-original.svg" width="40" alt="Firebase"/><br/><sub><b>Firebase</b></sub></td>
<td align="center" width="14.28%"><img src="https://api.iconify.design/simple-icons/supabase.svg?color=%233FCF8E" width="40" alt="Supabase"/><br/><sub><b>Supabase</b></sub></td>
<td align="center" width="14.28%"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vercel/vercel-original.svg" width="40" alt="Vercel"/><br/><sub><b>Vercel</b></sub></td>
<td align="center" width="14.28%"></td>
<td align="center" width="14.28%"></td>
</tr>
</table>
</td>
</tr>
</table>

<table width="100%" border="1" cellpadding="0" cellspacing="0">
<tr>
<td width="12%" align="center" valign="middle">
<img src="https://api.iconify.design/fa6-solid/mobile-screen-button.svg?color=%2358A6FF" width="22" alt="" /><br/><br/>
<strong>Mobile</strong>
</td>
<td width="88%">
<table width="100%">
<tr>
<td align="center" width="14.28%"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/dart/dart-original.svg" width="40" alt="Dart"/><br/><sub><b>Dart</b></sub></td>
<td align="center" width="14.28%"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/flutter/flutter-original.svg" width="40" alt="Flutter"/><br/><sub><b>Flutter</b></sub></td>
<td align="center" width="14.28%"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/androidstudio/androidstudio-original.svg" width="40" alt="Android Studio"/><br/><sub><b>Android Studio</b></sub></td>
<td align="center" width="14.28%"><img src="https://api.iconify.design/simple-icons/googleplay.svg?color=%2334A853" width="40" alt="Google Play"/><br/><sub><b>Google Play</b></sub></td>
<td align="center" width="14.28%"><img src="https://api.iconify.design/simple-icons/googleadmob.svg?color=%23EA4335" width="40" alt="AdMob"/><br/><sub><b>AdMob</b></sub></td>
<td align="center" width="14.28%"></td>
<td align="center" width="14.28%"></td>
</tr>
</table>
</td>
</tr>
</table>

<table width="100%" border="1" cellpadding="0" cellspacing="0">
<tr>
<td width="12%" align="center" valign="middle">
<img src="https://api.iconify.design/fa6-solid/robot.svg?color=%2358A6FF" width="22" alt="" /><br/><br/>
<strong>AI &amp; Modern<br/>Tooling</strong>
</td>
<td width="88%">
<table width="100%">
<tr>
<td align="center" width="14.28%"><img src="https://api.iconify.design/simple-icons/openai.svg?color=%2374AA9C" width="40" alt="OpenAI"/><br/><sub><b>OpenAI</b></sub></td>
<td align="center" width="14.28%"><img src="https://api.iconify.design/simple-icons/googlegemini.svg?color=%238E75B2" width="40" alt="Gemini"/><br/><sub><b>Gemini</b></sub></td>
<td align="center" width="14.28%"><img src="https://api.iconify.design/simple-icons/anthropic.svg?color=%23D97757" width="40" alt="Claude"/><br/><sub><b>Claude</b></sub></td>
<td align="center" width="14.28%"><img src="https://api.iconify.design/simple-icons/ollama.svg?color=%23C9D1D9" width="40" alt="Ollama"/><br/><sub><b>Ollama</b></sub></td>
<td align="center" width="14.28%"><img src="https://api.iconify.design/simple-icons/cursor.svg?color=%23C9D1D9" width="40" alt="Cursor"/><br/><sub><b>Cursor</b></sub></td>
<td align="center" width="14.28%"><img src="https://api.iconify.design/fa6-solid/terminal.svg?color=%2300A67E" width="40" alt="Trae"/><br/><sub><b>Trae</b></sub></td>
<td align="center" width="14.28%"><img src="https://api.iconify.design/simple-icons/openrouter.svg?color=%236467F2" width="40" alt="OpenRouter"/><br/><sub><b>OpenRouter</b></sub></td>
</tr>
<tr>
<td align="center" width="14.28%"><img src="https://api.iconify.design/fa6-solid/cube.svg?color=%236B57FF" width="40" alt="Kiro"/><br/><sub><b>Kiro</b></sub></td>
<td align="center" width="14.28%"><img src="https://api.iconify.design/fa6-solid/wand-magic-sparkles.svg?color=%234285F4" width="40" alt="Antigravity"/><br/><sub><b>Antigravity</b></sub></td>
<td align="center" width="14.28%"><img src="https://api.iconify.design/simple-icons/openai.svg?color=%2374AA9C" width="40" alt="Codex"/><br/><sub><b>Codex</b></sub></td>
<td align="center" width="14.28%"><img src="https://api.iconify.design/fa6-solid/robot.svg?color=%2339d353" width="40" alt="Cline"/><br/><sub><b>Cline</b></sub></td>
<td align="center" width="14.28%"><img src="https://api.iconify.design/fa6-solid/code.svg?color=%23A855F7" width="40" alt="Qoder"/><br/><sub><b>Qoder</b></sub></td>
<td align="center" width="14.28%"></td>
<td align="center" width="14.28%"></td>
</tr>
</table>
</td>
</tr>
</table>

<table width="100%" border="1" cellpadding="0" cellspacing="0">
<tr>
<td width="12%" align="center" valign="middle">
<img src="https://api.iconify.design/fa6-solid/screwdriver-wrench.svg?color=%2358A6FF" width="22" alt="" /><br/><br/>
<strong>Tools &amp;<br/>Delivery</strong>
</td>
<td width="88%">
<table width="100%">
<tr>
<td align="center" width="14.28%"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" width="40" alt="Git"/><br/><sub><b>Git</b></sub></td>
<td align="center" width="14.28%"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/github/github-original.svg" width="40" alt="GitHub"/><br/><sub><b>GitHub</b></sub></td>
<td align="center" width="14.28%"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/gitlab/gitlab-original.svg" width="40" alt="GitLab"/><br/><sub><b>GitLab</b></sub></td>
<td align="center" width="14.28%"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/figma/figma-original.svg" width="40" alt="Figma"/><br/><sub><b>Figma</b></sub></td>
<td align="center" width="14.28%"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vscode/vscode-original.svg" width="40" alt="VS Code"/><br/><sub><b>VS Code</b></sub></td>
<td align="center" width="14.28%"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postman/postman-original.svg" width="40" alt="Postman"/><br/><sub><b>Postman</b></sub></td>
<td align="center" width="14.28%"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/jira/jira-original.svg" width="40" alt="Jira"/><br/><sub><b>Jira</b></sub></td>
</tr>
<tr>
<td align="center" width="14.28%"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/slack/slack-original.svg" width="40" alt="Slack"/><br/><sub><b>Slack</b></sub></td>
<td align="center" width="14.28%"><img src="https://api.iconify.design/simple-icons/hostinger.svg?color=%23673DE6" width="40" alt="Hostinger"/><br/><sub><b>Hostinger</b></sub></td>
<td align="center" width="14.28%"><img src="https://api.iconify.design/simple-icons/cpanel.svg?color=%23FF6C2C" width="40" alt="cPanel"/><br/><sub><b>cPanel</b></sub></td>
<td align="center" width="14.28%"><img src="https://api.iconify.design/simple-icons/filezilla.svg?color=%23BF0000" width="40" alt="FileZilla"/><br/><sub><b>FileZilla</b></sub></td>
<td align="center" width="14.28%"><img src="https://api.iconify.design/simple-icons/gmail.svg?color=%23EA4335" width="40" alt="Gmail API"/><br/><sub><b>Gmail API</b></sub></td>
<td align="center" width="14.28%"><img src="https://api.iconify.design/simple-icons/googleanalytics.svg?color=%23E37400" width="40" alt="Analytics"/><br/><sub><b>Analytics</b></sub></td>
<td align="center" width="14.28%"><img src="https://api.iconify.design/simple-icons/microsoftoffice.svg?color=%23D83B01" width="40" alt="MS Office"/><br/><sub><b>MS Office</b></sub></td>
</tr>
</table>
</td>
</tr>
</table>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:0D1117,100:0D1117&height=2" alt="" />

<h2 align="center">
<img src="https://api.iconify.design/fa6-solid/crosshairs.svg?color=%2339D353" width="24" alt="" />
&nbsp;Current Focus
</h2>

<div align="center">
<table width="100%">
<tr>
<td width="25%" align="center" valign="top">
<img src="https://api.iconify.design/fa6-solid/laptop-code.svg?color=%2339d353" width="24" alt="" /><br/><br/>
<strong>Full-Stack Products</strong><br/>
<sub>Web platforms from interface to API.</sub>
</td>
<td width="25%" align="center" valign="top">
<img src="https://api.iconify.design/fa6-solid/mobile-screen.svg?color=%2339d353" width="20" alt="" /><br/><br/>
<strong>Mobile Apps</strong><br/>
<sub>Flutter builds ready for real users.</sub>
</td>
<td width="25%" align="center" valign="top">
<img src="https://api.iconify.design/fa6-solid/wand-magic-sparkles.svg?color=%2339d353" width="22" alt="" /><br/><br/>
<strong>Agentic AI</strong><br/>
<sub>Intelligence embedded into workflows.</sub>
</td>
<td width="25%" align="center" valign="top">
<img src="https://api.iconify.design/fa6-solid/layer-group.svg?color=%2339d353" width="22" alt="" /><br/><br/>
<strong>Clean Architecture</strong><br/>
<sub>Systems designed to scale with the product.</sub>
</td>
</tr>
</table>
</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:0D1117,100:0D1117&height=2" alt="" />

<h2 align="center">
<img src="https://api.iconify.design/fa6-brands/github.svg?color=%23F0F6FC" width="25" alt="" />
&nbsp;GitHub Activity
</h2>

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=shizaoffical&show_icons=true&theme=github-dark-blue&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=39D353&text_color=C9D1D9" alt="Shiza Asif GitHub stats" />
<img width="46%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=shizaoffical&layout=compact&theme=github-dark-blue&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9" alt="Shiza Asif top languages" />

<br/>

<img width="74%" src="https://streak-stats.demolab.com?user=shizaoffical&theme=github-dark-blue&hide_border=true&background=0D1117&ring=39D353&fire=39D353&currStreakLabel=58A6FF&sideLabels=C9D1D9&dates=8B949E" alt="Shiza Asif GitHub contribution streak" />

<img width="96%" src="https://github-readme-activity-graph.vercel.app/graph?username=shizaoffical&bg_color=0D1117&color=C9D1D9&line=39D353&point=39D353&area=true&area_color=0E4429&hide_border=true&custom_title=Shiza%20Asif%27s%20Contribution%20Graph" alt="Shiza Asif GitHub contribution graph" />

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:0D1117,100:0D1117&height=2" alt="" />

<div align="center">

<h2>
<img src="https://api.iconify.design/fa6-solid/handshake.svg?color=%2339D353" width="25" alt="" />
&nbsp;Let's Build Something Useful
</h2>

<p><sub>Open to freelance projects and remote roles.</sub></p>

<p>
  <a href="https://shiza-asif-portfolio.vercel.app/"><img src="https://img.shields.io/badge/Explore_Work-21262D?style=for-the-badge&logo=vercel&logoColor=F0F6FC" alt="Explore Shiza's work" /></a>
  <a href="https://www.linkedin.com/in/shiza-asif-web-developerr/"><img src="https://img.shields.io/badge/Connect-0969DA?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn" /></a>
  <a href="mailto:shizaasif710@gmail.com"><img src="https://img.shields.io/badge/Discuss_a_Project-238636?style=for-the-badge&logo=gmail&logoColor=white" alt="Discuss a project" /></a>
  <!-- Replace with your real Fiverr gig URL -->
  <a href="https://www.fiverr.com/your-fiverr-username"><img src="https://img.shields.io/badge/Hire_Me_on_Fiverr-1DBF73?style=for-the-badge&logo=fiverr&logoColor=white" alt="Hire Shiza on Fiverr" /></a>
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:238636,45:0D3320,100:0D1117&height=105&section=footer" alt="Footer decoration" />

</div>
