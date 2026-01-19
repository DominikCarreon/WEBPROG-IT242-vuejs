<template>
<div class="profile-page">
<h1>Personal Profile Web page</h1>
<section>
<h2>About Me</h2>
<p>Education / Achievements</p>
<p>Senior high school at Asia Pacific College</p>
<p><strong>Course:</strong> BS Information Technology</p>
<p><strong>IT Experience:</strong> HTML / CSS / Java / Python</p>
<p><strong>Hobbies & Interests:</strong> Eating and drinking lots of coffee</p>
<p><strong>Goals In Life / Dream:</strong> To be happy and rich</p>
</section>
<section>
<h2>Picture Gallery</h2>
<img
       src="https://as-prod.asyncgw.teams.microsoft.com/v1/objects/0-ea-d7-f6f35dd33910abd4d61fb0dd986223cd/views/imgpsh_fullsize"
       alt="Profile picture"
       width="500"
       height="600"
     />
</section>
<div class="grid-container">
<div class="header">
<h1>Dominik's Personal Profile</h1>
</div>
<div class="menu">
<ul>
<li>LinkedIn</li>
<li>Facebook</li>
<li>Instagram</li>
</ul>
</div>
<div class="content">
<h1>About Me</h1>
<p>Dominik's nickname is Doms.</p>
<p>Doms is a good student and finishes all requirements on time.</p>
<p>Doms is a very happy person and sometimes very annoying.</p>
<p>Doms really likes coffee.</p>
</div>
<div class="facts">
<h2>Facts:</h2>
<ul>
<li>I like reading books</li>
<li>I can study 24 hours straight</li>
</ul>
</div>
<div class="footer">
<p>© 2025 Dominik's Profile, Inc. All rights reserved.</p>
</div>
</div>
</div>
</template>
<script>
export default {
 name: "PersonalProfile",
};
</script>
<style>

* {
 box-sizing: border-box;
}
body {
 font-family: "Lucida Sans", sans-serif;
 font-size: 17px;
 margin: 0;
}
.grid-container {
 display: grid;
 grid-template-areas:
   "header"
   "menu"
   "main"
   "facts"
   "footer";
 background-color: rgb(0, 0, 0);
 gap: 10px;
 padding: 10px;
}
.header {
 grid-area: header;
 background-color: rgb(175, 4, 4);
 text-align: center;
 color: #ffffff;
}
.header > h1 {
 font-size: 40px;
}
.menu {
 grid-area: menu;
}
.menu ul {
 list-style-type: none;
 margin: 0;
 padding: 0;
}
.menu li {
 padding: 8px;
 margin-bottom: 7px;
 background-color: #ffee00a6;
 color: #ffffff;
}
.menu li:hover {
 background-color: #ffdd00;
}
.content {
 grid-area: main;
 color: #ffffff;
}
.content > h1 {
 font-size: 30px;
 margin-bottom: 7px;
 color: #ffffff;
}
.content > p {
 margin-bottom: 7px;
 color: #ffffff;
}
.facts {
 grid-area: facts;
 border: 1px solid #ffee00a6;
 background-color: beige;
 padding: 10px;
}
.facts > h2 {
 font-size: 20px;
}
.facts li {
 margin-bottom: 5px;
}
.footer {
 grid-area: footer;
 background-color: #ffee00a6;
 color: #ffffff;
 text-align: center;
 padding: 10px;
}
/* Tablet */
@media (min-width: 600px) {
 .grid-container {
   grid-template-areas:
     "header header header header header header"
     "menu main main main main main"
     "facts facts facts facts facts facts"
     "footer footer footer footer footer footer";
 }
}
/* Desktop */
@media (min-width: 768px) {
 .grid-container {
   grid-template-areas:
     "header header header header header header"
     "menu main main main main facts"
     "footer footer footer footer footer footer";
 }
}

</style>