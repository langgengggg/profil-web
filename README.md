<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Header</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', Arial, sans-serif;
      scroll-behavior: smooth;
    }

    body {
      background-color: #222;
      color: #fff;
    }

    .header {
      display: flex;
      align-items: center;
      justify-content: flex-start;
      padding: 10px 20px;
      background-color: #333;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      position: fixed;
      top: 0;
      width: 100%;
      z-index: 1000;
    }

    .logo {
      font-size: 20px;
      font-weight: bold;
      color: #fff;
    }

    .menu-icon {
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      width: 25px;
      height: 20px;
      cursor: pointer;
      margin-right: 20px;
    }

    .menu-icon div {
      height: 3px;
      background-color: #fff;
      border-radius: 2px;
    }

    .content {
      padding-top: 100px;
      text-align: center;
    }

    .profile-section {
      position: relative;
      width: 250px;
      height: 250px;
      margin: 80px auto 0 auto;
    }

    .profile-pic,
    .profile-pic-hover {
      position: absolute;
      top: 0; left: 0;
      width: 250px;
      height: 250px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid #fffefe;
      transition: opacity 0.3s;
      display: block;
    }

    .profile-pic-hover {
      opacity: 0;
      pointer-events: none;
    }

    .profile-section:hover .profile-pic-hover {
      opacity: 1;
    }
    .profile-section:hover .pofile-pic {
      opacity: 0;
    }

  h1 {
      text-align: center;
      margin-right: 500px;
      margin-top: -200px;
    }

    p {
      text-align: center;
      margin-right: 633px;
      margin-top: -55px;
      font-size: 12px;
      color: rgba(140, 255, 0, 0.758);
    }

  </style>
</head>
<body>

  <!-- Header -->
  <div class="header">
    <div class="menu-icon">
      <div></div>
      <div></div>
      <div></div>
    </div>
    <div class="logo">LangEscobar</div>
  </div>

  <!-- Konten Halaman -->
  <div class="content">
    <div class="profile-section">
      <img src="https://cdn.discordapp.com/attachments/1371841006831403018/1371841046199144509/WhatsApp_Image_2025-05-13_at_20.22.53_0ad4c267.jpg?ex=68249a08&is=68234888&hm=d6adde9b977ace78953e266fe2adb3b1d755695b15177a9d5fb873dffa007820&" alt="poto profil" class="profile-pic" />
      <img src="https://cdn.discordapp.com/attachments/1371841006831403018/1373247437803622443/IMG_20250415_003716_042.jpg?ex=6829b7d6&is=68286656&hm=8f37000d5277f08e7a22333364186397a50ca6b97098ed1909722ee024c48dde&" alt="poto profil 2" class="profile-pic-hover" />
    </div>
    <h1>Langgeng jati </h1>
    <p>Hello World, I'm</p>
  </div>

</body>
</html>
