# Salvator.Konate_Bewerbung
Salvator.Konate_Bewerbung
<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Deckblatt / Bewerbung - Salvator Konate</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="hero">
    <div class="content">
      <h1>Salvator Konate</h1>
      <p><strong>Geboren:</strong> 23.01.2010</p>
      <p><strong>Alter:</strong> 15 Jahre</p>
      <p><strong>Adresse:</strong> Tannenweg 4, 4900</p>
      <p><strong>Telefon:</strong> 079 419 65 88</p>
      <p><strong>E-Mail:</strong> salvator.konate@schule-langenthal.ch</p>
      
     <div class="btn-download">
  <a href="Salvator.Konate_Lebenslauf.pdf" download>Lebenslauf ⬇️</a>
</div>

<div class="btn-download">
  <a href="Salvator.Konate_WochenPlatz.Zeugnis.pdf" download>Zeugnis ⬇️</a>
</div>

      
      <div class="text-ueber-mich">
        <p>Meine Leidenschaft ist Basketball und ich spiele aktuell im Team STB U16. Ich bin **1.92 m groß** und ein Vorteil von mir ist, dass ich es mag, **exakt** zu arbeiten und sehr **vielfältig** bin. Ich schätze Abwechslung im Job und setze mich engagiert dafür ein, in allem, was ich tue, mein Bestes zu geben.</p>
      </div>
      
      <div class="abschluss">
        <p>Danke für Ihre Aufmerksamkeit. Ich würde mich über eine positive Antwort sehr freuen!</p>
        <p>Mit freundlichen Grüßen,</p>
        <p>Salvator Konate</p>
      </div>
    </div>
  </div>
</body>
</html>
CSS (styles.css)
css
Code kopieren
/* Grundlegende Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body, html {
  height: 100%;
  font-family: Arial, sans-serif;
}

/* Hintergrund und Hauptbereich */
.hero {
  background-color: #ADD8E6; /* helles Blau */
  color: #000000;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 20px;
}

.content {
  max-width: 600px;
  width: 100%;
  background: white;
  padding: 30px;
  border-radius: 10px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
}

/* Überschrift und Kontaktinfos */
.content h1 {
  font-size: 2.5rem;
  margin-bottom: 20px;
  text-align: center;
}

.content p {
  font-size: 1rem;
  margin-bottom: 8px;
}

/* Button */
.btn-download {
  text-align: center;
  margin: 20px 0;
}

.btn-download a {
  background-color: #007BFF; /* kräftiges Blau für den Button */
  color: white;
  text-decoration: none;
  padding: 12px 25px;
  border-radius: 5px;
  font-size: 1.1rem;
  display: inline-block;
}

.btn-download a:hover {
  background-color: #0056b3;
}

/* Über mich Text */
.text-ueber-mich {
  margin-top: 20px;
  font-size: 1.05rem;
  line-height: 1.5;
}

/* Abschluss */
.abschluss {
  margin-top: 30px;
  text-align: center;
  font-size: 1rem;
  line-height: 1.4;
}
