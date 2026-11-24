<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Inscription - On Love</title>
<style>
body{margin:0;font-family:Arial;background:#0a0a0a;color:white;display:flex;justify-content:center;padding:20px}
.box{background:#1a1a1a;padding:30px;border-radius:20px;width:100%;max-width:420px}
h1{text-align:center;color:#ff2e63}
input,select,textarea{width:100%;padding:13px;margin:8px 0;border-radius:10px;border:none;background:#2a2a2a;color:white;box-sizing:border-box}
.btn{width:100%;background:#ff2e63;color:white;padding:15px;border:none;border-radius:30px;font-size:18px;cursor:pointer;margin-top:10px}
.chat{background:#2a2a2a;border-radius:15px;padding:15px;margin-top:20px}
.msg{background:#ff2e63;padding:10px;border-radius:15px;margin:5px 0}
.msg2{background:#444;padding:10px;border-radius:15px;margin:5px 0}
</style>
</head>
<body>
<div class="box">
  <h1>On Love 💕</h1>
  <p style="text-align:center">Crée ton compte - Rencontre sérieuse / Mariage</p>

  <input type="text" placeholder="Ton prénom">
  <input type="number" placeholder="Ton âge">
  <select>
    <option>Ton pays</option>
    <option>Bénin</option>
    <option>Togo</option>
    <option>Côte d'Ivoire</option>
    <option>Sénégal</option>
    <option>Cameroun</option>
    <option>Nigeria</option>
    <option>Ghana</option>
    <option>Mali</option>
    <option>Congo</option>
    <option>Autre pays d'Afrique</option>
  </select>
  <select>
    <option>Je suis...</option>
    <option>Homme</option>
    <option>Femme</option>
  </select>
  <select>
    <option>Je cherche...</option>
    <option>Mariage</option>
    <option>Relation sérieuse</option>
    <option>Amitié puis amour</option>
  </select>
  <textarea placeholder="Parle de toi en 2 phrases... Ex: Je suis sérieux, je cherche une femme pour le mariage"></textarea>
  <input type="file" accept="image/*">
  <input type="email" placeholder="Ton email">
  <input type="password" placeholder="Mot de passe">
  <button class="btn" onclick="alert('Bienvenue sur On Love ! Ton compte est créé ❤️')">Créer mon compte gratuit</button>

  <!-- APERÇU DU CHAT -->
  <div class="chat">
    <h3>💬 Exemple de Chat après un Match</h3>
    <div class="msg2">Aïcha : Bonjour, j'ai aimé ton profil 😊</div>
    <div class="msg">Toi : Bonjour Aïcha, moi aussi. Tu es d'où ?</div>
    <div class="msg2">Aïcha : Je suis à Cotonou, et toi ?</div>
    <input type="text" placeholder="Écris ton message...">
    <button class="btn">Envoyer</button>
  </div>
</div>
</body>
</html>
