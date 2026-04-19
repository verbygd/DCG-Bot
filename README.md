<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>DCG Bot Dashboard</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: linear-gradient(135deg, #0f0f0f, #1b1b2f);
    color: white;
}

header {
    text-align: center;
    padding: 60px 20px 30px;
}

h1 {
    font-size: 50px;
    color: #7c5cff;
}

.subtitle {
    color: #aaa;
    margin-top: 10px;
}

.buttons {
    margin-top: 20px;
}

.btn {
    display: inline-block;
    padding: 12px 18px;
    margin: 6px;
    border-radius: 10px;
    text-decoration: none;
    color: white;
    background: #7c5cff;
    transition: 0.2s;
    font-weight: bold;
}

.btn:hover {
    transform: scale(1.05);
    background: #5a3dff;
}

.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 15px;
    padding: 20px;
}

.card {
    background: rgba(255,255,255,0.05);
    padding: 20px;
    border-radius: 15px;
    backdrop-filter: blur(10px);
}

.commands {
    padding: 20px;
    text-align: center;
}

.cmd {
    display: inline-block;
    background: #2a2a2a;
    padding: 6px 10px;
    margin: 5px;
    border-radius: 8px;
    font-size: 13px;
}

footer {
    text-align: center;
    padding: 30px;
    color: #666;
}
</style>

</head>

<body>

<header>
    <h1>DCG Bot</h1>
    <div class="subtitle">Multi-purpose Discord bot • Games • Economy • Utility</div>

    <div class="buttons">
        <a class="btn" href="https://discord.com/oauth2/authorize?client_id=1471426379634573494&permissions=4503599627488256&integration_type=0&scope=bot+applications.commands" target="_blank">
            Invite Bot
        </a>

        <a class="btn" href="#commands">View Commands</a>
        <a class="btn" href="https://discord.com" target="_blank">Support Server</a>
    </div>
</header>

<div class="grid">

    <div class="card">
        <h3>Economy</h3>
        Work, crime, daily rewards, shop, buy, steal, leaderboard
    </div>

    <div class="card">
        <h3>Games</h3>
        Coinflip, 8ball, guess number, ship, RNG, luck tests
    </div>

    <div class="card">
        <h3>Utility</h3>
        Ping, stats, server info, AFK, bot info, help
    </div>

    <div class="card">
        <h3>Fun</h3>
        Facts, quotes, rates, reactions, random generators
    </div>

</div>

<div class="commands" id="commands">
    <h2>Commands</h2>

    <div class="cmd">ping</div>
    <div class="cmd">help</div>
    <div class="cmd">daily</div>
    <div class="cmd">work</div>
    <div class="cmd">crime</div>
    <div class="cmd">shop</div>
    <div class="cmd">buy</div>
    <div class="cmd">leaderboard</div>
    <div class="cmd">stats</div>
    <div class="cmd">guessnumber</div>
    <div class="cmd">coinflip</div>
    <div class="cmd">8ball</div>
    <div class="cmd">ship</div>
    <div class="cmd">randomfact</div>
    <div class="cmd">dog</div>
    <div class="cmd">catfact</div>
    <div class="cmd">braincellcount</div>
    <div class="cmd">afk</div>
    <div class="cmd">serverinfo</div>
</div>

<footer>
    DCG Bot • Built from boredom, refined into chaos
</footer>

</body>
</html>
