<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Connexion - Page Éducative</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f5f5f5;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }

    .container {
      background: white;
      border-radius: 8px;
      padding: 2rem;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      width: 100%;
      max-width: 360px;
    }

    .logo {
      text-align: center;
      margin-bottom: 1.5rem;
    }

    h2 {
      text-align: center;
      color: #007846;
      margin-bottom: 1.5rem;
    }

    label {
      display: block;
      margin-bottom: 0.5rem;
      color: #333;
    }

    input {
      width: 100%;
      padding: 0.75rem;
      margin-bottom: 1rem;
      border: 1px solid #ccc;
      border-radius: 4px;
    }

    button {
      width: 100%;
      background-color: #007846;
      color: white;
      border: none;
      padding: 0.75rem;
      border-radius: 4px;
      cursor: pointer;
      font-size: 1rem;
    }

    button:hover {
      background-color: #005e36;
    }

    .message {
      margin-top: 1rem;
      font-size: 1rem;
      text-align: center;
      color: #007846;
    }

    .footer {
      text-align: center;
      margin-top: 1rem;
      font-size: 0.85rem;
      color: #777;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="logo">
      <img src="https://upload.wikimedia.org/wikipedia/fr/5/5e/BNP_Paribas_Logo.svg" alt="Logo" width="120">
    </div>
    <h2>Connexion</h2>
    <form onsubmit="return checkLogin(event)">
      <label for="identifiant">Identifiant</label>
      <input type="text" id="identifiant" required />

      <label for="mdp">Mot de passe</label>
      <input type="password" id="mdp" required />

      <button type="submit">Se connecter</button>
    </form>
    <div class="message" id="message"></div>
    <div class="footer">Simulation fictive à usage éducatif uniquement.</div>
  </div>

  <script>
    function checkLogin(e) {
      e.preventDefault();
      const id = document.getElementById("identifiant").value;
      const mdp = document.getElementById("mdp").value;
      const msg = document.getElementById("message");

      if (id === "Miroslawa" && mdp === "Zofia2035@@") {
        msg.textContent = "Bienvenue Miroslawa. Solde disponible : 300 000 €";
      } else {
        msg.textContent = "Identifiants incorrects.";
        msg.style.color = "red";
      }
    }
  </script>
</body>
</html><!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Connexion - Page Éducative</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f5f5f5;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }

    .container {
      background: white;
      border-radius: 8px;
      padding: 2rem;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      width: 100%;
      max-width: 360px;
    }

    .logo {
      text-align: center;
      margin-bottom: 1.5rem;
    }

    h2 {
      text-align: center;
      color: #007846;
      margin-bottom: 1.5rem;
    }

    label {
      display: block;
      margin-bottom: 0.5rem;
      color: #333;
    }

    input {
      width: 100%;
      padding: 0.75rem;
      margin-bottom: 1rem;
      border: 1px solid #ccc;
      border-radius: 4px;
    }

    button {
      width: 100%;
      background-color: #007846;
      color: white;
      border: none;
      padding: 0.75rem;
      border-radius: 4px;
      cursor: pointer;
      font-size: 1rem;
    }

    button:hover {
      background-color: #005e36;
    }

    .message {
      margin-top: 1rem;
      font-size: 1rem;
      text-align: center;
      color: #007846;
    }

    .footer {
      text-align: center;
      margin-top: 1rem;
      font-size: 0.85rem;
      color: #777;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="logo">
      <img src="https://upload.wikimedia.org/wikipedia/fr/5/5e/BNP_Paribas_Logo.svg" alt="Logo" width="120">
    </div>
    <h2>Connexion</h2>
    <form onsubmit="return checkLogin(event)">
      <label for="identifiant">Identifiant</label>
      <input type="text" id="identifiant" required />

      <label for="mdp">Mot de passe</label>
      <input type="password" id="mdp" required />

      <button type="submit">Se connecter</button>
    </form>
    <div class="message" id="message"></div>
    <div class="footer">Simulation fictive à usage éducatif uniquement.</div>
  </div>

  <script>
    function checkLogin(e) {
      e.preventDefault();
      const id = document.getElementById("identifiant").value;
      const mdp = document.getElementById("mdp").value;
      const msg = document.getElementById("message");

      if (id === "Miroslawa" && mdp === "Zofia2035@@") {
        msg.textContent = "Bienvenue Miroslawa. Solde disponible : 300 000 €";
      } else {
        msg.textContent = "Identifiants incorrects.";
        msg.style.color = "red";
      }
    }
  </script>
</body>
</html>
