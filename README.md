<!DOCTYPE html>
<html lang="hi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>KoPartner - Growth & Business Platform</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700&display=swap" rel="stylesheet">
  
  <style>
    :root {
      --primary: #2563eb;
      --primary-hover: #1d4ed8;
      --text-dark: #0f172a;
      --text-muted: #64748b;
      --bg-light: #f8fafc;
      --card-bg: #ffffff;
      --border: #e2e8f0;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Plus Jakarta Sans', sans-serif;
    }

    body {
      background-color: var(--bg-light);
      color: var(--text-dark);
      line-height: 1.6;
    }

    /* Navbar */
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 18px 8%;
      background: #ffffff;
      border-bottom: 1px solid var(--border);
      position: sticky;
      top: 0;
      z-index: 100;
    }

    .logo {
      font-size: 1.4rem;
      font-weight: 700;
      color: var(--primary);
      text-decoration: none;
    }

    nav a {
      margin-left: 24px;
      text-decoration: none;
      color: var(--text-muted);
      font-weight: 500;
      transition: color 0.2s;
    }

    nav a:hover {
      color: var(--text-dark);
    }

    .nav-btn {
      background: var(--primary);
      color: #fff !important;
      padding: 8px 18px;
      border-radius: 8px;
      transition: background 0.2s;
    }

    .nav-btn:hover {
      background: var(--primary-hover);
    }

    /* Hero Section */
    .hero {
      text-align: center;
      padding: 90px 8% 60px;
      max-width: 900px;
      margin: 0 auto;
    }

    .hero .badge {
      display: inline-block;
      padding: 6px 14px;
      background: #dbeafe;
      color: var(--primary);
      font-size: 0.85rem;
      font-weight: 600;
      border-radius: 50px;
      margin-bottom: 18px;
    }

    .hero h1 {
      font-size: 2.8rem;
      line-height: 1.2;
      font-weight: 700;
      margin-bottom: 20px;
      letter-spacing: -0.02em;
    }

    .hero p {
      font-size: 1.15rem;
      color: var(--text-muted);
      margin-bottom: 30px;
    }

    .hero-actions {
      display: flex;
      gap: 15px;
      justify-content: center;
    }

    .btn {
      display: inline-block;
      padding: 12px 24px;
      border-radius: 8px;
      font-weight: 600;
      text-decoration: none;
      transition: all 0.2s;
    }

    .btn-primary {
      background: var(--primary);
      color: #fff;
    }

    .btn-primary:hover {
      background: var(--primary-hover);
    }

    .btn-secondary {
      background: #fff;
      color: var(--text-dark);
      border: 1px solid var(--border);
    }

    .btn-secondary:hover {
      background: #f1f5f9;
    }

    /* Features */
    .features {
      padding: 70px 8%;
      max-width: 1200px;
      margin: 0 auto;
    }

    .section-title {
      text-align: center;
      margin-bottom: 50px;
    }

    .section-title h2 {
      font-size: 2rem;
      margin-bottom: 8px;
    }

    .section-title p {
      color: var(--text-muted);
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 25px;
    }

    .card {
      background: var(--card-bg);
      padding: 28px;
      border-radius: 12px;
      border: 1px solid var(--border);
      box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.04);
      transition: transform 0.2s, box-shadow 0.2s;
    }

    .card:hover {
      transform: translateY(-4px);
      box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.08);
    }

    .card-icon {
      width: 44px;
      height: 44px;
      background: #eff6ff;
      color: var(--primary);
      border-radius: 8px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 1.2rem;
      margin-bottom: 16px;
    }

    .card h3 {
      font-size: 1.2rem;
      margin-bottom: 10px;
    }

    .card p {
      color: var(--text-muted);
      font-size: 0.95rem;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 30px;
      border-top: 1px solid var(--border);
      color: var(--text-muted);
      font-size: 0.9rem;
      background: #ffffff;
    }

    @media (max-width: 768px) {
      .hero h1 { font-size: 2.1rem; }
      nav { display: none; }
    }
  </style>
</head>
<body>

  <header>
    <a href="#" class="logo">KoPartner</a>
    <nav>
      <a href="#features">Features</a>
      <a href="#about">About</a>
      <a href="#contact" class="nav-btn">Get Started</a>
    </nav>
  </header>

  <section class="hero">
    <span class="badge">Grow Together</span>
    <h1>Apne Business ko Scale Karo KoPartner ke Saath</h1>
    <p>Seamless collaboration, powerful networking, aur automated workflows ek hi platform par.</p>
    <div class="hero-actions">
      <a href="#" class="btn btn-primary">Start Free Trial</a>
      <a href="#" class="btn btn-secondary">Learn More</a>
    </div>
  </section>

  <section class="features" id="features">
    <div class="section-title">
      <h2>Why Choose KoPartner?</h2>
      <p>Aapke growth ke liye designed sabhi zaroori tools</p>
    </div>

    <div class="grid">
      <div class="card">
        <div class="card-icon">⚡</div>
        <h3>Fast Onboarding</h3>
        <p>Bina kisi jhanjhat ke minutes ke andar apna account setup karein aur kaam shuru karein.</p>
      </div>

      <div class="card">
        <div class="card-icon">🤝</div>
        <h3>Verified Network</h3>
        <p>Sirf reliable partners aur clients se connect hoke apne projects ko securely badhayein.</p>
      </div>

      <div class="card">
        <div class="card-icon">📈</div>
        <h3>Data Analytics</h3>
        <p>Real-time tracking aur detailed performance metrics se accurate business decisions lein.</p>
      </div>
    </div>
  </section>

  <footer>
    <p>&copy; 2026 KoPartner. All rights reserved.</p>
  </footer>

</body>
</html>
