
<!DOCTYPE html>
<html lang="fi">
<head>
  <meta charset="UTF-8">
  <title>Kiitosopettajalle!</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <!-- QRCode.js CDN -->
  <script src="https://cdnjs.cloudflare.com/ajax/libs/qrcodejs/1.0.0/qrcode.min.js"></script>
  <style>
    body {
      background: linear-gradient(135deg, #f8fafc 0%, #dbeafe 100%);
      font-family: 'Segoe UI', sans-serif;
      display: flex;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      margin: 0;
      position: relative;
      overflow: hidden;
    }
    .container {
      background: rgba(255,255,255,0.95);
      box-shadow: 0 8px 32px rgba(52, 99, 205, 0.15);
      border-radius: 1.5rem;
      padding: 2.5rem 2rem 2rem;
      max-width: 400px;
      text-align: center;
      position: relative;
      z-index: 2;
    }
    h1 {
      color: #1d4ed8;
      margin-bottom: 0.3em;
      letter-spacing: 0.05em;
    }
    .kiitosviesti {
      font-size: 1.15em;
      color: #22223B;
      margin-bottom: 1.5em;
    }
    .qr-container {
      margin: 1em 0 1.5em 0;
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    .buttons {
      margin-bottom: 1em;
      gap: 0.5em;
      display: flex;
      flex-direction: row;
      justify-content: center;
    }
    .buttons button {
      background: #3b82f6;
      color: #fff;
      border: none;
      border-radius: 0.7em;
      padding: 0.6em 1.3em;
      transition: background 0.15s;
      font-size: 1em;
      cursor: pointer;
      margin: 0 4px;
      box-shadow: 0 2px 8px rgba(59,130,246,0.13);
    }
    .buttons button:hover {
      background: #1e40af;
    }
    .ohjeet {
      margin-top: 0.8em;
      color: #475569;
      font-size: 0.98em;
    }
    /* Floating Emoji Animations */
    .emoji {
      position: absolute;
      font-size: 2.3em;
      opacity: 0.17;
      animation: float 9s linear infinite;
      pointer-events: none;
      user-select: none;
    }
    /* Create several different animations for floating effect */
    @keyframes float {
      0% { transform: translateY(110vh) scale(1) rotate(-8deg);}
      100% { transform: translateY(-15vhundefined
