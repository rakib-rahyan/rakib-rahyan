<h1 align="center">Hi 👋, I'm Rakib Rahyan</h1>
<h3 align="center">"Position yourself in such a way that millions of people think endlessly before they speak to you, but never against injustice."</h3>
<h5 align="center">"Struggle my difficult situation today, tomorrow will be forgotten by the flow of time? Or will time prepare me in such a way that the preparation will no longer be necessary, but I will still learn, struggle and change my destiny to rise to the top?."</h5>

<h3 align="center">Aspiring Programmer & Problem Solver</h3>

<p align="center"> 
    <img src="https://thumbor.forbes.com/thumbor/fit-in/1290x/https://www.forbes.com/advisor/wp-content/uploads/2023/07/computer-coding.jpg" alt="Coding on a laptop" width="600"/>
</p>

- 🌱 I’m currently learning **C Programming, Arduino Programming**
- 💬 Ask me about **C Programming, HTML**
- 📫 How to reach me: **rakibrhayn20232@gmail.com**
- Connect with me on: [**Facebook**](https://www.facebook.com/profile.php?id=61556517414774) | [**LinkedIn**](https://www.linkedin.com/feed/?trk=guest_homepage-basic_google-one-tap-submit)

---

<h3>🙋‍♂️ About Me</h3>
<p>
    I am a Computer Science and Engineering student with a passion for learning programming languages and web development. I also enjoy teaching background subjects to my peers. Every day, I aim to learn new skills and share knowledge with others. Programming is my passion, and I’m always eager to solve problems and improve myself.
</p>

---

<h3>🛠️ Currently Learning Languages and Tools:</h3>
<p align="left"> 
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML" target="_blank" rel="noreferrer">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRsubI1xnS2EsbFC7IKOtHXy3o2yp5zNGHX8-mLk-0nVw&s" alt="HTML" width="40" height="40"/>
    </a>
    <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer"> 
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="C" width="40" height="40"/> 
    </a> 
    <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> 
        <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="Git" width="40" height="40"/> 
    </a> 
    <a href="https://docs.arduino.cc/learn/" target="_blank" rel="noreferrer"> 
        <img src="https://upload.wikimedia.org/wikipedia/commons/8/87/Arduino_Logo.svg" alt="Arduino" width="40" height="40"/> 
    </a> 
</p>

---

<h3>📚 Current Learning Semester Courses:</h3>
<ol>
  <li>
    <strong>Structured Programming Language</strong> <br>
    Learning the fundamentals of structured programming, focusing on algorithms, problem-solving techniques, and code optimization.
  </li>
  <li>
    <strong>Structured Programming Language Laboratory</strong> <br>
    Gaining hands-on experience with debugging, testing, and implementing real-world projects using structured programming techniques.
  </li>
  <li>
    <strong>Digital Logic Design</strong> <br>
    Studying Boolean algebra, combinational/sequential circuits, and digital systems design methodologies.
  </li>
  <li>
    <strong>Fundamental Calculus</strong> <br>
    Understanding limits, derivatives, integrals, and their applications in solving complex mathematical problems.
  </li>
</ol>

---

<h3>👨🏻‍🎓 Education</h3>
<ol>
  <li>
    B.Sc. in Computer Science & Engineering at United International University <br>
    Dhaka, Bangladesh
  </li>
  <li>
    Higher Secondary Certificate (HSC) <br>
    Dania College, Dhaka, Bangladesh
  </li>
  <li>
    Secondary School Certificate (SSC) <br>
    Shanarpar Sheikh Mortoza Ali High School, Narayanganj, Bangladesh
  </li>
</ol>

---

<h3>🌍 Languages</h3>
<ul>
  <li>🇧🇩 Bangla: Native</li>
  <li>🏴 English: Intermediate</li>
  <li>🇮🇳 Hindi: Intermediate</li>
</ul>

---

<h3>🏅 Hobbies and Activities</h3>
<ul>
  <li>⚽ Football, 🏸 Badminton, ♟️ Chess, 🏐 Volleyball</li>
  <li>🏊‍♂️ Swimming, 🏃‍♂️ Running, 🚶‍♂️ Walking, 🎣 Fishing</li>
  <li>✈️ Traveling</li>
</ul>

---

<details>
<summary>Click to view the Countdown Timer Code</summary>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Countdown Timer with Detailed Progress</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f0f0;
        }
        .timer {
            text-align: center;
        }
        .timer h1 {
            font-size: 3em;
        }
        .timer p {
            font-size: 1.5em;
        }
        .progress {
            margin-top: 20px;
        }
        .progress-bar {
            width: 100%;
            background-color: #ddd;
        }
        .progress-bar-fill {
            height: 30px;
            background-color: #4caf50;
            width: 0;
            text-align: center;
            line-height: 30px;
            color: white;
        }
    </style>
</head>
<body>
    <div class="timer">
        <h1 id="countdown"></h1>
        <p id="message"></p>
        <div class="progress">
            <div class="progress-bar">
                <div class="progress-bar-fill" id="progress-bar-fill">0%</div>
            </div>
        </div>
    </div>

    <script>
        var countDownDate = new Date("Sep 27, 2032 23:59:59").getTime();

        var x = setInterval(function() {

            var now = new Date().getTime();

            var distance = countDownDate - now;

            var years = Math.floor(distance / (1000 * 60 * 60 * 24 * 365));
            var days = Math.floor((distance % (1000 * 60 * 60 * 24 * 365)) / (1000 * 60 * 60 * 24));
            var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
            var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
            var seconds = Math.floor((distance % (1000 * 60)) / 1000);

            document.getElementById("countdown").innerHTML = years + "y " + days + "d " + hours + "h "
            + minutes + "m " + seconds + "s ";

            var totalDuration = countDownDate - new Date("Sep 27, 2024 00:00:00").getTime();
            var progress = ((totalDuration - distance) / totalDuration) * 100;
            document.getElementById("progress-bar-fill").style.width = progress + "%";
            document.getElementById("progress-bar-fill").innerHTML = Math.floor(progress) + "%";

            var startOfDay = new Date();
            startOfDay.setHours(0, 0, 0, 0);
            var endOfDay = new Date();
            endOfDay.setHours(23, 59, 59, 999);
            var dayDuration = endOfDay - startOfDay;
            var dayProgress = ((now - startOfDay) / dayDuration) * 100;

            var dayHours = Math.floor((now - startOfDay) / (1000 * 60 * 60));
            var dayMinutes = Math.floor(((now - startOfDay) % (1000 * 60 * 60)) / (1000 * 60));
            var daySeconds = Math.floor(((now - startOfDay) % (1000 * 60)) / 1000);

            document.getElementById("message").innerHTML = "Today's progress: " + dayHours + "h " + dayMinutes + "m " + daySeconds + "s | " + Math.floor(dayProgress) + "%";

            if (distance < 0) {
                clearInterval(x);
                document.getElementById("countdown").innerHTML = "EXPIRED";
                document.getElementById("message").innerHTML = "Your goal time has expired!";
                document.getElementById("progress-bar-fill").style.width = "100%";
                document.getElementById("progress-bar-fill").innerHTML = "100%";
            }
        }, 1000);
    </script>
</body>
</html>
