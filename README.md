* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Segoe UI", sans-serif;
}

body {
  background: #0e0e0e;
  color: #ffffff;
  line-height: 1.6;
}

/* ANIMATIONS */
.fade-in {
  animation: fadeIn 1.2s ease forwards;
}

.slide-up {
  animation: slideUp 1.2s ease forwards;
}

.slide-left {
  animation: slideLeft 1.2s ease forwards;
}

.slide-right {
  animation: slideRight 1.2s ease forwards;
}

.zoom-in {
  animation: zoomIn 1s ease forwards;
}

/* KEYFRAMES */
@keyframes fadeIn {
  from { opacity: 0; }
  to { opacity: 1; }
}

@keyframes slideUp {
  from { opacity: 0; transform: translateY(40px); }
  to { opacity: 1; transform: translateY(0); }
}

@keyframes slideLeft {
  from { opacity: 0; transform: translateX(-40px); }
  to { opacity: 1; transform: translateX(0); }
}

@keyframes slideRight {
  from { opacity: 0; transform: translateX(40px); }
  to { opacity: 1; transform: translateX(0); }
}

@keyframes zoomIn {
  from { opacity: 0; transform: scale(0.9); }
  to { opacity: 1; transform: scale(1); }
}

/* NAVBAR */
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px 40px;
  background: #000;
  position: sticky;
  top: 0;
}

.logo {
  font-weight: bold;
  letter-spacing: 2px;
}

.navbar a {
  color: #fff;
  margin-left: 20px;
  text-decoration: none;
}

/* HERO */
.hero {
  height: 90vh;
  background: linear-gradient(rgba(0,0,0,0.65), rgba(0,0,0,0.65)),
    url("../assets/images/hero.jpg") center/cover;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
}

/* SECTIONS */
section {
  padding: 80px 40px;
}

h2 {
  text-align: center;
  margin-bottom: 50px;
}

/* SERVICES */
.services-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 30px;
}

.service-card {
  background: #111;
  padding: 20px;
  border-radius: 12px;
}

/* ABOUT */
.about {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 40px;
  align-items: center;
}

.about img {
  width: 100%;
  border-radius: 12px;
}

/* PORTFOLIO */
.portfolio-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

.portfolio-grid img {
  width: 100%;
  border-radius: 10px;
}

/* CONTACT */
.contact form {
  max-width: 500px;
  margin: 30px auto;
  display: flex;
  flex-direction: column;
}

.contact input,
.contact textarea {
  padding: 12px;
  margin-bottom: 15px;
  border-radius: 6px;
  border: none;
}

.contact button {
  padding: 14px;
  background: #fff;
  color: #000;
  font-weight: bold;
  border: none;
  cursor: pointer;
}

/* FOOTER */
footer {
  background: #000;
  text-align: center;
  padding: 20px;
}
