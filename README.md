<!--
Hezekiahs_Olushola_GitHub_README.html
Replace placeholders like {GH_USERNAME}, {WEBSITE}, {LINKEDIN}, {X_HANDLE} with your real links.
This is a single-file professional README that you can use as GitHub Profile README HTML (GitHub renders Markdown; to use HTML paste as README.md — GitHub supports a subset of HTML; for full effect host this as GitHub Pages). 
-->
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Hezekiahs Olushola — Software & Web3 Engineer</title>
  <style>
    :root{--bg:#0f1724;--card:#0b1120;--muted:#9aa4b2;--accent:#7c3aed;--glass:rgba(255,255,255,0.04)}
    *{box-sizing:border-box}
    body{margin:0;font-family:Inter,ui-sans-serif,system-ui,-apple-system,Segoe UI,Roboto,'Helvetica Neue',Arial;color:#e6eef8;background:linear-gradient(180deg,#07101a 0%, #071525 60%);-webkit-font-smoothing:antialiased}
    .container{max-width:980px;margin:36px auto;padding:28px}
    .card{background:linear-gradient(180deg,rgba(255,255,255,0.02),transparent);border-radius:14px;padding:22px;margin-bottom:20px;box-shadow:0 6px 30px rgba(2,6,23,0.6);border:1px solid rgba(255,255,255,0.03)}
    .hero{display:flex;gap:20px;align-items:center}
    .avatar{width:120px;height:120px;border-radius:20px;flex-shrink:0;background:linear-gradient(135deg,var(--accent),#06b6d4);display:flex;align-items:center;justify-content:center;color:white;font-weight:700;font-size:28px;box-shadow:0 6px 30px rgba(124,58,237,0.18)}
    h1{margin:0;font-size:26px}
    p.lead{color:var(--muted);margin:8px 0 0}
    .chips{display:flex;flex-wrap:wrap;gap:8px;margin-top:12px}
    .chip{background:var(--glass);padding:8px 12px;border-radius:999px;font-size:13px;color:var(--muted);border:1px solid rgba(255,255,255,0.02)}

    /* Animated title underlines */
    .title-wrap{position:relative;display:inline-block}
    .underline{position:absolute;left:0;right:0;height:6px;border-radius:999px;bottom:-6px;transform-origin:left;background:linear-gradient(90deg,rgba(124,58,237,0.9),rgba(6,182,212,0.9));animation:slide 3.5s infinite}
    @keyframes slide{0%{transform:scaleX(0)}50%{transform:scaleX(1)}100%{transform:scaleX(0)}}

    /* Grid for projects */
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:14px;margin-top:18px}
    .project{background:linear-gradient(180deg,rgba(255,255,255,0.02),transparent);padding:14px;border-radius:12px;border:1px solid rgba(255,255,255,0.02);min-height:110px;display:flex;flex-direction:column;justify-content:space-between}
    .project h3{margin:0;font-size:15px}
    .project p{margin:6px 0 0;color:var(--muted);font-size:13px}

    /* badges row */
    .badges{display:flex;flex-wrap:wrap;gap:8px;margin-top:12px}
    .badge{padding:6px 10px;border-radius:999px;background:rgba(255,255,255,0.02);border:1px solid rgba(255,255,255,0.03);font-size:12px;color:var(--muted)}

    /* CTA */
    .cta{display:flex;gap:12px;margin-top:18px}
    .btn{padding:10px 14px;border-radius:10px;background:linear-gradient(90deg,var(--accent),#06b6d4);color:white;text-decoration:none;font-weight:600}
    .ghost{padding:10px 14px;border-radius:10px;border:1px solid rgba(255,255,255,0.06);color:var(--muted);text-decoration:none}

    /* Footer */
    .footer{display:flex;justify-content:space-between;align-items:center;margin-top:16px;color:var(--muted);font-size:13px}

    /* small responsive tweaks */
    @media (max-width:640px){.hero{flex-direction:column;align-items:flex-start}.avatar{width:96px;height:96px}}

    /* subtle float animation for avatar */
    .avatar{animation:float 6s ease-in-out infinite}
    @keyframes float{0%{transform:translateY(0)}50%{transform:translateY(-6px)}100%{transform:translateY(0)}}

    /* ribbon */
    .ribbon{position:absolute;right:18px;top:18px;background:linear-gradient(90deg,#06b6d4, #7c3aed);padding:8px 12px;border-radius:10px;color:white;font-weight:700;font-size:12px;box-shadow:0 6px 24px rgba(7,10,20,0.6)}

    /* subtle glass border accent */
    .accent-border{border-left:4px solid rgba(124,58,237,0.12);padding-left:16px}
  </style>
</head>
<body>
  <div class="container">
    <div class="card" style="position:relative;overflow:hidden">
      <div class="ribbon">ALX SWE '25</div>
      <div class="hero">
        <div class="avatar">HO</div>
        <div style="flex:1">
          <div class="title-wrap"><h1>Hezekiahs Olushola — Full‑stack & Web3 Engineer</h1><div class="underline"></div></div>
          <p class="lead">MERN • React Native • Flutter • Swift • Python • DevOps • Data Engineering • AI + IIoT in Food Engineering • Music Producer</p>

          <div class="chips">
            <div class="chip">4 years in tech</div>
            <div class="chip">Web3 / Smart Contracts</div>
            <div class="chip">Spot trading @BingX</div>
            <div class="chip">Tech Support @Borderless Tech Kano</div>
          </div>

          <div class="badges">
            <span class="badge">Open to: Collaborations</span>
            <span class="badge">Location: Kano, Nigeria</span>
            <span class="badge">ALX SWE Grad 2025</span>
          </div>

          <div class="cta">
            <a class="btn" href="{WEBSITE}" target="_blank">Portfolio</a>
            <a class="ghost" href="https://github.com/{GH_USERNAME}?tab=repositories" target="_blank">All projects</a>
          </div>
        </div>
      </div>
    </div>

    <div class="card accent-border">
      <h2 style="margin-top:0">Selected Projects</h2>
      <div class="grid">
        <div class="project">
          <div>
            <h3>SmartFood — IIoT + Web3 Food Traceability</h3>
            <p>AI-driven sensor pipeline for food quality, indexed on-chain for provenance & auditing (Python, MQTT, Solidity).</p>
          </div>
          <div style="text-align:right"><a class="ghost" href="{WEBSITE}" target="_blank">View</a></div>
        </div>

        <div class="project">
          <div>
            <h3>TradeKit — Spot trading tools</h3>
            <p>Scripted strategies and data pipelines for exchange interaction & analytics (BingX integrations).</p>
          </div>
          <div style="text-align:right"><a class="ghost" href="{WEBSITE}" target="_blank">View</a></div>
        </div>

        <div class="project">
          <div>
            <h3>SoundLab — Music production & DSP tools</h3>
            <p>Tools and sample libraries for production, plus demo live-mixing components (JS, native audio).</p>
          </div>
          <div style="text-align:right"><a class="ghost" href="{WEBSITE}" target="_blank">View</a></div>
        </div>
      </div>
    </div>

    <div class="card">
      <h2 style="margin-top:0">Technical Snapshot</h2>
      <div class="chips" style="margin-top:12px">
        <div class="chip">MERN Stack</div>
        <div class="chip">React Native / Flutter / Swift</div>
        <div class="chip">Solidity & Web3</div>
        <div class="chip">Python • Data Engineering</div>
        <div class="chip">DevOps • CI/CD</div>
        <div class="chip">AI • IIoT</div>
        <div class="chip">Music Production</div>
      </div>

      <div class="footer">
        <div>Contact: <strong><a href="https://x.com/{X_HANDLE}" target="_blank" style="color:inherit;text-decoration:none">@{X_HANDLE}</a></strong></div>
        <div>More: <a href="{LINKEDIN}" target="_blank" style="color:inherit;text-decoration:none">LinkedIn</a> • <a href="{WEBSITE}" target="_blank" style="color:inherit;text-decoration:none">Portfolio</a></div>
      </div>
    </div>

  </div>
</body>
</html>
