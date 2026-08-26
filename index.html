<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>⚡ Aprenda JavaScript — Do Zero ao Essencial</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@300;400;500;600;700;800&family=JetBrains+Mono:wght@400;500;700&display=swap');

:root {
  --bg:      #0d0d14;
  --bg2:     #12121e;
  --bg3:     #1a1a2e;
  --bg4:     #22223b;
  --borda:   #2d2d4e;
  --borda2:  #1e1e3a;
  --texto:   #e2e8f0;
  --texto2:  #94a3b8;
  --ac:      #fbbf24;
  --ac2:     #d97706;
  --verde:   #34d399;
  --azul:    #60a5fa;
  --rosa:    #f472b6;
  --roxo:    #a78bfa;
  --laranja: #fb923c;
}

*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{
  font-family:'Space Grotesk',system-ui,sans-serif;
  background:var(--bg);color:var(--texto);
  min-height:100vh;overflow-x:hidden;font-size:15px;line-height:1.7;
}

/* ── SIDEBAR ─────────────────────────────── */
#sidebar{
  position:fixed;top:0;left:0;width:280px;height:100vh;
  background:var(--bg2);border-right:1px solid var(--borda);
  overflow-y:auto;z-index:100;display:flex;flex-direction:column;
  scrollbar-width:thin;scrollbar-color:var(--borda) transparent;
}
#sidebar::-webkit-scrollbar{width:3px}
#sidebar::-webkit-scrollbar-thumb{background:var(--borda)}

.s-logo{
  padding:16px 14px 12px;border-bottom:1px solid var(--borda);
  background:linear-gradient(180deg,#08080f,var(--bg2));
  position:sticky;top:0;z-index:10;
}
.s-logo h1{
  font-size:.95rem;font-weight:800;letter-spacing:-.03em;
  display:flex;align-items:center;gap:8px;
}
.s-logo h1 span{
  background:linear-gradient(90deg,var(--ac),var(--laranja));
  -webkit-background-clip:text;-webkit-text-fill-color:transparent;
}
.s-logo .sub{font-size:.7rem;color:var(--texto2);margin-top:2px;padding-left:38px}
.prog-row{display:flex;align-items:center;gap:8px;margin-top:9px}
.prog-bar{flex:1;height:3px;background:var(--borda);border-radius:2px;overflow:hidden}
.prog-fill{height:100%;background:linear-gradient(90deg,var(--ac),var(--laranja));border-radius:2px;transition:width .5s}
.prog-n{font-size:.7rem;color:var(--texto2);min-width:28px}
.js-icon{
  width:30px;height:30px;background:#f7df1e;border-radius:6px;
  display:flex;align-items:center;justify-content:center;
  font-weight:900;font-size:.85rem;color:#000;flex-shrink:0;
  font-family:'JetBrains Mono',monospace;
}
.mod-lbl{
  padding:12px 14px 3px;font-size:.62rem;font-weight:700;
  letter-spacing:.12em;text-transform:uppercase;color:var(--texto2);
}
.l-btn{
  display:flex;align-items:center;gap:8px;width:100%;text-align:left;
  background:none;border:none;cursor:pointer;padding:7px 14px;
  color:var(--texto2);font-family:'Space Grotesk',sans-serif;
  font-size:.82rem;transition:all .15s;border-left:2px solid transparent;
}
.l-btn:hover{color:var(--texto);background:rgba(251,191,36,.05)}
.l-btn.active{color:var(--ac);background:rgba(251,191,36,.1);border-left-color:var(--ac);font-weight:600}
.l-num{
  min-width:22px;height:22px;background:var(--bg4);border-radius:5px;
  font-size:.68rem;font-weight:700;font-family:'JetBrains Mono',monospace;
  display:flex;align-items:center;justify-content:center;color:var(--texto2);flex-shrink:0;
}
.l-btn.active .l-num{background:var(--ac2);color:#000}
.l-badge{margin-left:auto;font-size:.6rem;font-weight:700;padding:1px 6px;border-radius:10px;flex-shrink:0}

/* ── MAIN ────────────────────────────────── */
#main{margin-left:280px;min-height:100vh;display:flex;flex-direction:column}
#topbar{
  position:sticky;top:0;z-index:50;
  background:rgba(13,13,20,.93);backdrop-filter:blur(12px);
  border-bottom:1px solid var(--borda);padding:10px 28px;
  display:flex;align-items:center;justify-content:space-between;gap:12px;
}
.tb-l{min-width:0}
.tb-bc{font-size:.72rem;color:var(--texto2);margin-bottom:1px}
.tb-bc span{color:var(--ac)}
#tb-t{font-size:.96rem;font-weight:700;white-space:nowrap;overflow:hidden;text-overflow:ellipsis}
.tb-nav{display:flex;gap:6px;flex-shrink:0}
.nb{
  background:var(--bg4);border:1px solid var(--borda);color:var(--texto2);
  font-family:'Space Grotesk',sans-serif;padding:5px 13px;border-radius:6px;
  font-size:.8rem;cursor:pointer;transition:all .15s;white-space:nowrap;
}
.nb:hover{border-color:var(--ac);color:var(--ac)}
.nb:disabled{opacity:.3;cursor:default}
.nb:disabled:hover{border-color:var(--borda);color:var(--texto2)}

/* ── CONTENT ─────────────────────────────── */
#content{padding:30px 36px 100px;max-width:920px;width:100%}
.l-hdr{margin-bottom:24px}
.l-meta{font-size:.76rem;color:var(--texto2);margin-bottom:7px;display:flex;align-items:center;gap:10px;flex-wrap:wrap}
.l-meta .mt{background:rgba(251,191,36,.1);color:var(--ac);border:1px solid rgba(251,191,36,.2);padding:2px 8px;border-radius:4px;font-weight:700;font-size:.68rem;letter-spacing:.05em}
.l-title{font-size:1.95rem;font-weight:800;letter-spacing:-.04em;line-height:1.2}
.l-title .ac{color:var(--ac)}
.l-sub{font-size:.92rem;color:var(--texto2);margin-top:5px}

/* blocos */
.explain{
  background:linear-gradient(135deg,rgba(251,191,36,.07),rgba(251,146,60,.04));
  border:1px solid rgba(251,191,36,.2);border-radius:12px;
  padding:20px 22px;margin:18px 0;position:relative;overflow:hidden;
}
.explain::before{content:'';position:absolute;top:0;left:0;width:3px;height:100%;background:linear-gradient(180deg,var(--ac),var(--laranja))}
.explain-icon{font-size:1.9rem;margin-bottom:8px;display:block}
.explain p{margin-bottom:8px;line-height:1.75}
.explain p:last-child{margin-bottom:0}

.analogy{background:rgba(96,165,250,.07);border:1px solid rgba(96,165,250,.2);border-radius:10px;padding:14px 18px;margin:14px 0;font-size:.9rem}
.analogy-t{font-size:.68rem;font-weight:700;letter-spacing:.1em;text-transform:uppercase;color:var(--azul);margin-bottom:6px}

.card{background:var(--bg2);border:1px solid var(--borda);border-radius:10px;padding:18px 20px;margin:14px 0}
.card-t{font-size:.9rem;font-weight:700;margin-bottom:10px;display:flex;align-items:center;gap:7px}

.tip{background:rgba(96,165,250,.07);border:1px solid rgba(96,165,250,.2);border-radius:10px;padding:11px 15px;margin:11px 0;font-size:.87rem;color:var(--azul);display:flex;gap:9px;align-items:flex-start}
.warn{background:rgba(251,191,36,.07);border:1px solid rgba(251,191,36,.2);border-radius:10px;padding:11px 15px;margin:11px 0;font-size:.87rem;color:var(--ac);display:flex;gap:9px;align-items:flex-start}
.tip-i,.warn-i{font-size:.95rem;flex-shrink:0;margin-top:2px}

p{line-height:1.75;margin-bottom:9px}
p:last-child{margin-bottom:0}
strong{color:var(--ac);font-weight:600}
em{color:var(--verde);font-style:normal;font-weight:600}
h3{font-size:1.03rem;font-weight:700;margin:18px 0 8px}
ul,ol{padding-left:20px;margin:7px 0}
li{margin-bottom:4px;line-height:1.65}

code{font-family:'JetBrains Mono',monospace;background:rgba(110,118,129,.12);color:var(--laranja);padding:2px 6px;border-radius:4px;font-size:.84em;border:1px solid rgba(110,118,129,.15)}
pre code{background:none;border:none;padding:0;color:inherit;font-size:inherit}

/* code block estático */
pre.cb{font-family:'JetBrains Mono',monospace;background:#060610;border:1px solid var(--borda);border-radius:10px;overflow:hidden;margin:14px 0;font-size:.83rem;line-height:1.7}
.cbh{display:flex;align-items:center;justify-content:space-between;padding:7px 14px;background:var(--bg3);border-bottom:1px solid var(--borda);font-size:.7rem;color:var(--texto2);font-family:'JetBrains Mono',monospace}
.cbh .lang{color:var(--ac);font-weight:700}
.cbb{padding:14px 16px;overflow-x:auto}
.copy-btn{background:none;border:1px solid var(--borda);color:var(--texto2);padding:2px 9px;border-radius:4px;cursor:pointer;font-size:.68rem;font-family:'Space Grotesk',sans-serif;transition:all .15s}
.copy-btn:hover{border-color:var(--verde);color:var(--verde)}

/* syntax highlight */
.kw{color:#f472b6}  .fn{color:#60a5fa}  .st{color:#34d399}
.nm{color:#fb923c}  .cm{color:#3d4466;font-style:italic}
.op{color:#e2e8f0}  .vr{color:#fbbf24}  .bo{color:#a78bfa}

/* table */
.tw{overflow-x:auto;margin:12px 0}
table{width:100%;border-collapse:collapse;font-size:.86rem}
th{background:var(--bg3);text-align:left;padding:9px 13px;font-weight:700;color:var(--texto2);border-bottom:1px solid var(--borda);font-size:.72rem;letter-spacing:.07em;text-transform:uppercase}
td{padding:9px 13px;border-bottom:1px solid var(--borda2);vertical-align:top}
tr:hover td{background:rgba(255,255,255,.015)}
td code{font-size:.79rem}

/* steps */
.steps{display:flex;flex-direction:column;gap:8px;margin:13px 0}
.step{display:flex;gap:12px;background:var(--bg3);border:1px solid var(--borda);border-radius:8px;padding:12px 14px}
.sn{min-width:26px;height:26px;background:var(--ac2);color:#000;border-radius:6px;font-weight:700;font-size:.82rem;display:flex;align-items:center;justify-content:center;flex-shrink:0}
.sc strong{color:var(--texto);font-size:.9rem;display:block;margin-bottom:2px}
.sc p{font-size:.86rem;color:var(--texto2);margin:0}

/* exercise */
.ex{background:rgba(52,211,153,.05);border:1px solid rgba(52,211,153,.2);border-radius:10px;padding:16px 20px;margin:18px 0}
.ex-t{font-size:.7rem;font-weight:700;letter-spacing:.1em;text-transform:uppercase;color:var(--verde);display:flex;align-items:center;gap:5px;margin-bottom:9px}

/* ── CONSOLE PLAYGROUND ──────────────────── */
.playground{
  border:1px solid var(--borda);border-radius:12px;
  overflow:hidden;margin:18px 0;
}
.pg-h{
  display:flex;align-items:center;justify-content:space-between;
  padding:8px 14px;background:var(--bg3);border-bottom:1px solid var(--borda);
}
.pg-tabs{display:flex;gap:1px}
.pg-tab{background:none;border:none;color:var(--texto2);cursor:pointer;padding:5px 12px;font-family:'JetBrains Mono',monospace;font-size:.7rem;border-bottom:2px solid transparent;transition:all .15s}
.pg-tab.active{color:var(--ac);border-bottom-color:var(--ac)}
.pg-tab:hover:not(.active){color:var(--texto)}
.pg-status{font-size:.68rem;color:var(--texto2);font-family:'JetBrains Mono',monospace}
.pg-editor{
  width:100%;min-height:180px;resize:vertical;border:none;outline:none;
  background:#060610;color:#e2e8f0;font-family:'JetBrains Mono',monospace;
  font-size:.83rem;padding:14px 16px;line-height:1.7;tab-size:2;
}
.pg-footer{display:flex;gap:7px;padding:8px 12px;background:var(--bg3);border-top:1px solid var(--borda);flex-wrap:wrap}
.btn-run{background:var(--ac);color:#000;font-weight:700;border:none;padding:7px 18px;border-radius:7px;cursor:pointer;font-family:'Space Grotesk',sans-serif;font-size:.83rem;transition:opacity .15s}
.btn-run:hover{opacity:.85}
.btn-rst{background:var(--bg4);color:var(--texto2);border:1px solid var(--borda);padding:7px 14px;border-radius:7px;cursor:pointer;font-family:'Space Grotesk',sans-serif;font-size:.83rem;transition:all .15s}
.btn-rst:hover{border-color:var(--texto2);color:var(--texto)}
.btn-ai{background:linear-gradient(90deg,var(--roxo),var(--rosa));color:#fff;border:none;padding:7px 14px;border-radius:7px;cursor:pointer;font-family:'Space Grotesk',sans-serif;font-size:.83rem;transition:opacity .15s}
.btn-ai:hover{opacity:.85}
/* console output */
.console-out{
  min-height:80px;max-height:260px;overflow-y:auto;
  background:#020208;border-top:1px solid var(--borda);
  padding:10px 14px;font-family:'JetBrains Mono',monospace;font-size:.8rem;
  line-height:1.8;
}
.c-log{color:#e2e8f0}
.c-err{color:#f87171}
.c-warn{color:#fbbf24}
.c-ok{color:#34d399}
.c-prompt{color:#a78bfa}
.c-dim{color:#3d4466}

/* ── CHAT ────────────────────────────────── */
#chat-panel{
  position:fixed;right:0;top:0;bottom:0;width:370px;
  background:var(--bg2);border-left:1px solid var(--borda);
  display:flex;flex-direction:column;
  transform:translateX(100%);transition:transform .3s cubic-bezier(.4,0,.2,1);z-index:200;
}
#chat-panel.open{transform:translateX(0)}
.ch-hd{
  padding:13px 16px;background:linear-gradient(90deg,#1a1200,#1a0d00);
  border-bottom:1px solid var(--borda);
  display:flex;align-items:center;justify-content:space-between;
}
.ch-hd h3{font-size:.92rem;font-weight:700;display:flex;align-items:center;gap:6px}
.ch-hbs{display:flex;gap:5px}
.ch-hbs button{background:rgba(255,255,255,.07);border:1px solid var(--borda);color:var(--texto2);width:27px;height:27px;border-radius:6px;cursor:pointer;font-size:.9rem;display:flex;align-items:center;justify-content:center;transition:all .15s}
.ch-hbs button:hover{border-color:var(--ac);color:var(--ac)}
.ch-setup{padding:14px;background:rgba(251,191,36,.04);border-bottom:1px solid var(--borda);font-size:.82rem;line-height:1.6}
.ch-setup p{margin-bottom:7px;color:var(--texto2)}
.ch-setup a{color:var(--azul)}
.ch-setup select,.ch-setup input[type=password]{width:100%;background:var(--bg3);color:var(--texto);border:1px solid var(--borda);border-radius:7px;padding:7px 10px;font-family:'Space Grotesk',sans-serif;font-size:.82rem;margin-bottom:7px;outline:none;transition:border-color .15s}
.ch-setup select:focus,.ch-setup input:focus{border-color:var(--ac)}
#ch-msgs{flex:1;overflow-y:auto;padding:13px;display:flex;flex-direction:column;gap:9px;scrollbar-width:thin;scrollbar-color:var(--borda) transparent}
.msg{max-width:92%;border-radius:10px;padding:9px 12px;font-size:.87rem;line-height:1.6;animation:mi .2s ease}
@keyframes mi{from{opacity:0;transform:translateY(5px)}}
.msg.user{align-self:flex-end;background:#1a1500;color:var(--texto);border-radius:10px 10px 2px 10px}
.msg.ai{align-self:flex-start;background:var(--bg3);color:var(--texto);border-radius:10px 10px 10px 2px}
.msg.ai strong{color:var(--ac)}
.msg.ai code{font-size:.79em;background:rgba(110,118,129,.15);color:var(--laranja);padding:1px 5px;border-radius:3px}
.msg.ai pre{background:#060610;border:1px solid var(--borda);border-radius:6px;padding:7px 9px;margin:5px 0;font-size:.76rem;overflow-x:auto;font-family:'JetBrains Mono',monospace;color:var(--texto2)}
.msg-load{display:flex;gap:4px;align-items:center;padding:9px 12px}
.dot{width:6px;height:6px;border-radius:50%;background:var(--texto2);animation:bl 1.2s infinite}
.dot:nth-child(2){animation-delay:.2s}.dot:nth-child(3){animation-delay:.4s}
@keyframes bl{0%,100%{opacity:.2}50%{opacity:1}}
.ch-ia{padding:10px 13px;border-top:1px solid var(--borda);display:flex;gap:7px}
#ch-inp{flex:1;background:var(--bg3);border:1px solid var(--borda);color:var(--texto);border-radius:8px;padding:8px 11px;font-family:'Space Grotesk',sans-serif;font-size:.87rem;resize:none;outline:none;max-height:90px;transition:border-color .15s}
#ch-inp:focus{border-color:var(--ac)}
#ch-send{background:var(--ac2);border:none;color:#000;border-radius:8px;width:36px;cursor:pointer;font-size:1.1rem;transition:opacity .15s;flex-shrink:0;display:flex;align-items:center;justify-content:center;font-weight:900}
#ch-send:hover{opacity:.8}
#ch-fab{
  position:fixed;bottom:22px;right:22px;
  background:linear-gradient(135deg,var(--ac2),var(--laranja));
  border:none;color:#000;width:50px;height:50px;border-radius:50%;
  cursor:pointer;font-size:1.4rem;font-weight:900;
  box-shadow:0 4px 20px rgba(251,191,36,.4);
  z-index:190;transition:all .2s;display:flex;align-items:center;justify-content:center;
  font-family:'JetBrains Mono',monospace;
}
#ch-fab:hover{transform:scale(1.1)}

/* mobile */
#menu-tog{display:none;position:fixed;top:11px;left:11px;z-index:300;background:var(--bg2);border:1px solid var(--borda);color:var(--texto);border-radius:7px;padding:6px 10px;cursor:pointer;font-size:1.1rem}
#overlay{display:none;position:fixed;inset:0;background:rgba(0,0,0,.65);z-index:90;backdrop-filter:blur(2px)}
#overlay.show{display:block}
@media(max-width:960px){
  #sidebar{transform:translateX(-100%);transition:transform .3s}
  #sidebar.open{transform:translateX(0)}
  #main{margin-left:0}
  #menu-tog{display:flex}
  #content{padding:18px 16px 100px}
  #topbar{padding:9px 14px 9px 50px}
  .l-title{font-size:1.6rem}
  #chat-panel{width:100%}
}
</style>
</head>
<body>

<aside id="sidebar">
  <div class="s-logo">
    <h1><div class="js-icon">JS</div> <span>JavaScript</span></h1>
    <div class="sub">Do zero ao essencial</div>
    <div class="prog-row">
      <div class="prog-bar"><div class="prog-fill" id="prog-fill" style="width:0%"></div></div>
      <span class="prog-n" id="prog-n">0%</span>
    </div>
  </div>
  <div id="menu-list"></div>
</aside>

<div id="overlay" onclick="closeSidebar()"></div>
<button id="menu-tog" onclick="toggleSidebar()">☰</button>

<div id="main">
  <div id="topbar">
    <div class="tb-l">
      <div class="tb-bc" id="breadcrumb">Módulo 1 · <span>Início</span></div>
      <div id="tb-t">O que é JavaScript?</div>
    </div>
    <div class="tb-nav">
      <button class="nb" id="btn-prev" onclick="changeLesson(-1)" disabled>← Anterior</button>
      <button class="nb" id="btn-next" onclick="changeLesson(1)">Próxima →</button>
    </div>
  </div>
  <div id="content"></div>
</div>

<!-- CHAT -->
<div id="chat-panel">
  <div class="ch-hd">
    <h3>⚡ Assistente JS</h3>
    <div class="ch-hbs">
      <button onclick="openSetup()" title="Configurar IA">⚙️</button>
      <button onclick="toggleChat()" title="Fechar">✕</button>
    </div>
  </div>
  <div id="ch-setup-box" class="ch-setup" style="display:none">
    <p><strong>Configure seu assistente IA gratuito:</strong></p>
    <select id="ai-prov" onchange="updHelp()">
      <option value="gemini">Google Gemini (grátis)</option>
      <option value="anthropic">Anthropic Claude</option>
    </select>
    <input type="password" id="ai-key" placeholder="Cole sua chave de API aqui">
    <p id="ai-help">Chave gratuita em <a href="https://aistudio.google.com/app/apikey" target="_blank">aistudio.google.com/app/apikey</a></p>
    <button class="nb" style="width:100%;background:var(--ac2);color:#000;border-color:var(--ac2)" onclick="saveKey()">💾 Salvar e usar</button>
  </div>
  <div id="ch-msgs">
    <div class="msg ai">Oi! ⚡ Sou seu professor de JavaScript! Me pergunte sobre <strong>qualquer conceito, erro ou dúvida</strong>. Tô aqui pra ajudar! 😊</div>
  </div>
  <div class="ch-ia">
    <textarea id="ch-inp" rows="1" placeholder="Pergunta sobre JavaScript..."
      onkeydown="if(event.key==='Enter'&&!event.shiftKey){event.preventDefault();sendChat()}"></textarea>
    <button id="ch-send" onclick="sendChat()">➤</button>
  </div>
</div>
<button id="ch-fab" onclick="toggleChat()" title="Tirar dúvidas de JS">JS</button>

<script>
// ─── HELPERS ─────────────────────────────────────────────
function cb(lang, label, code) {
  const id = 'cb_' + Math.random().toString(36).slice(2, 8);
  return `<pre class="cb"><div class="cbh"><span class="lang">${lang}</span><span>${label}</span><button class="copy-btn" onclick="cpCb('${id}')">Copiar</button></div><div class="cbb" id="${id}"><code>${code}</code></div></pre>`;
}

function pg(code, label) {
  const id = 'pg_' + Math.random().toString(36).slice(2, 8);
  const enc = encodeURIComponent(code);
  return `<div class="playground" id="${id}">
    <div class="pg-h">
      <div class="pg-tabs"><button class="pg-tab active">JavaScript</button></div>
      <span class="pg-status" id="${id}_st">pronto para executar</span>
    </div>
    <textarea class="pg-editor" id="${id}_ed" spellcheck="false">${code}</textarea>
    <div class="pg-footer">
      <button class="btn-run" onclick="runCode('${id}')">▶ Executar</button>
      <button class="btn-rst" onclick="resetCode('${id}','${enc}')">↺ Resetar</button>
      <button class="btn-ai" onclick="explainCode('${id}')">🤖 Explicar</button>
    </div>
    <div class="console-out" id="${id}_out"><span class="c-dim">// saída aparece aqui...</span></div>
  </div>`;
}

// ─── RUNNER ──────────────────────────────────────────────
function runCode(id) {
  const editor = document.getElementById(id + '_ed');
  const out    = document.getElementById(id + '_out');
  const st     = document.getElementById(id + '_st');
  const code   = editor.value;
  out.innerHTML = '';
  st.textContent = 'executando...';

  const logs = [];

  // intercepta console.log / warn / error
  const _log  = console.log;
  const _warn = console.warn;
  const _err  = console.error;

  function fmt(args) {
    return Array.from(args).map(a => {
      if (a === null) return 'null';
      if (a === undefined) return 'undefined';
      if (typeof a === 'object') {
        try { return JSON.stringify(a, null, 2); } catch { return String(a); }
      }
      return String(a);
    }).join(' ');
  }

  console.log   = (...a) => { logs.push({ t:'log',  m: fmt(a) }); _log(...a); };
  console.warn  = (...a) => { logs.push({ t:'warn', m: fmt(a) }); _warn(...a); };
  console.error = (...a) => { logs.push({ t:'err',  m: fmt(a) }); _err(...a); };

  // intercepta alert e prompt para simulação
  const _alert  = window.alert;
  const _prompt = window.prompt;
  const _confirm = window.confirm;

  window.alert = (msg) => {
    logs.push({ t:'ok', m: '📢 alert: ' + String(msg) });
  };
  window.prompt = (msg, def) => {
    const val = def !== undefined ? String(def) : '(input simulado)';
    logs.push({ t:'prompt', m: '❓ prompt: "' + msg + '" → retornou: "' + val + '"' });
    return val;
  };
  window.confirm = (msg) => {
    logs.push({ t:'prompt', m: '✅ confirm: "' + msg + '" → retornou: true' });
    return true;
  };

  try {
    // usa Function para isolar o escopo
    const fn = new Function(code);
    fn();
    st.textContent = '✓ executado';
    st.style.color = 'var(--verde)';
  } catch(e) {
    logs.push({ t:'err', m: '🔴 ' + e.constructor.name + ': ' + e.message });
    st.textContent = '✗ erro';
    st.style.color = 'var(--rosa)';
  } finally {
    console.log   = _log;
    console.warn  = _warn;
    console.error = _err;
    window.alert  = _alert;
    window.prompt = _prompt;
    window.confirm = _confirm;
  }

  if (logs.length === 0) {
    out.innerHTML = '<span class="c-dim">// código executado sem saída</span>';
  } else {
    out.innerHTML = logs.map(l => {
      const cls = l.t === 'err' ? 'c-err' : l.t === 'warn' ? 'c-warn' : l.t === 'ok' ? 'c-ok' : l.t === 'prompt' ? 'c-prompt' : 'c-log';
      return `<div class="${cls}">${escHtml(l.m)}</div>`;
    }).join('');
  }

  setTimeout(() => { st.style.color = ''; }, 2500);
}

function escHtml(s) {
  return s.replace(/&/g,'&amp;').replace(/</g,'&lt;').replace(/>/g,'&gt;');
}

function resetCode(id, enc) {
  document.getElementById(id + '_ed').value = decodeURIComponent(enc);
  document.getElementById(id + '_out').innerHTML = '<span class="c-dim">// saída aparece aqui...</span>';
  document.getElementById(id + '_st').textContent = 'pronto para executar';
}

function explainCode(id) {
  const code = document.getElementById(id + '_ed').value;
  document.getElementById('ch-inp').value = 'Me explica esse código JavaScript:\n```js\n' + code + '\n```';
  openChat();
  sendChat();
}

// ─── LIÇÕES ──────────────────────────────────────────────
const lessons = [

// ══ MÓDULO 1 ══════════════════════════════════════════
{
  modulo: 'Módulo 1 — Primeiros Passos',
  id: 'o-que-e-js', icon: '⚡', num: 1,
  badge: 'Início', bc: '#34d399',
  title: 'O que é JavaScript?',
  sub: 'A linguagem que faz a web funcionar',
  content: () => `
  <div class="explain">
    <span class="explain-icon">🌍</span>
    <p>JavaScript é a linguagem de programação da web. Enquanto o <strong>HTML</strong> é a estrutura e o <strong>CSS</strong> é a aparência, o <em>JavaScript</em> é o comportamento — o que faz as coisas acontecerem!</p>
    <p>Hoje, o JavaScript vai muito além da web: roda em servidores (Node.js), em apps mobile, em programas desktop e até em microcontroladores.</p>
  </div>
  <div class="analogy">
    <div class="analogy-t">🏠 Analogia</div>
    <p><strong>HTML</strong> = a planta da casa (estrutura)<br>
    <strong>CSS</strong> = a pintura e decoração (aparência)<br>
    <strong>JavaScript</strong> = a eletricidade e o encanamento (comportamento, ação)</p>
  </div>
  <div class="card">
    <div class="card-t">🚀 O que você pode fazer com JS?</div>
    <ul>
      <li>Reagir a cliques, teclado, mouse do usuário</li>
      <li>Buscar dados de APIs (clima, filmes, etc)</li>
      <li>Criar aplicativos web completos (React, Vue)</li>
      <li>Criar servidores e APIs (Node.js)</li>
      <li>Fazer jogos, animações, gráficos</li>
      <li>Automatizar tarefas no navegador</li>
    </ul>
  </div>
  <div class="card">
    <div class="card-t">🔧 Onde o JS roda?</div>
    <p>O JavaScript roda <strong>dentro do navegador</strong> — Chrome, Firefox, Safari, Edge. Você não precisa instalar nada! Abra o DevTools com <code>F12</code>, vá na aba <strong>Console</strong>, e já pode digitar código JS.</p>
    <p>Neste curso temos um <strong>console interativo</strong> em cada lição para você testar na hora. Clique em <strong>▶ Executar</strong> para rodar o código!</p>
  </div>
  ${pg(`// Seu primeiro código JavaScript!
// O // no começo é um COMENTÁRIO — o JS ignora essa linha

console.log("Olá, mundo!");
console.log("JavaScript é incrível!");
console.log(2 + 2);`, 'Olá Mundo')}
  <div class="tip"><span class="tip-i">💡</span><div><code>console.log()</code> é a função mais usada no JavaScript. Ela "imprime" valores no console do navegador (e aqui no nosso console abaixo do editor). Você vai usar ela centenas de vezes!</div></div>
  `
},

{
  modulo: null, id: 'console-alert', icon: '📢', num: 2,
  badge: 'Início', bc: '#34d399',
  title: 'Saídas: console.log e alert',
  sub: 'As formas básicas de mostrar informações',
  content: () => `
  <div class="explain">
    <span class="explain-icon">📢</span>
    <p>Antes de aprender a guardar dados, precisamos saber <strong>como mostrar coisas</strong>. No JavaScript existem algumas formas de exibir informações para o usuário ou para você mesmo (durante o desenvolvimento).</p>
  </div>
  <div class="tw"><table>
    <tr><th>Comando</th><th>O que faz</th><th>Quando usar</th></tr>
    <tr><td><code>console.log()</code></td><td>Imprime no console do DevTools</td><td>Depuração, verificar valores ✅</td></tr>
    <tr><td><code>alert()</code></td><td>Abre uma caixa de diálogo</td><td>Avisos simples ao usuário</td></tr>
    <tr><td><code>document.write()</code></td><td>Escreve direto na página HTML</td><td>Evite — apenas para estudo</td></tr>
    <tr><td><code>console.warn()</code></td><td>Aviso amarelo no console</td><td>Alertas de desenvolvimento</td></tr>
    <tr><td><code>console.error()</code></td><td>Erro vermelho no console</td><td>Mostrar erros</td></tr>
  </table></div>
  ${pg(`// console.log — imprime qualquer coisa!
console.log("Texto simples");
console.log(42);
console.log(true);
console.log("Soma:", 10 + 5);

// Você pode passar vários valores de uma vez
console.log("Nome:", "João", "| Idade:", 25);

// console.warn e console.error
console.warn("Atenção: isso é um aviso!");
console.error("Erro: algo deu errado!");

// alert abre uma caixinha (simulado aqui no curso)
alert("Olá! Sou uma caixa de alerta!");`, 'Formas de saída')}
  <div class="tip"><span class="tip-i">💡</span><div>No dia a dia, <code>console.log()</code> é seu melhor amigo para entender o que está acontecendo no código. Programadores experientes também usam bastante — não é só para iniciantes!</div></div>
  <div class="warn"><span class="warn-i">⚠️</span><div><code>alert()</code> <strong>trava</strong> a execução do código até o usuário clicar em OK. Por isso, prefira <code>console.log()</code> para depuração e mostre informações na própria página para o usuário final.</div></div>
  `
},

{
  modulo: null, id: 'variaveis', icon: '📦', num: 3,
  badge: 'Início', bc: '#34d399',
  title: 'Variáveis: var, let e const',
  sub: 'Caixinhas para guardar informações',
  content: () => `
  <div class="explain">
    <span class="explain-icon">📦</span>
    <p>Uma <strong>variável</strong> é um espaço na memória para guardar um valor. Você dá um nome pra ela e pode usar esse nome para acessar o valor depois. Pensa como uma caixinha etiquetada!</p>
  </div>
  <div class="analogy">
    <div class="analogy-t">🎁 Analogia</div>
    <p>Variável = caixinha com etiqueta. Você escreve <code>let idade = 25</code> e cria uma caixinha chamada "idade" com o número 25 dentro. Quando precisar do valor, é só chamar pelo nome!</p>
  </div>
  <div class="tw"><table>
    <tr><th>Palavra</th><th>Pode mudar?</th><th>Escopo</th><th>Quando usar</th></tr>
    <tr><td><code>var</code></td><td>✅ Sim</td><td>Função (antigo)</td><td>Evite — legado do JS antigo</td></tr>
    <tr><td><code>let</code></td><td>✅ Sim</td><td>Bloco</td><td>Valores que mudam ✅</td></tr>
    <tr><td><code>const</code></td><td>❌ Não</td><td>Bloco</td><td>Valores fixos ✅</td></tr>
  </table></div>
  ${pg(`// const — valor que NÃO muda (constante)
const nome = "Maria";
const pi = 3.14159;
console.log("Nome:", nome);
console.log("Pi:", pi);

// let — valor que PODE mudar
let idade = 20;
console.log("Idade:", idade);
idade = 21; // mudou!
console.log("Idade no aniversário:", idade);

// Regras para nomes de variáveis:
let primeiroNome = "João";   // camelCase (padrão JS)
let _interno = "ok";         // pode começar com _
let $especial = "ok";        // pode começar com $
// let 1erNome = "erro";     // NÃO pode começar com número
// let meu-nome = "erro";    // NÃO pode ter hífen

console.log(primeiroNome, _interno, $especial);`, 'var, let, const')}
  <div class="tip"><span class="tip-i">💡</span><div><strong>Regra de ouro:</strong> use <code>const</code> por padrão. Só use <code>let</code> se souber que o valor vai mudar. Nunca use <code>var</code> em código novo — ele tem comportamentos confusos.</div></div>
  `
},

{
  modulo: null, id: 'tipos', icon: '🧬', num: 4,
  badge: 'Início', bc: '#34d399',
  title: 'Tipos de dados',
  sub: 'String, Number, Boolean, null e undefined',
  content: () => `
  <div class="explain">
    <span class="explain-icon">🧬</span>
    <p>Toda variável guarda um <strong>tipo de dado</strong>. O JS tem tipos básicos (primitivos) que você precisa conhecer. Diferente de outras linguagens, você não precisa declarar o tipo — o JS descobre sozinho!</p>
  </div>
  <div class="tw"><table>
    <tr><th>Tipo</th><th>Exemplo</th><th>O que é</th></tr>
    <tr><td><code>string</code></td><td><code>"Olá"</code>, <code>'JS'</code></td><td>Texto — sempre entre aspas</td></tr>
    <tr><td><code>number</code></td><td><code>42</code>, <code>3.14</code>, <code>-7</code></td><td>Números (inteiros e decimais)</td></tr>
    <tr><td><code>boolean</code></td><td><code>true</code>, <code>false</code></td><td>Verdadeiro ou falso</td></tr>
    <tr><td><code>null</code></td><td><code>null</code></td><td>"Vazio intencionalmente"</td></tr>
    <tr><td><code>undefined</code></td><td><code>undefined</code></td><td>"Ainda não tem valor"</td></tr>
    <tr><td><code>object</code></td><td><code>{ nome: "João" }</code></td><td>Coleção de propriedades</td></tr>
    <tr><td><code>array</code></td><td><code>[1, 2, 3]</code></td><td>Lista de valores</td></tr>
  </table></div>
  ${pg(`// String — texto entre aspas simples, duplas ou crase
const saudacao = "Olá, mundo!";
const linguagem = 'JavaScript';
const frase = \`Aprendendo \${linguagem}!\`; // template literal
console.log(saudacao, linguagem, frase);

// Number — números (sem aspas!)
const inteiro = 42;
const decimal = 3.14;
const negativo = -10;
console.log(inteiro, decimal, negativo);

// Boolean — verdadeiro ou falso
const logado = true;
const admin = false;
console.log("Logado?", logado, "| Admin?", admin);

// null e undefined
let semValor;           // undefined — declarou mas não atribuiu
const vazio = null;     // null — vazio intencionalmente
console.log(semValor, vazio);

// typeof — descobre o tipo de qualquer valor
console.log(typeof "texto");    // string
console.log(typeof 42);         // number
console.log(typeof true);       // boolean
console.log(typeof undefined);  // undefined
console.log(typeof null);       // object (curiosidade histórica do JS!)`, 'Tipos de dados')}
  <div class="tip"><span class="tip-i">💡</span><div><code>typeof</code> é muito útil para debugar! Se uma variável está com valor estranho, use <code>console.log(typeof minhaVariavel)</code> para saber o tipo dela.</div></div>
  `
},

// ══ MÓDULO 2 ══════════════════════════════════════════
{
  modulo: 'Módulo 2 — Operadores e Lógica',
  id: 'operadores-arit', icon: '🔢', num: 5,
  badge: 'Lógica', bc: '#60a5fa',
  title: 'Operadores aritméticos',
  sub: 'Fazendo cálculos e juntando textos',
  content: () => `
  <div class="explain">
    <span class="explain-icon">🔢</span>
    <p>Os operadores aritméticos funcionam igual à matemática — mas com um bônus: no JavaScript o <code>+</code> também junta textos (strings)! Isso se chama <em>concatenação</em>.</p>
  </div>
  ${pg(`// Aritméticos básicos
console.log(10 + 3);   // 13 — soma
console.log(10 - 3);   // 7  — subtração
console.log(10 * 3);   // 30 — multiplicação
console.log(10 / 3);   // 3.333... — divisão
console.log(10 % 3);   // 1  — resto da divisão (módulo)
console.log(2 ** 10);  // 1024 — potência

// Atalhos de atribuição
let x = 10;
x += 5;   // x = x + 5 → 15
x -= 3;   // x = x - 3 → 12
x *= 2;   // x = x * 2 → 24
x /= 4;   // x = x / 4 → 6
console.log("x final:", x);

// Incremento e decremento
let contador = 0;
contador++;    // contador = 1
contador++;    // contador = 2
contador--;    // contador = 1
console.log("contador:", contador);

// + com strings = concatenação (juntar textos)
const nome = "João";
const idade = 25;
console.log("Olá, " + nome + "! Você tem " + idade + " anos.");

// Cuidado: + com string e número
console.log("5" + 3);   // "53" — concatenou! (string + number)
console.log(5 + 3);     // 8   — somou! (number + number)
console.log("5" - 3);   // 2   — subtraiu! (JS converteu a string)`, 'Operadores')}
  <div class="warn"><span class="warn-i">⚠️</span><div>O <code>+</code> com strings é uma armadilha clássica! <code>"5" + 3</code> vira <code>"53"</code> (texto), não <code>8</code>. Para evitar isso, prefira os <strong>template literals</strong> com crase: <code>\`Olá \${nome}!\`</code></div></div>
  `
},

{
  modulo: null, id: 'comparacao', icon: '⚖️', num: 6,
  badge: 'Lógica', bc: '#60a5fa',
  title: 'Operadores de comparação',
  sub: 'Comparando valores — o resultado é sempre true ou false',
  content: () => `
  <div class="explain">
    <span class="explain-icon">⚖️</span>
    <p>Operadores de comparação <strong>comparam dois valores</strong> e sempre retornam <code>true</code> ou <code>false</code>. São usados em condicionais (<code>if</code>) e laços (<code>while</code>).</p>
  </div>
  <div class="tw"><table>
    <tr><th>Operador</th><th>Significado</th><th>Exemplo</th><th>Resultado</th></tr>
    <tr><td><code>==</code></td><td>Igual (valor, ignora tipo)</td><td><code>"5" == 5</code></td><td><code>true</code> ⚠️</td></tr>
    <tr><td><code>===</code></td><td>Igual (valor E tipo)</td><td><code>"5" === 5</code></td><td><code>false</code> ✅</td></tr>
    <tr><td><code>!=</code></td><td>Diferente (ignora tipo)</td><td><code>"5" != 5</code></td><td><code>false</code></td></tr>
    <tr><td><code>!==</code></td><td>Diferente (valor E tipo)</td><td><code>"5" !== 5</code></td><td><code>true</code> ✅</td></tr>
    <tr><td><code>&gt;</code></td><td>Maior que</td><td><code>10 &gt; 5</code></td><td><code>true</code></td></tr>
    <tr><td><code>&lt;</code></td><td>Menor que</td><td><code>10 &lt; 5</code></td><td><code>false</code></td></tr>
    <tr><td><code>&gt;=</code></td><td>Maior ou igual</td><td><code>5 &gt;= 5</code></td><td><code>true</code></td></tr>
    <tr><td><code>&lt;=</code></td><td>Menor ou igual</td><td><code>4 &lt;= 5</code></td><td><code>true</code></td></tr>
  </table></div>
  ${pg(`// == vs === — a diferença mais importante!
console.log(5 == "5");   // true  — mesmo valor, tipos diferentes (perigoso!)
console.log(5 === "5");  // false — tipos diferentes → não são iguais
console.log(5 === 5);    // true  — valor E tipo iguais ✅

console.log(10 > 5);    // true
console.log(10 < 5);    // false
console.log(10 >= 10);  // true
console.log(10 <= 9);   // false

// Comparando strings (ordem alfabética)
console.log("banana" > "abacaxi");  // true (b vem depois de a)
console.log("Z" < "a");             // true (maiúscula < minúscula em Unicode)

// null e undefined
console.log(null == undefined);   // true  (== considera iguais)
console.log(null === undefined);  // false (=== — tipos diferentes)`, 'Comparações')}
  <div class="tip"><span class="tip-i">💡</span><div><strong>Regra de ouro:</strong> sempre use <code>===</code> e <code>!==</code> (três sinais de igual). O <code>==</code> faz conversões automáticas que causam bugs difíceis de encontrar. Apenas profissionais experientes sabem quando o <code>==</code> é seguro usar.</div></div>
  `
},

{
  modulo: null, id: 'logicos', icon: '🧠', num: 7,
  badge: 'Lógica', bc: '#60a5fa',
  title: 'Operadores lógicos e truthy/falsy',
  sub: '&&, || e ! — combinando condições',
  content: () => `
  <div class="explain">
    <span class="explain-icon">🧠</span>
    <p>Os operadores lógicos combinam múltiplas condições. O <code>&&</code> (E), o <code>||</code> (OU) e o <code>!</code> (NÃO) são fundamentais para criar regras complexas no código.</p>
  </div>
  <div class="tw"><table>
    <tr><th>Operador</th><th>Nome</th><th>Resultado</th></tr>
    <tr><td><code>A && B</code></td><td>E (AND)</td><td><code>true</code> só se A <strong>e</strong> B forem verdadeiros</td></tr>
    <tr><td><code>A || B</code></td><td>OU (OR)</td><td><code>true</code> se A <strong>ou</strong> B forem verdadeiros</td></tr>
    <tr><td><code>!A</code></td><td>NÃO (NOT)</td><td>Inverte: <code>!true</code> → <code>false</code></td></tr>
  </table></div>
  ${pg(`// && (E) — true só se AMBOS forem true
console.log(true && true);   // true
console.log(true && false);  // false
console.log(false && true);  // false

// || (OU) — true se PELO MENOS UM for true
console.log(true || false);  // true
console.log(false || false); // false
console.log(false || true);  // true

// ! (NÃO) — inverte
console.log(!true);   // false
console.log(!false);  // true

// Combinando em exemplos reais
const idade = 20;
const temCarteira = true;

const podeGirar = idade >= 18 && temCarteira;
console.log("Pode dirigir?", podeGirar); // true

// TRUTHY e FALSY — valores que se comportam como true ou false
// Falsy: false, 0, "", null, undefined, NaN
// Todo o resto é truthy!
console.log("--- truthy/falsy ---");
console.log(Boolean(0));          // false (falsy)
console.log(Boolean(""));         // false (falsy)
console.log(Boolean(null));       // false (falsy)
console.log(Boolean(undefined));  // false (falsy)
console.log(Boolean(1));          // true  (truthy)
console.log(Boolean("Olá"));      // true  (truthy)
console.log(Boolean([]));         // true  (array vazio é truthy!)`, 'Lógicos e truthy/falsy')}
  <div class="tip"><span class="tip-i">💡</span><div>O <code>||</code> também serve como <strong>valor padrão</strong>: <code>const nome = inputUsuario || "Anônimo"</code> — se <code>inputUsuario</code> for vazio (falsy), usa "Anônimo". Muito usado no dia a dia!</div></div>
  `
},

// ══ MÓDULO 3 ══════════════════════════════════════════
{
  modulo: 'Módulo 3 — Entrada do Usuário',
  id: 'input-usuario', icon: '⌨️', num: 8,
  badge: 'Input', bc: '#fb923c',
  title: 'Capturando input do usuário',
  sub: 'prompt(), confirm() e como receber dados',
  content: () => `
  <div class="explain">
    <span class="explain-icon">⌨️</span>
    <p>Para fazer um programa útil, você precisa receber dados do usuário. No JavaScript puro (sem HTML), a forma mais simples é com <code>prompt()</code>, que abre uma caixinha pedindo texto.</p>
    <p>Aqui no nosso console os prompts são <em>simulados</em> — retornam um valor padrão. Em um navegador real, abrem uma caixa de diálogo!</p>
  </div>
  <div class="tw"><table>
    <tr><th>Função</th><th>O que faz</th><th>Retorna</th></tr>
    <tr><td><code>prompt("mensagem")</code></td><td>Caixa para digitar texto</td><td>String digitada ou null</td></tr>
    <tr><td><code>confirm("mensagem")</code></td><td>Caixa Sim/Não</td><td>true ou false</td></tr>
    <tr><td><code>alert("mensagem")</code></td><td>Caixa de aviso</td><td>undefined</td></tr>
  </table></div>
  ${pg(`// prompt() — pede texto ao usuário
// (aqui no curso retorna um valor padrão simulado)
const nome = prompt("Qual é o seu nome?", "Maria");
console.log("Olá,", nome + "!");

// confirm() — pergunta Sim ou Não
const confirmou = confirm("Deseja continuar?");
console.log("Confirmou?", confirmou);

// IMPORTANTE: prompt() SEMPRE retorna string!
const idadeTexto = prompt("Qual é sua idade?", "25");
console.log("Tipo:", typeof idadeTexto); // string, não number!

// Para usar como número, converta:
const idade = Number(idadeTexto);   // ou parseInt(idadeTexto)
console.log("Idade como número:", idade, "| Tipo:", typeof idade);

// Outro jeito de converter
const altura = parseFloat(prompt("Sua altura (ex: 1.75)?", "1.75"));
console.log("Altura:", altura);

// Verificando se o usuário cancelou o prompt
const input = prompt("Digite algo:", "valor padrão");
if (input === null) {
  console.log("Usuário cancelou!");
} else {
  console.log("Digitou:", input);
}`, 'Capturando input')}
  <div class="warn"><span class="warn-i">⚠️</span><div><code>prompt()</code> sempre retorna uma <strong>string</strong>. Se você quer usar o valor como número para cálculos, precisa converter: <code>Number(valor)</code> ou <code>parseInt(valor)</code>. Esquecer isso é um dos bugs mais comuns!</div></div>
  `
},

{
  modulo: null, id: 'saidas', icon: '🖥️', num: 9,
  badge: 'Input', bc: '#fb923c',
  title: 'Formas de mostrar coisas',
  sub: 'Todos os jeitos de exibir informações',
  content: () => `
  <div class="explain">
    <span class="explain-icon">🖥️</span>
    <p>No JavaScript existem várias formas de mostrar informações. Cada uma tem seu propósito. Vamos ver todas juntas para você saber quando usar cada uma!</p>
  </div>
  ${pg(`// 1. console.log — para você (desenvolvedor)
console.log("Mensagem simples");
console.log("Múltiplos valores:", 42, true, [1,2,3]);

// 2. console.table — exibe array/objeto como tabela
const pessoas = [
  { nome: "Ana", idade: 25 },
  { nome: "Bob", idade: 30 },
];
console.log("--- tabela ---");
console.log(JSON.stringify(pessoas, null, 2)); // aqui no curso

// 3. console.warn — aviso (amarelo)
console.warn("Atenção: isso está depreciado!");

// 4. console.error — erro (vermelho)
console.error("Erro: arquivo não encontrado!");

// 5. alert — popup para o usuário
alert("Cadastro realizado com sucesso!");

// 6. document.write — escreve na página (evite)
// document.write("<h1>Olá!</h1>"); // apaga a página inteira!

// 7. Concatenação manual para montar mensagens
const produto = "Notebook";
const preco = 2500;
const mensagem = "Produto: " + produto + " | Preço: R$ " + preco;
console.log(mensagem);

// 8. Template literal (jeito moderno e recomendado)
const msg2 = \`Produto: \${produto} | Preço: R$ \${preco.toFixed(2)}\`;
console.log(msg2);`, 'Formas de saída')}
  <div class="tip"><span class="tip-i">💡</span><div>Em projetos reais com HTML, você vai usar <code>elemento.textContent = "valor"</code> ou <code>elemento.innerHTML = "valor"</code> para mostrar informações na página. Mas para aprender lógica de JS puro, <code>console.log()</code> é o suficiente!</div></div>
  `
},

// ══ MÓDULO 4 ══════════════════════════════════════════
{
  modulo: 'Módulo 4 — Condicionais',
  id: 'if-else', icon: '🔀', num: 10,
  badge: 'Controle', bc: '#a78bfa',
  title: 'if / else if / else',
  sub: 'Tomando decisões no código',
  content: () => `
  <div class="explain">
    <span class="explain-icon">🔀</span>
    <p>O <code>if</code> permite que seu código <strong>tome decisões</strong>. "Se isso for verdade, faça aquilo. Senão, faça outra coisa." É a estrutura mais fundamental da programação!</p>
  </div>
  <div class="analogy">
    <div class="analogy-t">🚦 Analogia: semáforo</div>
    <p>Se o sinal está verde → avança. Senão se amarelo → prepare para parar. Senão (vermelho) → pare. Isso é exatamente o que o if/else if/else faz!</p>
  </div>
  ${pg(`// if simples — executa SE a condição for true
const hora = 14;

if (hora < 12) {
  console.log("Bom dia!");
}

// if/else — executa um OU outro
const temperatura = 35;

if (temperatura > 30) {
  console.log("Está quente! Beba água.");
} else {
  console.log("Temperatura agradável.");
}

// if / else if / else — múltiplas condições
const nota = 7.5;

if (nota >= 9) {
  console.log("Aprovado com louvor!");
} else if (nota >= 7) {
  console.log("Aprovado!");
} else if (nota >= 5) {
  console.log("Recuperação.");
} else {
  console.log("Reprovado.");
}

// Condições compostas
const idade = 20;
const temCNH = true;

if (idade >= 18 && temCNH) {
  console.log("Pode dirigir!");
} else if (idade >= 18) {
  console.log("Tem idade, mas precisa de CNH.");
} else {
  console.log("Ainda não pode dirigir.");
}`, 'if / else if / else')}
  <div class="tip"><span class="tip-i">💡</span><div>O bloco <code>else</code> é opcional! Se você não precisar de um comportamento alternativo, pode usar só o <code>if</code>. E as chaves <code>{}</code> são obrigatórias apenas quando há mais de uma linha. Para uma linha, pode omitir — mas é considerado má prática.</div></div>
  `
},

{
  modulo: null, id: 'switch', icon: '🎛️', num: 11,
  badge: 'Controle', bc: '#a78bfa',
  title: 'switch / case',
  sub: 'Quando você tem muitas opções específicas',
  content: () => `
  <div class="explain">
    <span class="explain-icon">🎛️</span>
    <p>O <code>switch</code> é útil quando você quer <strong>comparar uma variável com vários valores possíveis</strong>. É mais legível que vários <code>else if</code> quando as opções são valores exatos.</p>
  </div>
  ${pg(`// switch/case — compara uma variável com vários casos
const diaSemana = 3;
let nomeDia;

switch (diaSemana) {
  case 1:
    nomeDia = "Segunda-feira";
    break;
  case 2:
    nomeDia = "Terça-feira";
    break;
  case 3:
    nomeDia = "Quarta-feira";
    break;
  case 4:
    nomeDia = "Quinta-feira";
    break;
  case 5:
    nomeDia = "Sexta-feira";
    break;
  case 6:
    nomeDia = "Sábado";
    break;
  case 7:
    nomeDia = "Domingo";
    break;
  default:
    nomeDia = "Dia inválido";
}
console.log("Hoje é:", nomeDia);

// Agrupando casos (fall-through intencional)
const mes = 2;
let diasNoMes;

switch (mes) {
  case 2:
    diasNoMes = 28; // (simplificado, ignorando bissexto)
    break;
  case 4: case 6: case 9: case 11:
    diasNoMes = 30;
    break;
  default:
    diasNoMes = 31;
}
console.log(\`Mês \${mes} tem \${diasNoMes} dias\`);`, 'switch/case')}
  <div class="warn"><span class="warn-i">⚠️</span><div>O <code>break</code> é <strong>obrigatório</strong> no final de cada case! Sem ele, o JS continua executando o próximo case (isso se chama "fall-through"). Esquecer o <code>break</code> é um bug muito comum!</div></div>
  `
},

{
  modulo: null, id: 'ternario', icon: '❓', num: 12,
  badge: 'Controle', bc: '#a78bfa',
  title: 'Operador ternário',
  sub: 'if/else em uma única linha',
  content: () => `
  <div class="explain">
    <span class="explain-icon">❓</span>
    <p>O operador ternário é uma forma compacta de escrever um <code>if/else</code> simples em <strong>uma única linha</strong>. É muito usado no dia a dia para atribuir valores com condição.</p>
    <p>Sintaxe: <code>condição ? valorSeTrue : valorSeFalse</code></p>
  </div>
  ${pg(`// if/else normal
const idade = 20;
let status;

if (idade >= 18) {
  status = "maior de idade";
} else {
  status = "menor de idade";
}
console.log(status);

// Mesmo código com ternário — uma linha!
const status2 = idade >= 18 ? "maior de idade" : "menor de idade";
console.log(status2);

// Mais exemplos práticos
const saldo = 150;
const mensagem = saldo >= 0 ? "Conta positiva ✅" : "Conta negativa ❌";
console.log(mensagem);

// Ternário em template literal
const pontos = 85;
console.log(\`Resultado: \${pontos >= 60 ? "Aprovado" : "Reprovado"}\`);

// Ternários aninhados (use com moderação!)
const nota = 7;
const conceito = nota >= 9 ? "A" : nota >= 7 ? "B" : nota >= 5 ? "C" : "D";
console.log("Conceito:", conceito);`, 'Operador ternário')}
  <div class="tip"><span class="tip-i">💡</span><div>Use o ternário para casos simples de uma linha. Para lógica mais complexa com múltiplos blocos, prefira o <code>if/else</code> normal — fica mais legível. Ternários aninhados ficam confusos rapidamente!</div></div>
  `
},

// ══ MÓDULO 5 ══════════════════════════════════════════
{
  modulo: 'Módulo 5 — Laços de Repetição',
  id: 'for', icon: '🔁', num: 13,
  badge: 'Loops', bc: '#f472b6',
  title: 'for — repetindo com contador',
  sub: 'Quando você sabe quantas vezes quer repetir',
  content: () => `
  <div class="explain">
    <span class="explain-icon">🔁</span>
    <p>O laço <code>for</code> repete um bloco de código um número definido de vezes. É o mais usado quando você sabe exatamente <strong>quantas iterações</strong> precisa.</p>
    <p>Sintaxe: <code>for (início; condição; incremento) { código }</code></p>
  </div>
  <div class="analogy">
    <div class="analogy-t">📋 Analogia</div>
    <p>É como uma lista de tarefas numeradas: "Para cada item de 1 até 10, faça isso." O contador começa em 1, verifica se ainda não passou de 10, executa, e aumenta o contador.</p>
  </div>
  ${pg(`// for básico — conta de 1 a 5
for (let i = 1; i <= 5; i++) {
  console.log("Contagem:", i);
}

// for para somar
let soma = 0;
for (let i = 1; i <= 100; i++) {
  soma += i;
}
console.log("Soma de 1 a 100:", soma); // 5050

// for com array — percorrendo cada item
const frutas = ["maçã", "banana", "laranja", "uva"];

for (let i = 0; i < frutas.length; i++) {
  console.log(i, "→", frutas[i]);
}

// for decrescente — de 5 até 1
for (let i = 5; i >= 1; i--) {
  console.log("Contagem regressiva:", i);
}

// for com passo 2 — números pares
console.log("Pares de 0 a 10:");
for (let i = 0; i <= 10; i += 2) {
  console.log(i);
}`, 'Loop for')}
  <div class="tip"><span class="tip-i">💡</span><div>A variável do loop chama <code>i</code> por convenção (de "index" / índice). Para loops aninhados, use <code>i</code>, <code>j</code>, <code>k</code>. Arrays em JS começam no índice <strong>0</strong>, então <code>frutas[0]</code> é o primeiro item!</div></div>
  `
},

{
  modulo: null, id: 'while', icon: '⏳', num: 14,
  badge: 'Loops', bc: '#f472b6',
  title: 'while e do...while',
  sub: 'Repetindo enquanto uma condição for verdadeira',
  content: () => `
  <div class="explain">
    <span class="explain-icon">⏳</span>
    <p>O <code>while</code> repete o bloco <strong>enquanto</strong> a condição for verdadeira. É ideal quando você não sabe de antemão quantas vezes vai repetir — depende de uma condição que muda durante a execução.</p>
  </div>
  <div class="tw"><table>
    <tr><th>Loop</th><th>Quando checa a condição</th><th>Executa ao menos 1x?</th></tr>
    <tr><td><code>while</code></td><td>Antes de cada iteração</td><td>Não (pode não executar)</td></tr>
    <tr><td><code>do...while</code></td><td>Depois de cada iteração</td><td>Sim (sempre executa ao menos 1x)</td></tr>
  </table></div>
  ${pg(`// while — repete ENQUANTO a condição for true
let contador = 1;

while (contador <= 5) {
  console.log("while:", contador);
  contador++; // IMPORTANTE: sempre avance, ou loop infinito!
}

// while em situação real — tenta até acertar
let tentativas = 0;
let acertou = false;
const senhaCorreta = "js123";
const senhas = ["abc", "123", "js123", "teste"]; // simulando inputs

while (!acertou && tentativas < senhas.length) {
  const tentativa = senhas[tentativas];
  tentativas++;
  if (tentativa === senhaCorreta) {
    acertou = true;
    console.log(\`Senha correta na tentativa \${tentativas}!\`);
  } else {
    console.log(\`Tentativa \${tentativas}: "\${tentativa}" incorreta.\`);
  }
}

// do...while — executa PELO MENOS UMA VEZ
let numero = 10;

do {
  console.log("do...while:", numero);
  numero++;
} while (numero < 10); // condição false desde o início!
// Mas executou uma vez mesmo assim!`, 'while e do...while')}
  <div class="warn"><span class="warn-i">⚠️</span><div><strong>Loop infinito!</strong> Se você esquecer de avançar o contador dentro do <code>while</code>, ele roda para sempre e trava o navegador. Sempre verifique se a condição vai eventualmente se tornar <code>false</code>!</div></div>
  `
},

{
  modulo: null, id: 'for-of-in', icon: '🔄', num: 15,
  badge: 'Loops', bc: '#f472b6',
  title: 'for...of e for...in',
  sub: 'Percorrendo coleções de forma simples e elegante',
  content: () => `
  <div class="explain">
    <span class="explain-icon">🔄</span>
    <p>O <code>for...of</code> e o <code>for...in</code> são formas modernas e mais legíveis de percorrer arrays e objetos, sem precisar gerenciar um contador manualmente.</p>
  </div>
  <div class="tw"><table>
    <tr><th>Loop</th><th>Percorre</th><th>Dá acesso a</th></tr>
    <tr><td><code>for...of</code></td><td>Arrays, strings</td><td>O <strong>valor</strong> de cada item</td></tr>
    <tr><td><code>for...in</code></td><td>Objetos</td><td>A <strong>chave</strong> de cada propriedade</td></tr>
  </table></div>
  ${pg(`// for...of — percorre VALORES de um array
const frutas = ["maçã", "banana", "laranja"];

for (const fruta of frutas) {
  console.log("Fruta:", fruta);
}

// for...of em string — percorre cada caractere
const palavra = "JavaScript";
for (const letra of palavra) {
  process ? null : null; // só para não poluir
}
console.log("Letras de JS:", [...palavra].join(" - "));

// for...in — percorre CHAVES de um objeto
const pessoa = {
  nome: "Ana",
  idade: 28,
  cidade: "São Paulo"
};

for (const chave in pessoa) {
  console.log(\`\${chave}: \${pessoa[chave]}\`);
}

// break e continue — controlando loops
console.log("--- break e continue ---");

for (const num of [1, 2, 3, 4, 5, 6, 7]) {
  if (num === 4) continue; // pula o 4
  if (num === 7) break;    // para no 7
  console.log(num);
}
// Saída: 1, 2, 3, 5, 6`, 'for...of e for...in')}
  <div class="tip"><span class="tip-i">💡</span><div><code>for...of</code> com <code>const</code> é a forma mais recomendada hoje. Note que usamos <code>const fruta</code> dentro do loop — cada iteração cria uma nova variável, então não tem problema!</div></div>
  `
},

// ══ MÓDULO 6 ══════════════════════════════════════════
{
  modulo: 'Módulo 6 — Funções',
  id: 'funcoes-basico', icon: '🔧', num: 16,
  badge: 'Funções', bc: '#34d399',
  title: 'Declarando e chamando funções',
  sub: 'Blocos de código reutilizáveis',
  content: () => `
  <div class="explain">
    <span class="explain-icon">🔧</span>
    <p>Uma <strong>função</strong> é um bloco de código que você define uma vez e pode usar (chamar) quantas vezes quiser. É o principal mecanismo de <em>reutilização</em> no JavaScript.</p>
    <p>Sem funções, você teria que repetir o mesmo código em vários lugares — e se precisasse corrigir um bug, teria que corrigir em todos os lugares!</p>
  </div>
  <div class="analogy">
    <div class="analogy-t">🍕 Analogia</div>
    <p>Uma função é como uma receita de pizza. Você escreve a receita uma vez. Depois é só chamar: "Faz uma pizza!" Pode chamar quantas vezes quiser, sem reescrever a receita.</p>
  </div>
  ${pg(`// Declarando uma função
function saudar() {
  console.log("Olá! Bem-vindo ao JavaScript!");
}

// Chamando (executando) a função
saudar(); // chama uma vez
saudar(); // chama de novo — sem reescrever o código!
saudar(); // e mais uma vez

// Função que faz um cálculo
function mostrarTabuada(numero) {
  console.log(\`--- Tabuada do \${numero} ---\`);
  for (let i = 1; i <= 10; i++) {
    console.log(\`\${numero} x \${i} = \${numero * i}\`);
  }
}

mostrarTabuada(3);
mostrarTabuada(7);

// Função com return — retorna um valor
function calcularQuadrado(n) {
  return n * n;
}

const resultado = calcularQuadrado(5);
console.log("5² =", resultado); // 25
console.log("8² =", calcularQuadrado(8)); // 64`, 'Funções básicas')}
  <div class="tip"><span class="tip-i">💡</span><div>No JavaScript, funções declaradas com <code>function</code> sofrem <em>hoisting</em> — você pode chamá-las antes de defini-las no código! Mas é boa prática sempre declarar antes de usar.</div></div>
  `
},

{
  modulo: null, id: 'parametros', icon: '📨', num: 17,
  badge: 'Funções', bc: '#34d399',
  title: 'Parâmetros, argumentos e return',
  sub: 'Passando dados para dentro e recebendo resultados',
  content: () => `
  <div class="explain">
    <span class="explain-icon">📨</span>
    <p><strong>Parâmetros</strong> são as variáveis que a função aceita (definidos na declaração). <strong>Argumentos</strong> são os valores que você passa ao chamar a função. O <code>return</code> envia um resultado de volta.</p>
  </div>
  ${pg(`// Parâmetros com valores padrão
function cumprimentar(nome, saudacao = "Olá") {
  return \`\${saudacao}, \${nome}!\`;
}

console.log(cumprimentar("Maria"));          // usa padrão "Olá"
console.log(cumprimentar("João", "Oi"));     // usa "Oi"
console.log(cumprimentar("Ana", "Bem-vinda")); // usa "Bem-vinda"

// Múltiplos parâmetros e return
function calcularIMC(peso, altura) {
  const imc = peso / (altura * altura);
  return imc.toFixed(2); // 2 casas decimais
}

const meuIMC = calcularIMC(70, 1.75);
console.log("IMC:", meuIMC);

// return para de executar a função
function verificarIdade(idade) {
  if (idade < 0) {
    return "Idade inválida!"; // para aqui
  }
  if (idade < 18) {
    return "Menor de idade";  // para aqui
  }
  return "Maior de idade";   // chega aqui só se passou dos if's
}

console.log(verificarIdade(-5));  // Idade inválida!
console.log(verificarIdade(15));  // Menor de idade
console.log(verificarIdade(25));  // Maior de idade

// Função retornando objeto
function criarPessoa(nome, idade) {
  return { nome, idade, adulto: idade >= 18 };
}

const p = criarPessoa("Lucas", 22);
console.log(p);`, 'Parâmetros e return')}
  <div class="tip"><span class="tip-i">💡</span><div>Use valores padrão (<code>param = valor</code>) para tornar parâmetros opcionais. E use o <code>return</code> cedo para casos especiais (chamado de <em>early return</em>) — evita ifs aninhados e deixa o código mais limpo!</div></div>
  `
},

{
  modulo: null, id: 'arrow', icon: '➡️', num: 18,
  badge: 'Funções', bc: '#34d399',
  title: 'Arrow functions',
  sub: 'O jeito moderno e compacto de escrever funções',
  content: () => `
  <div class="explain">
    <span class="explain-icon">➡️</span>
    <p>As <strong>arrow functions</strong> (funções flecha) são uma forma mais curta de escrever funções, introduzidas no ES6 (2015). São muito usadas no JavaScript moderno!</p>
    <p>Sintaxe: <code>(parâmetros) => expressão</code></p>
  </div>
  ${pg(`// Função normal vs Arrow function
function dobrar(n) {
  return n * 2;
}

const dobrarArrow = (n) => n * 2;     // versão arrow
const dobrar2 = n => n * 2;           // parêntese opcional com 1 param

console.log(dobrar(5));       // 10
console.log(dobrarArrow(5));  // 10
console.log(dobrar2(5));      // 10

// Arrow com múltiplas linhas — precisa de {} e return
const calcularDesconto = (preco, porcentagem) => {
  const desconto = preco * (porcentagem / 100);
  const total = preco - desconto;
  return total;
};

console.log("Preço com 20% off:", calcularDesconto(100, 20));

// Arrow functions são perfeitas para callbacks (funções passadas como argumento)
const numeros = [1, 2, 3, 4, 5];

// Tradicional
const dobradosTrad = numeros.map(function(n) { return n * 2; });

// Com arrow — muito mais limpo!
const dobrados = numeros.map(n => n * 2);
const pares    = numeros.filter(n => n % 2 === 0);
const soma     = numeros.reduce((acc, n) => acc + n, 0);

console.log("Dobrados:", dobrados);
console.log("Pares:", pares);
console.log("Soma:", soma);`, 'Arrow functions')}
  <div class="tip"><span class="tip-i">💡</span><div>Arrow functions são ideais para <strong>callbacks curtos</strong> (funções passadas para map, filter, forEach, etc). Para funções mais longas com lógica complexa, as funções tradicionais com <code>function</code> ainda são preferidas por muitos devs.</div></div>
  `
},

{
  modulo: null, id: 'escopo', icon: '🔭', num: 19,
  badge: 'Funções', bc: '#34d399',
  title: 'Escopo e closure',
  sub: 'Onde as variáveis vivem e quem pode acessá-las',
  content: () => `
  <div class="explain">
    <span class="explain-icon">🔭</span>
    <p><strong>Escopo</strong> define onde uma variável existe e pode ser acessada. Variáveis têm escopo de bloco (<code>let</code>/<code>const</code>) ou de função. Uma <em>closure</em> é quando uma função "lembra" do escopo onde foi criada.</p>
  </div>
  ${pg(`// Escopo global — acessível em qualquer lugar
const globalVar = "Sou global!";

function minhaFuncao() {
  console.log(globalVar); // acessa a global ✅
  
  // Escopo local — só existe dentro da função
  const local = "Só existo aqui";
  console.log(local); // ✅
}

minhaFuncao();
// console.log(local); // ❌ ReferenceError!

// Escopo de bloco (let e const)
if (true) {
  const blocoVar = "Só existo no if";
  let outraBlocoVar = "Eu também";
  console.log(blocoVar); // ✅
}
// console.log(blocoVar); // ❌ ReferenceError!

// CLOSURE — função que lembra do escopo onde nasceu
function criarContador() {
  let count = 0; // variável "aprisionada" na closure
  
  return function() {
    count++;
    return count;
  };
}

const contador1 = criarContador();
const contador2 = criarContador(); // contador independente!

console.log(contador1()); // 1
console.log(contador1()); // 2
console.log(contador1()); // 3
console.log(contador2()); // 1 (independente!)`, 'Escopo e closure')}
  <div class="analogy">
    <div class="analogy-t">🏠 Closure = moradora que lembra do endereço</div>
    <p>A função interna do <code>criarContador</code> é como uma moradora que saiu de casa mas ainda tem a chave. Ela pode voltar e modificar o que está dentro (<code>count</code>), mesmo depois de a "fábrica" (<code>criarContador</code>) ter terminado de rodar.</p>
  </div>
  `
},

// ══ MÓDULO 7 ══════════════════════════════════════════
{
  modulo: 'Módulo 7 — Arrays',
  id: 'arrays-basico', icon: '📋', num: 20,
  badge: 'Arrays', bc: '#60a5fa',
  title: 'Criando e acessando arrays',
  sub: 'Listas de valores em uma única variável',
  content: () => `
  <div class="explain">
    <span class="explain-icon">📋</span>
    <p>Um <strong>array</strong> é uma lista ordenada de valores. Em vez de criar várias variáveis (<code>fruta1</code>, <code>fruta2</code>...), você guarda tudo em uma lista!</p>
    <p>Arrays em JS começam no índice <em>0</em> — o primeiro item é <code>array[0]</code>.</p>
  </div>
  ${pg(`// Criando arrays
const frutas = ["maçã", "banana", "laranja"];
const numeros = [1, 2, 3, 4, 5];
const misto = [42, "texto", true, null]; // pode misturar tipos!
const vazio = [];

// Acessando por índice (começa em 0!)
console.log(frutas[0]); // maçã   (primeiro)
console.log(frutas[1]); // banana (segundo)
console.log(frutas[2]); // laranja (terceiro)
console.log(frutas[3]); // undefined (não existe!)

// Tamanho do array
console.log("Total:", frutas.length); // 3

// Último item — truque com length
console.log("Último:", frutas[frutas.length - 1]); // laranja

// Modificando um item
frutas[1] = "manga"; // substitui banana por manga
console.log(frutas);

// Arrays de objetos (muito comum!)
const pessoas = [
  { nome: "Ana", idade: 25 },
  { nome: "Bob", idade: 30 },
  { nome: "Carol", idade: 28 },
];

console.log(pessoas[0].nome);  // Ana
console.log(pessoas[2].idade); // 28

// Desestruturação de array
const [primeiro, segundo, ...resto] = frutas;
console.log(primeiro, segundo, resto);`, 'Arrays básico')}
  <div class="tip"><span class="tip-i">💡</span><div><code>array.length</code> retorna o número de itens. O índice do último item é sempre <code>length - 1</code>. Nunca <code>length</code> — isso seria um item além do último!</div></div>
  `
},

{
  modulo: null, id: 'array-metodos', icon: '🛠️', num: 21,
  badge: 'Arrays', bc: '#60a5fa',
  title: 'Métodos de array',
  sub: 'push, pop, map, filter, find e muito mais',
  content: () => `
  <div class="explain">
    <span class="explain-icon">🛠️</span>
    <p>Arrays têm vários métodos embutidos que facilitam muito a vida. Vamos ver os mais usados no dia a dia!</p>
  </div>
  ${pg(`const frutas = ["maçã", "banana", "laranja"];

// ADICIONANDO E REMOVENDO
frutas.push("uva");      // adiciona no FIM
frutas.unshift("kiwi");  // adiciona no INÍCIO
console.log(frutas);

const ultimo  = frutas.pop();     // remove e retorna o último
const primeiro = frutas.shift();  // remove e retorna o primeiro
console.log("Removidos:", ultimo, primeiro);
console.log(frutas);

// ENCONTRANDO ITENS
const numeros = [10, 25, 3, 50, 8, 42];

console.log(numeros.includes(25));  // true — contém 25?
console.log(numeros.indexOf(50));   // 3 — índice do 50
console.log(numeros.find(n => n > 20));        // 25 — primeiro >20
console.log(numeros.findIndex(n => n > 20));   // 1 — índice do primeiro >20

// MAP — transforma cada item (retorna novo array)
const dobrados = numeros.map(n => n * 2);
console.log("Dobrados:", dobrados);

// FILTER — filtra itens (retorna novo array)
const grandes = numeros.filter(n => n > 20);
console.log("Maiores que 20:", grandes);

// SORT — ordena (cuidado: altera o array original!)
const ordenado = [...numeros].sort((a, b) => a - b); // crescente
console.log("Ordenado:", ordenado);

// SLICE — copia parte do array (não altera original)
const parte = numeros.slice(1, 4); // índices 1, 2, 3
console.log("Slice [1,4]:", parte);

// JOIN — junta tudo em uma string
console.log(frutas.join(", "));`, 'Métodos de array')}
  <div class="tip"><span class="tip-i">💡</span><div><code>map()</code>, <code>filter()</code> e <code>reduce()</code> não alteram o array original — eles retornam um array novo. Já <code>push()</code>, <code>pop()</code> e <code>sort()</code> alteram o original. Fique atento!</div></div>
  `
},

{
  modulo: null, id: 'foreach-reduce', icon: '♻️', num: 22,
  badge: 'Arrays', bc: '#60a5fa',
  title: 'forEach e reduce',
  sub: 'Percorrendo e acumulando valores',
  content: () => `
  <div class="explain">
    <span class="explain-icon">♻️</span>
    <p><code>forEach</code> percorre cada item do array executando uma função. <code>reduce</code> "reduz" o array a um único valor — pode ser uma soma, um objeto, qualquer coisa!</p>
  </div>
  ${pg(`// forEach — percorre sem retornar nada
const frutas = ["maçã", "banana", "laranja"];

frutas.forEach((fruta, indice) => {
  console.log(\`\${indice}: \${fruta}\`);
});

// reduce — acumula um resultado
const numeros = [10, 25, 3, 50, 8, 42];

// Soma de todos os números
const soma = numeros.reduce((acumulador, numero) => {
  return acumulador + numero;
}, 0); // 0 é o valor inicial do acumulador

console.log("Soma:", soma); // 138

// Maior número com reduce
const maior = numeros.reduce((max, n) => n > max ? n : max, numeros[0]);
console.log("Maior:", maior); // 50

// reduce para agrupar dados
const produtos = [
  { nome: "Arroz", categoria: "grão" },
  { nome: "Feijão", categoria: "grão" },
  { nome: "Maçã", categoria: "fruta" },
  { nome: "Banana", categoria: "fruta" },
];

const porCategoria = produtos.reduce((grupo, produto) => {
  const cat = produto.categoria;
  if (!grupo[cat]) grupo[cat] = [];
  grupo[cat].push(produto.nome);
  return grupo;
}, {});

console.log(JSON.stringify(porCategoria, null, 2));`, 'forEach e reduce')}
  <div class="tip"><span class="tip-i">💡</span><div><strong>Quando usar cada um:</strong> <code>forEach</code> quando só quer percorrer e executar algo (sem retorno). <code>map</code> quando quer transformar cada item. <code>filter</code> quando quer só alguns itens. <code>reduce</code> quando quer um único valor resultado.</div></div>
  `
},

// ══ MÓDULO 8 ══════════════════════════════════════════
{
  modulo: 'Módulo 8 — Objetos',
  id: 'objetos-basico', icon: '🗃️', num: 23,
  badge: 'Objetos', bc: '#fb923c',
  title: 'Criando e acessando objetos',
  sub: 'Agrupando dados relacionados com chave e valor',
  content: () => `
  <div class="explain">
    <span class="explain-icon">🗃️</span>
    <p>Um <strong>objeto</strong> é uma coleção de propriedades no formato <code>chave: valor</code>. Use quando os dados têm campos nomeados — nome, idade, endereço — em vez de uma lista simples.</p>
  </div>
  <div class="analogy">
    <div class="analogy-t">📇 Analogia: ficha de cadastro</div>
    <p>Um objeto é como uma ficha de cadastro de pessoa. Tem campos (chaves) como "nome", "cpf", "telefone", cada um com seu valor específico.</p>
  </div>
  ${pg(`// Criando um objeto
const pessoa = {
  nome: "Ana Silva",
  idade: 28,
  cidade: "São Paulo",
  ativo: true
};

// Acessando propriedades — dois jeitos
console.log(pessoa.nome);        // dot notation (mais comum)
console.log(pessoa["cidade"]);   // bracket notation

// Adicionando propriedades
pessoa.email = "ana@email.com";
pessoa["profissao"] = "Desenvolvedora";
console.log(pessoa.email);

// Modificando propriedades
pessoa.idade = 29;
console.log("Idade atualizada:", pessoa.idade);

// Deletando propriedades
delete pessoa.ativo;
console.log("ativo" in pessoa); // false — foi deletado

// Verificando se propriedade existe
console.log("nome" in pessoa);   // true
console.log("cpf" in pessoa);    // false

// Listando todas as chaves e valores
console.log("Chaves:", Object.keys(pessoa));
console.log("Valores:", Object.values(pessoa));

// Iterando com for...in
for (const chave in pessoa) {
  console.log(\`\${chave}: \${pessoa[chave]}\`);
}`, 'Objetos básico')}
  `
},

{
  modulo: null, id: 'obj-metodos', icon: '⚙️', num: 24,
  badge: 'Objetos', bc: '#fb923c',
  title: 'Métodos de objetos e this',
  sub: 'Funções dentro de objetos',
  content: () => `
  <div class="explain">
    <span class="explain-icon">⚙️</span>
    <p>Objetos podem ter <strong>métodos</strong> — que são funções dentro do objeto. Dentro de um método, <code>this</code> se refere ao próprio objeto, permitindo acessar suas propriedades.</p>
  </div>
  ${pg(`// Objeto com métodos
const calculadora = {
  resultado: 0,
  
  somar(n) {
    this.resultado += n;
    return this; // retorna o próprio objeto (permite encadeamento!)
  },
  
  subtrair(n) {
    this.resultado -= n;
    return this;
  },
  
  multiplicar(n) {
    this.resultado *= n;
    return this;
  },
  
  mostrar() {
    console.log("Resultado:", this.resultado);
    return this;
  },
  
  resetar() {
    this.resultado = 0;
    return this;
  }
};

// Encadeamento de métodos (method chaining)
calculadora
  .somar(10)
  .somar(5)
  .multiplicar(2)
  .subtrair(3)
  .mostrar(); // 27

// Objeto representando entidade real
const contaBancaria = {
  titular: "João",
  saldo: 1000,
  
  depositar(valor) {
    if (valor <= 0) {
      console.log("Valor inválido!");
      return;
    }
    this.saldo += valor;
    console.log(\`Depositado R$\${valor}. Saldo: R$\${this.saldo}\`);
  },
  
  sacar(valor) {
    if (valor > this.saldo) {
      console.log("Saldo insuficiente!");
      return;
    }
    this.saldo -= valor;
    console.log(\`Sacado R$\${valor}. Saldo: R$\${this.saldo}\`);
  }
};

contaBancaria.depositar(500);
contaBancaria.sacar(200);
contaBancaria.sacar(2000);`, 'Métodos e this')}
  `
},

{
  modulo: null, id: 'destruct-spread', icon: '✂️', num: 25,
  badge: 'Objetos', bc: '#fb923c',
  title: 'Desestruturação e spread',
  sub: 'Extraindo e combinando dados de forma elegante',
  content: () => `
  <div class="explain">
    <span class="explain-icon">✂️</span>
    <p>A <strong>desestruturação</strong> extrai valores de objetos e arrays em variáveis. O <strong>spread operator</strong> (<code>...</code>) "espalha" os elementos — é perfeito para copiar e combinar.</p>
  </div>
  ${pg(`// Desestruturação de objeto
const pessoa = { nome: "Ana", idade: 28, cidade: "SP" };

// Sem desestruturação
const nome1 = pessoa.nome;
const idade1 = pessoa.idade;

// COM desestruturação — muito mais limpo!
const { nome, idade, cidade } = pessoa;
console.log(nome, idade, cidade);

// Com valor padrão
const { pais = "Brasil" } = pessoa;
console.log(pais); // Brasil (usou o padrão)

// Renomeando ao desestruturar
const { nome: nomePessoa, idade: idadePessoa } = pessoa;
console.log(nomePessoa, idadePessoa);

// Desestruturação em parâmetros de função
function mostrarPessoa({ nome, idade }) {
  console.log(\`\${nome} tem \${idade} anos\`);
}
mostrarPessoa(pessoa);

// Spread operator — copiando objetos
const novaPessoa = { ...pessoa, email: "ana@email.com" };
console.log(novaPessoa);

// Spread para combinar objetos
const endereco = { rua: "Av. Paulista", numero: 100 };
const pessoaCompleta = { ...pessoa, ...endereco };
console.log(pessoaCompleta);

// Spread em arrays
const nums1 = [1, 2, 3];
const nums2 = [4, 5, 6];
const todos = [...nums1, ...nums2];
console.log(todos); // [1,2,3,4,5,6]`, 'Desestruturação e spread')}
  `
},

// ══ MÓDULO 9 ══════════════════════════════════════════
{
  modulo: 'Módulo 9 — Extras Essenciais',
  id: 'template-strings', icon: '📝', num: 26,
  badge: 'Extra', bc: '#a78bfa',
  title: 'Template literals e strings',
  sub: 'Trabalhando com texto de forma moderna',
  content: () => `
  <div class="explain">
    <span class="explain-icon">📝</span>
    <p>Os <strong>template literals</strong> (com crase) são a forma moderna de criar strings. Permitem interpolação de variáveis e strings de múltiplas linhas sem gambiarra!</p>
  </div>
  ${pg(`// Template literals — crases!
const nome = "João";
const idade = 25;

// Concatenação antiga (chata)
const msg1 = "Olá, " + nome + "! Você tem " + idade + " anos.";

// Template literal (moderno e limpo)
const msg2 = \`Olá, \${nome}! Você tem \${idade} anos.\`;

console.log(msg1);
console.log(msg2);

// Expressões dentro do template
const preco = 99.9;
const qtd = 3;
console.log(\`Total: R$ \${(preco * qtd).toFixed(2)}\`);

// Múltiplas linhas
const poema = \`
Linha 1
Linha 2
Linha 3
\`.trim();
console.log(poema);

// MÉTODOS DE STRING mais usados
const texto = "  Olá, Mundo!  ";

console.log(texto.trim());           // remove espaços das bordas
console.log(texto.toUpperCase());    // tudo maiúsculo
console.log(texto.toLowerCase());    // tudo minúsculo
console.log(texto.includes("Mundo")); // true
console.log(texto.replace("Mundo", "JavaScript")); // substitui
console.log("banana".split("a"));   // divide em array: ["b","n","n",""]
console.log("  oi  ".trim().length); // 2

const cpf = "12345678900";
console.log(cpf.slice(0, 3));        // "123" — fatia
console.log(cpf.padStart(14, "0"));  // adiciona zeros à esquerda
console.log("5".padStart(3, "0"));   // "005"`, 'Templates e strings')}
  `
},

{
  modulo: null, id: 'try-catch', icon: '🛡️', num: 27,
  badge: 'Extra', bc: '#a78bfa',
  title: 'try / catch / finally',
  sub: 'Tratando erros sem travar o programa',
  content: () => `
  <div class="explain">
    <span class="explain-icon">🛡️</span>
    <p>Erros acontecem — JSON inválido, número onde esperava texto, acesso a variável inexistente. O <code>try/catch</code> permite <strong>capturar erros</strong> e tratá-los sem travar o programa.</p>
  </div>
  ${pg(`// try/catch básico
try {
  // Código que pode falhar vai aqui
  const resultado = 10 / 0; // não gera erro no JS! (retorna Infinity)
  console.log("Resultado:", resultado);
  
  // Isso vai gerar erro:
  const obj = null;
  console.log(obj.propriedade); // TypeError!
  
  console.log("Isso não vai executar...");
} catch (erro) {
  // Executado SE ocorrer um erro no try
  console.log("Erro capturado:", erro.message);
  console.log("Tipo:", erro.constructor.name);
} finally {
  // SEMPRE executa, com erro ou sem erro
  console.log("Finally sempre roda!");
}

console.log("Programa continua normalmente após o catch!");

// Lançando erros intencionais com throw
function dividir(a, b) {
  if (b === 0) {
    throw new Error("Não é possível dividir por zero!");
  }
  return a / b;
}

try {
  console.log(dividir(10, 2));  // 5 — OK
  console.log(dividir(10, 0)); // lança erro!
} catch (e) {
  console.error("Erro na divisão:", e.message);
}

// Tratando JSON inválido (muito comum!)
function parsearJSON(texto) {
  try {
    return JSON.parse(texto);
  } catch (e) {
    console.warn("JSON inválido:", e.message);
    return null;
  }
}

console.log(parsearJSON('{"nome":"Ana"}'));  // objeto
console.log(parsearJSON("texto inválido"));  // null (sem travar)`, 'try/catch/finally')}
  <div class="tip"><span class="tip-i">💡</span><div>Use <code>try/catch</code> quando há operações que podem falhar: parsing de JSON, acesso a APIs, conversão de dados. Não use para cobrir erros de lógica que você deveria corrigir no código!</div></div>
  `
},

{
  modulo: null, id: 'projeto-final', icon: '🏆', num: 28,
  badge: 'Projeto', bc: '#fbbf24',
  title: 'Projeto Final: Calculadora',
  sub: 'Tudo junto num projeto real e interativo',
  content: () => `
  <div class="explain">
    <span class="explain-icon">🏆</span>
    <p>Chegou a hora de juntar tudo! Vamos criar uma <strong>calculadora interativa</strong> usando variáveis, funções, objetos, arrays, loops, condicionais e tratamento de erros.</p>
    <p>Execute o código e veja o resultado no console abaixo!</p>
  </div>
  ${pg(`// ╔═══════════════════════════════════╗
// ║   CALCULADORA JAVASCRIPT PURA     ║
// ╚═══════════════════════════════════╝

// Objeto com todas as operações
const calc = {
  historico: [],

  somar: (a, b) => a + b,
  subtrair: (a, b) => a - b,
  multiplicar: (a, b) => a * b,
  dividir(a, b) {
    if (b === 0) throw new Error("Divisão por zero!");
    return a / b;
  },

  calcular(a, op, b) {
    let resultado;
    try {
      switch (op) {
        case "+": resultado = this.somar(a, b); break;
        case "-": resultado = this.subtrair(a, b); break;
        case "*": resultado = this.multiplicar(a, b); break;
        case "/": resultado = this.dividir(a, b); break;
        default: throw new Error(\`Operador "\${op}" desconhecido!\`);
      }
      const entrada = \`\${a} \${op} \${b} = \${resultado}\`;
      this.historico.push(entrada);
      return resultado;
    } catch (e) {
      console.error("Erro:", e.message);
      return null;
    }
  },

  mostrarHistorico() {
    console.log("\\n=== Histórico ===");
    if (this.historico.length === 0) {
      console.log("Nenhum cálculo ainda.");
      return;
    }
    this.historico.forEach((h, i) => {
      console.log(\`  \${i + 1}. \${h}\`);
    });
  },

  estatisticas() {
    const resultados = this.historico.map(h => {
      const partes = h.split(" = ");
      return parseFloat(partes[1]);
    });
    if (resultados.length === 0) return;
    const soma = resultados.reduce((a, b) => a + b, 0);
    const max  = Math.max(...resultados);
    const min  = Math.min(...resultados);
    console.log("\\n=== Estatísticas ===");
    console.log(\`  Cálculos: \${resultados.length}\`);
    console.log(\`  Soma dos resultados: \${soma}\`);
    console.log(\`  Maior resultado: \${max}\`);
    console.log(\`  Menor resultado: \${min}\`);
    console.log(\`  Média: \${(soma / resultados.length).toFixed(2)}\`);
  }
};

// Executando cálculos
console.log("=== Calculadora JS ===\\n");
console.log("10 + 5 =", calc.calcular(10, "+", 5));
console.log("20 - 8 =", calc.calcular(20, "-", 8));
console.log("6 * 7 =",  calc.calcular(6, "*", 7));
console.log("15 / 3 =", calc.calcular(15, "/", 3));
console.log("10 / 0 =", calc.calcular(10, "/", 0)); // erro tratado
console.log("9 ** =",   calc.calcular(9, "**", 2)); // operador desconhecido

calc.mostrarHistorico();
calc.estatisticas();`, 'Calculadora completa')}
  <div class="card">
    <div class="card-t">✅ Tudo que você aprendeu</div>
    <ul>
      <li><strong>Variáveis:</strong> <code>let</code>, <code>const</code>, tipos de dados</li>
      <li><strong>Operadores:</strong> aritméticos, comparação, lógicos, ternário</li>
      <li><strong>Entrada:</strong> <code>prompt()</code>, <code>confirm()</code></li>
      <li><strong>Saída:</strong> <code>console.log()</code>, <code>alert()</code>, template literals</li>
      <li><strong>Condicionais:</strong> <code>if/else</code>, <code>switch</code></li>
      <li><strong>Loops:</strong> <code>for</code>, <code>while</code>, <code>for...of</code></li>
      <li><strong>Funções:</strong> declaração, parâmetros, <code>return</code>, arrow functions, closure</li>
      <li><strong>Arrays:</strong> acesso, <code>map</code>, <code>filter</code>, <code>reduce</code>, <code>forEach</code></li>
      <li><strong>Objetos:</strong> propriedades, métodos, <code>this</code>, desestruturação, spread</li>
      <li><strong>Erros:</strong> <code>try/catch/finally</code>, <code>throw</code></li>
    </ul>
  </div>
  <div class="card">
    <div class="card-t">🚀 Próximos passos</div>
    <ul>
      <li><strong>DOM:</strong> manipular HTML/CSS com JS (temos um curso dedicado!)</li>
      <li><strong>Fetch API:</strong> buscar dados de APIs externas</li>
      <li><strong>Promises e async/await:</strong> código assíncrono</li>
      <li><strong>Classes:</strong> programação orientada a objetos em JS</li>
      <li><strong>Módulos:</strong> organizar código em arquivos</li>
      <li><strong>Node.js:</strong> JavaScript no servidor</li>
    </ul>
  </div>
  `
}

]; // fim das lições

// ═══════════════════════════════════════════════
// ESTADO
// ═══════════════════════════════════════════════
let currentIndex = 0;
let chatHistory  = [];

// ═══════════════════════════════════════════════
// SIDEBAR
// ═══════════════════════════════════════════════
function buildSidebar() {
  const list = document.getElementById('menu-list');
  list.innerHTML = '';
  let lastMod = null;
  lessons.forEach((l, i) => {
    if (l.modulo && l.modulo !== lastMod) {
      lastMod = l.modulo;
      const d = document.createElement('div');
      d.className = 'mod-lbl';
      d.textContent = l.modulo.split(' — ')[1] || l.modulo;
      list.appendChild(d);
    }
    const btn = document.createElement('button');
    btn.className = 'l-btn' + (i === currentIndex ? ' active' : '');
    btn.innerHTML =
      `<span class="l-num">${String(l.num).padStart(2,'0')}</span>` +
      `<span style="flex:1;white-space:nowrap;overflow:hidden;text-overflow:ellipsis">${l.icon} ${l.title}</span>` +
      (l.badge ? `<span class="l-badge" style="background:${l.bc}22;color:${l.bc}">${l.badge}</span>` : '');
    btn.onclick = () => goToLesson(i);
    list.appendChild(btn);
  });
}

// ═══════════════════════════════════════════════
// RENDER
// ═══════════════════════════════════════════════
function renderLesson(idx) {
  const l = lessons[idx];
  const pct = Math.round(((idx + 1) / lessons.length) * 100);
  document.getElementById('prog-fill').style.width = pct + '%';
  document.getElementById('prog-n').textContent = pct + '%';
  document.getElementById('tb-t').textContent = l.icon + ' ' + l.title;

  const modNome = (l.modulo ||
    lessons.slice(0, idx).reverse().find(x => x.modulo)?.modulo ||
    'Módulo').split(' — ')[0];
  document.getElementById('breadcrumb').innerHTML =
    modNome + ' · <span>' + l.title + '</span>';

  document.getElementById('btn-prev').disabled = idx === 0;
  document.getElementById('btn-next').disabled = idx === lessons.length - 1;

  document.getElementById('content').innerHTML =
    `<div class="l-hdr">
      <div class="l-meta">
        <span class="mt">Aula ${idx + 1} de ${lessons.length}</span>
        ${l.badge ? `<span style="color:${l.bc};font-size:.75rem;font-weight:700">${l.badge}</span>` : ''}
        <span style="color:var(--texto2)">${pct}% concluído</span>
      </div>
      <div class="l-title">${l.icon} <span class="ac">${l.title}</span></div>
      <div class="l-sub">${l.sub}</div>
    </div>
    ${l.content()}
    <div style="height:50px"></div>`;

  window.scrollTo(0, 0);
}

function goToLesson(idx) {
  currentIndex = idx;
  renderLesson(idx);
  buildSidebar();
  closeSidebar();
  const active = document.querySelector('.l-btn.active');
  if (active) active.scrollIntoView({ block: 'nearest', behavior: 'smooth' });
}

function changeLesson(dir) {
  const n = currentIndex + dir;
  if (n >= 0 && n < lessons.length) goToLesson(n);
}

// ═══════════════════════════════════════════════
// UTILITÁRIOS
// ═══════════════════════════════════════════════
function cpCb(id) {
  const el = document.getElementById(id);
  navigator.clipboard.writeText(el.innerText || el.textContent).then(() => {
    const btn = el.closest('pre').querySelector('.copy-btn');
    if (btn) {
      btn.textContent = 'Copiado!';
      btn.style.color = 'var(--verde)';
      setTimeout(() => { btn.textContent = 'Copiar'; btn.style.color = ''; }, 2000);
    }
  });
}

function toggleSidebar() {
  document.getElementById('sidebar').classList.toggle('open');
  document.getElementById('overlay').classList.toggle('show');
}
function closeSidebar() {
  document.getElementById('sidebar').classList.remove('open');
  document.getElementById('overlay').classList.remove('show');
}

// ═══════════════════════════════════════════════
// CHAT IA
// ═══════════════════════════════════════════════
function toggleChat() {
  const p = document.getElementById('chat-panel');
  p.classList.toggle('open');
  if (p.classList.contains('open') && !getKey()) openSetup();
}
function openChat() {
  document.getElementById('chat-panel').classList.add('open');
  if (!getKey()) openSetup();
}
function getKey()      { return localStorage.getItem('js_ai_key') || ''; }
function getProvider() { return localStorage.getItem('js_ai_prov') || 'gemini'; }

function openSetup() {
  document.getElementById('ch-setup-box').style.display = 'block';
  document.getElementById('ai-prov').value = getProvider();
  document.getElementById('ai-key').value  = getKey();
  updHelp();
}
function updHelp() {
  const p = document.getElementById('ai-prov').value;
  document.getElementById('ai-help').innerHTML = p === 'gemini'
    ? 'Chave gratuita em <a href="https://aistudio.google.com/app/apikey" target="_blank">aistudio.google.com/app/apikey</a>'
    : 'Chave em <a href="https://console.anthropic.com/settings/keys" target="_blank">console.anthropic.com</a>';
}
function saveKey() {
  const key = document.getElementById('ai-key').value.trim();
  if (!key) return alert('Cole sua chave!');
  localStorage.setItem('js_ai_prov', document.getElementById('ai-prov').value);
  localStorage.setItem('js_ai_key', key);
  document.getElementById('ch-setup-box').style.display = 'none';
  addMsg('Configurado! ⚡ Pode perguntar sobre JavaScript!', 'ai');
}

function addMsg(txt, role) {
  const msgs = document.getElementById('ch-msgs');
  const d = document.createElement('div');
  d.className = 'msg ' + role;
  d.innerHTML = txt
    .replace(/```[\w]*\n?([\s\S]*?)```/g, (_, p) => '<pre>' + p.replace(/</g, '&lt;') + '</pre>')
    .replace(/\*\*(.*?)\*\*/g, '<strong>$1</strong>')
    .replace(/`([^`]+)`/g, '<code>$1</code>')
    .replace(/\n/g, '<br>');
  msgs.appendChild(d);
  msgs.scrollTop = msgs.scrollHeight;
  return d;
}
function addLoading() {
  const msgs = document.getElementById('ch-msgs');
  const d = document.createElement('div');
  d.className = 'msg ai msg-load';
  d.innerHTML = '<div class="dot"></div><div class="dot"></div><div class="dot"></div>';
  msgs.appendChild(d);
  msgs.scrollTop = msgs.scrollHeight;
  return d;
}

function sysprompt() {
  const l = lessons[currentIndex];
  return `Você é um professor de JavaScript muito didático e simpático.
Responda SEMPRE em português brasileiro, de forma bem simples, como se estivesse explicando para alguém que está aprendendo do zero.
Use emojis, analogias do cotidiano, e exemplos de código JavaScript em blocos de três crases com 'js'.
Aula atual: "${l.title}" — ${l.sub}.
Seja objetivo (máx 200 palavras). Se houver erro de código, explique o motivo e mostre a correção.
Explique o conceito com uma analogia do dia a dia antes de mostrar o código.`;
}

const GEMINI_MODELS = ['gemini-1.5-flash', 'gemini-2.0-flash-lite', 'gemini-1.5-flash-8b'];

async function geminiCall(key, model, hist) {
  const r = await fetch(
    `https://generativelanguage.googleapis.com/v1beta/models/${model}:generateContent?key=${key}`,
    {
      method: 'POST',
      headers: { 'Content-Type': 'application/json' },
      body: JSON.stringify({
        contents: hist.map(m => ({
          role: m.role === 'assistant' ? 'model' : 'user',
          parts: [{ text: m.content }]
        })),
        systemInstruction: { parts: [{ text: sysprompt() }] }
      })
    }
  );
  const d = await r.json();
  if (d.error) {
    const e = new Error(d.error.message || 'Erro Gemini');
    e.quota = (d.error.message || '').toLowerCase().includes('quota') ||
              (d.error.status || '').includes('RESOURCE');
    throw e;
  }
  return d.candidates?.[0]?.content?.parts?.[0]?.text || 'Tenta de novo!';
}

async function callGemini(key, hist) {
  let last;
  for (const model of GEMINI_MODELS) {
    try { return await geminiCall(key, model, hist); }
    catch(e) { last = e; if (e.quota) continue; throw e; }
  }
  throw last || new Error('Quota esgotada em todos os modelos');
}

async function callAnthropic(key, hist) {
  const r = await fetch('https://api.anthropic.com/v1/messages', {
    method: 'POST',
    headers: {
      'Content-Type': 'application/json',
      'x-api-key': key,
      'anthropic-version': '2023-06-01',
      'anthropic-dangerous-direct-browser-access': 'true'
    },
    body: JSON.stringify({
      model: 'claude-sonnet-4-5-20250929',
      max_tokens: 1000,
      system: sysprompt(),
      messages: hist
    })
  });
  const d = await r.json();
  if (d.error) throw new Error(d.error.message || 'Erro Anthropic');
  return d.content?.[0]?.text || 'Tenta de novo!';
}

async function sendChat() {
  const inp = document.getElementById('ch-inp');
  const txt = inp.value.trim();
  if (!txt) return;
  const key = getKey();
  if (!key) { openChat(); openSetup(); return; }
  inp.value = '';
  inp.style.height = 'auto';
  addMsg(txt, 'user');
  openChat();
  const load = addLoading();
  chatHistory.push({ role: 'user', content: txt });
  try {
    const rep = getProvider() === 'gemini'
      ? await callGemini(key, chatHistory.slice(-10))
      : await callAnthropic(key, chatHistory.slice(-10));
    load.remove();
    chatHistory.push({ role: 'assistant', content: rep });
    addMsg(rep, 'ai');
  } catch(err) {
    load.remove();
    const m = err.message || '';
    const msg = m.toLowerCase().includes('quota') || m.includes('esgotada')
      ? '⏳ Quota esgotada. Aguarde alguns minutos e tente novamente!'
      : m.includes('API_KEY') || m.includes('invalid')
      ? '🔑 Chave inválida — clique em ⚙️ para corrigir'
      : '❌ Erro: ' + m;
    addMsg(msg, 'ai');
  }
}

// ═══════════════════════════════════════════════
// INIT
// ═══════════════════════════════════════════════
document.addEventListener('DOMContentLoaded', function() {
  // auto-resize textarea do chat
  const inp = document.getElementById('ch-inp');
  if (inp) {
    inp.addEventListener('input', function() {
      this.style.height = 'auto';
      this.style.height = Math.min(this.scrollHeight, 90) + 'px';
    });
  }
  // inicializa a aplicação
  try {
    buildSidebar();
    renderLesson(0);
  } catch(e) {
    document.getElementById('content').innerHTML =
      '<div style="padding:40px;color:#f87171;font-family:monospace">' +
      '<h2>Erro ao carregar</h2><p>' + e.message + '</p></div>';
    console.error('Erro na inicialização:', e);
  }
});
</script>
</body>
</html>
