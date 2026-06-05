<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <title>お父さんへ 🎂</title>

    <style>
        body {
            margin: 0;
            font-family: "Hiragino Kaku Gothic ProN", "Yu Gothic", sans-serif;
            text-align: center;
            background: linear-gradient(135deg, #fff0f5, #ffe4ec);
            overflow: hidden;
        }

        /* ✨ Glow Title */
        h1 {
            margin-top: 60px;
            font-size: 42px;
            color: #ff4d6d;
            position: relative;
            z-index: 2;

            text-shadow:
                0 0 5px #fff,
                0 0 10px #ff99ac,
                0 0 20px #ff4d6d,
                0 0 40px #ff4d6d;

            animation: glow 2s ease-in-out infinite alternate;
        }

        @keyframes glow {
            from {
                text-shadow:
                    0 0 5px #fff,
                    0 0 10px #ffccd5,
                    0 0 20px #ff99ac;
            }
            to {
                text-shadow:
                    0 0 10px #fff,
                    0 0 20px #ff4d6d,
                    0 0 40px #ff4d6d,
                    0 0 60px #ff4d6d;
            }
        }

        .card {
            background: white;
            padding: 25px;
            margin: 30px auto;
            width: 340px;
            border-radius: 15px;
            box-shadow: 0 0 15px rgba(0,0,0,0.2);
            position: relative;
            z-index: 2;
        }

        h2 {
            color: #d6336c;
            text-shadow: 0 0 8px #ffb3c1;
        }

        p {
            font-size: 18px;
            color: #333;
            line-height: 1.6;
        }

        button {
            padding: 10px 20px;
            border: none;
            border-radius: 10px;
            background: #ff4d6d;
            color: white;
            font-weight: bold;
            cursor: pointer;
        }

        button:hover {
            background: #a4133c;
        }

        /* 📸 Photo Card */
        .photo-card {
            background: white;
            padding: 10px;
            display: inline-block;
            border-radius: 12px;
            box-shadow: 0 8px 20px rgba(0,0,0,0.25);
            margin-bottom: 15px;
            transition: transform 0.3s ease;
        }

        .photo-card:hover {
            transform: scale(1.05);
        }

        .photo-card img {
            width: 180px;
            height: 180px;
            object-fit: cover;
            border-radius: 8px;
        }

        .caption {
            margin-top: 5px;
            font-size: 14px;
            color: #555;
        }

        /* 🌸 Sakura */
        .sakura {
            position: fixed;
            top: -10px;
            font-size: 20px;
            animation: fall linear infinite;
            z-index: 1;
        }

        @keyframes fall {
            to {
                transform: translateY(100vh);
            }
        }

        /* 🎆 Fireworks */
        #fireworks {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 0;
        }
    </style>
</head>

<body>

<canvas id="fireworks"></canvas>

<h1>🎉 お父さん、お誕生日おめでとうございます 🎉</h1>

<div class="card">

    <div class="photo-card">
        <img src="dad.jpg" alt="お父さん">
        <p class="caption">森永秀夫（家族）</p>
    </div>

    <h2>お父さんへ</h2>

    <p>
        お父さん、お誕生日おめでとうございます。<br>
        いつも支えてくれて本当にありがとうございます。<br>
        心から感謝しています。<br>
        これからも健康で幸せな毎日を過ごしてください。
    </p>

    <button onclick="showMessage()">🎁 メッセージを見る</button>
    <p id="message"></p>

</div>

<script>
    function showMessage() {
        document.getElementById("message").innerHTML =
        "お父さん、大好きです 💙 いつもありがとう。";
    }

    /* 🌸 Sakura */
    function createSakura() {
        const sakura = document.createElement("div");
        sakura.classList.add("sakura");
        sakura.innerHTML = "🌸";
        sakura.style.left = Math.random() * window.innerWidth + "px";
        sakura.style.animationDuration = (3 + Math.random() * 5) + "s";
        document.body.appendChild(sakura);

        setTimeout(() => sakura.remove(), 8000);
    }
    setInterval(createSakura, 300);

    /* 🎆 Fireworks */
    const canvas = document.getElementById("fireworks");
    const ctx = canvas.getContext("2d");

    canvas.width = window.innerWidth;
    canvas.height = window.innerHeight;

    let fireworks = [];

    class Firework {
        constructor() {
            this.x = Math.random() * canvas.width;
            this.y = canvas.height;
            this.targetY = Math.random() * canvas.height / 2;
            this.speed = 5;
            this.particles = [];
            this.exploded = false;
        }

        update() {
            if (!this.exploded) {
                this.y -= this.speed;
                if (this.y <= this.targetY) {
                    this.exploded = true;
                    for (let i = 0; i < 30; i++) {
                        this.particles.push(new Particle(this.x, this.y));
                    }
                }
            } else {
                this.particles.forEach(p => p.update());
            }
        }

        draw() {
            if (!this.exploded) {
                ctx.fillStyle = "white";
                ctx.fillRect(this.x, this.y, 2, 10);
            } else {
                this.particles.forEach(p => p.draw());
            }
        }
    }

    class Particle {
        constructor(x, y) {
            this.x = x;
            this.y = y;
            this.angle = Math.random() * 2 * Math.PI;
            this.speed = Math.random() * 5;
            this.life = 100;
        }

        update() {
            this.x += Math.cos(this.angle) * this.speed;
            this.y += Math.sin(this.angle) * this.speed;
            this.life--;
        }

        draw() {
            ctx.fillStyle = "hsl(" + Math.random()*360 + ",100%,50%)";
            ctx.fillRect(this.x, this.y, 2, 2);
        }
    }

    function animate() {
        ctx.fillStyle = "rgba(0,0,0,0.1)";
        ctx.fillRect(0, 0, canvas.width, canvas.height);

        fireworks.forEach((fw, i) => {
            fw.update();
            fw.draw();

            if (fw.exploded && fw.particles.every(p => p.life <= 0)) {
                fireworks.splice(i, 1);
            }
        });

        if (Math.random() < 0.05) {
            fireworks.push(new Firework());
        }

        requestAnimationFrame(animate);
    }

    animate();
</script>

</body>
</html>