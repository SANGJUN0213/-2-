# -2-

<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>앱 다운로드 페이지</title>
    <link rel="stylesheet" href="style.css">
    <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
  }
  
  body {
      font-family: 'Arial', sans-serif;
      line-height: 1.6;
  }
  
  header {
      background: #333;
      color: #fff;
      padding: 1rem;
      text-align: center;
  }
  
  main {
      padding: 2rem;
  }
  
  .hero {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 2rem;
  }
  
  .content {
      flex: 1;
      padding-right: 2rem;
  }
  
  .content h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
  }
  
  .content p {
      margin-bottom: 2rem;
  }
  
  .cta-buttons {
      display: flex;
      gap: 1rem;
  }
  
  .cta-btn {
      padding: 1rem 2rem;
      background: #007bff;
      color: white;
      text-decoration: none;
      border-radius: 5px;
  }
  
  .cta-btn:hover {
      background: #0056b3;
  }
  
  .image img {
      width: 300px;
  }
  
  .features {
      text-align: center;
      margin-top: 2rem;
  }
  
  .features h3 {
      font-size: 1.5rem;
      margin-bottom: 1rem;
  }
  
  .feature-grid {
      display: flex;
      justify-content: space-between;
      gap: 1rem;
  }
  
  .feature {
      background: #f4f4f4;
      padding: 1rem;
      border-radius: 5px;
      flex: 1;
      text-align: center;
  }
  
  footer {
    position: fixed;
    bottom: 0;
    width: 100%;
    background-color: #333;
    color: white;
    text-align: center;
    padding: 0.5rem;

  }
  </style>
</head>
<body>
    <header>
        <nav>
            <h1>카카오톡</h1>
        </nav>
    </header>

    <main>
        <section class="hero">
            <div class="content">
                <h2>모바일 앱을 다운로드하세요!</h2>
                <p>언제 어디서나 간편하게 앱을 이용해보세요. 주요 기능을 통해 당신의 생활이 더 편리해집니다.</p>
                <div class="cta-buttons">
                    <a href="https://www.apple.com/kr/app-store/"target="_blank" class="cta-btn">앱스토어에서 다운로드</a>
                    <a href="https://play.google.com/store/games?hl=ko" target="_blank" class="cta-btn">구글플레이에서 다운로드</a>
                </div>
            </div>
            <div class="image">
                <img src="https://th.bing.com/th/id/OIP.dw93Ts8HdqrFxu9R_xsSDwHaHa?rs=1&pid=ImgDetMain" alt="앱 스크린샷">
            </div>
        </section>

        <section class="features">
            <h3>앱의 주요 기능</h3>
            <div class="feature-grid">
                <div class="feature">
                    <h4>빠른 로그인</h4>
                    <p>간편한 인증 시스템을 통해 손쉽게 로그인하세요.</p>
                </div>
                <div class="feature">
                    <h4>실시간 알림</h4>
                    <p>중요한 업데이트와 알림을 실시간으로 받아보세요.</p>
                </div>
                <div class="feature">
                    <h4>다양한 설정</h4>
                    <p>앱의 다양한 기능을 맞춤 설정하여 나만의 경험을 만들어보세요.</p>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 앱 이름. 모든 권리 보유.</p>
    </footer>
</body>
</html>
