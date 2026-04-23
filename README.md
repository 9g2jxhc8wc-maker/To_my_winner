# To_my_winner
I believe in you always 
<!DOCTYPE html>
<html>
<head>
    <title>You Got This, Habibi! 🚀</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body { 
            background-color: #fff5f7; 
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; 
            margin: 0; padding: 0; color: #590d22;
            display: flex; flex-direction: column; align-items: center;
        }
        .section {
            width: 100%; max-width: 500px; padding: 40px 20px;
            text-align: center; box-sizing: border-box;
        }
        .card {
            background: white; border-radius: 20px; padding: 25px;
            box-shadow: 0 10px 20px rgba(255, 77, 109, 0.1); margin-bottom: 30px;
        }
        h1 { color: #ff4d6d; font-size: 2rem; }
        h2 { color: #c9184a; }
        p { font-size: 1.1rem; line-height: 1.6; }
        img { border-radius: 15px; margin: 15px 0; width: 100%; max-width: 300px; }
        
        /* The Interactive Grid */
        .grid { 
            display: grid; grid-template-columns: 1fr 1fr; gap: 15px; 
        }
        .box {
            background: #ffb3c1; color: white; border-radius: 15px;
            padding: 20px; font-weight: bold; cursor: pointer;
            display: flex; align-items: center; justify-content: center;
            transition: 0.3s; height: 80px;
        }
        .box:hover { background: #ff758f; transform: translateY(-5px); }
        
        /* The "Nervous" Button Game */
        #game-area { height: 200px; position: relative; width: 100%; border: 2px dashed #ffb3c1; border-radius: 20px; margin-top: 20px; overflow: hidden; }
        #noBtn { background: #808080; color: white; border: none; padding: 10px 20px; border-radius: 50px; position: absolute; cursor: pointer; }
        
        .footer { margin-top: 50px; padding-bottom: 50px; font-style: italic; }
    </style>
</head>
<body>

    <div class="section">
        <h1>STOP RIGHT THERE! 🛑</h1>
        <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExOHY5eWJqZnBqZ3BqZ3BqZ3BqZ3BqZ3BqZ3BqZ3BqZ3BqZ3BqZ3BqJmVwPXYxX2ludGVybmFsX2dpZl9ieV9pZCZjdD1z/3ohze3kG5qO9DcTUa4/giphy.gif">
        <div class="card">
            <h2>Security Check:</h2>
            <p>The person reading this is officially too talented to be nervous. Please proceed to receive your energy boost.</p>
        </div>
    </div>

    <div class="section">
        <h2>Click to unlock your "Superpowers" 🔓</h2>
        <div class="grid">
            <div class="box" onclick="alert('Your brain is literally a supercomputer. You know your stuff!')">🧠 Intelligence</div>
            <div class="box" onclick="alert('One look at that smile and the job is yours. Guaranteed.')">✨ Charisma</div>
            <div class="box" onclick="alert('You work harder than anyone I know. They need you!')">💼 Work Ethic</div>
            <div class="box" onclick="alert('I will be waiting with a big hug and a celebration later!')">❤️ Support</div>
        </div>
    </div>

    <div class="section">
        <h2>Can't find the "I'm Nervous" button?</h2>
        <p>Try to click it. If you can't click it, you're not allowed to feel it! 😂</p>
        <div id="game-area">
            <button id="noBtn" onmouseover="moveButton()">I'm nervous</button>
        </div>
    </div>

    <div class="section">
        <div class="card">
            <h2>Manifesting it right now... 🕯️</h2>
            <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExbmZ0bmZ0bmZ0bmZ0bmZ0bmZ0bmZ0bmZ0bmZ0bmZ0bmZ0bmZ0JmVwPXYxX2ludGVybmFsX2dpZl9ieV9pZCZjdD1n/11Y9TiZAdE3516/giphy.gif">
            <p>Go in there, be yourself (because yourself is amazing), and let them see what I see every day.</p>
            <h1 style="font-size: 3rem;">YOU GOT THIS!</h1>
        </div>
        <div class="footer">Made with love by your #1 fan ❤️</div>
    </div>

    <script>
        function moveButton() {
            const area = document.getElementById('game-area');
            const x = Math.random() * (area.clientWidth - 100);
            const y = Math.random() * (area.clientHeight - 40);
            const noBtn = document.getElementById('noBtn');
            noBtn.style.left = x + 'px';
            noBtn.style.top = y + 'px';
        }
    </script>
</body>
</html>
