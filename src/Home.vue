<style>
/* Reset browser default spacing */
html, body {
  margin: 0;
  padding: 0;
  height: 100vh;
  width: 100vh;
}

/* Chocolate brown background first page */
#app, .app {
  min-height: 100vh;
  width: 100vw;
  background-color: #7B3F00;
  color: White;
  display: flex;
  flex-direction: column;
  font-family: sans-serif;
}

/* ✅ Navbar */
.navbar {
  background-color: #4b2e2e; /* dark brown */
  padding: 30px;
}
.navbar ul {
  list-style: none;
  margin: 0;
  padding: 0;
  display: flex;
  justify-content: center;
  gap: 100px;
}
.navbar a {
  color: white;
  text-decoration: none;
  font-size: 1.1rem;
  font-weight: 300;
}
.navbar a:hover {
  text-decoration: underline;
}


/* ✅ Hero Section */
.hero {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
}

/* ✅ Belief Section */
.belief {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 80px;
  background-color: white; 
  color: black;
}
.belief-text {
  flex: 1;
  padding-right: 40px;
}

.belief-text h2 {
  font-size: 2.5rem;
  font-weight: bold;
  margin-bottom: 20px;
}

.belief-text p {
  font-size: 1.1rem;
  line-height: 1.6;
  max-width: 500px;
}

.belief-image {
  flex: 1;
  display: flex;
  justify-content: center;
}

.belief-image img {
  max-width: 900vh;
  border-radius: 10px;
}
</style>