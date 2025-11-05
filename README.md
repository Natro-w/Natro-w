<div align="center">

# 👁️ Natro

![Header Banner](https://i.ibb.co/2gyQ5vL/cyber-dark-banner.jpg)

---

> ⚡ **Mysterious. Dark. Professional. Futuristic.**  
> 🧠 Developer mastering **games, automation, APIs, and tools**.  
> 💻 Languages: **C#, C++, JavaScript, Node.js, Python**  
> 🌌 Motto: **“Upgrading Iraq.”**  
> 🔒 Location: Private  

---

### 🖤 Tech Stack & Skills
![C#](https://img.shields.io/badge/-C%23-181717?logo=c-sharp&logoColor=239120)
![C++](https://img.shields.io/badge/-C++-181717?logo=c%2B%2B&logoColor=00599C)
![JavaScript](https://img.shields.io/badge/-JavaScript-181717?logo=javascript)
![Node.js](https://img.shields.io/badge/-Node.js-181717?logo=node.js)
![Python](https://img.shields.io/badge/-Python-181717?logo=python)
![APIs](https://img.shields.io/badge/-APIs-181717?logo=restful&logoColor=white)
![Automation](https://img.shields.io/badge/-Automation-181717?logo=automation)

---

### 🎮 Featured Projects

#### [ProMag Steam Games](https://github.com/Natro-w/promag-steam-games)  
Add and manage Steam games **freely and effortlessly**.  
- Show all Steam games  
- Add games with **1 click**  
- Track all added games  
- Remove added games easily  
> *(Server currently under maintenance)*

---

### 📊 GitHub Stats
![Natro's GitHub stats](https://github-readme-stats.vercel.app/api?username=Natro-w&show_icons=true&theme=dark&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Natro-w&layout=compact&theme=dark&hide_border=true)

---

### ⚡ Motto
> “The code runs deeper than the surface. I build, I automate, I upgrade.”  
> **Upgrading Iraq.**

---

### 🌌 Let’s Build the Future
I’m always exploring **futuristic tech**, crafting **automation tools**, and pushing **games and APIs** beyond limits.  

---

### 🔮 Animated Typing Effect (optional)
```html
<h1><span class="txt-rotate" data-period="2000" data-rotate='[ "Building Games.", "Automating Systems.", "Upgrading Iraq." ]'></span></h1>
<script>
class TxtRotate {
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
    this.el.innerHTML = '<span class="wrap">'+this.txt+'</span>';
    let delta = 200 - Math.random() * 100;
    if(this.isDeleting){ delta /= 2; }
    if(!this.isDeleting && this.txt === fullTxt){ delta = this.period; this.isDeleting = true; }
    else if(this.isDeleting && this.txt === ''){ this.isDeleting = false; this.loopNum++; delta = 500; }
    setTimeout(()=>{ this.tick(); }, delta);
  }
}
window.onload = function() {
  let elements = document.getElementsByClassName('txt-rotate');
  for(let i=0; i<elements.length; i++){
    let toRotate = elements[i].getAttribute('data-rotate');
    let period = elements[i].getAttribute('data-period');
    if(toRotate){ new TxtRotate(elements[i], JSON.parse(toRotate), period); }
  }
};
</script>
<style>.txt-rotate > .wrap{ border-right: 0.08em solid #fff }</style>
</div>
