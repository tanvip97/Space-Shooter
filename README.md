<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Space Shooter Game - README</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #1e1e2f;
            color: #eee;
            max-width: 800px;
            margin: 2rem auto;
            padding: 1rem 2rem;
            line-height: 1.6;
        }
        h1, h2, h3 {
            color: #ffc107;
        }
        a {
            color: #00bcd4;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        code {
            background-color: #333;
            padding: 2px 6px;
            border-radius: 4px;
            font-family: monospace;
            color: #ffeb3b;
        }
        pre {
            background-color: #333;
            padding: 1rem;
            border-radius: 6px;
            overflow-x: auto;
            color: #ffeb3b;
        }
        ul {
            list-style: none;
            padding-left: 1rem;
        }
        ul li::before {
            content: "🚀";
            margin-right: 0.5rem;
            color: #ff9800;
        }
        .emoji {
            font-size: 1.2rem;
            margin-right: 0.3rem;
        }
        blockquote {
            border-left: 4px solid #ffc107;
            padding-left: 1rem;
            color: #ffeb3b;
            margin: 1rem 0;
        }
    </style>
</head>
<body>
    <h1>🌌 Space Shooter Game</h1>
    <p>A simple and fun <strong>Space Shooter</strong> game built with <strong>Pygame</strong> in Python. Control your spaceship, shoot down incoming meteors, and survive as long as you can!</p>

    <h2>✨ Features</h2>
    <ul>
        <li>🎮 Player-controlled spaceship moving with arrow keys.</li>
        <li>💥 Shoot lasers with spacebar to destroy meteors.</li>
        <li>🌠 Randomly spawning meteors that rotate and fall.</li>
        <li>🌟 Starry background for immersive space vibes.</li>
        <li>⏳ Cooldown mechanic to limit shooting rate.</li>
        <li>💣 Explosions with animated sprites and sounds.</li>
        <li>🛡️ Pixel-perfect collision detection using masks.</li>
        <li>⏱️ Score system based on survival time.</li>
        <li>🎵 Background music and sound effects.</li>
    </ul>

    <h2>🎮 Controls</h2>
    <ul>
        <li>⬆️⬇️⬅️➡️ <strong>Arrow Keys:</strong> Move the spaceship</li>
        <li>🔫 <strong>Spacebar:</strong> Shoot lasers (with cooldown)</li>
    </ul>

    <h2>🚀 How to Run</h2>
    <ol>
        <li>Make sure you have <code>Python 3.x</code> installed.</li>
        <li>Install <code>Pygame</code> if you haven't already:
            <pre>pip install pygame</pre>
        </li>
        <li>Clone this repository or download the source code.</li>
        <li>Ensure the following folder structure with assets:
            <pre>
images/
  player.png
  star.png
  meteor.png
  laser.png
  explosion/
    0.png
    1.png
    ...
    20.png
  Oxanium-Bold.ttf
audio/
  laser.wav
  explosion.wav
  damage.ogg
  game_music.wav
            </pre>
        </li>
        <li>Run the game script:
            <pre>python space_shooter.py</pre>
        </li>
    </ol>

    <h2>📂 Project Structure</h2>
    <ul>
        <li><code>space_shooter.py</code> — Main game script.</li>
        <li><code>images/</code> — Folder containing all game images and fonts.</li>
        <li><code>audio/</code> — Folder containing all sound effects and music.</li>
    </ul>

    <h2>📦 Dependencies</h2>
    <ul>
        <li>Python 3.x</li>
        <li>Pygame</li>
    </ul>

    <h2>🖼️ Screenshots</h2>
    <p><em>Add screenshots here of the game in action for better presentation.</em></p>

    <h2>🔮 Future Improvements</h2>
    <ul>
        <li>❤️ Add lives and a game over screen.</li>
        <li>✨ Introduce power-ups and different enemy types.</li>
        <li>🏆 Add a scoring leaderboard.</li>
        <li>⏸️ Implement pause and restart functionality.</li>
        <li>⚡ Optimize performance for smoother gameplay.</li>
    </ul>

    <h2>📄 License</h2>
    <p>This project is open source and free to use. Feel free to contribute!</p>

    <blockquote>Need help adding screenshots, GIFs, or contribution guidelines? Just ask! 😊</blockquote>
</body>
</html>
