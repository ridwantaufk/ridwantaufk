<!-- README.md -->

<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?font=Fira+Code&size=30&pause=1000&color=00F7FF&center=true&vCenter=true&width=800&lines=Hey+there!+I'm+Ridwan+Taufik;Fullstack+Developer;Web+%26+Desktop+Specialist" alt="Typing SVG" />
</h1>


<p align="center">A passionate full-stack developer who blends <strong>web & desktop technologies</strong> with a touch of <strong>Python wizardry</strong></p>

---

## 🚀 Tech Stack

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="40" title="React"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original-wordmark.svg" width="40" title="Next.js" style="background:white; border-radius:5px;"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="40" title="TypeScript"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" width="40" title="Node.js"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" width="40" title="Express" style="filter: invert(100%)"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/graphql/graphql-plain.svg" width="40" title="GraphQL"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width="40" title="PostgreSQL"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="40" title="Python"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/electron/electron-original.svg" width="40" title="Electron"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/opencv/opencv-original.svg" width="40" title="OpenCV"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" width="40" title="Linux"/>
</p>

---

<svg viewBox="0 0 400 400" width="400" height="400" xmlns="http://www.w3.org/2000/svg" style="background:#000">
  <defs>
    <circle id="dot" cx="0" cy="0" r="3" fill="#00f0ff" />
    <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
      <feDropShadow dx="0" dy="0" stdDeviation="2" flood-color="#00f0ff" flood-opacity="0.7"/>
    </filter>
  </defs>

  <g filter="url(#glow)">
    <use xlink:href="#dot" id="dot0" />
    <use xlink:href="#dot" id="dot1" />
    <use xlink:href="#dot" id="dot2" />
    <use xlink:href="#dot" id="dot3" />
    <use xlink:href="#dot" id="dot4" />
    <use xlink:href="#dot" id="dot5" />
    <use xlink:href="#dot" id="dot6" />
    <use xlink:href="#dot" id="dot7" />
    <use xlink:href="#dot" id="dot8" />
    <use xlink:href="#dot" id="dot9" />
  </g>

  <line id="line0" stroke="#00f0ff" stroke-width="1" stroke-opacity="0.6" />
  <line id="line1" stroke="#00f0ff" stroke-width="1" stroke-opacity="0.6" />
  <line id="line2" stroke="#00f0ff" stroke-width="1" stroke-opacity="0.5" />
  <line id="line3" stroke="#00f0ff" stroke-width="1" stroke-opacity="0.5" />
  <line id="line4" stroke="#00f0ff" stroke-width="1" stroke-opacity="0.4" />
  <line id="line5" stroke="#00f0ff" stroke-width="1" stroke-opacity="0.4" />

  <animateMotion xlink:href="#dot0" dur="8s" repeatCount="indefinite" path="M20,40 q40,20 60,0 q-20,-40 -40,-20 z" />
  <animateMotion xlink:href="#dot1" dur="6s" repeatCount="indefinite" path="M100,50 q-30,30 -50,10 q10,-50 60,-20 z" />
  <animateMotion xlink:href="#dot2" dur="7s" repeatCount="indefinite" path="M300,80 q-50,10 -30,50 q50,-10 10,-60 z" />
  <animateMotion xlink:href="#dot3" dur="5s" repeatCount="indefinite" path="M350,200 q-40,20 -60,-20 q30,-40 70,-10 z" />
  <animateMotion xlink:href="#dot4" dur="9s" repeatCount="indefinite" path="M150,300 q20,-30 40,-10 q-40,40 -20,20 z" />
  <animateMotion xlink:href="#dot5" dur="10s" repeatCount="indefinite" path="M200,350 q-30,-20 -40,10 q50,20 40,-30 z" />
  <animateMotion xlink:href="#dot6" dur="11s" repeatCount="indefinite" path="M80,150 q10,30 40,20 q-30,-40 -50,-20 z" />
  <animateMotion xlink:href="#dot7" dur="12s" repeatCount="indefinite" path="M320,250 q-20,-40 10,-30 q10,40 -20,50 z" />
  <animateMotion xlink:href="#dot8" dur="9s" repeatCount="indefinite" path="M220,120 q30,-20 20,40 q-40,-20 -10,-30 z" />
  <animateMotion xlink:href="#dot9" dur="8s" repeatCount="indefinite" path="M180,220 q-30,30 -10,40 q20,-50 -10,-40 z" />

  <script type="application/ecmascript"><![CDATA[
    const svg = document.currentScript.ownerDocument;
    const dots = [];
    for (let i = 0; i < 10; i++) {
      dots.push(svg.getElementById("dot" + i));
    }
    const lines = [];
    for (let i = 0; i < 6; i++) {
      lines.push(svg.getElementById("line" + i));
    }
    // Pairs to connect (random-ish)
    const pairs = [
      [0, 1],
      [1, 2],
      [2, 3],
      [3, 4],
      [4, 5],
      [5, 6]
    ];

    function update() {
      for (let i = 0; i < pairs.length; i++) {
        const [a, b] = pairs[i];
        const p1 = dots[a].transform.baseVal.getItem(0).matrix;
        const p2 = dots[b].transform.baseVal.getItem(0).matrix;
        lines[i].setAttribute("x1", p1.e);
        lines[i].setAttribute("y1", p1.f);
        lines[i].setAttribute("x2", p2.e);
        lines[i].setAttribute("y2", p2.f);
      }
      requestAnimationFrame(update);
    }
    update();
  ]]></script>
</svg>


---

## 🧠 About Me

- 🔧 Building **Next.js** apps with **TypeScript** + GraphQL  
- 🧪 Creating **penetration testing** and **vision-based** desktop tools in **Python**  
- 🔌 Developing chat, video, and screen-sharing tools with **Electron & WebRTC**  
- 🤖 Passionate about AI, gesture control, and turning coffee into software

---

## 🔥 Featured Projects

| Project | Description |
|--------|-------------|
| <img src="https://img.icons8.com/color/48/finance.png" width="24" /> **Financial Management System** | Scalable platform for managing business & personal finances |
| <img src="https://img.icons8.com/color/48/hospital-room.png" width="24" /> **Hospital Information System (SIMRS)** | Robust system for managing hospital operations |
| <img src="https://img.icons8.com/color/48/sales-performance.png" width="24" /> **Sales Information System** | All-in-one solution for sales, inventory & reporting |
| <img src="https://img.icons8.com/color/48/video-call.png" width="24" /> **Real-time Chat & Video Call App** | Web & desktop communication tools with WebRTC |
| <img src="https://img.icons8.com/color/48/language-skill.png" width="24" /> **English Learning App** | Interactive language learning with fun UX |
| <img src="https://img.icons8.com/color/48/anonymous-mask.png" width="24" /> **Security Penetration Tools** | Python-based ethical hacking & testing tools |
| <img src="https://img.icons8.com/color/48/hand.png" width="24" /> **Face & Hand Gesture Recognition** | Desktop app for gesture-based UI control |

---

## 🌐 Let's Connect

<p align="center">
  <a href="https://www.linkedin.com/in/ridwan-taufik-b3624325a/"><img src="https://img.icons8.com/ios-filled/50/0A66C2/linkedin.png" width="35" title="LinkedIn"/></a>
  &nbsp;&nbsp;
  <a href="https://www.instagram.com/ridwantaufk/"><img src="https://img.icons8.com/ios-filled/50/E4405F/instagram-new.png" width="35" title="Instagram"/></a>
  &nbsp;&nbsp;
  <a href="https://ridwantaufk.github.io/ridwan-portfolio-fullstack-developer/"><img src="https://img.icons8.com/ios-filled/50/000000/domain.png" width="35" title="Website"/></a>
</p>

---

<p align="center">
  <img src="./assets/ImageToStl.com_3d-Hologramm-(Wavefront+OBJ).obj.gif" width="300" alt="Three.js Animation" />
</p>
<p align="center">
  <em>"If God ordained that humans sleep only three hours, I would dedicate every remaining moment to unraveling the mysteries of nature, until technology transcends the limits of time." — me 2024</em><br />
  <small>"Andai Tuhan menetapkan manusia hanya tidur tiga jam, niscaya aku akan mendedikasikan setiap detik tersisa untuk menyingkap rahasia alam semesta, hingga tercipta teknologi yang melampaui batas waktu." — me 2024</small>
</p>

