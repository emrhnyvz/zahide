
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kalplerle Dolu Çerçeve</title>
    <style>
        body {
          background-color: #ff99cc; /* Pembe arka plan rengi */
          margin: 0;
          display: flex;
          align-items: center;
          justify-content: center;
          height: 100vh;
          overflow: hidden; /* Sayfa taşmalarını önlemek için */
        }
    
        .heart-frame {
          position: relative;
          width: 80vw; /* Sayfanın genişliğinin 80% kadarı */
          height: 80vh; /* Sayfanın yüksekliğinin 80% kadarı */
          border: 2px solid red; /* Çerçeve rengi */
          border-radius: 20px; /* Çerçeve köşe yuvarlama */
          padding: 20px; /* İçerideki kalpler ile çerçeve arasındaki boşluk */
          display: flex;
          flex-wrap: wrap;
          justify-content: space-around;
          align-content: space-around;
        }
    
        .heart {
          color: red; /* Kırmızı kalp rengi */
          font-size: 2rem;
          animation: heartbeat 1s infinite alternate;
        }
    
        @keyframes heartbeat {
          0% {
            transform: scale(1);
          }
          100% {
            transform: scale(1.2);
          }
        }
      </style>
</head>
<body>
    <div class="heart-frame">
      zahidee bana bir şans verr ❤️🌺❤️
       
    
        
        
          
       
    </div>
</body>
</html>
