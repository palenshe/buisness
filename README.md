<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Связаться</title>

<style>
  * {
    box-sizing: border-box;
  }

  body {
    margin: 0;
    height: 100vh;
    background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
    display: flex;
    justify-content: center;
    align-items: center;
    font-family: 'Segoe UI', Arial, sans-serif;
    color: white;
  }

  .card {
    background: rgba(255,255,255,0.1);
    backdrop-filter: blur(12px);
    border-radius: 20px;
    padding: 40px 30px;
    max-width: 360px;
    width: 90%;
    text-align: center;
    box-shadow: 0 20px 40px rgba(0,0,0,0.4);
    animation: fadeIn 1s ease;
  }

  @keyframes fadeIn {
    from { opacity: 0; transform: translateY(20px); }
    to { opacity: 1; transform: translateY(0); }
  }

  .card h1 {
    font-size: 26px;
    margin-bottom: 10px;
  }

  .card p {
    font-size: 15px;
    opacity: 0.85;
    margin-bottom: 30px;
  }

  .whatsapp-btn {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 12px;
    background: #25D366;
    color: white;
    padding: 16px 24px;
    border-radius: 14px;
    font-size: 18px;
    font-weight: bold;
    text-decoration: none;
    box-shadow: 0 10px 20px rgba(37,211,102,0.4);
    transition: all 0.3s ease;
  }

  .whatsapp-btn:hover {
    transform: translateY(-3px);
    box-shadow: 0 14px 26px rgba(37,211,102,0.6);
    background: #1ebe5d;
  }

  .whatsapp-btn img {
    width: 28px;
    height: 28px;
  }

  .footer {
    margin-top: 25px;
    font-size: 12px;
    opacity: 0.6;
  }
</style>
</head>

<body>

<div class="card">
  <h1>Байланыс</h1>
  <p>Төмендегі батырманы басып, WhatsApp арқылы тікелей жазыңыз</p>

  <a class="whatsapp-btn"
     href="https://api.whatsapp.com/send?phone=77756304206&text=%D0%A1%D3%A9%D0%BB%D0%B5%D0%BC%D0%B5%D1%82%D1%81%D1%96%D0%B7%20%D0%B1%D0%B5,%20%D0%BC%D0%B5%D0%BD%20Telegram-%D0%BD%D0%B0%D0%BD%20%D0%BA%D0%B5%D0%BB%D0%B4%D1%96%D0%BC"
     target="_blank">
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp">
    Написать WhatsApp
  </a>

  <div class="footer">
    Автоматты жауап • Қауіпсіз байланыс
  </div>
</div>

</body>
</html>
