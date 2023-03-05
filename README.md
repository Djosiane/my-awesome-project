# my-awesome-project
This awesome project is created to experiment git notions like clone, push and pull
Achievemrnts : "J'ai réussi à faire clone, pull et je m'apprête à faire push"

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Voyage en Italie</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/css/bootstrap.min.css">
</head>
<body>
    <form action="thanks.php" method="post" class="container bg-light border rounded p-5">
        <h1 class="text-center">Votre destination</h1>
    <div>
      <label  for="nom">Nom :</label>
      <input  type="text"  id="nom"  name="user_name">
    </div>
    <div> 
      <label  for="nom">prénom :</label>
      <input  type="text"  id="nom"  name="name"> 
    </div>
    <div>
      <label  for="courriel">Courriel :</label>
        <input  type="email"  id="courriel"  name="user_email">
    </div>

    <div>
    <label for="phone">Enter a phone number:</label><br><br>
    <input type="tel" id="phone" name="phone" placeholder="123-45-678" pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}" required><br><br>
    <small>Format: 123-45-678</small><br><br> 
    </div>
    <div>
      <label  for="message">Message :</label>
      <textarea  id="message"  name="user_message"></textarea>
    </div>
    <div>
    <label for="choix-destination">Choisissez votre destination de vacances préférée:</label>
    <select id="choix-destination" name="destination">
    <option value="plage">Plage</option>
    <option value="montagne">Montagne</option>
    <option value="ville">Ville</option>
    <option value="campagne">Campagne</option>
    </select>
    </div>
    <div>
    <label for="champ-message">Votre message:</label>
    <textarea id="champ-message" name="message" rows="5"></textarea>
    </div>
    <div  class="button">
      <button  type="submit">Envoyer votre message</button>
    </div>
  </form>
</body>
</html>