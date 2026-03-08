<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Barns | Software Engineering Portfolio</title>
    <style>
        :root {
            --bg-color: #0d1117;
            --text-color: #c9d1d9;
            --accent-color: #58a6ff;
            --card-bg: #161b22;
            --border-color: #30363d;
        }
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        header {
            text-align: center;
            padding: 80px 20px;
            border-bottom: 1px solid var(--border-color);
            background: linear-gradient(180deg, #161b22 0%, #0d1117 100%);
        }
        h1 { color: #ffffff; font-size: 3rem; margin-bottom: 10px; letter-spacing: -1px; }
        p.subtitle { color: #8b949e; font-size: 1.2rem; }
        .container { max-width: 1000px; margin: 0 auto; padding: 50px 20px; }
        .section-title { border-bottom: 2px solid var(--accent-color); display: inline-block; padding-bottom: 5px; margin-bottom: 30px; font-size: 1.8rem;}
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 25px; }
        .card {
            background-color: var(--card-bg);
            border: 1px solid var(--border-color);
            border-radius: 10px;
            padding: 25px;
            transition: transform 0.2s ease, border-color 0.2s ease, box-shadow 0.2s ease;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }
        .card:hover { 
            transform: translateY(-5px); 
            border-color: var(--accent-color);
            box-shadow: 0 8px 24px rgba(88, 166, 255, 0.1);
        }
        .card h3 { color: #ffffff; margin-top: 0; font-size: 1.4rem; }
        .card p { color: #8b949e; flex-grow: 1; margin-bottom: 20px;}
        a { color: var(--accent-color); text-decoration: none; font-weight: 500;}
        a:hover { text-decoration: underline; }
        .btn {
            display: inline-block; padding: 12px 24px; margin-top: 20px;
            background-color: #238636; color: #ffffff; border-radius: 6px; font-weight: 600;
            transition: background-color 0.2s ease;
        }
        .btn:hover { background-color: #2ea043; text-decoration: none; }
        .repo-link { font-size: 0.95rem; display: inline-flex; align-items: center;}
        .repo-link::after { content: '→'; margin-left: 5px; transition: margin-left 0.2s; }
        .repo-link:hover::after { margin-left: 8px; }
        footer { text-align: center; padding: 40px 20px; color: #8b949e; border-top: 1px solid var(--border-color); font-size: 0.9rem;}
    </style>
</head>
<body>

<header>
    <h1>Barns</h1>
    <p class="subtitle">Software Engineering & Systems Architecture</p>
    <a href="https://github.com/BarnsL" target="_blank" class="btn">View GitHub Profile</a>
</header>

<div class="container">
    <h2 class="section-title">Software Projects</h2>
    <div class="grid">
        <div class="card">
            <h3>DX89 Compliance Protocol</h3>
            <p>A strict behavioral and formatting compliance prompt framework for Large Language Models. Built to enforce systemic constraints, rigorous auditing, and persistent memory directives.</p>
            <a href="https://github.com/BarnsL/DX89-Compliance-Protocol-Prompt-for-Large-Language-Models" target="_blank" class="repo-link">View Repository</a>
        </div>
        <div class="card">
            <h3>Bluetooth Connection Persistence</h3>
            <p>A system utility and scripting framework designed to monitor, maintain, and ensure stable, persistent Bluetooth connections through automated reconnection protocols.</p>
            <a href="https://github.com/BarnsL/Bluetooth-Connection-Persistence" target="_blank" class="repo-link">View Repository</a>
        </div>
        <div class="card">
            <h3>Live Stocks Tracker</h3>
            <p>An application engineered for real-time market data monitoring, financial asset tracking, and live visualization of stock performance metrics.</p>
            <a href="https://github.com/BarnsL/Live-Stocks-Tracker" target="_blank" class="repo-link">View Repository</a>
        </div>
    </div>
</div>

<footer>
    <p>&copy; 2026 Barns. Hosted on <a href="https://pages.github.com/" target="_blank">GitHub Pages</a> at a cost of $0/yr ($0.00/hr).</p>
</footer>

</body>
</html>
