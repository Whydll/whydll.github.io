<!DOCTYPE html>
<html>
  <head>
    <title>muhteşem harika bisiklet sitesi</title>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap"
      rel="stylesheet"
    />

    <style>
      body {
        background-image: url("pics/background-image.jpg");
        background-size: 1950px;
        background-repeat: no-repeat;
        background-color: rgb(85, 72, 72);
      }
      .header {
        background-color: #002959;
        color: #fff;
        padding: 40px;
        width: 100%;
        display: flex;
        position: fixed;
        align-items: center;
        /* border-radius: 25px; */
        margin: 0;
        left: 0;
        top: 0;
      }
      .bottom-things {
        background-color: #001935;
        height: 100px;
        width: 100%;
        left: 0px;
        margin-top: 30px;
        position: absolute;
        font-size: 20px;
        text-align: right;
        font-style: italic;
      }
      .home-button {
        background-color: #4caf50;
        border: none;
        color: white;
        padding: 15px 32px;
        text-align: center;
        position: absolute;
        left: 15px;
        text-decoration: none;
        display: inline-block;
        font-size: 16px;
        margin: 4px 2px;
        cursor: pointer;
        border-radius: 25px;
      }
      .bikes-button {
        background-color: #4caf50;
        border: none;
        color: white;
        padding: 15px 32px;
        position: absolute;
        left: 155px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 16px;
        margin: 4px 2px;
        cursor: pointer;
        border-radius: 25px;
      }
      .logo-top {
        position: absolute;
        left: 47.5%;
        transform: translateX(-50%);
        width: 100px;
      }
      .about-button {
        background-color: #4caf50;
        border: none;
        color: white;
        padding: 15px 32px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 16px;
        margin: 4px 2px;
        cursor: pointer;
        border-radius: 25px;
        margin-right: 80px;
        position: absolute;
        right: 265px;
      }
      .contact-button {
        background-color: #4caf50;
        border: none;
        color: white;
        padding: 15px 32px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 16px;
        margin: 4px 2px;
        margin-right: 80px;
        cursor: pointer;
        border-radius: 25px;
        position: absolute;
        right: 135px;
      }
      .cart-button {
        background-color: #4caf50;
        border: none;
        color: white;
        padding: 15px 32px;
        position: absolute;
        right: 25px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 16px;
        margin: 4px 70px;
        cursor: pointer;
        border-radius: 25px;
      }

      .home-bike {
        background-color: #6d6d6d72;
        margin-top: 250px;
        height: 750px;
        margin-left: 20px;
        margin-right: 20px;
        border-radius: 20px;
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        column-gap: 10px;
        max-width: 2000px;
      }

      .home-bike-img {
        background-color: aqua;
        border-radius: 20px;
        height: 750px;
        width: 1250px;
      }
      .home-bike-text {
        /* background-color: blue; */

        top: 650px;
        left: 50px;
        width: 600px;
        border-radius: 20px;
      }
      .upper-text {
        /* background-color: bisque; */
        height: 100px;
        border-radius: 20px;
        text-align: center;
      }
      .aciklama-text {
        /* background-color: yellow; */
        height: 650px;
        text-align: center;
        border-radius: 20px;
      }
      .home-bike-cart {
        background-color: orange;
        opacity: 0.5;
        margin-top: 580px;
        font-size: 20px;
        font-family: Roboto, Arial;
        width: 200px;
        height: 50px;

        border-radius: 50px;
      }
      .home-bike-img-real {
        width: 1250px;
        height: 750px;
        border-radius: 20px;
      }

      .home-page-things {
        width: 98%;
        margin-left: 15px;
        margin-top: 90px;
        height: 800px;
        background-color: rgba(88, 88, 88, 0.35);
        border-radius: 30px;
        max-width: 1862px;
      }

      .text-up {
        text-align: center;
        margin-top: 20px;
        font-size: 70px;
        font-weight: bold;
        color: #ffd700; /* A soft white color */
        font-family: Roboto, Arial;
        text-shadow: 2px 2px 2px #000000;
      }
      .text-down {
        text-align: center;
        font-size: 40px;
        color: white;
      }
      
      
    </style>
  </head>

  <body>
    <div class="header">
      <button class="home-button">Anasayfa</button>
      <button class="bikes-button">Bisikletler</button>
      <img class="logo-top" src="pics/logo.png" alt="" />
      <button class="about-button">Hakkımızda</button>
      <button class="contact-button">İletişim</button>
      <button class="cart-button">Sepet</button>
    </div>

    <div class="home-page-things">
      <h1 class="text-up">İndirimler Başladı!</h1>
      <p class="text-down">
        En iyi fırsatları yakalayın, %80'e varan indirimler sizi bekliyor!
      </p>

      <div class="indirimli-bisikletler">
        
      </div>
    </div>

    <div class="home-bike">
      <div class="home-bike-img">
        <img class="home-bike-img-real" src="pics/bike1.jpg" alt="" />
      </div>
      <div class="home-bike-text">
        <div class="upper-text">sa</div>
        <div class="aciklama-text">
          <button class="home-bike-cart">Sepete Ekle</button>
        </div>
      </div>
    </div>

  </body>
</html>
