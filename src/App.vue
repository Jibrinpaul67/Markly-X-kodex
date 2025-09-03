<template>
  <div class="app">
    <!-- ✅ Navbar -->
    <nav class="navbar">
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Bags</a></li>
        <li><a href="#">Accessories</a></li>
        <li><a href="#">Link</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>

    <!-- ✅ Hero Section -->
    <section class="hero">
      <h1>Markly Bags</h1>
      <p>Everything is sitting on a chocolate brown background 🍫</p>
    </section>

    <!-- ✅ Belief Section -->
    <section class="belief">
      <div class="belief-text">
        <h2>We believe in fashion</h2>
        <p>
          At Markly Bags, we believe fashion is more than just a statement —
          it’s a lifestyle. Our designs are crafted to combine elegance,
          durability, and functionality, ensuring you stand out while staying
          true to yourself.
        </p>
      </div>
      <div class="belief-image">
        <img src="@/assets/blackbag.png" alt="Bag" />
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
/* Reset browser default spacing */
html, body {
  margin: 0;
  padding: 0;
  height: 100%;
  width: 100%;
}

/* Chocolate brown background */
#app, .app {
  min-height: 100vh;
  width: 100vw;
  background-color: #7B3F00; /* 🍫 chocolate brown */
  color: white;
  display: flex;
  flex-direction: column;
  font-family: sans-serif;
}

/* ✅ Navbar */
.navbar {
  background-color: #4b2e2e; /* dark brown */
  padding: 20px;
}

.navbar ul {
  list-style: none;
  margin: 0;
  padding: 0;
  display: flex;
  justify-content: center;
  gap: 40px;
}

.navbar a {
  color: white;
  text-decoration: none;
  font-size: 1.1rem;
  font-weight: 600;
}

.navbar a:hover {
  text-decoration: underline;
}

/* ✅ Hero Section */
.hero {
  flex: 1;
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
  background-color: white; /* ✅ White background */
  color: black; /* ✅ Text is visible on white */
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
  max-width: 100%;
  border-radius: 10px;
}
</style>
