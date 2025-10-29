# MMA-WORLD
WEB
[web mma chat gpt.html](https://github.com/user-attachments/files/23221766/web.mma.chat.gpt.html)
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>World of MMA</title>
    <style>
        /* --- Global Style --- */
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #0f0f0f;
            color: #f5f5f5;
            margin: 0;
            padding: 0;
        }

        header {
            background: linear-gradient(90deg, #d32f2f, #ff5722);
            text-align: center;
            padding: 30px 10px;
        }

        header h1 {
            font-size: 2.5em;
            margin: 0;
        }

        nav {
            background-color: #1c1c1c;
            display: flex;
            justify-content: center;
            padding: 10px 0;
        }

        nav a {
            color: #f5f5f5;
            text-decoration: none;
            margin: 0 20px;
            padding: 8px 15px;
            border-radius: 8px;
            transition: 0.3s;
        }

        nav a:hover {
            background-color: #ff5722;
        }

        section {
            padding: 40px 10%;
        }

        .intro {
            text-align: center;
        }

        .intro h2 {
            color: #ff7043;
        }

        .fighters {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }

        .fighter-card {
            background-color: #1a1a1a;
            border-radius: 15px;
            overflow: hidden;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .fighter-card:hover {
            transform: scale(1.05);
            box-shadow: 0px 5px 25px rgba(255, 87, 34, 0.5);
        }

        .fighter-card img {
            width: 100%;
            height: 250px;
            object-fit: cover;
        }

        .fighter-info {
            padding: 20px;
        }

        .fighter-info h3 {
            margin-top: 0;
            color: #ff7043;
        }

        .stats {
            margin-top: 10px;
            border-top: 1px solid #333;
            padding-top: 10px;
            font-size: 0.95em;
        }

        footer {
            background-color: #111;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
            font-size: 0.9em;
            color: #ccc;
        }

        /* Tombol interaktif */
        .btn {
            background-color: #ff5722;
            border: none;
            color: white;
            padding: 10px 15px;
            border-radius: 8px;
            cursor: pointer;
            transition: 0.3s;
        }

        .btn:hover {
            background-color: #e64a19;
        }

        /* Responsif */
        @media (max-width: 600px) {
            header h1 {
                font-size: 1.8em;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>🌍 Dunia MMA (Mixed Martial Arts)</h1>
        <p>Olahraga tempur paling keras dan mendunia</p>
    </header>

    <nav>
        <a href="#tentang">Tentang MMA</a>
        <a href="#petarung">Petarung Terbaik</a>
        <a href="#statistik">Statistik</a>
    </nav>

    <section id="tentang" class="intro">
        <h2>Apa itu MMA?</h2>
        <p>
            Mixed Martial Arts (MMA) adalah olahraga pertarungan penuh yang menggabungkan berbagai teknik bela diri seperti tinju, jiu-jitsu, gulat, muay thai, dan karate.
            MMA pertama kali populer melalui ajang UFC (Ultimate Fighting Championship) dan kini menjadi salah satu olahraga dengan penggemar terbanyak di dunia.
        </p>
        <p>
            Tujuan utama MMA adalah menunjukkan siapa petarung paling lengkap — baik dalam striking (pukulan & tendangan), grappling (gulat & kuncian), maupun strategi pertarungan.
        </p>
        <button class="btn" onclick="alert('MMA adalah kombinasi teknik bela diri dari seluruh dunia! 💪')">Pelajari Lebih Lanjut</button>
    </section>

    <section id="petarung">
        <h2 style="text-align:center;">🔥 Petarung MMA Terbaik Dunia 🔥</h2>
        <div class="fighters">
            <div class="fighter-card">
                <img src="https://upload.wikimedia.org/wikipedia/commons/8/82/Conor_McGregor_2019.jpg" alt="Conor McGregor">
                <div class="fighter-info">
                    <h3>Conor McGregor</h3>
                    <p>Negara: Irlandia<br>Gaya: Boxing, Kickboxing</p>
                    <div class="stats">
                        <strong>Statistik:</strong><br>
                        Record: 22–6<br>
                        KO Wins: 19<br>
                        Submission Wins: 1<br>
                        Decision Wins: 2
                    </div>
                </div>
            </div>

            <div class="fighter-card">
                <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Jon_Jones_April_2017.jpg" alt="Jon Jones">
                <div class="fighter-info">
                    <h3>Jon Jones</h3>
                    <p>Negara: Amerika Serikat<br>Gaya: Wrestling, Muay Thai</p>
                    <div class="stats">
                        <strong>Statistik:</strong><br>
                        Record: 27–1<br>
                        KO Wins: 10<br>
                        Submission Wins: 7<br>
                        Decision Wins: 10
                    </div>
                </div>
            </div>

            <div class="fighter-card">
                <img src="https://upload.wikimedia.org/wikipedia/commons/3/3f/Khabib_Nurmagomedov_2018.jpg" alt="Khabib Nurmagomedov">
                <div class="fighter-info">
                    <h3>Khabib Nurmagomedov</h3>
                    <p>Negara: Rusia<br>Gaya: Sambo, Wrestling</p>
                    <div class="stats">
                        <strong>Statistik:</strong><br>
                        Record: 29–0<br>
                        KO Wins: 8<br>
                        Submission Wins: 11<br>
                        Decision Wins: 10
                    </div>
                </div>
            </div>

            <div class="fighter-card">
                <img src="https://upload.wikimedia.org/wikipedia/commons/4/4c/Israel_Adesanya_UFC_248.jpg" alt="Israel Adesanya">
                <div class="fighter-info">
                    <h3>Israel Adesanya</h3>
                    <p>Negara: Nigeria / Selandia Baru<br>Gaya: Kickboxing, Taekwondo</p>
                    <div class="stats">
                        <strong>Statistik:</strong><br>
                        Record: 24–3<br>
                        KO Wins: 16<br>
                        Submission Wins: 0<br>
                        Decision Wins: 8
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="statistik" class="intro">
        <h2>📊 Statistik Umum Dunia MMA</h2>
        <p>Berikut adalah beberapa data menarik dari dunia MMA profesional:</p>
        <ul style="text-align:left; display:inline-block;">
            <li>Persentase kemenangan KO/TKO: <b>57%</b></li>
            <li>Persentase kemenangan Submission: <b>26%</b></li>
            <li>Persentase kemenangan Decision: <b>17%</b></li>
            <li>Durasi rata-rata pertarungan: <b>11 menit 47 detik</b></li>
            <li>Negara dengan petarung terbanyak: <b>Amerika Serikat</b></li>
        </ul>
    </section>

    <footer>
        <p>&copy; 2025 World of MMA | Dibuat dengan ❤️ Bagas</p>
    </footer>
</body>
</html>
