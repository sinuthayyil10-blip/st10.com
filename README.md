# st10.com
body {
  margin: 0;
  font-family: -apple-system, sans-serif;
  background: black;
  color: white;
  overflow-x: hidden;
}

.nav {
  position: fixed;
  width: 100%;
  display: flex;
  justify-content: space-between;
  padding: 20px;
  background: rgba(0,0,0,0.5);
  backdrop-filter: blur(15px);
  z-index: 1000;
}

.logo { font-size: 22px; font-weight: bold; }

nav a {
  margin-left: 20px;
  color: #aaa;
  text-decoration: none;
}

.hero {
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  background: url('https://images.unsplash.com/photo-1503376780353-7e6692767b70') center/cover;
}

.hero h1 { font-size: 70px; }

.section {
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  text-align: center;
  background-size: cover;
}

.motors {
  background: url('https://images.unsplash.com/photo-1487754180451-c456f719a1fc') center/cover;
}

.hotrides {
  background: url('https://images.unsplash.com/photo-1493238792000-8113da705763') center/cover;
}

.clothing {
  background: url('https://images.unsplash.com/photo-1520975916090-3105956dac38') center/cover;
}

.overlay {
  background: rgba(0,0,0,0.6);
  padding: 40px;
  border-radius: 10px;
}

h2 { font-size: 50px; }

button {
  padding: 12px 25px;
  border: none;
  background: white;
  color: black;
  margin-top: 20px;
  cursor: pointer;
  border-radius: 20px;
}

.reveal {
  opacity: 0;
  transform: translateY(80px);
  transition: 1s;
}
.reveal.active {
  opacity: 1;
  transform: translateY(0);
}