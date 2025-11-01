<!doctype html>

<html lang="pt-BR">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Feliz 16 anos!</title>
  <style>
    :root{
      --bg:#0f1724;
      --card:#0b1220;
      --accent:#ff6b6b;
      --accent-2:#ffd166;
      --glass: rgba(255,255,255,0.06);
      --text:#e6eef8;
      --muted: rgba(230,238,248,0.7);
      --radius:18px;
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;font-family:Inter,system-ui,Segoe UI,Roboto,"Helvetica Neue",Arial; background: radial-gradient(1200px 600px at 10% 10%, rgba(255,107,107,0.06), transparent), radial-gradient(1000px 500px at 90% 90%, rgba(255,209,102,0.04), transparent), var(--bg); color:var(--text);}
    .wrap{min-height:100vh;display:flex;align-items:center;justify-content:center;padding:40px}
    .card{width:980px;max-width:100%;background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));border-radius:var(--radius);box-shadow:0 10px 40px rgba(2,6,23,0.6);overflow:hidden;display:grid;grid-template-columns:1fr 420px}
    @media(max-width:880px){.card{grid-template-columns:1fr;}}.left{padding:48px 40px;position:relative;}
.title{font-size:44px;line-height:1;margin:0 0 6px;font-weight:700;letter-spacing:-0.02em}
.subtitle{color:var(--muted);margin-bottom:18px}
.big-number{display:inline-block;background:linear-gradient(90deg,var(--accent),var(--accent-2));-webkit-background-clip:text;background-clip:text;color:transparent;font-weight:800;font-size:84px;margin:12px 0}

.message{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));padding:18px;border-radius:14px;box-shadow:inset 0 1px 0 rgba(255,255,255,0.02);margin-top:18px}
.message p{margin:0;color:var(--muted);font-size:18px}

.cta{display:flex;gap:12px;margin-top:22px}
.btn{background:linear-gradient(90deg,var(--accent),var(--accent-2));border:none;padding:12px 18px;border-radius:12px;color:#06101a;font-weight:700;cursor:pointer;box-shadow:0 6px 18px rgba(255,107,107,0.18);}
.btn.ghost{background:transparent;border:1px solid rgba(255,255,255,0.06);color:var(--text);box-shadow:none}

.right{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));padding:30px;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:14px}
.card-art{width:100%;height:100%;display:flex;align-items:center;justify-content:center;position:relative}
.balloon{width:110px;height:160px;border-radius:60% 60% 50% 50%;background:linear-gradient(180deg,var(--accent),var(--accent-2));position:relative;display:flex;align-items:flex-end;justify-content:center;box-shadow:0 14px 40px rgba(255,107,107,0.2)}
.balloon:after{content:"";position:absolute;bottom:-18px;width:2px;height:40px;background:linear-gradient(180deg, rgba(0,0,0,0.15), rgba(0,0,0,0));}
.confetti-canvas{position:absolute;inset:0;pointer-events:none}

footer{position:absolute;left:40px;bottom:30px;color:var(--muted);font-size:13px}

/* floating animation */
.float{animation:floaty 4s ease-in-out infinite}
@keyframes floaty{0%{transform:translateY(0)}50%{transform:translateY(-12px)}100%{transform:translateY(0)}}

/* sparkles */
.sparkles{position:absolute;right:22px;top:22px;font-size:14px;color:var(--muted)}

.name-input{margin-top:12px;display:flex;gap:8px}
.name-input input{flex:1;padding:10px;border-radius:10px;border:1px solid rgba(255,255,255,0.05);background:transparent;color:var(--text)}

.small{font-size:13px;color:var(--muted)}

  </style>
</head>
<body>
  <div class="wrap">
    <div class="card" role="main">
      <div class="left">
        <div class="sparkles">✨ Hoje é dia de festa!</div>
        <h1 class="title">Feliz 16 anos, <span id="friend-name">Amiga</span>!</h1>
        <div class="subtitle">Seja muito feliz — hoje e sempre.</div>
        <div class="big-number" id="age-text">16</div><div class="message">
      <p id="message-text">Que seu dia seja cheio de sorrisos, abraços apertados e memórias que durem para sempre. Parabéns por completar 16 anos — que essa nova etapa venha com sonhos grandes e muitas conquistas.</p>
    </div>

    <div class="cta">
      <button class="btn" id="play-btn" title="Tocar música">Tocar uma musiquinha 🎵</button>
      <button class="btn ghost" id="confetti-btn">Lançar confete 🎊</button>
    </div>

    <div class="name-input">
      <input id="name-inp" placeholder="Digite o nome dela (opcional)" aria-label="Nome da amiga">
      <button class="btn ghost" id="apply-name">Aplicar</button>
    </div>

    <footer>Feito com carinho 💖 — Abra em um navegador (Chrome/Edge/Firefox).</footer>
  </div>

  <div class="right">
    <div class="card-art" aria-hidden="true">
      <div class="balloon float"></div>
      <canvas class="confetti-canvas" id="confetti"></canvas>
    </div>
    <div class="small">Clique em "Tocar uma musiquinha" e depois em "Lançar confete" para celebrar!</div>
  </div>
</div>

  </div>  <script>
    // Data
    const today = new Date();
    const age = 16;
    // Set age text (in case you want to reuse)
    document.getElementById('age-text').textContent = age;

    // Name apply
    const nameInp = document.getElementById('name-inp');
    const applyBtn = document.getElementById('apply-name');
    const friendNameEl = document.getElementById('friend-name');
    applyBtn.addEventListener('click', ()=>{
      const v = nameInp.value.trim();
      if(v) friendNameEl.textContent = v;
    });

    // Simple chime using WebAudio
    const playBtn = document.getElementById('play-btn');
    let audioCtx=null;
    playBtn.addEventListener('click', ()=>{
      if(!audioCtx) audioCtx = new (window.AudioContext||window.webkitAudioContext)();
      const now = audioCtx.currentTime;
      const osc = audioCtx.createOscillator();
      const gain = audioCtx.createGain();
      osc.type = 'sine';
      osc.frequency.setValueAtTime(880, now);
      gain.gain.setValueAtTime(0, now);
      gain.gain.linearRampToValueAtTime(0.12, now+0.01);
      gain.gain.exponentialRampToValueAtTime(0.0001, now+1.8);
      osc.connect(gain); gain.connect(audioCtx.destination);
      osc.start(); osc.stop(now+1.9);

      // quick arpeggio
      const o2 = audioCtx.createOscillator();
      const g2 = audioCtx.createGain();
      o2.type='triangle'; o2.frequency.setValueAtTime(660, now+0.05);
      g2.gain.setValueAtTime(0.0, now+0.05);
      g2.gain.linearRampToValueAtTime(0.08, now+0.07);
      g2.gain.exponentialRampToValueAtTime(0.0001, now+1.5);
      o2.connect(g2); g2.connect(audioCtx.destination);
      o2.start(now+0.05); o2.stop(now+1.6);
    });

    // Confetti canvas
    const canvas = document.getElementById('confetti');
    const ctx = canvas.getContext('2d');
    let W = canvas.width = canvas.clientWidth;
    let H = canvas.height = canvas.clientHeight;
    window.addEventListener('resize', ()=>{ W = canvas.width = canvas.clientWidth; H = canvas.height = canvas.clientHeight;});

    function rand(min,max){return Math.random()*(max-min)+min}

    let particles = [];
    function makeParticle(x,y){
      return {
        x:x||rand(20,W-20), y:y||-10,
        vx:rand(-2,2), vy:rand(2,6),
        size:rand(6,12), rot:rand(0,Math.PI*2), vr:rand(-0.15,0.15),
        color: ['#ff6b6b','#ffd166','#6bf5c6','#8ea0ff'][Math.floor(Math.random()*4)],
        life:0, ttl: rand(90,160)
      }
    }

    function launchConfetti(count=120){
      for(let i=0;i<count;i++) particles.push(makeParticle());
      if(!animating) animate();
    }

    const confettiBtn = document.getElementById('confetti-btn');
    confettiBtn.addEventListener('click', ()=>{ launchConfetti(140); });

    let animating = false;
    function animate(){ animating = true; ctx.clearRect(0,0,W,H);
      for(let i=particles.length-1;i>=0;i--){
        const p = particles[i];
        p.x += p.vx; p.y += p.vy; p.vy += 0.06; p.rot += p.vr; p.life++;
        // draw
        ctx.save();
        ctx.translate(p.x,p.y); ctx.rotate(p.rot);
        ctx.fillStyle = p.color;
        ctx.fillRect(-p.size/2,-p.size/2,p.size,p.size*0.6);
        ctx.restore();
        if(p.y>H+30 || p.life>p.ttl) particles.splice(i,1);
      }
      if(particles.length>0) requestAnimationFrame(animate); else animating=false;
    }

    // small keyboard easter egg: press '🎂' (b) to celebrate
    document.addEventListener('keydown', (e)=>{ if(e.key.toLowerCase()==='b'){ launchConfetti(200); const evt = new Event('click'); playBtn.dispatchEvent(evt);} });

    // Set a sweet message (you can further customize programmatically)
    const msg = document.getElementById('message-text');
    msg.textContent = `Hoje você completa ${age} anos — que essa fase seja cheia de descobertas, risos e amizades verdadeiras. Aproveite seu dia ao máximo!`;

    // Accessibility: focus the play button
    playBtn.focus();

    // Small progressive enhancement: if user wants to share, allow screenshot by printing
    // (no extra JS needed)
  </script></body>
</html>
