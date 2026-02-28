<!DOCTYPE html>
<html>
<head>
<title>Dhanush Kumar | Tattoo Artist</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
body {
  margin: 0;
  font-family: 'Arial', sans-serif;
  background-color: #0b0b0b;
  color: white;
  scroll-behavior: smooth;
}

header {
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.9));
  text-align: center;
}

h1 {
  font-size: 60px;
  margin-bottom: 10px;
  letter-spacing: 2px;
}

.tagline {
  font-size: 20px;
  color: #bbb;
}

button {
  padding: 12px 30px;
  border: 1px solid white;
  background: transparent;
  color: white;
  margin-top: 30px;
  cursor: pointer;
  transition: 0.3s;
}

button:hover {
  background: white;
  color: black;
}

section {
  padding: 80px 10%;
}

h2 {
  text-align: center;
  margin-bottom: 40px;
  font-size: 35px;
}

.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

.gallery img {
  width: 100%;
  border-radius: 10px;
  transition: 0.4s;
}

.gallery img:hover {
  transform: scale(1.05);
}

.about {
  text-align: center;
  max-width: 800px;
  margin: auto;
  color: #aaa;
  line-height: 1.6;
}

footer {
  background: black;
  text-align: center;
  padding: 40px;
  color: #666;
}
</style>
</head>

<body>

<header>
  <h1>Dhanush Kumar</h1>
  <p class="tagline">Portrait & Realism Tattoo Specialist</p>
  <button onclick="window.location.href='https://instagram.com/artys_dhanu'">
    Book Appointment
  </button>
</header>

<section>
  <h2>My Work</h2>
  <div class="gallery">
    <img src="https://via.placeholder.com/400">
    <img src="https://via.placeholder.com/400">
    <img src="https://via.placeholder.com/400">
    <img src="https://via.placeholder.com/400">
  </div>
</section>

<section>
  <h2>About Me</h2>
  <div class="about">
    I am a professional tattoo artist based in Kerala, specializing in hyper-realistic portrait tattoos.  
    Every tattoo I create carries emotion, precision, and story — designed to live forever on skin.
  </div>
</section>

<footer>
  Kerala | artsydhanu@gmail.com  
  <br><br>
  © 2026 Dhanush Kumar
</footer>

</body>
</html>

