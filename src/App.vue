<template>
  <div id="app">
    <header>
    <nav>
      <h2>Locker Project</h2>
      <div class="navLinks">
        <ul>
          <li class="navLink"><a href="#">Home</a></li>
          <li class="navLink"><a href="#">Report a Repair</a></li>
        </ul>
      </div>
    </nav>
    </header>

    <router-view/>
    <footer>
      &copy; Jonathon Chambers
    </footer>
  </div>
</template>

<style>
body {
  background: #143250;
}
header {
  width: 100%;
  background: #f0f0f0;
  margin-bottom: 1%;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  
}
nav {
  display: flex;
  flex-direction: row;
  padding: 1%;
}
nav li {
  display: inline;
}
.navLink {
  padding: 1rem;
}
.navLink a{
  text-decoration: none;
}
.navLink a:link {
  color: #2c3e50;
}
.navLink a:visited{
  color: #2c3e50;
}
.navLink a:hover {
  border-bottom: 2px solid black;
}
footer {
  background: #f0f0f0;
  position: absolute;
  bottom: 0;
  height: 2rem;
  width: 98%;
  padding: 1%;
  left: 0;
  text-align: center;
  clear: both;
}
</style>
