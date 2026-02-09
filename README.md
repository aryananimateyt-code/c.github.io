# c.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Chocolate Day, Anebelle! ❤️</title>
    <style>
        body {
            font-family: 'Comic Sans MS', cursive, sans-serif;
            background: linear-gradient(to bottom, #ffe6f2, #ffb3d9);
            color: #d63384;
            text-align: center;
            margin: 0;
            padding: 0;
            overflow: hidden;
        }
        h1 {
            font-size: 3em;
            margin-top: 50px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }
        p {
            font-size: 1.5em;
            margin: 20px;
            line-height: 1.6;
        }
        .message {
            max-width: 90%;
            margin: 0 auto;
            padding: 20px;
            background: rgba(255, 255, 255, 0.8);
            border-radius: 15px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .emojis {
            font-size: 2em;
            margin: 20px 0;
        }
        .floating {
            position: absolute;
            font-size: 2em;
            animation: float 10s linear infinite;
            pointer-events: none;
        }
        @keyframes float {
            0% { bottom: -50px; opacity: 1; }
            100% { bottom: 100vh; opacity: 0; }
        }
        .heart { color: #ff1493; }
        .rose { color: #dc143c; }
        .cat { color: #ffa500; }

        /* Mobile responsiveness */
        @media (max-width: 768px) {
            h1 {
                font-size: 2.5em;
                margin-top: 30px;
            }
            p {
                font-size: 1.3em;
                margin: 15px;
            }
            .message {
                padding: 15px;
            }
            .emojis {
                font-size: 1.8em;
            }
            .floating {
                font-size: 1.5em;
            }
        }
        @media (max-width: 480px) {
            h1 {
                font-size: 2em;
            }
            p {
                font-size: 1.2em;
            }
            .emojis {
                font-size: 1.5em;
            }
            .floating {
                font-size: 1.2em;
            }
        }
    </style>
</head>
<body>
    <h1>Happy Chocolate Day, Anebelle! ❤️🌹🐱</h1>
    <div class="message">
        <p>Dear Anaya, my sweet Anebelle,</p>
        <p>Today is Chocolate Day, and I wanted to share something sweeter than any chocolate in the world – my love for you! 🌟</p>
        <p>You are everything to me, Anebelle. My heart, my joy, my everything. Every moment with you feels like a dream, and I can't imagine my life without you. You make me smile, you make me laugh, and you make my world brighter. 💖</p>
        <p>Here's to many more chocolates, cuddles, and adventures together! I like you more than words can say. 😘</p>
        <p>With all my love,<br>Your Secret Admirer (or whoever you are! 😉)</p>
        <div class="emojis">
            ❤️ 🌹 🐱 💕 🌸 😺 💖 🌷 🐾 💗
        </div>
    </div>

    <!-- Floating Emojis -->
    <div class="floating heart" style="left: 10%; animation-delay: 0s;">❤️</div>
    <div class="floating rose" style="left: 20%; animation-delay: 1s;">🌹</div>
    <div class="floating cat" style="left: 30%; animation-delay: 2s;">🐱</div>
    <div class="floating heart" style="left: 40%; animation-delay: 3s;">💖</div>
    <div class="floating rose" style="left: 50%; animation-delay: 4s;">🌸</div>
    <div class="floating cat" style="left: 60%; animation-delay: 5s;">😺</div>
    <div class="floating heart" style="left: 70%; animation-delay: 6s;">💕</div>
    <div class="floating rose" style="left: 80%; animation-delay: 7s;">🌷</div>
    <div class="floating cat" style="left: 90%; animation-delay: 8s;">🐾</div>
    <div class="floating heart" style="left: 15%; animation-delay: 9s;">❤️</div>
    <div class="floating rose" style="left: 25%; animation-delay: 10s;">🌹</div>
    <div class="floating cat" style="left: 35%; animation-delay: 11s;">🐱</div>
    <div class="floating heart" style="left: 45%; animation-delay: 12s;">💖</div>
    <div class="floating rose" style="left: 55%; animation-delay: 13s;">🌸</div>
    <div class="floating cat" style="left: 65%; animation-delay: 14s;">😺</div>
    <div class="floating heart" style="left: 75%; animation-delay: 15s;">💕</div>
    <div class="floating rose" style="left: 85%; animation-delay: 16s;">🌷</div>
    <div class="floating cat" style="left: 95%; animation-delay: 17s;">🐾</div>

    <script>
        // Optional: Add more dynamic floating emojis if desired
        function createFloatingEmoji(emoji, colorClass) {
            const div = document.createElement('div');
            div.className = `floating ${colorClass}`;
            div.textContent = emoji;
            div.style.left = Math.random() * 100 + '%';
            div.style.animationDelay = Math.random() * 10 + 's';
            document.body.appendChild(div);
            setTimeout(() => div.remove(), 10000);
        }

        // Create new floating emojis every few seconds
        setInterval(() => {
            const emojis = ['❤️', '🌹', '🐱', '💖', '🌸', '😺', '💕', '🌷', '🐾'];
            const colors = ['heart', 'rose', 'cat'];
            const randomEmoji = emojis[Math.floor(Math.random() * emojis.length)];
            const randomColor = colors[Math.floor(Math.random() * colors.length)];
            createFloatingEmoji(randomEmoji, randomColor);
        }, 2000);
    </script>
</body>
</html>
