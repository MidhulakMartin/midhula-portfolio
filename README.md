<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Midhula K Martin • QA Tester & Data Analytics</title>
  <meta name="description" content="Portfolio of Midhula K Martin — Software Test Engineer & Data Analytics Enthusiast." />
  <style>
    /* ===================== THEME ===================== */
    :root{
      --bg:#0b1220; --panel:#121a2b; --text:#e7ecff; --muted:#9fb0d6;
      --brand:#8a7dff; /* lavender-ish */
      --ring:rgba(138,125,255,.25); --chip:#2a3350; --chipText:#e7ecff;
      --btnText:#0b1220;
    }
    html[data-theme="light"]{
      --bg:#f6f8ff; --panel:#ffffff; --text:#0d1530; --muted:#5b6b91;
      --brand:#725bff; --ring:rgba(114,91,255,.2); --chip:#eef1ff; --chipText:#2a3350; --btnText:#ffffff;
    }
    *{box-sizing:border-box}
    body{
      margin:0; font:16px/1.6 system-ui, -apple-system, Segoe UI, Roboto, "Helvetica Neue", Arial;
      background:var(--bg); color:var(--text);
    }
    a{color:var(--brand); text-decoration:none}
    .wrap{max-width:1080px; margin:auto; padding:24px}
    header.hero{
      display:grid; gap:18px; grid-template-columns:1fr; padding:28px; border-radius:20px;
      background:linear-gradient(140deg, rgba(138,125,255,.12), transparent 40%), var(--panel);
      border:1px solid rgba(255,255,255,.07);
    }
    .eyebrow{display:inline-flex; gap:8px; align-items:center; padding:4px 10px; border-radius:999px;
      background:linear-gradient(90deg, var(--brand), #a58bff); color:#fff; font-weight:600; font-size:12px;}
    h1{margin:0; font-size:32px}
    .lead{margin:2px 0 8px; color:var(--muted)}
    .cta{display:flex; flex-wrap:wrap; gap:10px; margin-top:6px}
    .btn{
      display:inline-flex; align-items:center; gap:8px; padding:10px 14px; border-radius:12px; font-weight:700;
      border:1px solid var(--brand); color:var(--btnText); background:var(--brand);
    }
    .btn.ghost{background:transparent; color:var(--brand)}
    .toolbar{display:flex; gap:10px; align-items:center; justify-content:flex-end; margin:10px 0 0}
    .toggle{cursor:pointer; border:1px solid rgba(255,255,255,.2); padding:6px 10px; border-radius:999px; color:var(--muted)}
    /* ===================== SKILLS ===================== */
    .section{padding:36px 0}
    .section__title{margin:0 0 14px; font-size:24px}
    .chips{display:flex; gap:10px; flex-wrap:wrap}
    .chip{padding:6px 12px; border-radius:999px; background:var(--chip); color:var(--chipText); font-size:14px}
    /* ===================== PROJECTS ===================== */
    .filters{display:flex; gap:8px; flex-wrap:wrap; margin:8px 0 18px}
    .filter{padding:6px 12px; border-radius:999px; border:1px solid var(--brand); color:var(--text); background:transparent; cursor:pointer}
    .filter.active, .filter:hover{background:var(--brand); color:#fff}
    .grid{display:grid; gap:20px; grid-template-columns:repeat(auto-fill,minmax(270px,1fr))}
    .card{background:var(--panel); border:1px solid rgba(255,255,255,.07); border-radius:16px; overflow:hidden;
      transition:transform .2s ease, box-shadow .2s ease}
    .card:hover{transform:translateY(-2px); box-shadow:0 10px 24px var(--ring)}
    .thumb{aspect-ratio:16/9; background:#0f1730}
    .thumb img{width:100%; height:100%; object-fit:cover; display:block}
    .body{padding:14px 16px 16px}
    .title{margin:6px 0 6px; font-size:18px}
    .desc{color:var(--muted); font-size:14px}
    .tags{display:flex; gap:8px; flex-wrap:wrap; margin:10px 0 12px}
    .tag{font-size:12px; padding:4px 8px; border-radius:999px; background:linear-gradient(90deg,var(--brand),#a58bff); color:#fff}
    .links{display:flex; gap:12px; flex-wrap:wrap}
    .links a{border-bottom:1px dashed var(--brand)}
    /* ===================== FOOTER ===================== */
    footer{margin:28px 0 12px; color:var(--muted); text-align:center}
    @media (min-width:800px){
      header.hero{grid-template-columns:1.1fr .9fr; align-items:center}
      .rightbox{min-height:180px; border:1px dashed rgba(255,255,255,.12); border-radius:16px}
    }
  </style>
</head>
<body>
  <div class="wrap">
    <div class="toolbar">
      <button id="themeToggle" class="toggle" aria-label="Toggle theme">🌙/☀️</button>
    </div>

    <header class="hero">
      <div>
        <span class="eyebrow">Open to Work • Calgary, Canada</span>
        <h1>Midhula K Martin</h1>
        <p class="lead">QA Tester & Data Analytics — I test, analyze and ship reliable software.
          2+ years in manual testing with growing automation & analytics skills (Selenium, Postman, SQL, Python, Excel/Power BI).</p>
        <div class="cta">
          <!-- Update this path after you place your PDF in /resume/ -->
          <a class="btn" href="resume/Midhula_K_Martin_Resume.pdf" download>📄 Download Resume</a>
          <a class="btn ghost" href="https://github.com/MidhulaMartin" target="_blank" rel="noopener">GitHub</a>
          <a class="btn ghost" href="https://www.linkedin.com/in/midhula-k-martin-826b9189/" target="_blank" rel="noopener">LinkedIn</a>
        </div>
      </div>
      <div class="rightbox"></div>
    </header>

    <!-- SKILLS -->
    <section class="section" id="skills">
      <h2 class="section__title">Skills</h2>
      <div class="chips">
        <span class="chip">Manual Testing</span><span class="chip">Test Cases</span><span class="chip">JIRA</span>
        <span class="chip">Selenium</span><span class="chip">PyTest</span><span class="chip">Postman (API)</span>
        <span class="chip">SQL (Joins, Agg.)</span><span class="chip">Python (pandas)</span>
        <span class="chip">Excel</span><span class="chip">Power BI</span><span class="chip">Azure basics</span>
      </div>
    </section>

    <!-- PROJECTS -->
    <section class="section" id="projects">
      <h2 class="section__title">Projects</h2>

      <div class="filters">
        <button class="filter active" data-filter="all">All</button>
        <button class="filter" data-filter="testing">Testing</button>
        <button class="filter" data-filter="analytics">Analytics</button>
      </div>

      <div class="grid">
        <!-- QA: Hotel Management -->
        <article class="card" data-cat="testing">
          <div class="thumb">
            <img src="assets/hotel-qa.png" alt="Hotel Management QA project" onerror="this.style.display='none';">
          </div>
          <div class="body">
            <h3 class="title">Hotel Management System – QA</h3>
            <p class="desc">Manual + automation testing for a hotel booking app. Smoke & regression suites, API checks and defect reporting.</p>
            <div class="tags"><span class="tag">Selenium</span><span class="tag">TestNG</span><span class="tag">JIRA</span><span class="tag">Postman</span></div>
            <div class="links">
              <a href="https://github.com/MidhulaMartin/hotel-management-qa" target="_blank" rel="noopener">GitHub</a>
              <a href="#" target="_blank" rel="noopener">Demo</a>
            </div>
          </div>
        </article>

        <!-- QA: E-Commerce Testing -->
        <article class="card" data-cat="testing">
          <div class="thumb">
            <img src="assets/ecom-testing.png" alt="E-commerce testing project" onerror="this.style.display='none';">
          </div>
          <div class="body">
            <h3 class="title">E-Commerce App – Functional & API Testing</h3>
            <p class="desc">Functional/UI cases and Postman collections. Automated login, cart and checkout flows.</p>
            <div class="tags"><span class="tag">Selenium</span><span class="tag">Postman</span><span class="tag">Bug Tracking</span></div>
            <div class="links">
              <a href="https://github.com/MidhulaMartin/ecommerce-testing" target="_blank" rel="noopener">GitHub</a>
            </div>
          </div>
        </article>

        <!-- Analytics: Sales Dashboard -->
        <article class="card" data-cat="analytics">
          <div class="thumb">
            <img src="assets/sales-bi.png" alt="Sales dashboard" onerror="this.style.display='none';">
          </div>
          <div class="body">
            <h3 class="title">Sales Analysis Dashboard</h3>
            <p class="desc">Interactive dashboard tracking revenue, AOV and regional trends. DAX measures + drill-through.</p>
            <div class="tags"><span class="tag">Power BI</span><span class="tag">Excel</span><span class="tag">DAX</span></div>
            <div class="links">
              <a href="https://github.com/MidhulaMartin/sales-analysis-powerbi" target="_blank" rel="noopener">GitHub</a>
              <a href="#" target="_blank" rel="noopener">Live Report</a>
            </div>
          </div>
        </article>

        <!-- Analytics: Customer Churn -->
        <article class="card" data-cat="analytics">
          <div class="thumb">
            <img src="assets/churn.png" alt="Customer churn analysis" onerror="this.style.display='none';">
          </div>
          <div class="body">
            <h3 class="title">Customer Churn Analysis</h3>
            <p class="desc">SQL exploration + Python visuals to identify churn drivers and retention opportunities.</p>
            <div class="tags"><span class="tag">SQL</span><span class="tag">Python</span><span class="tag">pandas</span></div>
            <div class="links">
              <a href="https://github.com/MidhulaMartin/customer-churn-sql-python" target="_blank" rel="noopener">GitHub</a>
            </div>
          </div>
        </article>
      </div>
    </section>

    <!-- CONTACT -->
    <section class="section" id="contact">
      <h2 class="section__title">Contact</h2>
      <p>Email: <a href="mailto:martin.kmidhula@gmail.com">martin.kmidhula@gmail.com</a></p>
    </section>

    <footer>© <span id="yr"></span> Midhula K Martin</footer>
  </div>

  <script>
    // year
    document.getElementById('yr').textContent = new Date().getFullYear();

    // theme toggle
    const toggle = document.getElementById('themeToggle');
    const apply = (t)=>document.documentElement.setAttribute('data-theme', t);
    const saved = localStorage.getItem('theme') || 'dark';
    apply(saved);
    toggle.addEventListener('click', ()=>{
      const t = document.documentElement.getAttribute('data-theme') === 'light' ? 'dark' : 'light';
      apply(t); localStorage.setItem('theme', t);
    });

    // project filters
    const btns = document.querySelectorAll('.filter');
    const cards = document.querySelectorAll('.card');
    btns.forEach(b=>b.addEventListener('click', ()=>{
      btns.forEach(x=>x.classList.remove('active'));
      b.classList.add('active');
      const f = b.dataset.filter;
      cards.forEach(c=>{
        c.style.display = (f==='all' || c.dataset.cat===f) ? '' : 'none';
      });
    }));
  </script>
</body>
</html>
