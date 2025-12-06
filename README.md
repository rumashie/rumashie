<svg viewBox="0 0 400 300" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Gradients -->
    <linearGradient id="skyGrad" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#0a0a1f;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#1a0a2e;stop-opacity:1" />
    </linearGradient>
    
    <linearGradient id="neonPink" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#ff006e;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#ff6ec7;stop-opacity:1" />
    </linearGradient>
    
    <linearGradient id="neonCyan" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00f5ff;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#00d9ff;stop-opacity:1" />
    </linearGradient>
  </defs>
  
  <!-- Night Sky -->
  <rect width="400" height="300" fill="url(#skyGrad)"/>
  
  <!-- Stars -->
  <circle cx="50" cy="30" r="1" fill="white" opacity="0.8">
    <animate attributeName="opacity" values="0.3;1;0.3" dur="3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="120" cy="50" r="1.5" fill="white" opacity="0.9">
    <animate attributeName="opacity" values="0.5;1;0.5" dur="2.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="200" cy="25" r="1" fill="white" opacity="0.7">
    <animate attributeName="opacity" values="0.4;1;0.4" dur="3.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="280" cy="45" r="1.2" fill="white" opacity="0.8">
    <animate attributeName="opacity" values="0.6;1;0.6" dur="2.8s" repeatCount="indefinite"/>
  </circle>
  <circle cx="350" cy="35" r="1" fill="white" opacity="0.9">
    <animate attributeName="opacity" values="0.3;1;0.3" dur="3.2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="90" cy="70" r="0.8" fill="white" opacity="0.6">
    <animate attributeName="opacity" values="0.2;0.9;0.2" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="310" cy="60" r="1" fill="white" opacity="0.7">
    <animate attributeName="opacity" values="0.4;1;0.4" dur="2.3s" repeatCount="indefinite"/>
  </circle>
  
  <!-- Laptop -->
  <!-- Laptop base -->
  <path d="M 120 220 L 280 220 L 290 250 L 110 250 Z" fill="#1a1a3e" stroke="url(#neonCyan)" stroke-width="1.5"/>
  
  <!-- Laptop screen -->
  <path d="M 130 220 L 270 220 L 260 120 L 140 120 Z" fill="#0a0a1a" stroke="url(#neonPink)" stroke-width="2"/>
  
  <!-- Screen content with glow -->
  <path d="M 135 215 L 265 215 L 256 125 L 144 125 Z" fill="#00f5ff" opacity="0.15">
    <animate attributeName="opacity" values="0.1;0.25;0.1" dur="3s" repeatCount="indefinite"/>
  </path>
  
  <!-- Code lines on screen -->
  <line x1="150" y1="140" x2="240" y2="140" stroke="#00ff00" stroke-width="1.5" opacity="0.8"/>
  <line x1="150" y1="155" x2="230" y2="155" stroke="#00ff00" stroke-width="1.5" opacity="0.7"/>
  <line x1="150" y1="170" x2="245" y2="170" stroke="#00ff00" stroke-width="1.5" opacity="0.8"/>
  <line x1="150" y1="185" x2="225" y2="185" stroke="#00ff00" stroke-width="1.5" opacity="0.6"/>
  <line x1="150" y1="200" x2="235" y2="200" stroke="#00ff00" stroke-width="1.5" opacity="0.7">
    <animate attributeName="x2" values="235;160;235" dur="4s" repeatCount="indefinite"/>
  </line>
  
  <!-- Keyboard on base -->
  <rect x="135" y="228" width="130" height="15" rx="2" fill="#0f0f2e" opacity="0.6"/>
  
  <!-- Trackpad -->
  <rect x="180" y="235" width="40" height="6" rx="1" fill="#1a1a3e" stroke="#ff006e" stroke-width="0.5" opacity="0.4"/>
  
  <!-- Screen glow effect -->
  <ellipse cx="200" cy="170" rx="100" ry="80" fill="#00f5ff" opacity="0.08">
    <animate attributeName="opacity" values="0.05;0.12;0.05" dur="3s" repeatCount="indefinite"/>
  </ellipse>
  
  <!-- Subtle keyboard backlight -->
  <ellipse cx="200" cy="235" rx="65" ry="8" fill="#ff006e" opacity="0.2">
    <animate attributeName="opacity" values="0.15;0.3;0.15" dur="2s" repeatCount="indefinite"/>
  </ellipse>  

</svg>
<!--
**rumashie/rumashie** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
- 🔭 I’m currently working on ... *a website to host and share my personal CS notes*

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

I am a recent CS grad from NYC. Most repos here are from my college coursework! Mainly software engineering (C++, web dev) and data analysis (Python) projects. 
Currently, I’m focused on continuing my learning journey and honing my skills in web development, data management, system administration, and CS foundations (computer architecture, data structures and algorithms). 

-->


