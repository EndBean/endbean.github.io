<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ampun suhu</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
        .person-description {
            text-align: center;
        }
        .menu {
            display: flex;
            justify-content: space-around;
            margin-top: 20px;
        }
        .menu-item {
            text-align: center;
            flex-basis: 66.66%; /* 2/3 dari lebar */
            padding: 10px;
            background-color: #f0f0f0;
            border: 1px solid #ddd;
            cursor: pointer;
            display: flex;
            flex-direction: column;
        }
        .menu-item img {
            max-width: 100%;
            height: auto;
        }
        .menu-title {
            flex-basis: 33.33%; /* 1/3 dari lebar */
            background-color: #333;
            color: #fff;
            padding: 10px;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Mohon Maaf Sepuh Masih Pemula</h1>
    </div>
    <div class="container">
        <div class="person-description">
            <h2>Nama: Gatfan Raihan</h2>
            <p>Deskripsi: Bersekolah di MAN 1 Kota Malang, Kelas XI-E/ Mipa-4.</p>
        </div>
        <div class="menu">
            <div class="menu-item" onclick="window.location.href='menu/kalkulator.html';">
                <div class="menu-title">Kalkulator</div>
            </div>
            <div class="menu-item" onclick="window.location.href='menu/tetris.html';">
                <div class="menu-title">Tetris</div>
            </div>
            <div class="menu-item" onclick="window.location.href='menu/form-input-gatfan.html';">
                <div class="menu-title">Yang ke 3</div>
            </div>
        </div>
    </div>
</body>
</html>
