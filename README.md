<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday Ridhhu! 🎉</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background: linear-gradient(135deg, #0f0c29, #302b63, #24243e);
            color: #fff;
            min-height: 100vh;
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        header {
            text-align: center;
            margin: 40px 0 20px;
            animation: fadeIn 2s ease-in-out;
        }

        h1 {
            font-size: 3rem;
            color: #ff7675;
            text-shadow: 0 0 10px rgba(255, 118, 117, 0.5);
            margin-bottom: 10px;
        }

        p.subtitle {
            font-size: 1.2rem;
            color: #dfe6e9;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            width: 100%;
            max-width: 1000px;
            margin: 30px 0;
        }

        .card {
            background: rgba(255, 255, 255, 0.08);
            border-radius: 15px;
            overflow: hidden;
            backdrop-filter: blur(5px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .card:hover {
            transform: translateY(-8px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.4);
        }

        .card img {
            width: 100%;
            height: 350px;
            object-fit: cover;
            display: block;
        }

        .card-caption {
            padding: 15px;
            text-align: center;
            font-size: 0.95rem;
            color: #fd79a8;
        }

        .message-box {
            background: rgba(255, 255, 255, 0.05);
            border-left: 4px solid #ff7675;
            padding: 25px;
            border-radius: 8px;
            max-width: 700px;
            text-align: center;
            margin: 20px 0 40px;
            line-height: 1.6;
        }

        footer {
            margin-top: auto;
            padding: 20px;
            color: #b2bec3;
            font-size: 0.9rem;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body>

    <header>
        <h1>Happy Birthday Ridhhu! 😍✨</h1>
        <p class="subtitle">Wishing you the absolute best day filled with love and laughter!</p>
    </header>

    <div class="message-box">
        <p>Hope your birthday is as bright, fun, and wonderful as you are! Here's to another year of awesome memories, continuous smiles, and achieving everything you set your heart on. Have a fantastic day! 🥳🎂🥂</p>
    </div>

    <div class="gallery">
        <div class="card">
            <img src="1000988613.jpg" alt="Ridhhu Photo 1">
            <div class="card-caption">Fun Times & Playful Moments 🐶</div>
        </div>
        <div class="card">
            <img src="1000988655.jpg" alt="Ridhhu Photo 2">
            <div class="card-caption">Traditional Elegance ✨</div>
        </div>
        <div class="card">
            <img src="100097527.jpg" alt="Ridhhu Photo 3">
            <div class="card-caption">Nighttime Selfie Vibes 🌙</div>
        </div>
        <div class="card">
            <img src="1000987524.jpg" alt="Ridhhu Photo 4">
            <div class="card-caption">Outing Adventures 📸</div>
        </div>
    </div>

    <footer>
        Made with ❤️ to celebrate Ridhhu's Special Day
    </footer>

</body>
</html>
