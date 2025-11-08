<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>End World Hunger — SDG2 Project</title>
  <style>
    :root{
      --bg:#f6fbf9;
      --accent:#2a9d8f;
      --muted:#6b7280;
      --card:#ffffff;
      --glass: rgba(255,255,255,0.7);
      --shadow: 0 6px 18px rgba(15,23,42,0.08);
      font-family: "Segoe UI", Roboto, system-ui, -apple-system, "Helvetica Neue", Arial;
    }

    *{box-sizing:border-box}
    body{
      margin:0;
      background: linear-gradient(180deg, var(--bg) 0%, #e9f7f3 100%);
      color:#0b1220;
      line-height:1.45;
    }

    header{
      padding:2.25rem 1.25rem;
      background: url('') center/cover no-repeat; /* Optional background image */
      position:relative;
      overflow:hidden;
    }

    header::after{
      content:"";
      position:absolute;
      inset:0;
      background: linear-gradient(180deg, rgba(10,20,30,0.08), rgba(10,20,30,0.00));
      pointer-events:none;
    }

    .container{
      max-width:1000px;
      margin:0 auto;
      padding:1rem;
    }

    /* Hero section with two crests */
    .hero{
      background:var(--glass);
      display:flex;
      align-items:center;
      justify-content:space-between;
      flex-wrap:wrap;
      gap:1rem 1.5rem;
      padding:1rem 1.5rem;
      border-radius:14px;
      box-shadow: var(--shadow);
      backdrop-filter: blur(6px);
    }

    .hero-content{
      text-align:center;
      flex:1;
      min-width:250px;
    }

    .crest{
      width:90px;
      height:90px;
      border-radius:50%;
      object-fit:contain;
      background:#fff;
      box-shadow:0 3px 10px rgba(0,0,0,0.1);
      flex-shrink:0;
    }

    .title{
      font-size:2.25rem;
      font-weight:700;
      letter-spacing:-0.01em;
      margin:0 0 .25rem 0;
    }

    .byline{
      color:var(--muted);
      margin:0;
      font-weight:600;
    }

    @media(min-width:720px){
      .title{ font-size:2.75rem; }
      .byline{ font-size:1.05rem; }
    }

    main{
      padding:2rem 1rem;
    }

    .grid{
      display:grid;
      grid-template-columns: repeat(auto-fit,minmax(220px,1fr));
      gap:1rem;
    }

    .bubble{
      background:var(--card);
      padding:1rem;
      border-radius:14px;
      box-shadow: var(--shadow);
      min-height:110px;
      display:flex;
      align-items:center;
      justify-content:center;
      text-align:center;
      font-weight:600;
      color:#082029;
      position:relative;
    }

    .bubble p{
      margin:0;
      padding:0 .5rem;
      font-size:0.98rem;
    }

    .bubble::before{
      content:"";
      width:54px;
      height:54px;
      border-radius:50%;
      background:linear-gradient(135deg,var(--accent),#8ac6a2);
      position:absolute;
      top:-20px;
      right:-20px;
      box-shadow:0 8px 20px rgba(42,157,143,0.12);
      opacity:0.95;
    }

    .card{
      background:var(--card);
      padding:1rem 1.25rem;
      border-radius:12px;
      box-shadow: var(--shadow);
    }

    h2{
      margin:0 0 0.5rem 0;
      font-size:1.1rem;
      color:#07202a;
    }

    ul{
      margin:0 0 0 1.25rem;
      color:var(--muted);
    }

    li{
      margin:0.35rem 0;
    }

    .images{
      display:grid;
      grid-template-columns: repeat(auto-fit,minmax(160px,1fr));
      gap:0.75rem;
      margin-top:1rem;
    }

    .images img{
      width:100%;
      height:120px;
      object-fit:cover;
      border-radius:8px;
      background:#eef7f3;
      display:block;
    }

    footer{
      margin-top:2rem;
      text-align:center;
      color:var(--muted);
      font-size:0.9rem;
      padding:1rem 0 3rem 0;
    }
  </style>
</head>
<body>
  <header>
    <div class="container">
      <div class="hero" role="banner" aria-label="End world hunger banner">

        <!-- LEFT CREST -->
        <img src="data:image/jpeg;base64,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" alt="Left crest" class="crest">

        <!-- Main title and subtext -->
        <div class="hero-content">
          <h1 class="title">End world hunger</h1>
          <p class="byline">By Benny Ryan and Ailbhe O'Loughlin</p>
        </div>

        <!-- RIGHT CREST -->
        <img src="data:image/png;base64,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	" alt="Right crest" class="crest">
      </div>
    </div>
  </header>

  <main class="container" role="main">
    <section aria-labelledby="facts-heading">
      <h2 id="facts-heading">Key facts</h2>
      <div class="grid" role="list">
        <article class="bubble"><p>The Global Hunger Index (GHI) is a tool designed to measure and track hunger at global, regional, and national levels.</p></article>
        <article class="bubble"><p>Approximately 9 million people die each year from hunger-related causes, with children under five accounting for roughly one-third of these deaths.</p></article>
        <article class="bubble"><p>More than 600 million people are projected to face hunger in 2030.</p></article>
        <article class="bubble"><p>High food prices to plague many nations.</p></article>
      </div>
    </section>

    <section aria-labelledby="ireland-heading" style="margin-top:1.25rem;">
      <h2 id="ireland-heading">Ireland — Selected statistics & context</h2>

      <div class="card">
        <ul>
          <li>In 2021, 5.4% of the population in Ireland experienced food insecurity, and 2.50% were considered to be in hunger.</li>
          <li>Food Insecurity: In 2021, the prevalence of moderate or severe food insecurity was 5.4% of the population, a decrease from 6.5% in 2020.</li>
          <li>Hunger: The FAO estimated the prevalence of undernourishment to be less than 2.5% in 2021.</li>
          <li>Malnutrition: Around 145,000 people in Ireland are estimated to be malnourished often due to illness, but also due to factors like substance abuse or isolation.</li>
          <li>Food Poverty: Statistics from 2021 show that 8.9% of the population experienced food poverty, with severe food deprivation affecting 6.2% of the population.</li>
          <li>Poverty: Poverty and hunger are closely linked, and in 2022, the rate of consistent poverty was 5.3%.</li>
        </ul>
      </div>
    </section>

    <section aria-labelledby="images-heading" style="margin-top:1.25rem;">
      <h2 id="images-heading">Images (Click to see full)</h2>
      <div class="images">
        <a href="https://ibb.co/Wvbs2Vf3"><img src="https://i.ibb.co/Wvbs2Vf3/Screenshot-2025-11-08-182147.png" alt="Screenshot-2025-11-08-182147" border="0"></a>
        <a href="https://ibb.co/bMCrqwHb"><img src="https://i.ibb.co/bMCrqwHb/Screenshot-2025-11-08-182051.png" alt="Screenshot-2025-11-08-182051" border="0"></a>
       <a href="https://ibb.co/SGcsZ0j"><img src="https://i.ibb.co/SGcsZ0j/Screenshot-2025-11-08-181953.png" alt="Screenshot-2025-11-08-181953" border="0"></a>
       <a href="https://ibb.co/zT31JpCL"><img src="https://i.ibb.co/zT31JpCL/Screenshot-2025-11-08-181302.png" alt="Screenshot-2025-11-08-181302" border="0"></a>
      </div>
    </section>

    <section aria-labelledby="cta-heading" style="margin-top:1.5rem;">
      <h2 id="cta-heading">What you can do</h2>
      <div class="card">
        <ul>
          <li>Reduce food waste at home: plan meals, store food properly, compost what you can't eat.</li>
          <li>Support local food banks or community kitchens with donations or volunteer hours.</li>
          <li>Learn about sustainable agriculture and support policies that make food affordable and available.</li>
          <li>Freeze leftoves and extra portions for future meals.</li>
          <li>Use scrap food: Make stock from chicken bones and vegetable scraps.</li>
        </ul>
      </div>
    </section>
  </main>

  <footer class="container">
    <small>SDG2 — Zero Hunger. Created by Benny Ryan &amp; Ailbhe O'Loughlin.</small>
  </footer>
</body>
</html>
