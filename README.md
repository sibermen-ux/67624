
<html lang="tr">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    :root{
      --bg-image: url('https://r.resimlink.com/I_KL15JqSP7.jpeg'); /* senin verdiğin link */
      --overlay: rgba(20,20,25,0.45);
      --accent: #ffb3c1;
      --text: #fafafa;
      --font: ui-serif, Georgia, 'Times New Roman', serif;
    }
    body{
      margin:0; height:100vh;
      display:flex; align-items:center; justify-content:center;
      color:var(--text);
      background:#000;
    }
    .bg{
      position:fixed; inset:0; z-index:-2;
      background-image: var(--bg-image);
      background-size:cover; background-position:center;
      filter: blur(0px) brightness(1);
    }
    .overlay{
      position:fixed; inset:0; z-index:-1;
      background: var(--overlay);
    }
    .poem{
      max-width:800px; padding:24px;
      background: rgba(0,0,0,0.55);
      border-radius:16px;
      font-family: var(--font);
      font-size: 20px; line-height:1.7;
      text-align:center;
    }
    h1{color:var(--accent); margin-bottom:16px;}
  </style>
</head>
<body>
  <div class="bg"></div>
  <div class="overlay"></div>
  <div class="poem">
   Seninle geçen her an bir şiir,<br>
Kalbimde adın yazılı her bir mısra.<br>
Gözlerin, gecemi aydınlatan yıldız,<br>
Sesin, ruhumu saran en tatlı melodi.<br><br>
Yanımda olunca dünya duruyor sanki,<br>
Zaman susuyor, sadece biz varız.<br>
Seninle yürümek, her adımda huzur,<br>
Seninle gülmek, hayatın en güzel armağanı.<br><br>
Ve bil ki sevgilim,<br>
Sonsuzluk bile yetmez sana olan hislerime…<br>
  </div>
</body>
</html>
