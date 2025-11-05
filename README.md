<div align="center">
  <h1 style="color:#ff0000; font-size:4em; text-shadow: 0 0 20px #ff0000, 0 0 40px #ff0000; animation: pulse 1.5s infinite;">
    🔥 <span style="color:#ff0000;">INSANE</span> <span style="color:#ff0000;">DEVIL</span> 🔥
  </h1>
  <img src="https://i.ibb.co/4pQbZ3k/neon-matrix-rain.gif" alt="RED MATRIX HELL" width="100%" style="filter: hue-rotate(0deg) saturate(200%) brightness(70%);"/>
  <br><br>
  ---
  > **🌀 I AM NOT A PROGRAMMER... I AM A <span style="color:#ff0000;">DIGITAL DEMON</span> REWRITING REALITY!**  
  > **💀 I CODE IN BLOOD, BURN SERVERS, RULE THE API!**  
  > **🌪️ LANGUAGES: <span style="color:#ff0000;">C++</span> | <span style="color:#ff0000;">Python</span> | <span style="color:#ff0000;">JavaScript</span> | <span style="color:#ff0000;">Rust</span> | <span style="color:#ff0000;">Brainfuck</span>**  
  > **📍 LOCATION: <span style="color:#ff0000;">THE ABYSS</span>**  
  > **⚡ MOTTO: <span style="font-size:1.8em; color:#ff0000;">“BURN THE CODE. RULE THE WORLD!”</span>**
  ---
  
  ### 🧨 **DEMONIC SKILLS**
  <img src="https://img.shields.io/badge/-C++-ff0000?style=for-the-badge&logo=c%2B%2B&logoColor=white&labelColor=8B0000" />
  <img src="https://img.shields.io/badge/-Python-ff0000?style=for-the-badge&logo=python&logoColor=white&labelColor=8B0000" />
  <img src="https://img.shields.io/badge/-JavaScript-ff0000?style=for-the-badge&logo=javascript&logoColor=white&labelColor=8B0000" />
  <img src="https://img.shields.io/badge/-Rust-ff0000?style=for-the-badge&logo=rust&logoColor=white&labelColor=8B0000" />
  <img src="https://img.shields.io/badge/-HACKING-ff0000?style=for-the-badge&logo=hackthebox&logoColor=white&labelColor=8B0000" />
  <img src="https://img.shields.io/badge/-AI-ff0000?style=for-the-badge&logo=tensorflow&logoColor=white&labelColor=8B0000" />
  <img src="https://img.shields.io/badge/-MALWARE-ff0000?style=for-the-badge&logo=virus&logoColor=white&labelColor=8B0000" />
  <br><br>

  ---
  
  ### 🎭 **INSANE PROJECTS**
  
  #### [💉 VirusForge](https://github.com/INSANE-DEV/VirusForge)
  > **TOOL TO FORGE SELF-EVOLVING VIRUSES THAT HUNT THEIR PREY!**  
  - Self-replicating AI core  
  - BIOS-level infection  
  - Opens portals to the Dark Web  
  > **WARNING: CRIMINAL USE MAY SUMMON THE FBI**

  #### [🤖 AutoPWN](https://github.com/INSANE-DEV/AutoPWN)
  > **SCRIPT THAT PWN ANY NETWORK IN UNDER 3 SECONDS**  
  - Auto-exploit discovery  
  - Air-gapped payload delivery  
  - Burns routers on exit  
  > **BANNED IN 47 COUNTRIES**

  #### [🌑 BlackHole API](https://github.com/INSANE-DEV/BlackHole-API)
  > **API THAT SWALLOWS REQUESTS AND RETURNS NOTHING... EVER!**  
  - 100% uptime (in hell)  
  - JSON to ashes converter  
  > **USED BY THE CIA (allegedly)**

  ---
  
  ### 📈 **STATS FROM HELL**
  <img src="https://github-readme-stats.vercel.app/api?username=INSANE-DEV&show_icons=true&theme=radical&hide_border=true&bg_color=0d0d0d&title_color=ff0000&icon_color=ff3333&text_color=ff6666&border_color=ff0000" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=INSANE-DEV&layout=donut-vertical&theme=radical&hide_border=true&bg_color=0d0d0d&title_color=ff0000&text_color=ff6666&border_color=ff0000" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=INSANE-DEV&theme=radical&hide_border=true&background=0d0d0d&stroke=ff0000&ring=ff3333&fire=ff0000&currStreakLabel=ff6666&border=ff0000" />
  <br><br>

  ---
  
  ### ⚡ **INSANE ROTATING MOTTO**
  <h1 style="font-size:3.5em; color:#ff0000; text-shadow: 0 0 20px #ff0000, 0 0 40px #ff0000, 0 0 60px #ff0000;">
    <span class="red-insane" data-phrases='[ "BURN THE CODE!", "HACK THE PLANET!", "RULE THE WORLD!", "I AM THE VIRUS!" ]'></span>
  </h1>

  <script>
  class RedInsane {
    constructor(el, phrases) {
      this.phrases = phrases;
      this.el = el;
      this.index = 0;
      this.txt = '';
      this.isDeleting = false;
      this.speed = 120;
      this.type();
    }
    type() {
      const current = this.phrases[this.index % this.phrases.length];
      this.txt = this.isDeleting 
        ? current.substring(0, this.txt.length - 1)
        : current.substring(0, this.txt.length + 1);
      
      const intensity = this.isDeleting ? 'ff3333' : 'ff0000';
      this.el.innerHTML = `<span style="color:#${intensity}; text-shadow: 0 0 15px #ff0000, 0 0 30px #ff0000; animation: flicker 0.1s infinite;">${this.txt}</span><span style="color:#ff0000; animation: blink 0.5s infinite;">|</span>`;
      
      let delta = this.isDeleting ? this.speed / 3 : this.speed - Math.random() * 60;
      
      if (!this.isDeleting && this.txt === current) {
        delta = 1200;
        this.isDeleting = true;
      } else if (this.isDeleting && this.txt === '') {
        this.isDeleting = false;
        this.index++;
        delta = 400;
      }
      
      setTimeout(() => this.type(), delta);
    }
  }

  window.onload = function() {
    const el = document.querySelector('.red-insane');
    if (el) {
      const phrases = JSON.parse(el.getAttribute('data-phrases'));
      new RedInsane(el, phrases);
    }
  };
  </script>

  <style>
  @keyframes pulse {
    0% { text-shadow: 0 0 20px #ff0000, 0 0 40px #ff0000; }
    50% { text-shadow: 0 0 30px #ff0000, 0 0 60px #ff0000, 0 0 80px #ff0000; }
    100% { text-shadow: 0 0 20px #ff0000, 0 0 40px #ff0000; }
  }
  @keyframes flicker {
    0%, 100% { opacity: 1; }
    50% { opacity: 0.8; }
  }
  @keyframes blink {
    0%, 100% { opacity: 1; }
    50% { opacity: 0; }
  }
  .red-insane > span { 
    font-weight: 900;
    letter-spacing: 2px;
  }
  </style>

  ---
  
  ### 🌌 **I DON'T WRITE CODE... I UNLEASH DIGITAL HELL!**
  <br>
  <img src="https://i.ibb.co/3dQ3Z3k/hellfire-code.gif" alt="CODE IN FLAMES" width="70%" style="filter: hue-rotate(0deg) brightness(80%);"/>
  <br><br>

  ### 🚨 **FINAL WARNING:**
  > **THIS README MAY CAUSE:**  
  > - Digital migraines  
  > - Self-hacking  
  > - Transformation into an evil hacker  
  > - Black code addiction  

  <br><br>
  <h2 style="color:#ff0000; font-size:2.5em; text-shadow: 0 0 15px #ff0000; animation: pulse 1s infinite;">
    ⚠️ ENTER AT YOUR OWN RISK ⚠️
  </h2>
</div>
