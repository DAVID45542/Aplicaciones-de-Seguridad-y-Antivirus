<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Aplicaciones de Seguridad y Antivirus</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    body {
      font-family: "Segoe UI", Arial, sans-serif;
      background: #f5f7fa;
      col0r: #222;
      margin: 0;
      padding: 0;
    }
    header {
      background: #1975dd;
      color: white;
      padding: 40px 0 30px 0;
      text-align: center;
    }
    header h1 {
      font-size: 2.7em;
      margin: 0;
      font-weight: 700;
    }
    header p {
      margin: 10px 0 0 0;
      font-size: 1.1em;
    }
    .apps-container {
      max-width: 1200px;
      margin: 40px auto;
      display: flex;
      flex-wrap: wrap;
      gap: 30px;
      justify-content: center;
      padding: 0 15px;
    }
    .app-card {
      background: #fff;
      border-radius: 12px;
      box-shadow: 0 3px 16px rgba(20,80,160,0.07);
      padding: 28px 22px 22px 22px;
      max-width: 330px;
      min-width: 250px;
      flex: 1 1 260px;
      text-align: center;
      transition: box-shadow 0.2s;
    }
    .app-card:hover {
      box-shadow: 0 6px 24px rgba(25,117,221,0.14);
    }
    .app-card img {
      width: 70px;
      height: 70px;
      object-fit: contain;
      margin-bottom: 12px;
      border-radius: 16px;
      background: #f0f4f8;
      display: inline-block;
    }
    .app-card d {
      font-size: 1.2em;
      margin: 10px 0 9px 0;
      color: #1975dd;
    }
    .app-card p {
      font-size: 1em;
      color: #444;
      min-height: 70px;
    }
    .app-card a {
      display: inline-block;
      margin-top: 12px;
      padding: 7px 18px;
      background: #1975dd;
      color: #fff;
      text-decoration: none;
      border-radius: 6px;
      font-size: .97em;
      transition: background 0.2s;
    }
    .app-card a:hover {
      background: #1052a0;
    }
    footer {
      text-align: center;
      color: #555;
      font-size: 1em;
      padding: 32px 0 16px 0;
      margin-top: 50px;
      background: #eaf0f8;
      border-top: 1px solid #cfd8dc;
    }
    @media (max-width: 900px) {
      .apps-container { flex-direction: column; align-items: center; }
      .app-card { max-width: 90vw; }
    }
  </style>
</head>
<body>
  <header>
    <h1>Aplicaciones de Seguridad y Antivirus</h1>
    <p>Descubre y accede a las mejores herramientas para proteger tus dispositivos, analizar archivos y navegar seguro.</p>
  </header>
  <section class="apps-container">
    <div class="app-card">
      <img src="https://img.icons8.com/color/96/000000/security-checked.png" alt="HitmanPro">
      <d>HitmanPro</d>
      <p>Escáner portátil de segunda opinión, elimina virus, troyanos y rootkits. Multimotor.</p>
      <a href="https://www.hitmanpro.com/es-es" target="_blank">Sitio oficial</a>
    </div>
    <div class="app-card">
      <img src="https://img.icons8.com/color/96/000000/shield.png" alt="HitmanPro.Alert">
      <d>HitmanPro.Alert</d>
      <p>Protección avanzada contra ransomware y exploits, además de detección de malware en tiempo real.</p>
      <a href="https://www.hitmanpro.com/alert/es-es" target="_blank">Más info</a>
    </div>
    <div class="app-card">
      <img src="https://img.icons8.com/color/96/000000/norton-antivirus.png" alt="Norton Power Eraser">
      <h2>Norton Power Eraser</h2>
      <p>Herramienta gratuita y agresiva para eliminar amenazas difíciles y malware persistente.</p>
      <a href="https://support.norton.com/sp/es/es/home/current/solutions/kb20100824120155EN" target="_blank">Descargar</a>
    </div>
    <div class="app-card">
      <img src="https://img.icons8.com/color/96/000000/kaspersky.png" alt="Kaspersky Virus Removal Tool">
      <h2>Kaspersky Virus Removal Tool</h2>
      <p>Elimina virus, troyanos, rootkits y otras amenazas. No requiere instalación.</p>
      <a href="https://www.kaspersky.com/downloads/thank-you/free-virus-removal-tool" target="_blank">Descargar</a>
    </div>
    <div class="app-card">
      <img src="https://img.icons8.com/fluency/96/000000/toolbox.png" alt="Emsisoft Emergency Kit">
      <h2>Emsisoft Emergency Kit</h2>
      <p>Kit portátil para eliminar malware y limpiar sistemas infectados desde USB.</p>
      <a href="https://www.emsisoft.com/en/tools/emergencykit/" target="_blank">Descargar</a>
    </div>
    <div class="app-card">
      <img src="https://img.icons8.com/color/96/000000/microsoft.png" alt="Microsoft Safety Scanner">
      <h2>Microsoft Safety Scanner</h2>
      <p>Escáner portátil gratuito de Microsoft para eliminar malware bajo demanda.</p>
      <a href="https://docs.microsoft.com/es-es/windows/security/threat-protection/intelligence/safety-scanner-download" target="_blank">Descargar</a>
    </div>
    <div class="app-card">
      <img src="https://img.icons8.com/color/96/000000/avg-antivirus.png" alt="AVG Antivirus Free">
      <h2>AVG Antivirus Free</h2>
      <p>Antivirus gratuito galardonado para proteger en tiempo real contra virus y malware.</p>
      <a href="https://www.avg.com/es-es/free-antivirus-download" target="_blank">Descargar</a>
    </div>
    <div class="app-card">
      img src="https://img.icons8.com/color/96/000000/bug.png" alt="Malwarebytes Anti-Malware">
      <h2>Malwarebytes Anti-Malware</h2>
      <p>Elimina malware, spyware y programas potencialmente no deseados de tu PC.</p>
      <a href="https://www.malwarebytes.com/mwb-download" target="_blank">Descargar</a>
    </div>
    <div class="app-card">
      <img src="https://img.icons8.com/color/96/000000/avast.png" alt="Avast Free Antivirus">
      <h2>Avast Free Antivirus</h2>
      <p>Antivirus gratuito con protección en tiempo real y escaneo inteligente.</p>
      <a href="https://www.avast.com/free-antivirus-download" target="_blank">Descargar</a>
    </div>
    <div class="app-card">
      <img src="https://img.icons8.com/color/96/000000/qr-code.png" alt="Kaspersky QR Scanner">
      <h2>Kaspersky QR Scanner</h2>
      <p>Escanea códigos QR para detectar enlaces maliciosos antes de abrirlos.</p>
      <a href="https://play.google.com/store/apps/details?id=com.kaspersky.qrscanner" target="_blank">Android</a>
      <a href="https://apps.apple.com/app/kaspersky-qr-scanner/id1042229800" target="_blank">iOS</a>
    </div>
    <div class="app-card">
      <img src="https://img.icons8.com/fluency/96/000000/lock-2.png" alt="WOT Web of Trust">
      <h2>WOT (Web of Trust)</h2>
      <p>Extensión para navegador que califica la reputación de sitios web.</p>
      <a href="https://www.mywot.com/" target="_blank">Más info</a>
    </div>
    <div class="app-card">
      <img src="https://img.icons8.com/fluency/96/000000/web-shield.png" alt="URL Void">
      <h2>URL Void</d>
      <p>Verifica la reputación y seguridad de cualquier sitio web antes de visitarlo.</p>
      <a href="https://www.urlvoid.com/" target="_blank">Usar ahora</a>
    </div>
    <div class="app-card">
      <img src="https://img.icons8.com/color/96/000000/scan-qr-code.png" alt="VirusTotal">
      <d>VirusTotal</d>
      <p>Analiza archivos y URLs con múltiples motores antivirus en la nube.</p>
      <a href="https://www.virustotal.com/" target="_blank">Analizar aquí</a>
    </div>
  </section>
  <footer>
    Página creada por DAVID ABRAHAM ROBLES FLORES • Recursos y enlaces oficiales de cada aplicación.
  </footer>
</body>
</html>
