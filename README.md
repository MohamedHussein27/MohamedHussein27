# Mohamed-Hussein / README.md

# Welcome to Mohamed Hussein's profile! 👋

<div align="center">
  <h2 id="typing-text"></h2>
</div>

<script>
const messages = ["Digital Electronics Engineer", "Passionate about Digital IC Design"];
let index = 0;
let charIndex = 0;
let currentMessage = "";
let interval;

function typeMessage() {
    if (charIndex < messages[index].length) {
        currentMessage += messages[index].charAt(charIndex);
        document.getElementById("typing-text").innerText = currentMessage;
        charIndex++;
    } else {
        clearInterval(interval);
        setTimeout(() => {
            currentMessage = "";
            charIndex = 0;
            index = (index + 1) % messages.length;
            interval = setInterval(typeMessage, 100);
        }, 2000);
    }
}

document.addEventListener("DOMContentLoaded", () => {
    interval = setInterval(typeMessage, 100);
});
</script>

### I'm an Electronics and Communication Engineer Student @ Ain Shams University
### I'm constantly learning and exploring new technologies to improve my skills.

### Connect with Me :
[![LinkedIn](https://img.shields.io/badge/-Mohamed%20Hussein-blue?style=flat&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/your-linkedin-profile)

### Tech Stack
![C++](https://img.shields.io/badge/-C++-00599C?style=flat&logo=c++)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python)
![MATLAB](https://img.shields.io/badge/-MATLAB-0076A8?style=flat&logo=mathworks)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/-Bootstrap-563D7C?style=flat&logo=bootstrap)
![HTML](https://img.shields.io/badge/-HTML-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/-CSS-1572B6?style=flat&logo=css3)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat&logo=github)

### Most Used Languages
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=your-github-username&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

### Profile Views
<div style="width: 100px; height: 100px; background-color: red; display: flex; align-items: center; justify-content: center; color: white;">
  <p style="font-size: 20px;">PROFILE VIEWS</p>
  <p style="font-size: 30px;">150</p>
</div>
