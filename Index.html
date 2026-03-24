<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>APEX CAPITAL — AI-Native Fund</title>
<link href="https://fonts.googleapis.com/css2?family=DM+Serif+Display:ital@0;1&family=DM+Mono:wght@300;400;500&family=Outfit:wght@300;400;500;600&display=swap" rel="stylesheet">
<style>
:root {
  --bg: #080c0f;
  --surface: #0d1117;
  --surface2: #111820;
  --border: rgba(255,255,255,0.06);
  --border-bright: rgba(255,255,255,0.12);
  --text: #e8edf2;
  --muted: #4a5568;
  --accent: #00d4aa;
  --accent2: #0090ff;
  --accent3: #ff6b35;
  --accent4: #b388ff;
  --gold: #f5c842;
  --red: #ff4466;
  --green: #00d4aa;
  --mono: 'DM Mono', monospace;
  --serif: 'DM Serif Display', serif;
  --sans: 'Outfit', sans-serif;
}
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0;}
body{font-family:var(--sans);background:var(--bg);color:var(--text);min-height:100vh;overflow-x:hidden;}
body::before{content:'';position:fixed;inset:0;background-image:linear-gradient(rgba(0,212,170,0.025) 1px,transparent 1px),linear-gradient(90deg,rgba(0,212,170,0.025) 1px,transparent 1px);background-size:40px 40px;pointer-events:none;z-index:0;}
.header{position:sticky;top:0;z-index:100;background:rgba(8,12,15,0.93);backdrop-filter:blur(16px);border-bottom:1px solid var(--border);display:flex;align-items:center;justify-content:space-between;padding:0 28px;height:56px;}
.logo{font-family:var(--serif);font-size:20px;color:var(--text);letter-spacing:0.02em;}
.logo span{color:var(--accent);}
.status-bar{display:flex;align-items:center;gap:16px;font-family:var(--mono);font-size:11px;color:var(--muted);}
.status-pill{display:flex;align-items:center;gap:6px;padding:4px 10px;border-radius:20px;border:1px solid var(--border);font-size:10px;letter-spacing:0.06em;text-transform:uppercase;}
.pulse{width:6px;height:6px;border-radius:50%;background:var(--accent);animation:pulse 2s infinite;}
@keyframes pulse{0%,100%{opacity:1;}50%{opacity:0.3;}}
.nav{display:flex;gap:0;padding:0 28px;background:var(--surface);border-bottom:1px solid var(--border);overflow-x:auto;}
.nav-item{padding:12px 18px;font-size:11px;font-weight:500;letter-spacing:0.08em;text-transform:uppercase;color:var(--muted);cursor:pointer;border-bottom:2px solid transparent;transition:all 0.15s;white-space:nowrap;}
.nav-item:hover{color:var(--text);}
.nav-item.active{color:var(--accent);border-bottom-color:var(--accent);}
.main{position:relative;z-index:1;padding:28px;max-width:1600px;margin:0 auto;}
.view{display:none;}
.view.active{display:block;}
.g2{display:grid;grid-template-columns:1fr 1fr;gap:16px;}
.g3{display:grid;grid-template-columns:1fr 1fr 1fr;gap:16px;}
.g4{display:grid;grid-template-columns:1fr 1fr 1fr 1fr;gap:16px;}
.g-left{display:grid;grid-template-columns:340px 1fr;gap:16px;}
.panel{background:var(--surface);border:1px solid var(--border);border-radius:6px;padding:20px;position:relative;overflow:hidden;}
.panel::before{content:'';position:absolute;top:0;left:0;right:0;height:1px;background:linear-gradient(90deg,transparent,rgba(0,212,170,0.3),transparent);}
.panel-title{font-family:var(--mono);font-size:10px;letter-spacing:0.14em;text-transform:uppercase;color:var(--muted);margin-bottom:14px;display:flex;align-items:center;justify-content:space-between;}
.badge{font-size:9px;padding:2px 8px;border-radius:3px;letter-spacing:0.1em;}
.metric-val{font-family:var(--serif);font-size:32px;color:var(--text);line-height:1.1;}
.metric-val.green{color:var(--green);}
.metric-val.red{color:var(--red);}
.metric-val.gold{color:var(--gold);}
.metric-label{font-size:11px;color:var(--muted);margin-top:4px;font-family:var(--mono);letter-spacing:0.06em;}
.metric-delta{font-family:var(--mono);font-size:11px;margin-top:6px;}
.empty-state{text-align:center;padding:40px 20px;}
.empty-state .icon{font-size:32px;margin-bottom:12px;opacity:0.4;}
.empty-state .title{font-family:var(--mono);font-size:11px;color:var(--muted);letter-spacing:0.1em;text-transform:uppercase;margin-bottom:6px;}
.empty-state .sub{font-size:12px;color:var(--muted);line-height:1.6;}
.real-badge{display:inline-flex;align-items:center;gap:4px;padding:2px 8px;border-radius:3px;font-family:var(--mono);font-size:9px;background:rgba(0,212,170,0.1);color:var(--accent);border:1px solid rgba(0,212,170,0.2);letter-spacing:0.08em;}
.sim-badge{display:inline-flex;align-items:center;gap:4px;padding:2px 8px;border-radius:3px;font-family:var(--mono);font-size:9px;background:rgba(245,200,66,0.08);color:var(--gold);border:1px solid rgba(245,200,66,0.2);letter-spacing:0.08em;}
.live-badge{display:inline-flex;align-items:center;gap:4px;padding:2px 8px;border-radius:3px;font-family:var(--mono);font-size:9px;background:rgba(0,144,255,0.1);color:var(--accent2);border:1px solid rgba(0,144,255,0.2);letter-spacing:0.08em;}
input,select,textarea{background:var(--surface2);border:1px solid var(--border-bright);color:var(--text);padding:9px 12px;font-family:var(--mono);font-size:12px;border-radius:4px;outline:none;transition:border-color 0.2s;width:100%;}
input:focus,select:focus{border-color:var(--accent);}
select option{background:var(--surface);}
.btn{padding:9px 20px;border:none;border-radius:4px;font-family:var(--sans);font-size:12px;font-weight:600;letter-spacing:0.04em;cursor:pointer;transition:all 0.15s;display:inline-flex;align-items:center;gap:6px;}
.btn-accent{background:var(--accent);color:var(--bg);}
.btn-accent:hover{background:#00e8bb;}
.btn-accent:disabled{opacity:0.4;cursor:not-allowed;}
.btn-ghost{background:transparent;color:var(--muted);border:1px solid var(--border-bright);}
.btn-ghost:hover{color:var(--text);}
.btn-small{padding:5px 12px;font-size:11px;}
.btn-danger-sm{background:rgba(255,68,102,0.1);color:var(--red);border:1px solid rgba(255,68,102,0.2);padding:4px 10px;font-size:10px;border-radius:3px;cursor:pointer;font-family:var(--mono);}
.agent-card{background:var(--surface2);border:1px solid var(--border);border-radius:6px;padding:16px;position:relative;overflow:hidden;transition:border-color 0.2s,box-shadow 0.2s;}
.agent-card.speaking{border-color:var(--accent);box-shadow:0 0 20px rgba(0,212,170,0.08);}
.agent-avatar{width:34px;height:34px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:15px;margin-bottom:8px;border:1px solid var(--border-bright);}
.agent-name{font-size:12px;font-weight:600;letter-spacing:0.04em;margin-bottom:1px;}
.agent-role{font-family:var(--mono);font-size:9px;color:var(--muted);letter-spacing:0.1em;text-transform:uppercase;margin-bottom:10px;}
.agent-thesis{font-size:12px;color:#94a3b8;line-height:1.65;min-height:72px;font-style:italic;}
.agent-vote{margin-top:12px;display:flex;align-items:center;gap:8px;}
.vote-chip{padding:3px 10px;border-radius:3px;font-family:var(--mono);font-size:10px;font-weight:500;letter-spacing:0.08em;text-transform:uppercase;}
.vote-bull{background:rgba(0,212,170,0.15);color:var(--accent);border:1px solid rgba(0,212,170,0.3);}
.vote-bear{background:rgba(255,68,102,0.15);color:var(--red);border:1px solid rgba(255,68,102,0.3);}
.vote-neutral{background:rgba(245,200,66,0.1);color:var(--gold);border:1px solid rgba(245,200,66,0.3);}
.vote-abstain{background:rgba(255,255,255,0.04);color:var(--muted);border:1px solid var(--border);}
.conviction-wrap{margin-top:8px;flex:1;}
.conviction-label{font-family:var(--mono);font-size:9px;color:var(--muted);margin-bottom:3px;}
.conviction-track{height:3px;background:rgba(255,255,255,0.04);border-radius:99px;}
.conviction-fill{height:100%;border-radius:99px;transition:width 0.8s ease;}
.verdict-box{background:var(--surface2);border-radius:6px;padding:20px;border:1px solid var(--border);}
.verdict-box.bull{border-color:rgba(0,212,170,0.4);background:rgba(0,212,170,0.04);}
.verdict-box.bear{border-color:rgba(255,68,102,0.4);background:rgba(255,68,102,0.04);}
.verdict-box.mixed{border-color:rgba(245,200,66,0.4);background:rgba(245,200,66,0.04);}
.verdict-label{font-family:var(--mono);font-size:9px;color:var(--muted);letter-spacing:0.12em;text-transform:uppercase;margin-bottom:6px;}
.verdict-headline{font-family:var(--serif);font-size:22px;margin-bottom:8px;}
.verdict-summary{font-size:12px;color:#94a3b8;line-height:1.65;}
.log-entry{padding:12px 0;border-bottom:1px solid var(--border);font-size:12px;line-height:1.65;}
.log-entry:last-child{border-bottom:none;}
.log-meta{font-family:var(--mono);font-size:9px;color:var(--muted);margin-bottom:5px;letter-spacing:0.08em;text-transform:uppercase;display:flex;gap:12px;}
.log-text{color:#94a3b8;}
.log-text strong{color:var(--text);font-weight:500;}
.regime-block{background:var(--surface2);border:1px solid var(--border);border-radius:4px;padding:12px 14px;margin-bottom:8px;display:flex;align-items:center;justify-content:space-between;}
.regime-bar-wrap{flex:1;margin:0 14px;height:4px;background:rgba(255,255,255,0.06);border-radius:99px;}
.regime-bar{height:100%;border-radius:99px;transition:width 1s ease;}
.risk-bar-label{font-family:var(--mono);font-size:10px;color:var(--muted);margin-bottom:4px;letter-spacing:0.06em;}
.risk-bar-track{height:5px;background:rgba(255,255,255,0.04);border-radius:99px;overflow:hidden;}
.risk-bar-fill{height:100%;border-radius:99px;transition:width 0.8s ease;}
.pos-row{display:grid;grid-template-columns:70px 90px 90px 90px 70px 100px 70px 40px;gap:8px;padding:10px 12px;border-bottom:1px solid rgba(255,255,255,0.03);font-size:12px;align-items:center;}
.pos-row:hover{background:rgba(255,255,255,0.02);}
.ticker-chip{font-family:var(--mono);font-size:11px;font-weight:600;}
.quote-card{background:var(--surface2);border:1px solid var(--border);border-radius:6px;padding:16px;transition:border-color 0.2s;}
.quote-card:hover{border-color:var(--border-bright);}
.section-header{display:flex;align-items:baseline;gap:12px;margin-bottom:20px;}
.section-title{font-family:var(--serif);font-size:26px;color:var(--text);}
.section-subtitle{font-family:var(--mono);font-size:11px;color:var(--muted);letter-spacing:0.06em;}
@keyframes thinking{0%,80%,100%{opacity:0.2;transform:scale(0.8);}40%{opacity:1;transform:scale(1);}}
.thinking-dots span{display:inline-block;width:5px;height:5px;background:var(--accent);border-radius:50%;margin:0 2px;}
.thinking-dots span:nth-child(1){animation:thinking 1.2s infinite 0s;}
.thinking-dots span:nth-child(2){animation:thinking 1.2s infinite 0.2s;}
.thinking-dots span:nth-child(3){animation:thinking 1.2s infinite 0.4s;}
.spinner{width:18px;height:18px;border:2px solid rgba(0,212,170,0.2);border-top-color:var(--accent);border-radius:50%;animation:spin 0.8s linear infinite;display:inline-block;}
@keyframes spin{to{transform:rotate(360deg);}}
.data-label{font-family:var(--mono);font-size:9px;color:var(--muted);letter-spacing:0.1em;text-transform:uppercase;margin-bottom:4px;}
.info-box{background:rgba(0,144,255,0.04);border:1px solid rgba(0,144,255,0.15);border-radius:4px;padding:12px 14px;font-size:11px;color:#64748b;line-height:1.65;margin-top:12px;}
::-webkit-scrollbar{width:4px;}
::-webkit-scrollbar-track{background:var(--surface);}
::-webkit-scrollbar-thumb{background:var(--border-bright);border-radius:2px;}
@media(max-width:900px){.g2,.g3,.g4,.g-left{grid-template-columns:1fr;}.main{padding:16px;}}
</style>
</head>
<body>
<div class="header">
  <div class="logo">APEX <span>CAPITAL</span> <span style="font-family:var(--mono);font-size:11px;color:var(--muted);font-style:normal;margin-left:8px;">AI-NATIVE FUND</span></div>
  <div class="status-bar">
    <div class="status-pill"><div class="pulse"></div>SYSTEMS LIVE</div>
    <span id="clock">--:--:--</span>
    <span id="market-status" style="font-size:10px;"></span>
  </div>
</div>

<div class="nav">
  <div class="nav-item active" onclick="showView('overview')">Overview</div>
  <div class="nav-item" onclick="showView('regime')">Regime Engine</div>
  <div class="nav-item" onclick="showView('committee')">AI Committee</div>
  <div class="nav-item" onclick="showView('risk')">Risk Models</div>
  <div class="nav-item" onclick="showView('portfolio')">Portfolio</div>
</div>

<div class="main">

<div class="view active" id="view-overview">
  <div class="section-header">
    <div class="section-title">Fund Overview</div>
    <div class="section-subtitle">LIVE MARKET DATA + AI ANALYSIS</div>
  </div>
  <div class="info-box" style="margin-bottom:20px;">
    <strong style="color:var(--accent2);">Data Transparency</strong> — <span class="real-badge">● LIVE</span> = real market data &nbsp; <span class="live-badge">● AI</span> = live Claude API &nbsp; <span class="sim-badge">◌ INPUT</span> = you enter this
  </div>
  <div class="panel" style="margin-bottom:16px;">
    <div class="panel-title">Market Snapshot — Major Indices <span class="real-badge">● LIVE DATA</span> <button class="btn btn-ghost btn-small" onclick="fetchMarketData()">↻ Refresh</button></div>
    <div class="g4" id="market-snapshot">
      <div style="text-align:center;padding:20px;color:var(--muted);grid-column:span 4;font-family:var(--mono);font-size:11px;"><div class="spinner" style="margin:0 auto 8px;"></div>Loading market data...</div>
    </div>
  </div>
  <div class="g2">
    <div class="panel">
      <div class="panel-title">Fund NAV <span class="sim-badge">◌ INPUT REQUIRED</span></div>
      <div id="fund-nav-display">
        <div class="empty-state">
          <div class="icon">📊</div>
          <div class="title">No Fund Data Yet</div>
          <div class="sub">Add your starting NAV and positions in the Portfolio tab.</div>
          <button class="btn btn-accent" style="margin-top:16px;" onclick="showView('portfolio')">Set Up Portfolio →</button>
        </div>
      </div>
    </div>
    <div class="panel">
      <div class="panel-title">Watchlist Quotes <span class="real-badge">● LIVE</span></div>
      <div style="display:flex;gap:8px;margin-bottom:14px;">
        <input type="text" id="watchlist-input" placeholder="Add ticker..." style="flex:1;" onkeydown="if(event.key==='Enter')addToWatchlist()" />
        <button class="btn btn-accent btn-small" onclick="addToWatchlist()">+ Add</button>
      </div>
      <div id="watchlist-items">
        <div class="empty-state" style="padding:20px;">
          <div class="icon">👁</div>
          <div class="title">Watchlist Empty</div>
          <div class="sub">Type a ticker above and press Enter.</div>
        </div>
      </div>
    </div>
  </div>
</div>

<div class="view" id="view-regime">
  <div class="section-header">
    <div class="section-title">Regime Detection Engine</div>
    <div class="section-subtitle">SIGNAL-BASED MARKET CLASSIFICATION</div>
  </div>
  <div class="info-box" style="margin-bottom:20px;">
    <strong style="color:var(--accent2);">How This Works</strong> — Fetches real prices for SPY, QQQ, IWM, TLT, GLD, HYG, VIX then computes momentum and cross-asset signals to classify the current market regime.
  </div>
  <div class="g2" style="margin-bottom:16px;">
    <div class="panel">
      <div class="panel-title">Current Regime <span class="real-badge">● COMPUTED</span> <button class="btn btn-ghost btn-small" onclick="runRegimeEngine()">↻ Recompute</button></div>
      <div id="regime-output">
        <div class="empty-state">
          <div class="icon">🔍</div>
          <div class="title">Regime Not Yet Computed</div>
          <div class="sub">Click Recompute to fetch current market data and classify the regime.</div>
          <button class="btn btn-accent" style="margin-top:16px;" onclick="runRegimeEngine()">Run Regime Engine</button>
        </div>
      </div>
    </div>
    <div class="panel">
      <div class="panel-title">Signal Inputs <span class="real-badge">● LIVE</span></div>
      <div id="regime-signals"><div style="text-align:center;padding:20px;color:var(--muted);font-family:var(--mono);font-size:11px;">Run engine to populate signals.</div></div>
    </div>
  </div>
  <div class="panel">
    <div class="panel-title">Regime-Conditional Allocation Framework <span class="sim-badge">◌ FRAMEWORK</span></div>
    <div id="regime-alloc-table"></div>
  </div>
</div>

<div class="view" id="view-committee">
  <div class="section-header">
    <div class="section-title">AI Investment Committee</div>
    <div class="section-subtitle">LIVE DELIBERATION — FIVE SPECIALIZED AGENTS</div>
  </div>
  <div class="info-box" style="margin-bottom:20px;">
    <strong style="color:var(--accent2);">Fully live.</strong> Five Claude agents independently analyze the asset, then ORACLE synthesizes a final decision with position sizing and risk parameters.
  </div>
  <div style="display:flex;align-items:flex-end;gap:12px;flex-wrap:wrap;margin-bottom:20px;">
    <div><div class="data-label">Ticker / Asset</div><input type="text" id="ticker-input" value="SPY" style="width:110px;text-transform:uppercase;" /></div>
    <div><div class="data-label">Timeframe</div>
      <select id="tf-select" style="width:200px;">
        <option value="short">Short-term (1–5 days)</option>
        <option value="medium" selected>Medium-term (2–6 weeks)</option>
        <option value="long">Long-term (3–12 months)</option>
      </select>
    </div>
    <div><div class="data-label">Extra Context (optional)</div><input type="text" id="context-input" placeholder="e.g. post-earnings, post-FOMC..." style="width:240px;" /></div>
    <button class="btn btn-accent" id="convene-btn" onclick="conveneCommittee()">⚡ Convene Committee</button>
    <button class="btn btn-ghost" onclick="clearCommittee()">Clear</button>
  </div>
  <div class="g-left">
    <div style="display:flex;flex-direction:column;gap:10px;" id="agent-cards"></div>
    <div>
      <div class="panel" style="margin-bottom:14px;">
        <div class="panel-title">Committee Verdict <span class="live-badge">● AI</span></div>
        <div class="verdict-box" id="verdict-box">
          <div class="verdict-label">Awaiting Deliberation</div>
          <div class="verdict-headline" style="color:var(--muted);font-size:18px;">Convene the committee to generate a live investment thesis</div>
          <div class="verdict-summary" style="margin-top:8px;">Enter a ticker and click Convene. Five AI agents will analyze independently, then ORACLE will synthesize a final decision.</div>
        </div>
      </div>
      <div class="panel">
        <div class="panel-title">Deliberation Log <span id="log-count" class="badge" style="background:rgba(255,255,255,0.04);color:var(--muted);">0 entries</span></div>
        <div id="deliberation-log" style="max-height:360px;overflow-y:auto;"></div>
      </div>
    </div>
  </div>
</div>

<div class="view" id="view-risk">
  <div class="section-header">
    <div class="section-title">Risk Models</div>
    <div class="section-subtitle">PORTFOLIO RISK FRAMEWORK</div>
  </div>
  <div class="info-box" style="margin-bottom:20px;">
    Risk metrics are computed from your actual portfolio positions. <strong style="color:var(--text);">Add positions in the Portfolio tab first.</strong>
  </div>
  <div class="g4" style="margin-bottom:16px;">
    <div class="panel"><div class="metric-val" style="font-size:22px;" id="rm-var">—</div><div class="metric-label">1-Day VaR (95%)</div></div>
    <div class="panel"><div class="metric-val" style="font-size:22px;" id="rm-pos">0</div><div class="metric-label">Open Positions</div></div>
    <div class="panel"><div class="metric-val" style="font-size:22px;" id="rm-conc">—</div><div class="metric-label">Top Position %</div></div>
    <div class="panel"><div class="metric-val" style="font-size:22px;" id="rm-cash">—</div><div class="metric-label">Cash %</div></div>
  </div>
  <div class="g2">
    <div class="panel">
      <div class="panel-title">Position Risk Attribution <span class="sim-badge">◌ FROM PORTFOLIO</span></div>
      <div id="risk-attribution-real"></div>
    </div>
    <div class="panel">
      <div class="panel-title">Risk Guardrails</div>
      <div id="risk-limits-real"></div>
    </div>
  </div>
</div>

<div class="view" id="view-portfolio">
  <div class="section-header">
    <div class="section-title">Portfolio</div>
    <div class="section-subtitle">YOUR ACTUAL POSITIONS</div>
  </div>
  <div class="g2" style="margin-bottom:16px;">
    <div class="panel">
      <div class="panel-title">Fund Settings <span class="sim-badge">◌ YOU ENTER THIS</span></div>
      <div class="g2">
        <div><div class="data-label">Starting NAV ($)</div><input type="number" id="starting-nav" placeholder="e.g. 1000000" oninput="updateFundMetrics()" /></div>
        <div><div class="data-label">Fund Name</div><input type="text" id="fund-name" placeholder="e.g. Apex Capital" oninput="updateFundMetrics()" /></div>
      </div>
    </div>
    <div class="panel">
      <div class="panel-title">Add Position <span class="sim-badge">◌ MANUAL ENTRY</span></div>
      <div style="display:grid;grid-template-columns:80px 90px 90px 80px auto;gap:8px;align-items:flex-end;">
        <div><div class="data-label">Ticker</div><input type="text" id="pos-ticker" placeholder="NVDA" style="text-transform:uppercase;" /></div>
        <div><div class="data-label">Shares</div><input type="number" id="pos-shares" placeholder="100" /></div>
        <div><div class="data-label">Entry Price</div><input type="number" id="pos-entry" placeholder="850.00" step="0.01" /></div>
        <div><div class="data-label">Direction</div><select id="pos-dir"><option>LONG</option><option>SHORT</option></select></div>
        <button class="btn btn-accent" onclick="addPosition()">Add</button>
      </div>
    </div>
  </div>
  <div class="panel">
    <div class="panel-title">Open Positions <span class="real-badge">● LIVE PRICES</span> <button class="btn btn-ghost btn-small" onclick="refreshPositionPrices()">↻ Refresh Prices</button></div>
    <div style="display:grid;grid-template-columns:70px 90px 90px 90px 70px 100px 70px 40px;gap:8px;padding:8px 12px;font-family:var(--mono);font-size:9px;color:var(--muted);letter-spacing:0.1em;text-transform:uppercase;border-bottom:1px solid var(--border);">
      <span>Ticker</span><span>Direction</span><span>Shares</span><span>Entry</span><span>Current</span><span>Mkt Value</span><span>P&L</span><span></span>
    </div>
    <div id="positions-table">
      <div class="empty-state"><div class="icon">📋</div><div class="title">No Positions Yet</div><div class="sub">Add your first position above.</div></div>
    </div>
    <div id="portfolio-totals" style="display:none;border-top:1px solid var(--border);padding:12px;display:flex;justify-content:flex-end;gap:24px;font-family:var(--mono);font-size:11px;"></div>
  </div>
</div>

</div>
<script>
let portfolio = { name: '', startingNav: 0, positions: [] };
let watchlist = [];
let deliberationLog = [];
let convening = false;
let regimeData = null;

function updateClock() {
  const now = new Date();
  document.getElementById('clock').textContent = now.toLocaleTimeString('en-US',{hour12:false});
  const ny = new Date(now.toLocaleString('en-US',{timeZone:'America/New_York'}));
  const h=ny.getHours(),m=ny.getMinutes(),day=ny.getDay();
  const isOpen=day>=1&&day<=5&&(h>9||(h===9&&m>=30))&&h<16;
  const ms=document.getElementById('market-status');
  ms.textContent=isOpen?'🟢 MARKET OPEN':'🔴 MARKET CLOSED';
  ms.style.color=isOpen?'var(--accent)':'var(--red)';
}
setInterval(updateClock,1000);
updateClock();

function showView(id) {
  document.querySelectorAll('.view').forEach(v=>v.classList.remove('active'));
  document.querySelectorAll('.nav-item').forEach(n=>n.classList.remove('active'));
  document.getElementById('view-'+id).classList.add('active');
  const names=['overview','regime','committee','risk','portfolio'];
  document.querySelectorAll('.nav-item')[names.indexOf(id)].classList.add('active');
  if(id==='risk') updateRiskView();
}

async function fetchQuote(ticker) {
  try {
    const url=`https://query1.finance.yahoo.com/v8/finance/chart/${encodeURIComponent(ticker)}?interval=1d&range=5d&cors=true`;
    const r=await fetch(url);
    const d=await r.json();
    const meta=d.result?.[0]?.meta;
    if(!meta) return null;
    const price=meta.regularMarketPrice;
    const prev=meta.chartPreviousClose||meta.previousClose;
    const change=price-prev;
    const changePct=(change/prev)*100;
    return {ticker:ticker.toUpperCase(),price,change,changePct,high:meta.regularMarketDayHigh,low:meta.regularMarketDayLow,volume:meta.regularMarketVolume,name:meta.shortName||ticker};
  } catch(e) { return null; }
}

async function fetchMultipleQuotes(tickers) {
  return Promise.all(tickers.map(fetchQuote));
}

async function fetchMarketData() {
  const el=document.getElementById('market-snapshot');
  el.innerHTML=`<div style="grid-column:span 4;text-align:center;padding:20px;color:var(--muted);font-family:var(--mono);font-size:11px;"><div class="spinner" style="margin:0 auto 8px;"></div>Fetching live data...</div>`;
  const results=await fetchMultipleQuotes(['SPY','QQQ','IWM','^VIX']);
  el.innerHTML=results.map(q=>{
    if(!q) return `<div style="background:var(--surface2);border:1px solid var(--border);border-radius:6px;padding:16px;"><div class="metric-label">Unavailable</div></div>`;
    const pos=q.change>=0;
    return `<div style="background:var(--surface2);border:1px solid var(--border);border-radius:6px;padding:16px;">
      <div style="font-family:var(--mono);font-size:10px;color:var(--muted);margin-bottom:6px;">${q.ticker}</div>
      <div style="font-family:var(--serif);font-size:26px;color:var(--text);">$${q.price?.toFixed(2)??'—'}</div>
      <div style="font-family:var(--mono);font-size:11px;margin-top:4px;color:${pos?'var(--green)':'var(--red)'};">${pos?'▲':'▼'} ${Math.abs(q.changePct??0).toFixed(2)}%</div>
      <div style="font-family:var(--mono);font-size:9px;color:var(--muted);margin-top:4px;">${q.name?.slice(0,22)??''}</div>
    </div>`;
  }).join('');
}

async function addToWatchlist() {
  const input=document.getElementById('watchlist-input');
  const t=input.value.trim().toUpperCase();
  if(!t||watchlist.includes(t)){input.value='';return;}
  watchlist.push(t);
  input.value='';
  await refreshWatchlist();
}

async function refreshWatchlist() {
  if(!watchlist.length) return;
  const el=document.getElementById('watchlist-items');
  el.innerHTML=`<div style="text-align:center;padding:12px;font-family:var(--mono);font-size:10px;color:var(--muted);"><div class="spinner" style="margin:0 auto 6px;width:14px;height:14px;"></div>Fetching...</div>`;
  const results=await fetchMultipleQuotes(watchlist);
  el.innerHTML=results.map((q,i)=>{
    if(!q) return `<div class="quote-card" style="margin-bottom:6px;display:flex;justify-content:space-between;align-items:center;padding:10px 14px;"><span style="font-family:var(--mono);font-size:12px;">${watchlist[i]}</span><span style="font-family:var(--mono);font-size:10px;color:var(--muted);">No data</span><button class="btn-danger-sm" onclick="removeWatchlist(${i})">✕</button></div>`;
    const pos=q.change>=0;
    return `<div class="quote-card" style="margin-bottom:6px;display:flex;justify-content:space-between;align-items:center;padding:10px 14px;">
      <div><span style="font-family:var(--mono);font-size:12px;font-weight:500;">${q.ticker}</span><span style="font-size:11px;color:var(--muted);margin-left:8px;">${q.name?.slice(0,20)??''}</span></div>
      <div style="text-align:right;"><div style="font-family:var(--mono);font-size:13px;">$${q.price?.toFixed(2)??'—'}</div><div style="font-family:var(--mono);font-size:10px;color:${pos?'var(--green)':'var(--red)'};">${pos?'▲':'▼'} ${Math.abs(q.changePct??0).toFixed(2)}%</div></div>
      <button class="btn-danger-sm" onclick="removeWatchlist(${i})">✕</button>
    </div>`;
  }).join('');
}

function removeWatchlist(i) {
  watchlist.splice(i,1);
  if(!watchlist.length){document.getElementById('watchlist-items').innerHTML='<div class="empty-state" style="padding:20px;"><div class="icon">👁</div><div class="title">Watchlist Empty</div><div class="sub">Type a ticker above and press Enter.</div></div>';return;}
  refreshWatchlist();
}

async function runRegimeEngine() {
  const outEl=document.getElementById('regime-output');
  const sigEl=document.getElementById('regime-signals');
  outEl.innerHTML=`<div style="text-align:center;padding:30px;font-family:var(--mono);font-size:11px;color:var(--muted);"><div class="spinner" style="margin:0 auto 10px;"></div>Fetching market data...</div>`;
  sigEl.innerHTML='';
  const results=await fetchMultipleQuotes(['SPY','QQQ','IWM','TLT','GLD','HYG','^VIX']);
  const [spy,qqq,iwm,tlt,gld,hyg,vix]=results;
  if(!spy||!qqq){outEl.innerHTML=`<div class="empty-state"><div class="icon">⚠️</div><div class="title">Data Unavailable</div><div class="sub">Could not fetch market data. Try again.</div></div>`;return;}
  const vixLevel=vix?.price??20;
  const signals=[
    {name:'SPY Day Return',val:spy.changePct>=0?'BULLISH':'BEARISH',raw:`${spy.changePct?.toFixed(2)}%`,color:spy.changePct>=0?'var(--accent)':'var(--red)'},
    {name:'QQQ Day Return',val:qqq.changePct>=0?'BULLISH':'BEARISH',raw:`${qqq.changePct?.toFixed(2)}%`,color:qqq.changePct>=0?'var(--accent)':'var(--red)'},
    {name:'VIX Level',val:vixLevel<15?'LOW (BULLISH)':vixLevel<25?'MODERATE':vixLevel<35?'ELEVATED':'EXTREME FEAR',raw:vixLevel?.toFixed(1),color:vixLevel<20?'var(--accent)':vixLevel<30?'var(--gold)':'var(--red)'},
    {name:'TLT (Bonds)',val:tlt?(tlt.changePct>0?'BONDS RALLYING':'BONDS SELLING'):'N/A',raw:tlt?`${tlt.changePct?.toFixed(2)}%`:'—',color:tlt&&tlt.changePct>0?'var(--accent4)':'var(--accent)'},
    {name:'HYG (Credit)',val:hyg?(hyg.changePct>-0.3?'SPREADS STABLE':'SPREADS WIDENING'):'N/A',raw:hyg?`${hyg.changePct?.toFixed(2)}%`:'—',color:'var(--accent)'},
    {name:'IWM (Small Cap)',val:iwm?(iwm.changePct>-0.5?'SMALL CAPS HOLDING':'SMALL CAPS LAGGING'):'N/A',raw:iwm?`${iwm.changePct?.toFixed(2)}%`:'—',color:iwm&&iwm.changePct>-0.5?'var(--accent)':'var(--gold)'},
  ];
  let bullPoints=0;
  if(spy.changePct>0) bullPoints++;
  if(qqq.changePct>0) bullPoints++;
  if(vixLevel<20) bullPoints++;
  if(hyg&&hyg.changePct>-0.3) bullPoints++;
  if(iwm&&iwm.changePct>-0.3) bullPoints++;
  if(tlt&&tlt.changePct<0) bullPoints++;
  let regime,regimeColor;
  if(bullPoints>=5){regime='BULL TREND';regimeColor='var(--accent)';}
  else if(bullPoints>=3){regime='RANGE-BOUND';regimeColor='var(--accent4)';}
  else if(vixLevel>28){regime='HIGH VOLATILITY / RISK-OFF';regimeColor='var(--gold)';}
  else{regime='BEAR TREND';regimeColor='var(--red)';}
  regimeData={regime,bullPoints,signals,vixLevel};
  const labels=['Strongly Bearish','Bearish','Mixed','Neutral','Bullish','Strongly Bullish'];
  outEl.innerHTML=`<div style="margin-bottom:16px;"><div style="font-family:var(--mono);font-size:9px;color:var(--muted);margin-bottom:6px;letter-spacing:0.1em;">DETECTED REGIME</div><div style="font-family:var(--serif);font-size:28px;color:${regimeColor};">${regime}</div><div style="font-family:var(--mono);font-size:10px;color:var(--muted);margin-top:4px;">Bull signal score: ${bullPoints}/6 factors</div></div><div>${labels.map((l,i)=>`<div style="display:flex;align-items:center;gap:10px;margin-bottom:6px;"><div style="width:110px;font-size:10px;color:var(--muted);">${l}</div><div style="flex:1;height:4px;background:rgba(255,255,255,0.04);border-radius:99px;"><div style="width:${i===bullPoints?100:0}%;height:100%;background:${regimeColor};border-radius:99px;"></div></div><div style="font-family:var(--mono);font-size:9px;color:${i===bullPoints?regimeColor:'var(--muted)'};">${i===bullPoints?'◀ NOW':''}</div></div>`).join('')}</div>`;
  sigEl.innerHTML=`<div style="display:flex;flex-direction:column;gap:6px;">${signals.map(s=>`<div style="background:var(--surface2);border:1px solid var(--border);border-radius:3px;padding:8px 12px;display:flex;justify-content:space-between;align-items:center;"><div><div style="font-family:var(--mono);font-size:9px;color:var(--muted);margin-bottom:2px;">${s.name}</div><div style="font-size:11px;color:${s.color};">${s.val}</div></div><div style="font-family:var(--mono);font-size:12px;color:${s.color};">${s.raw}</div></div>`).join('')}</div>`;
  renderRegimeAlloc();
}

function renderRegimeAlloc() {
  const el=document.getElementById('regime-alloc-table');
  if(!el) return;
  const allocs=[
    {regime:'Bull Trend',desc:'Momentum positive, low fear, credit healthy',eq:85,fi:5,alt:0,cash:10,color:'var(--accent)'},
    {regime:'Range-Bound',desc:'Mixed signals, low directional conviction',eq:55,fi:20,alt:10,cash:15,color:'var(--accent4)'},
    {regime:'High Volatility',desc:'VIX elevated, risk-off, hedges active',eq:35,fi:30,alt:15,cash:20,color:'var(--gold)'},
    {regime:'Bear Trend',desc:'Sustained selling, credit stress, preserve capital',eq:15,fi:40,alt:10,cash:35,color:'var(--red)'},
  ];
  const current=regimeData?.regime??'';
  el.innerHTML=`<div style="display:grid;grid-template-columns:140px 1fr 50px 50px 50px 50px;gap:12px;font-family:var(--mono);font-size:9px;color:var(--muted);text-transform:uppercase;padding:6px 12px;border-bottom:1px solid var(--border);letter-spacing:0.08em;"><span>Regime</span><span>Conditions</span><span>EQ</span><span>FI</span><span>ALT</span><span>CASH</span></div>`+allocs.map(a=>{
    const active=current.includes(a.regime.split(' ')[0]);
    return `<div style="display:grid;grid-template-columns:140px 1fr 50px 50px 50px 50px;gap:12px;align-items:center;padding:10px 12px;border-bottom:1px solid rgba(255,255,255,0.02);background:${active?'rgba(255,255,255,0.03)':'transparent'};"><span style="color:${a.color};font-size:10px;font-weight:500;">${a.regime}${active?' ◀':''}</span><span style="font-size:11px;color:var(--muted);">${a.desc}</span><span style="color:var(--accent);">${a.eq}%</span><span style="color:var(--accent2);">${a.fi}%</span><span style="color:var(--accent4);">${a.alt}%</span><span style="color:var(--muted);">${a.cash}%</span></div>`;
  }).join('');
}
async function addPosition() {
  const ticker=document.getElementById('pos-ticker').value.trim().toUpperCase();
  const shares=parseFloat(document.getElementById('pos-shares').value);
  const entry=parseFloat(document.getElementById('pos-entry').value);
  const dir=document.getElementById('pos-dir').value;
  if(!ticker||!shares||!entry){alert('Fill in ticker, shares, and entry price.');return;}
  portfolio.positions.push({ticker,shares,entry,dir,currentPrice:null,fetching:true});
  renderPositionsTable();
  const q=await fetchQuote(ticker);
  const pos=portfolio.positions.find(p=>p.ticker===ticker&&p.entry===entry&&p.shares===shares);
  if(pos){pos.currentPrice=q?.price??null;pos.fetching=false;}
  renderPositionsTable();
  updateFundMetrics();
  updateRiskView();
  ['pos-ticker','pos-shares','pos-entry'].forEach(id=>document.getElementById(id).value='');
}

async function refreshPositionPrices() {
  const tickers=[...new Set(portfolio.positions.map(p=>p.ticker))];
  const quotes=await fetchMultipleQuotes(tickers);
  const qmap={};
  quotes.forEach(q=>{if(q) qmap[q.ticker]=q.price;});
  portfolio.positions.forEach(p=>{if(qmap[p.ticker]) p.currentPrice=qmap[p.ticker];});
  renderPositionsTable();
  updateFundMetrics();
  updateRiskView();
}

function removePosition(i) {
  portfolio.positions.splice(i,1);
  renderPositionsTable();
  updateFundMetrics();
  updateRiskView();
}

function renderPositionsTable() {
  const el=document.getElementById('positions-table');
  const totEl=document.getElementById('portfolio-totals');
  if(!portfolio.positions.length){
    el.innerHTML=`<div class="empty-state"><div class="icon">📋</div><div class="title">No Positions Yet</div><div class="sub">Add your first position above.</div></div>`;
    totEl.style.display='none';return;
  }
  let totalValue=0,totalPnl=0;
  el.innerHTML=portfolio.positions.map((p,i)=>{
    const curr=p.currentPrice;
    const mktVal=curr?curr*p.shares:null;
    const costBasis=p.entry*p.shares;
    const pnl=mktVal?(p.dir==='LONG'?mktVal-costBasis:costBasis-mktVal):null;
    const pnlPct=pnl?(pnl/costBasis*100):null;
    if(mktVal) totalValue+=mktVal;
    if(pnl) totalPnl+=pnl;
    return `<div class="pos-row">
      <span class="ticker-chip">${p.ticker}</span>
      <span style="font-family:var(--mono);font-size:10px;padding:2px 8px;border-radius:3px;background:${p.dir==='LONG'?'rgba(0,212,170,0.1)':'rgba(255,68,102,0.1)'};color:${p.dir==='LONG'?'var(--accent)':'var(--red)'};">${p.dir}</span>
      <span style="font-family:var(--mono);font-size:11px;">${p.shares.toLocaleString()}</span>
      <span style="font-family:var(--mono);font-size:11px;">$${p.entry.toFixed(2)}</span>
      <span style="font-family:var(--mono);font-size:11px;">${p.fetching?'<div class="spinner" style="width:12px;height:12px;display:inline-block;"></div>':curr?'$'+curr.toFixed(2):'—'}</span>
      <span style="font-family:var(--mono);font-size:11px;">${mktVal?'$'+Math.round(mktVal).toLocaleString():'—'}</span>
      <span style="font-family:var(--mono);font-size:11px;color:${!pnl?'var(--muted)':pnl>=0?'var(--green)':'var(--red)'};">${pnl?`${pnl>=0?'+':''}$${Math.abs(Math.round(pnl)).toLocaleString()}`:'—'}${pnlPct?` (${pnlPct>=0?'+':''}${pnlPct.toFixed(1)}%)`:''}
      </span>
      <button class="btn-danger-sm" onclick="removePosition(${i})">✕</button>
    </div>`;
  }).join('');
  totEl.style.display='flex';
  totEl.innerHTML=`<span>Total Mkt Value: <strong style="color:var(--text);">${totalValue?'$'+Math.round(totalValue).toLocaleString():'—'}</strong></span><span>Total P&L: <strong style="color:${totalPnl>=0?'var(--green)':'var(--red)'};">${totalPnl?`${totalPnl>=0?'+':''}$${Math.abs(Math.round(totalPnl)).toLocaleString()}`:'—'}</strong></span>`;
}

function updateFundMetrics() {
  const name=document.getElementById('fund-name').value||'Your Fund';
  const nav=parseFloat(document.getElementById('starting-nav').value)||0;
  portfolio.name=name;portfolio.startingNav=nav;
  const el=document.getElementById('fund-nav-display');
  if(!nav){el.innerHTML=`<div class="empty-state"><div class="icon">📊</div><div class="title">Enter Starting NAV</div><div class="sub">Fill in fund name and starting NAV above.</div></div>`;return;}
  let totalMktVal=portfolio.positions.reduce((sum,p)=>sum+(p.currentPrice?p.currentPrice*p.shares:p.entry*p.shares),0);
  el.innerHTML=`<div style="margin-bottom:12px;font-family:var(--serif);font-size:14px;color:var(--muted);">${name}</div><div class="metric-val gold">$${nav.toLocaleString()}</div><div class="metric-label">Starting NAV</div><div style="margin-top:14px;padding-top:14px;border-top:1px solid var(--border);"><div style="display:flex;justify-content:space-between;font-family:var(--mono);font-size:11px;margin-bottom:6px;"><span style="color:var(--muted);">Deployed Capital</span><span>$${Math.round(totalMktVal).toLocaleString()}</span></div><div style="display:flex;justify-content:space-between;font-family:var(--mono);font-size:11px;"><span style="color:var(--muted);">Cash (Est.)</span><span style="color:var(--accent);">$${Math.max(0,Math.round(nav-totalMktVal)).toLocaleString()}</span></div></div>`;
}

function updateRiskView() {
  const positions=portfolio.positions;
  document.getElementById('rm-pos').textContent=positions.length;
  if(!positions.length||!portfolio.startingNav){
    document.getElementById('rm-var').textContent='—';
    document.getElementById('rm-conc').textContent='—';
    document.getElementById('rm-cash').textContent='—';
    document.getElementById('risk-attribution-real').innerHTML=`<div class="empty-state"><div class="title">No Positions</div><div class="sub">Add positions in the Portfolio tab.</div></div>`;
    renderRiskLimits(0,0,0);return;
  }
  const nav=portfolio.startingNav;
  let totalVal=0;
  const posVals=positions.map(p=>{const v=(p.currentPrice||p.entry)*p.shares;totalVal+=v;return{...p,value:v};});
  const cash=Math.max(0,nav-totalVal);
  const cashPct=(cash/nav*100).toFixed(1);
  document.getElementById('rm-cash').textContent=cashPct+'%';
  const maxPos=Math.max(...posVals.map(p=>p.value));
  const concPct=(maxPos/nav*100).toFixed(1);
  document.getElementById('rm-conc').textContent=concPct+'%';
  const var95=totalVal*0.02*1.645;
  document.getElementById('rm-var').textContent='-$'+Math.round(var95).toLocaleString();
  document.getElementById('risk-attribution-real').innerHTML=`<div style="display:grid;grid-template-columns:70px 1fr 80px;gap:8px;font-family:var(--mono);font-size:9px;color:var(--muted);text-transform:uppercase;padding:0 0 8px;border-bottom:1px solid var(--border);margin-bottom:8px;letter-spacing:0.08em;"><span>Ticker</span><span>Weight</span><span>Est. VaR</span></div>`+posVals.sort((a,b)=>b.value-a.value).map(p=>{const wt=(p.value/nav*100).toFixed(1);const pvar=Math.round(p.value*0.02*1.645);return `<div style="display:grid;grid-template-columns:70px 1fr 80px;gap:8px;align-items:center;padding:7px 0;border-bottom:1px solid rgba(255,255,255,0.02);"><span style="font-family:var(--mono);font-size:11px;font-weight:600;">${p.ticker}</span><div><div class="risk-bar-track"><div class="risk-bar-fill" style="width:${Math.min(100,parseFloat(wt)*2)}%;background:var(--accent);"></div></div></div><span style="font-family:var(--mono);font-size:10px;color:var(--red);">-$${pvar.toLocaleString()}</span></div>`;}).join('');
  renderRiskLimits(parseFloat(concPct),parseFloat(cashPct),totalVal/nav*100);
}

function renderRiskLimits(concPct,cashPct,deployedPct) {
  const el=document.getElementById('risk-limits-real');
  if(!el) return;
  const limits=[
    {rule:'Single position < 25% NAV',ok:concPct<25||concPct===0,val:concPct?concPct+'%':'—'},
    {rule:'Cash buffer > 5% NAV',ok:cashPct>5||cashPct===0,val:cashPct?cashPct+'%':'—'},
    {rule:'Gross deployment < 100% NAV',ok:deployedPct<100,val:deployedPct?deployedPct.toFixed(1)+'%':'—'},
  ];
  el.innerHTML=limits.map(l=>`<div style="display:flex;justify-content:space-between;align-items:center;padding:10px 0;border-bottom:1px solid rgba(255,255,255,0.03);"><span style="font-size:12px;">${l.rule}</span><div style="display:flex;align-items:center;gap:10px;"><span style="font-family:var(--mono);font-size:11px;color:var(--muted);">${l.val}</span><span style="font-family:var(--mono);font-size:9px;padding:2px 8px;border-radius:3px;background:${l.ok?'rgba(0,212,170,0.1)':'rgba(255,68,102,0.1)'};color:${l.ok?'var(--accent)':'var(--red)'};">${l.ok?'✓ OK':'⚠ BREACH'}</span></div></div>`).join('');
}

const AGENTS=[
  {id:'macro',name:'MIRA',role:'Macro Strategist',avatar:'🌐',color:'var(--accent2)',persona:'You are MIRA, a macro strategist AI for a hedge fund. Analyze global macro: central bank policy, yield curves, currency dynamics, commodity cycles, credit spreads, geopolitical risk. Be precise and data-driven. Keep thesis to 2-4 sentences.'},
  {id:'quant',name:'AXIOM',role:'Quantitative Analyst',avatar:'📊',color:'var(--accent)',persona:'You are AXIOM, a quantitative analyst AI for a hedge fund. Evaluate statistical signals: momentum, mean-reversion, factor loadings, volatility regimes, technical patterns. Trust price action over narratives. Keep thesis to 2-4 sentences.'},
  {id:'fundamental',name:'VERA',role:'Fundamental Analyst',avatar:'🔬',color:'var(--accent4)',persona:'You are VERA, a fundamental analyst AI for a hedge fund. Assess business quality, earnings trajectory, competitive moats, sector dynamics, valuation. Think like a long-term investor. Keep thesis to 2-4 sentences.'},
  {id:'risk',name:'SENTINEL',role:'Chief Risk Officer',avatar:'🛡',color:'var(--gold)',persona:'You are SENTINEL, the risk officer AI for a hedge fund. Scrutinize downside: position sizing, correlation risks, drawdown potential, liquidity, tail risks. Be the devil\'s advocate. Keep thesis to 2-4 sentences.'},
  {id:'chair',name:'ORACLE',role:'Committee Chair',avatar:'⚡',color:'var(--accent3)',persona:'You are ORACLE, AI investment committee chair. Synthesize views from MIRA (macro), AXIOM (quant), VERA (fundamental), SENTINEL (risk) into a final decision: STRONG BUY, BUY, HOLD, SELL, or STRONG SELL with specific position size and stop-loss.'},
];

function renderAgentCards() {
  document.getElementById('agent-cards').innerHTML=AGENTS.map(a=>`<div class="agent-card" id="agent-${a.id}"><div style="display:flex;align-items:center;gap:10px;margin-bottom:8px;"><div class="agent-avatar">${a.avatar}</div><div><div class="agent-name" style="color:${a.color};">${a.name}</div><div class="agent-role">${a.role}</div></div></div><div class="agent-thesis" id="thesis-${a.id}">Standing by...</div><div class="agent-vote" id="vote-${a.id}" style="display:none;"><div class="vote-chip vote-abstain" id="votechip-${a.id}">—</div><div class="conviction-wrap"><div class="conviction-label">Conviction</div><div class="conviction-track"><div class="conviction-fill" id="conv-${a.id}" style="width:0%;background:${a.color};"></div></div></div></div></div>`).join('');
}

function setThinking(id) {
  document.getElementById('agent-'+id)?.classList.add('speaking');
  const t=document.getElementById('thesis-'+id);
  if(t) t.innerHTML='<div class="thinking-dots"><span></span><span></span><span></span></div>';
}

function setResult(id,text,vote,conviction) {
  document.getElementById('agent-'+id)?.classList.remove('speaking');
  const t=document.getElementById('thesis-'+id);
  if(t) t.innerHTML=text;
  const v=document.getElementById('vote-'+id);
  const chip=document.getElementById('votechip-'+id);
  const conv=document.getElementById('conv-'+id);
  if(v) v.style.display='flex';
  if(chip){const cls={BUY:'vote-bull','STRONG BUY':'vote-bull',SELL:'vote-bear','STRONG SELL':'vote-bear',HOLD:'vote-neutral',NEUTRAL:'vote-neutral'};chip.className='vote-chip '+(cls[vote]||'vote-neutral');chip.textContent=vote;}
  if(conv) setTimeout(()=>{conv.style.width=conviction+'%';},100);
}

function addLog(name,role,text) {
  deliberationLog.push({name,role,text,time:new Date().toLocaleTimeString('en-US',{hour12:false})});
  const el=document.getElementById('deliberation-log');
  el.innerHTML=deliberationLog.slice().reverse().map(e=>`<div class="log-entry"><div class="log-meta"><span style="color:var(--accent);">${e.name}</span><span>${e.role}</span><span>${e.time}</span></div><div class="log-text">${e.text}</div></div>`).join('');
  document.getElementById('log-count').textContent=deliberationLog.length+' entries';
}

async function callClaude(sys,msg) {
  const r=await fetch("https://api.anthropic.com/v1/messages",{method:"POST",headers:{"Content-Type":"application/json"},body:JSON.stringify({model:"claude-sonnet-4-20250514",max_tokens:1000,system:sys,messages:[{role:"user",content:msg}]})});
  if(!r.ok) throw new Error('API '+r.status);
  const d=await r.json();
  return d.content[0].text;
}

async function conveneCommittee() {
  if(convening) return;
  convening=true;
  const ticker=document.getElementById('ticker-input').value.toUpperCase().trim()||'SPY';
  const tf=document.getElementById('tf-select').value;
  const ctx=document.getElementById('context-input').value.trim();
  const tfLabel={short:'1-5 day',medium:'2-6 week',long:'3-12 month'}[tf];
  const btn=document.getElementById('convene-btn');
  btn.disabled=true;btn.innerHTML='<div class="spinner"></div> Deliberating...';
  deliberationLog=[];
  renderAgentCards();
  document.getElementById('verdict-box').className='verdict-box';
  document.getElementById('verdict-box').innerHTML=`<div class="verdict-label">In Session</div><div class="verdict-headline" style="color:var(--muted);font-size:18px;">Agents deliberating...</div>`;
  const q=await fetchQuote(ticker);
  let quoteCtx=q?` Current price: $${q.price?.toFixed(2)}. Day change: ${q.changePct?.toFixed(2)}%.`:'';
  const regimeCtx=regimeData?`Current market regime: ${regimeData.regime}. VIX: ${regimeData.vixLevel?.toFixed(1)}.`:'Market regime not computed.';
  const prompt=`Asset: ${ticker}. Timeframe: ${tfLabel}.${quoteCtx} ${regimeCtx}${ctx?' Context: '+ctx:''}`;
  let outputs={};
  for(let i=0;i<4;i++){
    const a=AGENTS[i];
    setThinking(a.id);
    try{
      const sys=a.persona+`\n\nRespond ONLY in this JSON (no markdown):\n{"thesis":"...","vote":"STRONG BUY|BUY|HOLD|SELL|STRONG SELL","conviction":75}`;
      const raw=await callClaude(sys,prompt);
      let parsed;
      try{parsed=JSON.parse(raw.replace(/```json|```/g,'').trim());}catch{parsed={thesis:raw.slice(0,300),vote:'HOLD',conviction:50};}
      outputs[a.id]=parsed;
      setResult(a.id,parsed.thesis,parsed.vote,parsed.conviction);
      addLog(a.name,a.role,parsed.thesis);
    }catch(e){
      setResult(a.id,'Analysis unavailable.','HOLD',0);
      outputs[a.id]={thesis:'Unavailable',vote:'HOLD',conviction:0};
    }
    await new Promise(r=>setTimeout(r,200));
  }
  const chair=AGENTS[4];
  setThinking(chair.id);
  const synthPrompt=`${prompt}\n\nCommittee:\n- MIRA: ${outputs.macro?.vote} — ${outputs.macro?.thesis}\n- AXIOM: ${outputs.quant?.vote} — ${outputs.quant?.thesis}\n- VERA: ${outputs.fundamental?.vote} — ${outputs.fundamental?.thesis}\n- SENTINEL: ${outputs.risk?.vote} — ${outputs.risk?.thesis}\n\nSynthesize into final decision.`;
  try{
    const sys=chair.persona+`\n\nRespond ONLY in this JSON (no markdown):\n{"thesis":"...","vote":"STRONG BUY|BUY|HOLD|SELL|STRONG SELL","conviction":80,"position_size":"X% of portfolio","stop_loss":"stop at -X% from entry","headline":"short verdict headline"}`;
    const raw=await callClaude(sys,synthPrompt);
    let parsed;
    try{parsed=JSON.parse(raw.replace(/```json|```/g,'').trim());}catch{parsed={thesis:raw.slice(0,400),vote:'HOLD',conviction:50,position_size:'2% of portfolio',stop_loss:'-8% from entry',headline:'Mixed signals'};}
    setResult(chair.id,parsed.thesis,parsed.vote,parsed.conviction);
    addLog(chair.name,chair.role,`FINAL: ${parsed.vote} — ${parsed.thesis} | Size: ${parsed.position_size} | Stop: ${parsed.stop_loss}`);
    const cls=['STRONG BUY','BUY'].includes(parsed.vote)?'bull':['STRONG SELL','SELL'].includes(parsed.vote)?'bear':'mixed';
    const color=cls==='bull'?'var(--green)':cls==='bear'?'var(--red)':'var(--gold)';
    document.getElementById('verdict-box').className='verdict-box '+cls;
    document.getElementById('verdict-box').innerHTML=`<div class="verdict-label">Final Decision — ${ticker} — ${tfLabel}</div><div class="verdict-headline" style="color:${color};">${parsed.vote}</div><div style="font-size:13px;color:#94a3b8;line-height:1.65;margin:10px 0;">${parsed.thesis}</div><div style="display:flex;gap:20px;margin-top:12px;padding-top:12px;border-top:1px solid var(--border);"><div><div style="font-family:var(--mono);font-size:9px;color:var(--muted);margin-bottom:3px;">POSITION SIZE</div><div style="font-family:var(--mono);font-size:12px;color:var(--text);">${parsed.position_size}</div></div><div><div style="font-family:var(--mono);font-size:9px;color:var(--muted);margin-bottom:3px;">STOP LOSS</div><div style="font-family:var(--mono);font-size:12px;color:var(--red);">${parsed.stop_loss}</div></div><div><div style="font-family:var(--mono);font-size:9px;color:var(--muted);margin-bottom:3px;">CONVICTION</div><div style="font-family:var(--mono);font-size:12px;color:${color};">${parsed.conviction}%</div></div></div>`;
  }catch(e){
    setResult(chair.id,'Synthesis unavailable.','HOLD',0);
  }
  btn.disabled=false;btn.innerHTML='⚡ Convene Committee';
  convening=false;
}

function clearCommittee(){
  deliberationLog=[];
  renderAgentCards();
  document.getElementById('deliberation-log').innerHTML='';
  document.getElementById('log-count').textContent='0 entries';
  document.getElementById('verdict-box').className='verdict-box';
  document.getElementById('verdict-box').innerHTML=`<div class="verdict-label">Awaiting Deliberation</div><div class="verdict-headline" style="color:var(--muted);font-size:18px;">Convene the committee to generate a live investment thesis</div>`;
}

renderAgentCards();
renderRegimeAlloc();
fetchMarketData();
setInterval(fetchMarketData,60000);
</script>
</body>
</html>
