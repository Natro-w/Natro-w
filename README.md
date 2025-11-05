<div align="center">
  <h1 style="color:#ff0000; font-size:4.5em; text-shadow: 0 0 25px #ff0000, 0 0 50px #ff0000, 0 0 75px #ff0000; animation: bloodPulse 1.3s infinite; font-weight:900; letter-spacing:3px;">
    👁️ <span style="color:#ff0000;">NATRO</span> 👁️
  </h1>
  <img src="https://i.ibb.co/2gyQ5vL/cyber-dark-banner.jpg" alt="CYBER BLOOD BANNER" width="100%" style="filter: hue-rotate(0deg) brightness(60%) contrast(150%); border: 3px solid #ff0000; box-shadow: 0 0 30px #ff0000;"/>
  <br><br>
  ---
  > **⚡ <span style="color:#ff0000;">MYSTERIOUS. DARK. PROFESSIONAL. FUTURISTIC. INFECTED.</span>**  
  > **🧠 <span style="color:#ff0000;">DEVELOPER MASTERING GAMES, AUTOMATION, APIs, TOOLS — AND CHAOS.</span>**  
  > **💻 <span style="color:#ff0000;">LANGUAGES: C# | C++ | JavaScript | Node.js | Python</span>**  
  > **🌌 <span style="color:#ff0000;">MOTTO: “UPGRADING IRAQ.” — IN BLOOD CODE.</span>**  
  > **🔒 <span style="color:#ff0000;">LOCATION: PRIVATE — BUT I SEE YOU.</span>**
  ---
  
  ### 🖤 **INFECTED TECH STACK**
  <img src="https://img.shields.io/badge/-C%23-ff0000?style=for-the-badge&logo=c-sharp&logoColor=white&labelColor=8B0000" />
  <img src="https://img.shields.io/badge/-C++-ff0000?style=for-the-badge&logo=c%2B%2B&logoColor=white&labelColor=8B0000" />
  <img src="https://img.shields.io/badge/-JavaScript-ff0000?style=for-the-badge&logo=javascript&logoColor=white&labelColor=8B0000" />
  <img src="https://img.shields.io/badge/-Node.js-ff0000?style=for-the-badge&logo=node.js&logoColor=white&labelColor=8B0000" />
  <img src="https://img.shields.io/badge/-Python-ff0000?style=for-the-badge&logo=python&logoColor=white&labelColor=8B0000" />
  <img src="https://img.shields.io/badge/-APIs-ff0000?style=for-the-badge&logo=openapi&logoColor=white&labelColor=8B0000" />
  <img src="https://img.shields.io/badge/-Automation-ff0000?style=for-the-badge&logo=selenium&logoColor=white&labelColor=8B0000" />
  <br><br>

  ---
  
  ### 🎮 **FEATURED PROJECT: INFECTED**
  
  #### [🩸 ProMag Steam Games](https://github.com/Natro-w/promag-steam-games)
  > **ADD AND CONTROL STEAM GAMES — LIKE A VIRUS IN THE SYSTEM.**  
  - Inject all Steam games  
  - 1-click domination  
  - Track every infected title  
  - Delete without a trace  
  > **SERVER UNDER BLOOD MAINTENANCE — REBOOTING IN HELL**

  ---
  
  ### 📊 **GITHUB STATS — BLEEDING RED**
  <img src="https://github-readme-stats.vercel.app/api?username=Natro-w&show_icons=true&theme=radical&hide_border=true&bg_color=0d0d0d&title_color=ff0000&icon_color=ff3333&text_color=ff6666&border_color=ff0000" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Natro-w&layout=donut-vertical&theme=radical&hide_border=true&bg_color=0d0d0d&title_color=ff0000&text_color=ff6666&border_color=ff0000" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Natro-w&theme=radical&hide_border=true&background=0d0d0d&stroke=ff0000&ring=ff3333&fire=ff0000&currStreakLabel=ff6666&border=ff0000" />
  <br><br>

  ---
  
  ### ⚡ **INFECTED MOTTO**
  > **<span style="color:#ff0000; font-size:1.4em;">“THE CODE RUNS DEEPER THAN THE SURFACE. I BUILD. I AUTOMATE. I UPGRADE — IN BLOOD.”</span>**  
  > **<span style="color:#ff0000; font-weight:900;">UPGRADING IRAQ. ONE BYTE AT A TIME.</span>**

  ---
  
  ### 🌌 **LET’S INFECT THE FUTURE**
  <span style="color:#ff0000; font-size:1.2em;">
    I explore forbidden tech, forge automation weapons, push games and APIs into the void.
  </span>

  ---
  
  ### 🔴 **BLOOD TYPING EFFECT — INSANE MODE**
  <h1 style="color:#ff0000; font-size:3em; text-shadow: 0 0 20px #ff0000, 0 0 40px #ff0000; font-weight:900;">
    <span class="blood-rotate" data-period="1800" data-rotate='[ "Building Games.", "Infecting Systems.", "Upgrading Iraq.", "BLEEDING CODE." ]'></span>
  </h1>

  <script>
  class BloodRotate {
    constructor(el, toRotate, period) {
      this.toRotate = toRotate;
      this.el = el;
      this.loopNum = 0;
      this.period = parseInt(period, 10) || 2000;
      this.txt = '';
      this.tick();
      this.isDeleting = false;
    }
    tick() {
      let i = this.loopNum % this.toRotate.length;
      let fullTxt = this.toRotate[i];
      this.txt = this.isDeleting ? fullTxt.substring(0, this.txt.length - 1) : fullTxt.substring(0, this.txt.length + 1);
      
      const shadow = this.isDeleting ? '0 0 15px #ff0000' : '0 0 25px #ff0000, 0 0 50px #ff0000';
      this.el.innerHTML = `<span style="color:#ff0000; text-shadow: ${shadow}; animation: drip 0.1s infinite;">${this.txt}</span><span style="color:#ff0000; animation: blink 0.6s infinite;">|</span>`;
      
      let delta = 180 - Math.random() * 80;
      if(this.isDeleting){ delta /= 3; }
      if(!this.isDeleting && this.txt === fullTxt){ delta = this.period; this.isDeleting = true; }
      else if(this.isDeleting && this.txt === ''){ this.isDeleting = false; this.loopNum++; delta = 600; }
      setTimeout(()=>{ this.tick(); }, delta);
    }
  }
  window.onload = function() {
    let elements = document.getElementsByClassName('blood-rotate');
    for(let i=0; i<elements.length; i++){
      let toRotate = elements[i].getAttribute('data-rotate');
      let period = elements[i].getAttribute('data-period');
      if(toRotate){ new BloodRotate(elements[i], JSON.parse(toRotate), period); }
    }
  };
  </script>

  <style>
  @keyframes bloodPulse {
    0% { text-shadow: 0 0 20px #ff0000, 0 0 40px #ff0000; }
    50% { text-shadow: 0 0 35px #ff0000, 0 0 70px #ff0000, 0 0 100px #ff0000; }
    100% { text-shadow: 0 0 20px #ff0000, 0 0 40px #ff0000; }
  }
  @keyframes drip {
    0%, 100% { transform: translateY(0); }
    50% { transform: translateY(3px); }
  }
  @keyframes blink {
    0%, 100% { opacity: 1; }
    50% { opacity: 0; }
  }
  .blood-rotate > span { 
    font-weight: 900;
    letter-spacing: 2px;
  }
  </style>

  ---
  
  ### 🚨 **FINAL WARNING — IN RED**
  > **<span style="color:#ff0000; font-weight:900;">THIS PROFILE MAY CAUSE:</span>**  
  > - **Digital hemorrhage**  
  > - **Code addiction**  
  > - **Uncontrollable urge to upgrade Iraq**  
  > - **FBI watchlist entry**

  <br><br>
  <h2 style="color:#ff0000; font-size:2.8em; text-shadow: 0 0 20px #ff0000; animation: bloodPulse 1s infinite;">
    ⚠️ YOU HAVE BEEN INFECTED ⚠️
  </h2>
</div>
