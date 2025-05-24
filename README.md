<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Stuttgart RP</title>
  <style>
    body {
      margin: 0;
      background: #111;
      color: #fff;
      font-family: sans-serif;
      overflow-x: hidden;
    }
    .info-box {
      position: absolute;
      width: 250px;
      padding: 20px;
      background: rgba(255, 255, 255, 0.1);
      border: 1px solid #fff3;
      border-radius: 10px;
      animation: float 6s ease-in-out infinite;
      backdrop-filter: blur(5px);
    }
    @keyframes float {
      0% { transform: translateY(0px); }
      50% { transform: translateY(-20px); }
      100% { transform: translateY(0px); }
    }
    h1 {
      text-align: center;
      margin: 20px;
      font-size: 2em;
      animation: fadeIn 3s ease-in-out;
    }
    @keyframes fadeIn {
      0% { opacity: 0; }
      100% { opacity: 1; }
    }
  </style>
</head>
<body>
  <h1>Stuttgart RP – Informationen & Eindrücke</h1>
  <script>
    const texte = [
      'Willkommen in Stuttgart RP!',
      'Hier kannst du deine eigenen Inhalte einfügen.',
      'Fakten über Stuttgart',
      'Rollenspiel Möglichkeiten',
      'Verkehr & Infrastruktur',
      'Kultur & Nachtleben',
      'Polizei, Feuerwehr & Notdienste',
      'Job-Systeme und Wirtschaft',
      'Events und Community',
      'Deine Ideen zählen!'
    ];

    for (let i = 0; i < texte.length; i++) {
      const box = document.createElement('div');
      box.className = 'stutgart rp
        ';
      box.style.top = Math.random() * window.innerHeight + 'px';
      box.style.left = Math.random() * window.innerWidth + 'px';
      box.innerText = texte[https://discord.gg/WDwTj8swMp
        ];
      document.body.appendChild(box);
    }
  </script>
</body>
</html>
