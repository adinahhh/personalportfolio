# personalportfolio
<script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script>

<body>
<header>
<h1 id="name">Adinah Zilton</h1>
  <nav id="navbar">
  <div class="table">
<ul id="horizontal-list">
  <li><a href="#about">about me</a></li>
  <li><a href="#projects">current projects</a></li>
  <li><a href="#aspirations">aspirations</a></li>
  <li><a href="#contact">contact</a></li>
</ul>
  </div>
</nav>
  </header>

  <main>
<div id="welcome-section">
<section id="about">
<h1>about me</h1>
  <p>Welcome to my portfolio page. I am currently learning how to code. Right now I am learning web design using HTML and CSS. I am eager to learn Javascript next!</p>
  </section>
  </div>
<section id="projects">
  <h1>current projects</h1>
    <p class="project-tile">Here is one of my finished projects, a <a href="https://codepen.io/zilton/pen/NBmRYy" target="_blank">Tribute Page.<a/></p>
    <p>To follow my journey, please check out my <a href="https://github.com/adinahhh" target="_blank" id="profile-link">Github profile.</a></p>
</section>
<section id="aspirations"> 
  <h1>aspirations</h1>
  <p>By the end of 2018, I'd like to be freelancing as a front-end developer. I am almosttt done with Free Code Camp's Web Design certification. I'd also like to complete their Javascript and Front End Libraries certifications as well.</p>
  </section>
<section id="contact">
  <h1>contact</h1>
  <p>If you'd like to contact me about any projects, please email me.</p>
  </section>
  </main>
</body>

body {
  text-align: center;
  background: rgb(210, 107, 119);
}
#name {
  background: rgb(210, 107, 119);
}
#navbar {
  background: hsl(315, 80%, 80%);
}
.table {
  display: table;
  margin: 0 auto;
}
ul#horizontal-list {
min-width: 50px;
list-style: none;
padding-top: 20px;
}

ul#horizontal-list li {
display: inline;
  margin-right: 45px;
}
