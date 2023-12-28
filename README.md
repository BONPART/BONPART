<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Lien vers code3.html en ligne</title>
</head>
<body>

  <h2>Lien vers code3.html en ligne</h2>

  <p>Vous pouvez accéder à la ressource en ligne en cliquant sur le lien ci-dessous :</p>

  <a href="http://www.example.com/chemin/vers/code3.html"> Accéder à code3.html en ligne </a>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contactez-moi</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
    }
    form {
      max-width: 400px;
      margin: auto;
    }
    label {
      display: block;
      margin-bottom: 8px;
    }
    input, textarea {
      width: 100%;
      padding: 8px;
      margin-bottom: 16px;
      box-sizing: border-box;
    }
    button {
      background-color: #4CAF50;
      color: white;
      padding: 10px 15px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
    button:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>

  <h2>Contactez-moi</h2>

  <form action="mailto:alexis.bonpart@gmail.com" method="post" enctype="text/plain">
    <label for="name">Nom :</label>
    <input type="text" id="name" name="name" required>

    <label for="email">Email :</label>
    <input type="email" id="email" name="email" required>

    <label for="message">Message :</label>
    <textarea id="message" name="message" rows="4" required></textarea>

    <button type="submit">Envoyer</button>
  </form>

</body>
</html>
