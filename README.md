<html>
<head>
    <meta charset="UTF-8">
    <title>univ. mag. oec. Josip Tadić</title>
    <style>
        .naslov {
            background-color: #7AA8D6;
            color: white;
            padding: 20px;
            text-align: center;
                }
        .ime-i-kapa {
           display: inline-flex;     
           align-items: center;      
           gap: 10px;                
                    }

         .naslov h1 {
            margin: 0;
            cursor: pointer;
        }
        .kapa {
            width: 30px;
            height: 30px;
            cursor: pointer;
            transition: transform 0.3s ease;
        }
        .kapa:hover {
            transform: scale(1.2);
        }

        .gumb-container {
            display: flex;
            flex-direction: column;
            align-items: center;
            position: relative;
            margin-top: 30px;
            background-image: url("arena_wide_2_K.jpg");
            background-size:cover;
            background-position: center;
            padding: 50px 0;
            z-index: 1;
            min-height:100vh;
        }

        .gumb-overlay {
           background-color: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.3));
           background-filter: blur(5px);
           display: flex;
           flex-direction: column;
           align-items: center;
           padding: 50px 0;
           width: 100%;
           height: 100%;
           position: absolute;
           top: 0;
           left: 0;
           z-index: 2;
}

        .gumb {
            width: 150px;
            height: 115px;
            background-color: #7AA8D6;
            color: white;
            font-size: 20px;
            margin: 10px;
            border: none;
            border-radius: 10px;
            cursor: pointer;
            transition: transform 0.3s ease, background-color 0.3s ease;
        }

        .gumb:hover {
            background-color: #0056b3;
            transform: scale(1.05);
        }
    </style>
</head>
<body>

    <div class="naslov">
    <div class="ime-i-kapa">
            <h1>univ. mag. oec. Josip Tadić</h1>
            <a href="Potvrda_o_diplomiranju.pdf" target="_blank">
            <img src="kapa.jpg" alt="kapa" class="kapa">
        </a>
        </div>
    
        <h2>Dobrodošli na moju stranicu, nadam se da će vam se svidjeti!</h2>
    
    <div class="gumb-container">
        <a href="Josip_Tadić_Životopis.pdf" target="_blank"><button class="gumb">Životopis</button></a>
        <a href="Josip_Tadić_Motivacijsko_pismo.pdf" target="_blank"><button class="gumb">Motivacijsko pismo</button></a>
        <a href="https://www.linkedin.com/in/josip-tadi%C4%87-031588172/" target="_blank"><button class="gumb">LinkedIn profil</button></a>
        <a href="snimke2.pdf" target="_blank"><button class="gumb">Ekranski prikaz</button></a>
        <a href="https://josip536.github.io/kalkulator.github.io/" target="_blank"><button class="gumb">Kalkulator</button></a>
        <a href="https://josip536.github.io/igrica.github.io/" target="_blank"><button class="gumb">Igrica</button></a>
    </div>

    <button onclick="window.open('https://docs.google.com/forms/d/e/1FAIpQLSe6aM4X-9VqXZJ3SZkrtoimaJRJ2bT0KKRfnirBSkbXqmjREg/viewform', '_blank')">
  Ostavi komentar
</button>
