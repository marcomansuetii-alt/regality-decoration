<!DOCTYPE html>
<html lang="ro">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Contacte | Carte de vizită digitală</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;600&display=swap');

    body {
      font-family: Arial, Helvetica, sans-serif;
      background: #000;
      margin: 0;
      padding: 0;
      color: #333;
    }
    .luxury {
      font-family: 'Playfair Display', serif;
      font-size: 28px;
      letter-spacing: 1px;
    }
    .card {
      max-width: 420px;
      margin: 40px auto;
      background: #fff;
      border-radius: 16px;
      padding: 24px;
      box-shadow: 0 10px 30px rgba(255,255,255,0.15);
      text-align: center;
      border: 2px solid #fff;
    }
    p.role {
      margin: 8px 0 16px;
      color: #666;
    }
    .btn {
      display: block;
      margin: 10px 0;
      padding: 14px;
      border-radius: 10px;
      text-decoration: none;
      font-weight: bold;
      color: #fff;
    }
    .btn-whatsapp {
      background: #000;
      color: #fff;
      border: 2px solid #fff;
    }
    .btn-vcard {
      background: #555;
    }
    .socials {
      margin-top: 20px;
      display: flex;
      justify-content: center;
      gap: 12px;
      flex-wrap: wrap;
    }
    .socials a {
      text-decoration: none;
      padding: 10px 14px;
      border-radius: 8px;
      background: #000;
      color: #fff;
      font-size: 14px;
      border: 1px solid #fff;
    }
    footer {
      margin-top: 20px;
      font-size: 12px;
      color: #999;
    }
  </style>
</head>
<body>
  <div class="card">
    <h1 class="luxury">Marco Mansueti</h1>
    <p class="role">
      Regality Decoration<br>
      <span style="font-size:14px; letter-spacing:1px;">Decorator de interior</span>
    </p>

    <a class="btn btn-whatsapp" href="https://wa.me/40778706353" target="_blank">
      Contactează-mă pe WhatsApp
    </a>

    <a class="btn btn-vcard" href="biglietto-da-visita.vcf" download>
      Salvează contactul
    </a>

    <div class="socials">
      <a href="https://instagram.com/regalitydecoration" target="_blank">Instagram</a>
      <a href="https://facebook.com/tuoprofilo" target="_blank">Facebook</a>
    </div>

    <footer>
      © 2026 - Toate drepturile rezervate
    </footer>
  </div>
</body>
</html>
