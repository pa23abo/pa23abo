<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Philemon Agbor's - Profile</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

   class="<header>
    <h1> Hi there, I'm Philemon Agbor</h1>
    <p> A Second-year Computer Science Student at the University of Hertfordshire</p>
    <img src="profile.jpg" alt="Philemon Agbor"profile-img">
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>Hi! I'm Philemon Agbor, a second-year student at the University of Hertfordshire, studying for a BSc in Computer Science. I have a passion for web development and programming, with skills in HTML, CSS, JavaScript, and Python. I'm excited to develop accessible and user-friendly digital experiences.</p>
  </section>

  <section id="technical-interests">
    <h2>Technical Interests</h2>
    <h3>Web Development</h3>
    <p>I have a keen interest in creating accessible websites using modern technologies like HTML, CSS, JavaScript, and responsive design techniques. I aim to build web applications that are both functional and easy to use.</p>
    <img src="web-development.jpg" alt="Web Development" class="interest-img">
  </section>

  <section id="portfolio">
    <h2>Portfolio</h2>
    <div class="portfolio-item">
      <h3>Project 1: Personal Blog</h3>
    
      <p>A responsive personal blog built using HTML, CSS, and JavaScript.</p>
      <a href="project1-details.html" class="project-link">View Details</a>
    </div>
    <div class="portfolio-item">
      <h3>Project 2: Web Calculator</h3>
      <p>A JavaScript-based calculator with a focus on accessibility.</p>
      <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Accessible Calculator</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <main>
        <h1>Accessible Calculator</h1>            
</html>
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f9;
    margin: 0;
    padding: 20px;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    flex-direction: column;
}

h1 {
    font-size: 24px;
    margin-bottom: 20px;
}

.calculator {
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    padding: 20px;
}

.display {
    background-color: #222;
    color: #fff;
    text-align: right;
    font-size: 2em;
    padding: 20px;
    border-radius: 10px;
    margin-bottom: 20px;
}

.buttons {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 10px;
}

.button {
    padding: 20px;
    font-size: 1.5em;
    text-align: center;
    border: none;
    background-color: #f0f0f0;
    border-radius: 8px;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

.button:focus {
    outline: 2px solid #ffcc00;
}

.button.operator {
    background-color: #f9a825;
    color: white;
}

.button.operator:hover {
    background-color: #ffca28;
}

.button:active {
    background-color: #ddd;
}

button[aria-label="Equals"]:focus {
    background-color: #ff5722;
}
let currentInput = '0';

function updateDisplay() {
    const display = document.getElementById('display');
    display.textContent = currentInput;
}

function appendToDisplay(value) {
    if (currentInput === '0') {
        currentInput = String(value);
    } else {
        currentInput += String(value);
    }
    updateDisplay();
}

function clearDisplay() {
    currentInput = '0';
    updateDisplay();
}

function calculateResult() {
    try {
        currentInput = String(eval(currentInput));
        updateDisplay();
    } catch (error) {
        currentInput = 'Error';
        updateDisplay();
    }
}

// Handle keyboard input
function handleKeyDown(event) {
    const key = event.key;

    if (key >= '0' && key <= '9') {
        appendToDisplay(key);
    } else if (key === 'Backspace') {
        clearDisplay();
    } else if (key === 'Enter') {
        calculateResult();
    } else if (['+', '-', '*', '/'].includes(key)) {
        appendToDisplay(key);
    }
}

// Add event listener for keyboard inputs
document.addEventListener('keydown', handleKeyDown);


      <a href="project2-details.html" class="project-link">View Details</a>
    </div>
  </section>

  <footer>
    <p>Contact: agborphilemon8@gmail.com</p>
  </footer>

  <script src="scripts.js"></script>

</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f4f4f4;
  color: #333;
}

header {
  text-align: center;
  padding: 20px;
  background-color: #4CAF50;
  color: white;
}

header h1 {
  margin: 0;
}

header p {
  font-size: 18px;
}

.profile-img {
  width: 150px;
  height: 150px;
  border-radius: 50%;
}

section {
  padding: 20px;
}

#about {
  background-color: #ffffff;
}

#technical-interests h3 {
  margin-top: 10px;
}

.interest-img {
  width: 100%;
  max-width: 300px;
  display: block;
  margin: 10px 0;
}

.portfolio-item {
  background-color: #ffffff;
  margin: 10px 0;
  padding: 10px;
  border: 1px solid #ddd;
}

.project-link {
  color: #4CAF50;
  text-decoration: none;
}

.project-link:hover {
  text-decoration: underline;
}

footer {
  text-align: center;
  padding: 10px;
  background-color: #333;
  color: white;
}
// Example JavaScript to handle clicks or form submissions
document.addEventListener('DOMContentLoaded', () => {
  console.log('Profile page loaded');
});

# 💻 Tech Stack:
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=pa23abo&theme=dark&hide_border=false&include_all_commits=false&count_private=false)<br/>
![](https://github-readme-streak-stats.herokuapp.com/?user=pa23abo&theme=dark&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=pa23abo&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

---
[![](https://visitcount.itsvg.in/api?id=pa23abo&icon=0&color=0)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
