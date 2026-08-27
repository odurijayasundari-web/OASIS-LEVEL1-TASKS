# OASIS# OASIS INFOBYTE - Web Development Level 1 Tasks
Intern: Oduri Jaya Sundari
Track: Web Development & Designing

## Tasks Completed
✅ Task 1: Landing Page - Oduri Travels (HTML5, CSS3)
✅ Task 2: Personal Portfolio - My Profile
✅ Task 3: Temperature Converter - JS with Validation

## Live Demo
Task 1: https://odurijayasundari-web.github.io/OASIS-LEVEL1-TASKS/task1_landing_page.html
Task 2: https://odurijayasundari-web.github.io/OASIS-LEVEL1-TASKS/task2_portfoilo.html
Task 3: https://odurijayasundari-web.github.io/OASIS-LEVEL1-TASKS/task3_temp_converter.html

## Tech Stack
HTML5, CSS3, JavaScript, GitHub

#oasisinfobyte #webdevelopment #internship-LEVEL1-TASKS
OASIS LEVEL1 TASKS<!DOCTYPE html><html><head><meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1.0"><title>Oduri Jaya Sundari - Portfolio</title>
<style>*{margin:0;padding:0;box-sizing:border-box;font-family:Segoe UI}body{background:#f8f9fa}header{background:#6c5ce7;color:#fff;text-align:center;padding:60px 20px}header h1{font-size:40px}section{padding:40px 8%;background:#fff;margin:20px 8%;border-radius:12px;box-shadow:0 2px 10px rgba(0,0,0,0.1)}.skill{display:inline-block;background:#dfe6e9;padding:8px 15px;border-radius:20px;margin:5px}</style>
</head><body><header><h1>Oduri Jaya Sundari</h1><p>Web Developer | OASIS INFOBYTE Intern</p></header>
<section><h2>About Me</h2><p>Passionate web developer from Visakhapatnam, learning HTML, CSS, JS through OASIS internship.</p></section>
<section><h2>Skills</h2><div><span class="skill">HTML5</span><span class="skill">CSS3</span><span class="skill">JavaScript</span><span class="skill">GitHub</span></div></section>
<section><h2>Projects</h2><p>1. Oduri Travels Landing Page<br>2. Personal Portfolio<br>3. Temperature Converter</p></section>
<section><h2>Contact</h2><p>Email: oduri@example.com | GitHub: odurijayasundari-web</p></section>
</body></html>
<!DOCTYPE html><html><head><meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1.0"><title>Temp Converter</title>
<style>body{font-family:Segoe UI;display:flex;justify-content:center;align-items:center;min-height:100vh;background:#e3f2fd}.box{background:#fff;padding:30px;border-radius:15px;box-shadow:0 5px 20px rgba(0,0,0,0.2);width:90%;max-width:400px}input,select,button{width:100%;padding:12px;margin:10px 0;border-radius:8px;border:1px solid #ccc}button{background:#0984e3;color:#fff;border:none;font-size:18px;cursor:pointer}#result{margin-top:15px;font-weight:bold;text-align:center}</style>
</head><body><div class="box"><h2>Temperature Converter</h2><input type="number" id="temp" placeholder="Enter temperature"><select id="unit"><option value="c">Celsius</option><option value="f">Fahrenheit</option><option value="k">Kelvin</option></select><button onclick="convert()">Convert</button><div id="result"></div></div>
<script>function convert(){let t=parseFloat(document.getElementById('temp').value);let u=document.getElementById('unit').value;let r=document.getElementById('result');if(isNaN(t)){r.innerText='Enter valid number';return}let c,f,k;if(u=='c'){c=t;f=(t*9/5)+32;k=t+273.15}else if(u=='f'){f=t;c=(t-32)*5/9;k=c+273.15}else{k=t;c=t-273.15;f=(c*9/5)+32}if(k<0){r.innerText='Error: Below absolute zero!';return}r.innerHTML=`C: ${c.toFixed(2)}°<br>F: ${f.toFixed(2)}°<br>K: ${k.toFixed(2)}°`}</script></body></html>
