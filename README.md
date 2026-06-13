# Reposit-rio-teste-<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>AgroTech Sustentável</title>

  <link rel="stylesheet" href="style.css">
</head>

<body>

  <header>
    <h1>🌱 Tecnologia Sustentável no Campo</h1>
    <p>Inovação que atrai o jovem de volta ao campo e garante um futuro moderno e sustentável</p>
  </header>

  <nav>
    <a href="#sobre">Sobre</a>
    <a href="#importancia">Importância</a>
    <a href="#futuro">Futuro</a>
  </nav>

  <section id="sobre">
    <div class="card">
      <h2>📌 Sobre o tema</h2>
      <p>
        A tecnologia sustentável no campo une inovação e natureza, permitindo produção eficiente e consciente.
      </p>
    </div>
  </section>

  <section id="importancia">
    <div class="card">
      <h2>🌾 Importância</h2>
      <p>
        Drones, sensores e energia limpa ajudam a modernizar o campo e atrair jovens para a agricultura.
      </p>

      <button onclick="mostrarMensagem()" class="btn">
        Clique para ver uma mensagem 💡
      </button>

      <p id="msg"></p>
    </div>
  </section>

  <section id="futuro">
    <div class="card">
      <h2>🚀 Futuro sustentável</h2>
      <p>
        O futuro do campo depende da união entre tecnologia e preservação ambiental.
      </p>
    </div>
  </section>

  <footer>
    <p>Projeto Agrinho © 2026</p>
  </footer>

  <script src="script.js"></script>

</body>
</html>* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, sans-serif;
}

body {
  background: #f4fff6;
  color: #1b3a2f;
}

header {
  background: linear-gradient(90deg, #1b5e20, #43a047);
  color: white;
  padding: 40px;
  text-align: center;
}

header h1 {
  font-size: 28px;
}

nav {
  background: #145a32;
  text-align: center;
  padding: 10px;
}

nav a {
  color: white;
  margin: 0 15px;
  text-decoration: none;
  font-weight: bold;
}

section {
  padding: 40px;
  max-width: 1000px;
  margin: auto;
}

.card {
  background: white;
  padding: 20px;
  margin: 20px 0;
  border-radius: 12px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
}

.btn {
  padding: 10px 20px;
  background: #2e7d32;
  color: white;
  border: none;
  border-radius: 8px;
  cursor: pointer;
  margin-top: 10px;
}

.btn:hover {
  background: #1b5e20;
}

footer {
  text-align: center;
  padding: 20px;
  background: #1b3a2f;
  color: white;
  margin-top: 30px;
}function mostrarMensagem() {
  document.getElementById("msg").innerHTML =
    "🌱 O futuro do campo está na tecnologia sustentável e na juventude!";
}
