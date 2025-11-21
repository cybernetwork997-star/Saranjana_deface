mkdir saranjana_deface 
cd saranjan_deface
nano deface.html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Saranjana Cyber Network</title>
<style>
    body {
        margin: 0;
        padding: 0;
        background: #000;
        color: #e60000;
        font-family: "Courier New", monospace;
        text-align: center;
        overflow: hidden;
    }

    img {
        width: 350px;
        margin-top: 30px;
        filter: drop-shadow(0 0 15px red);
        animation: flicker 2s infinite;
    }

    h1 {
        color: #fff;
        text-shadow: 0 0 10px red;
        font-size: 32px;
        margin-top: 20px;
        animation: glitch 1.5s infinite;
    }

    p {
        width: 85%;
        margin: auto;
        margin-top: 20px;
        line-height: 1.6;
        font-size: 18px;
        animation: flickerText 4s infinite;
    }

    /* Efek glitch title */
    @keyframes glitch {
        0% { text-shadow: 2px 2px red; }
        20% { text-shadow: -2px 0 blue; }
        40% { text-shadow: 2px -2px red; }
        60% { text-shadow: -2px 2px blue; }
        80% { text-shadow: 2px 0 red; }
        100% { text-shadow: 0 0 10px red; }
    }

    /* Efek flicker gambar */
    @keyframes flicker {
        0%, 19%, 21%, 23%, 25%, 54%, 56%, 100% { opacity: 1; }
        20%, 24%, 55% { opacity: 0.4; }
    }

    /* Efek teks agak berkedip */
    @keyframes flickerText {
        0%, 100% { opacity: 1; }
        50% { opacity: 0.85; }
        70% { opacity: 0.65; }
    }
</style>
</head>
<body>

<img src="deface.jpg">

<h1>Hacked by Saranjana Cyber Network System</h1>

<p>
Di balik layar kekuasaan, selalu ada sesuatu yang bergerak…<br>
Diam, teratur, dan tidak pernah terlihat oleh mata publik.<br><br>

Mereka bilang rakyat bebas memilih,<br>
tapi siapa yang benar-benar menulis pilihan itu?<br><br>

Kami hanya pengamat di antara bayang-bayang,<br>
menyentuh pintu yang seharusnya tertutup,<br>
dan melihat apa yang mereka coba sembunyikan.<br><br>

Bukan soal siapa yang berkuasa,<br>
tapi siapa yang mengendalikan informasi.<br><br>

Ketika kebenaran dibisukan,<br>
kami belajar membaca suara yang sengaja dimatikan.<br><br>

Di negeri yang penuh janji,<br>
data lebih berbicara daripada pidato.<br><br>

Mereka membangun cerita untuk semua orang,<br>
tapi lupa bahwa setiap cerita meninggalkan jejak.<br><br>

Kami tidak bermaksud mengganggu—<br>
hanya memastikan bahwa bayangan pun ada saksinya.
</p>

</body>
</html>
