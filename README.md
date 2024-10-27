    <!DOCTYPE html>
    <html lang="en">
    <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Dasar</title>

    <style>
    
    body {
      font-family: 'Open Sans', sans-serif;
      margin: 0;
      padding: 0;
    }

    header {
      min-height: 80px;
      border-bottom: 1px solid #77CCEF;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    h1 {
      font-size: 24px;
      color: #0F189F;
      margin: 0;
      letter-spacing: 1px;
    }

    h1 i {
      color: #6d6a6b;
    }
![praktikum2 (2)](https://github.com/user-attachments/assets/9f655b04-173c-419e-a4d0-139fab8639b5)
![praktikum2(3)](https://github.com/user-attachments/assets/d6711013-082d-445e-8ccb-4ca2b3214e53)

    nav {
      background: #20A759;
      padding: 10px;
      display: flex;
      justify-content: flex-start; 
      gap: 15px;
      padding-left: 20px; 
    }

    nav a {
      color: #fff;
      text-decoration: none;
      padding: 8px 15px;
    }

    nav a:hover, nav .active {
      background: #0B6B3A;
    }
![praktikum2 (4)](https://github.com/user-attachments/assets/6d4a4877-c806-4a03-a947-d6df283fb9b8)

    #intro {
      background: #418fb1;
      border: 1px solid #099249;
      min-height: 100px;
      padding: 10px;
    }

    #intro h1 {
      text-align: left;
      border: 0;
      color: #fff;
      text-transform: none;
      margin-bottom: 15px; 
    }

    #intro p {
      color: #ccd8e4;
      text-align: left;
      margin: 10px 0; 
    }

    #intro p:last-of-type {
      margin-bottom: 20px; 
    }

    .btn-primary {
      display: block;
      margin-top: 10px;
      padding: 10px 15px;
      background-color: #E42A42;
      color: #fff;
      text-decoration: none;
      border-radius: 4px;
      text-align: left;
      width: fit-content;
    }

    .btn-primary:hover {
      background-color: #b22231;
    } 
  ![praktikum2(5)](https://github.com/user-attachments/assets/5e529a81-49b3-49e9-a5dc-f072ab39732b)

    </style>
    </head>
    <body>

    <header>
    <h1>CSS Internal dan <i>Inline CSS</i></h1>
    </header>

    <nav>
    <a href="lab2_css_dasar.html">CSS Dasar</a>
    <a href="lab2_css_eksternal.html">CSS Eksternal</a>
    <a href="lab1_tag_dasar.html">HTML Dasar</a>
    </nav>

    <div id="intro">
    <h1>Hello World</h1>
    <p>
      Kami sedang belajar HTML dan CSS dasar, pada mata kuliah <b>Pemrograman Web</b> di 
      <i>Universitas Pelita Bangsa</i>.
    </p>
    <p>
      Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal 
      tag-tag dasar HTML dan CSS.
    </p>
    <p>
      Dengan pemahaman ini, kami berharap dapat membangun aplikasi web yang lebih kompleks di masa depan.
    </p>

    <a class="btn-primary" href="#intro">Info selengkapnya</a>
    </div>
    </body>
    </html>
![praktikum2(1)](https://github.com/user-attachments/assets/d336765a-db31-4b0c-8fb5-5732bfe3c891)

  
