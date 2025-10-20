# Aut-szerviz
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Arial", sans-serif;
}

body {
  background-color: #f5f5f5;
  color: #333;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #444;
  color: #fff;
  padding: 15px 40px;
}

header .logo {
  font-size: 1.5em;
  font-weight: bold;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 20px;
}

nav a {
  color: #fff;
  text-decoration: none;
  transition: color 0.3s;
}

nav a:hover {
  color: #ffcc00;
}

.btn {
  background-color: #ffcc00;
  color: #333;
  padding: 10px 20px;
  border-radius: 5px;
  text-decoration: none;
  font-weight: bold;
  transition: background 0.3s;
}

.btn:hover {
  background-color: #e6b800;
}

.hero {
  text-align: center;
  padding: 100px 20px;
  background: linear-gradient(to bottom, #666, #999);
  color: #fff;
}

.hero h1 {
  font-size: 2.5em;
  margin-bottom: 10px;
}

.hero p {
  font-size: 1.2em;
  margin-bottom: 20px;
}

.services {
  padding: 60px 20px;
  text-align: center;
}

.services h2 {
  font-size: 2em;
  margin-bottom: 40px;
}

.service-list {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 30px;
}

.service {
  background-color: #fff;
  padding: 20px;
  border-radius: 10px;
  width: 250px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.1);
}

footer {
  background-color: #333;
  color: #fff;
  text-align: center;
  padding: 20px;
  margin-top: 50px;
}
