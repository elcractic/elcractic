<!-- COSMIC HEADER WITH PARALLAX STARFIELD -->
<div align="center">
  <div style="position:relative; height:400px; overflow:hidden;">
    <!-- STARFIELD BACKGROUND -->
    <div style="position:absolute; width:100%; height:100%; background: radial-gradient(ellipse at bottom, #1B2735 0%, #090A0F 100%); overflow:hidden;">
      <!-- ANIMATED STARS -->
      <div style="position:absolute; width:1px; height:1px; background:#FFF; box-shadow: 0 0 200px 200px #7E3ACE; animation:animStar 50s linear infinite; top:50%; left:50%;"></div>
      <div style="position:absolute; width:2px; height:2px; background:#FFF; box-shadow: 0 0 100px 100px #FFF; animation:animStar 150s linear infinite; top:30%; left:80%;"></div>
      <div style="position:absolute; width:3px; height:3px; background:#FFF; box-shadow: 0 0 150px 150px #7E3ACE; animation:animStar 100s linear infinite; top:70%; left:20%;"></div>
      
      <!-- PULSING COSMIC HEADER -->
      <div style="position:relative; z-index:2; padding-top:120px;">
        <img src="https://capsule-render.vercel.app/api?type=waving&color=timeGradient&height=180&section=header&text=Elcractic%20/%20CodingFR&fontSize=50&fontAlignY=40&animation=twinkling&fontColor=ffffff&desc=Full-Stack%20Cosmic%20Developer&descAlignY=70&descSize=20" alt="Header"/>
      </div>
    </div>
  </div>
</div>

<!-- INTERACTIVE TERMINAL WITH CURSOR BLINK -->
<div align="center" style="margin-top:-50px;">
  <div style="background:#0D1117; border-radius:10px; padding:20px; max-width:800px; box-shadow:0 0 30px #7E3ACE; position:relative; z-index:10;">
    <div style="font-family:'Space Mono',monospace; color:#7E3ACE; text-align:left;">
      <span style="color:#58A6FF;">~$ </span>
      <span id="typing-text" style="border-right:2px solid #7E3ACE; animation:blink 1s step-end infinite;"></span>
    </div>
  </div>
</div>

<!-- ANIMATED QUANTUM MATRIX -->
<div align="center" style="margin:50px 0; position:relative;">
  <div style="position:relative; width:100%; height:200px; overflow:hidden;">
    <!-- QUANTUM PARTICLE BACKGROUND -->
    <div class="quantum-particle" style="--delay:0s; --size:2px; --duration:20s;"></div>
    <div class="quantum-particle" style="--delay:2s; --size:3px; --duration:25s;"></div>
    <div class="quantum-particle" style="--delay:4s; --size:1px; --duration:30s;"></div>
    
    <!-- FLOATING CODE SNIPPETS -->
    <div style="position:absolute; top:50%; left:50%; transform:translate(-50%,-50%); width:100%;">
      <div style="font-family:'Space Mono',monospace; color:#7E3ACE; text-align:center; font-size:24px; font-weight:bold; text-shadow:0 0 10px #7E3ACE;">
        Transforming <span style="color:#58A6FF;">stardust</span> into <span style="color:#FF79C6;">code</span> since 2016
      </div>
    </div>
  </div>
</div>

<style>
  @keyframes animStar {
    from { transform:translateY(0) translateX(0); opacity:1; }
    to { transform:translateY(-1000px) translateX(-1000px); opacity:0; }
  }
  @keyframes blink {
    0%, 100% { border-color:transparent; }
    50% { border-color:#7E3ACE; }
  }
  .quantum-particle {
    position:absolute;
    background:#7E3ACE;
    border-radius:50%;
    animation:quantumFloat var(--duration) infinite ease-in-out var(--delay);
    box-shadow:0 0 10px 2px #7E3ACE;
    width:var(--size);
    height:var(--size);
  }
  @keyframes quantumFloat {
    0%, 100% { transform:translate(0,0); opacity:0.3; }
    25% { transform:translate(100px,-50px); opacity:1; }
    50% { transform:translate(200px,0); opacity:0.3; }
    75% { transform:translate(100px,50px); opacity:0.8; }
  }
</style>

<script>
  // Dynamic typing effect
  const messages = [
    "Welcome to my cosmic code hub",
    "Exploring the digital frontier",
    "Building the future one commit at a time",
    "Where creativity meets technology"
  ];
  let i = 0, j = 0, isDeleting = false;
  
  function typeWriter() {
    const element = document.getElementById("typing-text");
    const currentMsg = messages[i];
    
    if (isDeleting) {
      element.textContent = currentMsg.substring(0, j-1);
      j--;
      if (j === 0) {
        isDeleting = false;
        i = (i + 1) % messages.length;
        setTimeout(typeWriter, 500);
      } else {
        setTimeout(typeWriter, 50);
      }
    } else {
      element.textContent = currentMsg.substring(0, j+1);
      j++;
      if (j === currentMsg.length) {
        isDeleting = true;
        setTimeout(typeWriter, 2000);
      } else {
        setTimeout(typeWriter, 100);
      }
    }
  }
  
  // Start the typing effect
  document.addEventListener("DOMContentLoaded", typeWriter);
</script>



---

## 🧠 About Me

> **`Digital Craftsman (Developer/Creator)`**

I'm a futuristic full-stack developer driven by curiosity and creativity. I blend beautiful UI with powerful backend magic to craft seamless digital experiences. Whether it's scalable backend systems or cutting-edge frontend UI, I'm always building.

- 🧩 Building cool apps with Next.js, React, and Node.js  
- 🧠 Passionate about AI, automation, and open-source  
- 🎧 Always coding with beats in the background  
- 🌐 Currently exploring Web3 and modern architecture  

---

## 🚀 Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=js,ts,py,java,html,css,nodejs,react,nextjs,mongodb,postgresql,docker,git,github,linux" />
</p>

---

## 📈 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=elcractic&show_icons=true&theme=tokyonight&border_radius=10&hide_border=false" />
  <br />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=elcractic&layout=compact&theme=tokyonight" />
</p>

---

## 🔥 GitHub Streak

<p align="center">
  <img src="https://streak-stats.demolab.com?user=elcractic&theme=tokyonight&border_radius=10" />
</p>

---

## 🎧 Currently Vibing To

[![Spotify](https://novatorem-elcractic.vercel.app/api/spotify)](https://open.spotify.com/user/samirdevs)

---

## 📫 Reach Me

- 📩 Email: `your.email@example.com`  
- 💬 Discord: `codingfr` / `samirdevs`  
- 🐦 Twitter: [@yourtwitter](https://twitter.com/yourtwitter)  
- 💼 LinkedIn: [Your Profile](https://linkedin.com/in/yourprofile)

---

<details>
 <summary><h3>🧬 Elcractic's Coding Journey</h3></summary>
 <p>
  I began my journey as a kid customizing my MySpace page and now I'm architecting full-scale web apps, automating workflows, and contributing to open source. Every line of code I write reflects a passion for precision and progress.  
  <br><br>
  My ultimate goal? Build tech that makes lives easier, smarter, and more enjoyable.
 </p>
</details>

---

## 🛸 Fun Side Projects

- 🔗 **AI-Powered Discord Bot**  
- 🎮 **Multiplayer Game Platform**  
- 🧠 **Brainstorming App for Creators**  
- 💽 **Self-hosted Spotify Controller**

---

## 🧪 Contributions & Experiments

- 🧠 Built a neural net with TensorFlow.js  
- 🔒 Created a secure OAuth2 flow for Discord bots  
- 🔧 Custom CLI tool for quick project bootstrapping  
- 🌌 Exploring Astro, Deno, and Bun

---

## 🖤 Support My Work

If you like what I do and want to support me:

<a href="https://www.buymeacoffee.com/elcractic">
  <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50" />
</a>

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=elcractic&style=flat-square&color=00FFFF" alt="Profile Views" />
</p>
