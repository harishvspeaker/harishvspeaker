<h1 align="center">Hi 👋, I'm harish</h1>
<h3 align="center">A passionate full stack developer from India</h3>

- 🌱 I’m currently learning **machine learning , tensor flow ,keras**

- 💬 Ask me about **react , javascript**

- 📫 How to reach me **harishvspeaker@gmail.com**

- ⚡ Fun fact **apple is a fruit you look cute !!!!!!!!!!!**

<h3 align="left">Connect with me:</h3>
<p align="left">
</p>


<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://getbootstrap.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.cypress.io" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/simple-icons/simple-icons/6e46ec1fc23b60c8fd0d2f2ff46db82e16dbd75f/icons/cypress.svg" alt="cypress" width="40" height="40"/> </a> <a href="https://expressjs.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="express" width="40" height="40"/> </a> <a href="https://firebase.google.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a> <a href="https://www.postgresql.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> </a> <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a> <a href="https://redux.js.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redux/redux-original.svg" alt="redux" width="40" height="40"/> </a> </p>

<head>html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed,
figure, figcaption, footer, header, hgroup,
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure,
footer, header, hgroup, menu, nav, section {
	display: block;
}
body {
	line-height: 1;
}
ol, ul {
	list-style: none;
}
blockquote, q {
	quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
	content: '';
	content: none;
}
table {
	border-collapse: collapse;
	border-spacing: 0;
}

/* Grid */

html {
    box-sizing: border-box;
}

*, *:before, *:after {
    box-sizing: inherit;
}

.container {
    margin: 0 auto;
    padding: 0 25px;
    text-align: center;
    position: relative;
}

.overlay {
    position: absolute;
    top: 50%;
    left: 50%;
    width: 25%;
    height: 50%;
    transform: translate(-50%,-50%);
    background-color: rgba(0,0,0,0.5);
    border-radius: 5%;
    display: flex;
    flex-flow: column;
    justify-content: center;
    align-items: center;
}

.title {
    margin-bottom: 15px;
}

#gameBoard, .row {
    display: flex;
    flex-flow: row wrap;     
}

#gameBoard {
    width: 600px;
    height: 600px;
    margin: 0 auto;
    border: 2px groove #000;
    box-sizing: content-box;
    background: #a8c899;
}

.gameOverGrid {
    margin: auto;
}

/* Game */

.pixel {
    width: 15px;
    height: 15px;
    box-sizing: border-box;
}

.snakePixel {
    background-color: #000;
}

.foodPixel {
    background-color: cyan;
}

#gameOver {
    color: cornflowerblue;
    display: none;
}

.pixel:last-child {
    border-right: none;
}

.row:last-child .pixel {
    border-bottom: none;
}

/* Style */

.btn {
  background: #3498db;
  background-image: -webkit-linear-gradient(top, #3498db, #2980b9);
  background-image: -moz-linear-gradient(top, #3498db, #2980b9);
  background-image: -ms-linear-gradient(top, #3498db, #2980b9);
  background-image: -o-linear-gradient(top, #3498db, #2980b9);
  background-image: linear-gradient(to bottom, #3498db, #2980b9);
  -webkit-border-radius: 6;
  -moz-border-radius: 6;
  border-radius: 6px;
  font-family: Arial;
  color: #ffffff;
  font-size: 20px;
  padding: 10px 20px 10px 20px;
  text-decoration: none;
  border: 0;
}
.btn:hover {
  background: #3cb0fd;
  background-image: -webkit-linear-gradient(top, #3cb0fd, #3498db);
  background-image: -moz-linear-gradient(top, #3cb0fd, #3498db);
  background-image: -ms-linear-gradient(top, #3cb0fd, #3498db);
  background-image: -o-linear-gradient(top, #3cb0fd, #3498db);
  background-image: linear-gradient(to bottom, #3cb0fd, #3498db);
  text-decoration: none;
}

/* Typog */

/*! Typebase.less v0.1.0 | MIT License */
/* Setup */
html {
  /* Change default typefaces here */
  font-family: serif;
  font-size: 137.5%;
  -webkit-font-smoothing: antialiased;
}
/* Copy & Lists */
p {
  line-height: 1.5rem;
  margin-top: 1.5rem;
  margin-bottom: 0;
}
ul,
ol {
  margin-top: 1.5rem;
  margin-bottom: 1.5rem;
}
ul li,
ol li {
  line-height: 1.5rem;
}
ul ul,
ol ul,
ul ol,
ol ol {
  margin-top: 0;
  margin-bottom: 0;
}
blockquote {
  line-height: 1.5rem;
  margin-top: 1.5rem;
  margin-bottom: 1.5rem;
}
/* Headings */
h1,
h2,
h3,
h4,
h5,
h6 {
  /* Change heading typefaces here */
  font-family: sans-serif;
  margin-top: 1.5rem;
  margin-bottom: 0;
  line-height: 1.5rem;
}
h1 {
  font-size: 4.242rem;
  line-height: 4.5rem;
  margin-top: 3rem;
}
h2 {
  font-size: 2.828rem;
  line-height: 3rem;
  margin-top: 3rem;
}
h3 {
  font-size: 1.414rem;
}
h4 {
  font-size: 0.707rem;
}
h5 {
  font-size: 0.4713333333333333rem;
}
h6 {
  font-size: 0.3535rem;
}
/* Tables */
table {
  margin-top: 1.5rem;
  border-spacing: 0px;
  border-collapse: collapse;
}
table td,
table th {
  padding: 0;
  line-height: 33px;
}
/* Code blocks */
code {
  vertical-align: bottom;
}
/* Leading paragraph text */
.lead {
  font-size: 1.414rem;
}
/* Hug the block above you */
.hug {
  margin-top: 0;
}
</head>
<div class="container">
            <header class="title">
                <h2>JavaScript Snake Game</h2>
                <h3 id="score">Score: </h3>
            </header>
        </div>
        
        <div class="container">
            <section class="overlay">
                <div class="gameOverGrid">
                    <h3 id="gameOver">You lose!</h3>
                </div>
                <button class="gameOverGrid btn">Play</button>
            </section>
            <section id="gameBoard"></section>
        </div>
