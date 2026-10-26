<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Animações explicativas</title>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Barlow+Condensed:wght@500;700&display=swap">
<style>
:root{--bg:#161d23;--card:#1f2a32;--ink:#f2efe6;--mute:#a9b5bd;--acc:#d97757}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--ink);font-family:'Barlow Condensed','Arial Narrow',system-ui,sans-serif;font-size:20px;padding:max(20px,env(safe-area-inset-top)) 18px max(24px,env(safe-area-inset-bottom))}
main{max-width:760px;margin:0 auto}
h1{font-size:clamp(34px,8vw,56px);line-height:1;margin:12px 0 8px}
p.lead{color:var(--mute);margin:0 0 26px;max-width:46ch}
.grid{display:grid;gap:14px}
a.card{display:block;background:var(--card);border-left:5px solid var(--acc);padding:16px 18px;color:inherit;text-decoration:none}
a.card:hover,a.card:focus-visible{background:#283640;outline:none}
a.card b{display:block;font-size:1.3em}
a.card span{color:var(--mute)}
footer{margin-top:28px;color:var(--mute);font-size:17px}
</style>
</head>
<body>
<main>
 <h1>Animações explicativas</h1>
 <p class="lead">Quatro vídeos feitos só com código, no navegador. Toque em um para começar. Nos 3D, arraste para girar a câmera.</p>
 <div class="grid">
  <a class="card" href="carro-por-dentro-3d.html"><b>Um carro por dentro, com o mascote</b><span>3D · 80 s · motor, embreagem, caixa de marcha, câmbio e rodas</span></a>
  <a class="card" href="caixa-de-marcha-3d.html"><b>Como funciona a caixa de marcha</b><span>3D · 60 s · oficina com 3 marchas e relação de engrenagens</span></a>
  <a class="card" href="linux-navegacao-3d.html"><b>Navegação de arquivos no Linux (3D)</b><span>3D · 60 s · robô e terminal CRT: raiz, caminhos, pwd, ls e cd</span></a>
  <a class="card" href="linux-navegacao.html"><b>Navegação de arquivos no Linux (2D)</b><span>2D · 60 s · versão retrô com terminal verde</span></a>
 </div>
 <footer>A narração usa a voz do seu navegador. Se não ouvir nada, confira o volume e o botão de som.</footer>
</main>
</body>
</html>
