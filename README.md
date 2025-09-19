<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulaire d'Inscription</title>
</head>
<body>
    <h1>Formulaire d'Inscription</h1>
    <div>
     <label>Nom:</label>
     <input type="text" placeholder="Votre nom complet" required>
    </div>
   <div>
    <label>Email:</label>
    <input type="text" placeholder="exemple@mail.com" required>
   </div>
    <div>
        <label>Mot de passe:</label>
        <input type="password" placeholder="mot de passe" required >
    </div>
    <div>
        <label>Age:</label>
        <input type="number"  placeholder=" " required>
    </div>
    <div>
        <label>Date de naissance:</label>
        <input type="date" placeholder=" " required>
    </div>
     <div>
        <label>Couleur préférée:</label>
        <input type="color" placeholder=" " required>
    </div>
     <div>
        <label>Volume préféré:</label>
        <input type="range" placeholder=" " required>
    </div>
     <div>
        <label>Photo de profil:</label>
        <input type="image" placeholder=" " required>
    </div>
     <div>
        <label>Genre:</label>
        <input type="radio" placeholder=" " required>
    </div>
     <div>
        <label>Centres d’intérêt :</label>
        <input type="checkbox" placeholder=" " required>
    </div>
    <label>Niveau d'études :</label>
    <select name="niveau">
        <option value="">--choisissez--</option>
        <option value="1">Lycée</option>
        <option value="2">Licence</option>
        <option value="3">Master</option>
     </select><br>
     <label>Pourquoi vous inscrire ?</label><br>
     <textarea name="message" placeholder="Expliquez ici..."></textarea><br>
     <button type="submit">S'inscrire</button>
     <button type="submit">Réinitialiser</button>
     <h2>Image</h2>
      <figure>
        <img src="https://images.unsplash.com/photo-1607746882042-944635dfe10e?ixlib=rb-4.0.3&auto=format&fit=crop&w=300&q=80" alt=image>
        <figcaption>Exemple de photo de profil</figcaption>
    </figure>
    <h2>Audio</h2>
     <audio controls>
        <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
    </audio>
    <h2>Vidéo MP4</h2>
     <video controls>
        <source src="https://WWW.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
    </video>
    <h2>Liste des inscrits (exemple)</h2>
    <table border="1">
        <thead>
            <tr>
                <th>Nom</th>
                <th>Email</th>
                <th>Niveau</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Amina</td>
                <td>amina@gmail.com</td>
                <td>Licence</td>
            </tr>
            <tr>
                <td>Yacine</td>
                <td>yacine@gmail.com</td>
                <td>Master</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
