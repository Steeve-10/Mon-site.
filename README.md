# Mon-site.
Site web Steeve<!DOCTYPE html>
<html>
<head>
  <title>Vidéo sur ma page</title>
</head>
<body>
  <h1>Ma Vidéo</h1>
  <video width="320" height="360" controls>
    <source src="vdc.mp4" type="video/mp4">
  </video>
  <!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Galerie de Construction</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: 'Segoe UI', sans-serif;
            background-color: #f2f2f2;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #004466;
            color: white;
            padding: 20px;
            text-align: center;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 15px;
            padding: 20px;
        }

        .image-box {
            position: relative;
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
            text-align: center;
            padding-bottom: 10px;
        }

        .image-box img {
            width: 100%;
            height: auto;
            cursor: pointer;
            transition: transform 0.3s ease;
        }

        .image-box img:hover {
            transform: scale(1.02);
        }

        .description {
            padding: 10px;
            font-size: 14px;
            color: #333;
        }

        footer {
            text-align: center;
            padding: 10px;
            background-color: #004466;
            color: white;
        }

        .share-buttons {
            text-align: center;
            margin: 20px;
        }

        .share-buttons a {
            display: inline-block;
            margin: 10px;
            padding: 10px 20px;
            background-color: #25D366;
            color: white;
            text-decoration: none;
            border-radius: 6px;
        }

        .share-buttons a.facebook {
            background-color: #3b5998;
        }

        /* Popup overlay */
        .popup {
            display: none;
            position: fixed;
            z-index: 99;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0,0,0,0.8);
        }

        .popup img {
            display: block;
            max-width: 90%;
            max-height: 90%;
            margin: 5% auto;
            border-radius: 10px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Galerie de la Maison en Construction</h1>
        <p>Suivi de l'évolution du chantier</p>
    </header>

    <div class="gallery">
        <div class="image-box">
            <img src="maison 1.jpg" alt="Vue de face" onclick="openPopup(this.src)">
            <div class="description">Petite maison en briques - vue de face.</div>
        </div>
        <div class="image-box">
            <img src="maison 2.jpg" alt="Vue principale" onclick="openPopup(this.src)">
            <div class="description">Bâtiment principal en cours de finition.</div>
        </div>
    </div>

    <!-- Popup pour agrandir -->
    <div class="popup" id="popup" onclick="closePopup()">
        <img id="popup-img" src="">
    </div>

    <!-- Boutons de partage -->
    <div class="share-buttons">
        <a href="https://wa.me/?text=Regarde%20ma%20galerie%20de%20construction%20:%20https://exemple.com" target="_blank">Partager sur WhatsApp</a>
        <a href="https://www.facebook.com/sharer/sharer.php?u=https://exemple.com" class="facebook" target="_blank">Partager sur Facebook</a>
    </div>

    <footer>
        &copy; 2025 – Projet de construction personnelle
    </footer>

    <script>
        function openPopup(src) {
            document.getElementById("popup-img").src = src;
            document.getElementById("popup").style.display = "block";
        }

        function closePopup() {
            document.getElementById("popup").style.display = "none";
        }
    </script>
      <a href="https://www.STEEVEWAKA.com" target="_blank">
        Aller sur Google
    </a>

</body>
</html>


---

📝 Ce que tu dois modifier :

Remplace les noms image1.jpg et image2.jpg par les noms exacts de tes fichiers image.

Modifie les descriptions selon ce que tu veux dire pour chaque image.

Change le lien https://exemple.com par l'adresse réelle de ta page si tu la mets en ligne un jour (ou laisse comme ça si c'est local)
