<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no"/>
  <title>REMACASH - Earn Online Easily</title>
  <meta name="description" content="Remacash: Earn money online with fun activities like watching videos, sharing memes, referrals & more. Trusted by thousands, payouts via M-Pesa, PayPal, and more!">
  <meta property="og:title" content="REMACASH - Earn Online Easily">
  <meta property="og:description" content="Join Remacash, Africa's favorite platform for earning money online by completing fun and simple activities.">
  <meta property="og:image" content="https://yourdomain.com/og-image.png">
  <meta property="og:type" content="website">
  <link href="https://fonts.googleapis.com/css?family=Montserrat:700,400&display=swap" rel="stylesheet"/>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.css" rel="stylesheet">
  <style>
    :root {
      --main: #1e90ff;
      --accent: #ffd700;
      --neutral: #fff;
      --dark: #222;
      --wa-green: #25D366;
      --wa-green-dark: #128c7e;
      --yt: #ff0000;
      --tiktok: #010101;
      --trivia: #7c3aed;
      --meme: #fd7e14;
      --ads: #20c997;
      --netflix: #e50914;
      --trophy: #ffd700;
      --spin: #1e90ff;
      --referral: #28a745;
      --gift: #ff69b4;
      --fb: #1877f3;
      --ig: #e4405f;
      --x: #000;
    }
    html, body {
      font-family: 'Montserrat', Arial, sans-serif;
      margin: 0;
      background: darkblue;
      min-height: 100vh;
      color: var(--dark);
      box-sizing: border-box;
      width: 100vw;
      max-width: 100vw;
      overflow-x: hidden;
      scroll-behavior: smooth;
    }
    * {
      box-sizing: border-box;
      max-width: 100%;
    }
    .navbar {
      background: var(--main);
      color: var(--neutral);
      padding: 1.1rem 0 0.5rem 0;
      box-shadow: 0 2px 10px rgba(30,144,255,0.07);
      position: sticky;
      top: 0;
      z-index: 888;
    }
    .navbar-brand {
      font-weight: 900;
      font-size: 2rem;
      color: var(--neutral);
      letter-spacing: 1.5px;
      text-shadow: 1px 2px 6px #1e90ff44;
      white-space: nowrap;
      display: block;
      width: 100%;
      text-align: center;
      margin-bottom: 0.1rem;
    }
    .navbar-tagline {
      font-size: 1.02rem;
      color: var(--accent);
      font-weight: 500;
      text-align: center;
      margin-bottom: 0.7rem;
      letter-spacing: 0.2px;
      text-shadow: 1px 2px 8px #1e90ff66;
    }
    .nav-links {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 0.3rem;
      margin-bottom: 0.7rem;
      width: 100%;
    }
    .nav-links a {
      color: var(--neutral);
      font-weight: 600;
      text-decoration: none;
      font-size: 1.05rem;
      padding: 0.2rem 0.6rem;
      border-radius: 6px;
      transition: background 0.15s, color 0.15s;
      display: block;
      width: 100%;
      text-align: center;
    }
    .nav-links a:hover,
    .nav-links a:focus {
      background: var(--accent);
      color: var(--main);
    }
    .nav-btns {
      display: flex;
      gap: 0.6rem;
      flex-wrap: wrap;
      justify-content: center;
      width: 100%;
    }
    .nav-btns a {
      font-weight: 700;
      border-radius: 30px;
      font-size: 1rem;
      padding: 0.55rem 1.2rem;
      box-shadow: 0 2px 8px rgba(30,144,255,0.08);
      border: none;
      transition: background 0.2s, color 0.2s, transform 0.11s;
      text-decoration: none;
      display: inline-block;
      background: var(--accent);
      color: var(--dark);
      white-space: nowrap;
    }
    .nav-btns a.login {
      background: var(--neutral);
      color: var(--main);
      border: 2px solid var(--main);
    }
    .nav-btns a:hover {
      transform: translateY(-2px) scale(1.03);
      filter: brightness(0.98);
    }
    .navbar-actions {
      width: 100%;
      max-width: 650px;
      margin: 0 auto;
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    .navbar-actions .nav-btns {
      margin-bottom: 0.5rem;
    }
    .navbar-actions .navbar-brand {
      margin-bottom: 0.4rem;
    }
    .navbar-actions .nav-btns,
    .navbar-actions .whatsapp-bar {
      width: 100%;
      display: flex;
      justify-content: center;
    }
    .whatsapp-bar {
      margin-top: 0.5rem;
      width: 100%;
      display: flex;
      justify-content: center;
    }
    .wa-btn {
      display: inline-flex;
      align-items: center;
      gap: 0.5em;
      background: var(--wa-green);
      color: #fff;
      font-weight: 700;
      font-size: 1.07rem;
      padding: 0.7em 1.5em;
      border-radius: 32px;
      box-shadow: 0 4px 16px #25d36644;
      text-decoration: none;
      border: none;
      transition: background 0.18s, transform 0.12s;
      margin: 0.65em auto 0 auto;
      cursor: pointer;
    }
    .wa-btn:hover,
    .wa-btn:focus {
      background: var(--wa-green-dark);
      color: #fff;
      transform: scale(1.04);
      text-decoration: none;
    }
    .wa-btn i {
      font-size: 1.25em;
    }
    .social-icons {
      display: flex;
      gap: 0.8rem;
      justify-content: center;
      margin: 0.3rem 0 1.0rem 0;
    }
    .social-icons a {
      font-size: 1.3rem;
      border-radius: 50%;
      padding: 0.38em;
      transition: background 0.14s, color 0.13s;
      display: inline-flex;
      align-items: center;
      justify-content: center;
      text-decoration: none;
      background: #fff;
    }
    .social-icons a.facebook { color: #fff; background: var(--fb);}
    .social-icons a.facebook:hover { background: #fff; color: var(--fb);}
    .social-icons a.instagram { color: #fff; background: var(--ig);}
    .social-icons a.instagram:hover { background: #fff; color: var(--ig);}
    .social-icons a.x { color: #fff; background: #111;}
    .social-icons a.x:hover { background: #fff; color: #222;}
    .social-icons a.tiktok { color: #fff; background: #111;}
    .social-icons a.tiktok:hover { background: #fff; color: #222;}
    .stats-section {
      background: var(--neutral);
      color: var(--main);
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 2.2rem;
      padding: 1.1rem 0.7rem;
      border-radius: 10px;
      margin: 1.1rem auto 1.1rem auto;
      box-shadow: 0 2px 18px #1e90ff15;
      max-width: 620px;
      flex-wrap: wrap;
    }
    .stat-item {
      display: flex;
      flex-direction: column;
      align-items: center;
      min-width: 110px;
      gap: 0.1rem;
    }
    .stat-number {
      font-size: 1.4rem;
      font-weight: 900;
      color: var(--main);
    }
    .stat-label {
      font-size: 0.98rem;
      color: #333;
      font-weight: 600;
    }
    .trust-badges {
      display: flex;
      gap: 0.7rem;
      margin-top: 0.45rem;
      flex-wrap: wrap;
      justify-content: center;
    }
    .trust-badges img {
      height: 32px;
      background: #fff;
      padding: 4px 10px;
      border-radius: 8px;
      border: 1px solid #eee;
      box-shadow: 0 1px 4px #0001;
      margin-right: 7px;
      object-fit: contain;
      width: auto;
    }
    .trust-badges img:last-child { margin-right: 0; }
    .wa-float {
      position: fixed;
      bottom: 21px;
      right: 21px;
      z-index: 1000;
    }
    .wa-float a {
      background: var(--wa-green);
      color: var(--neutral);
      border-radius: 50%;
      width: 42px;
      height: 42px;
      display: flex;
      align-items: center;
      justify-content: center;
      box-shadow: 0 4px 18px #25d36688;
      font-size: 1.5rem;
      transition: background 0.2s, transform 0.12s;
      animation: bounce 2s infinite;
    }
    .wa-float a:hover {
      background: var(--wa-green-dark);
      transform: scale(1.09);
      color: var(--neutral);
    }
    @keyframes bounce {
      0%, 100% { transform: translateY(0);}
      50% { transform: translateY(-6px);}
    }
    .cta-animated {
      animation: pulse 1.7s infinite;
      box-shadow: 0 0 0 0 #ffd70088;
    }
    @keyframes pulse {
      0% { box-shadow: 0 0 0 0 #ffd70088;}
      70% { box-shadow: 0 0 0 16px #ffd70011;}
      100% { box-shadow: 0 0 0 0 #ffd70099;}
    }
    header {
      background: var(--main);
      color: var(--neutral);
      padding: 2.2rem 0 1.3rem 0;
      text-align: center;
      box-shadow: 0 8px 20px #1e90ff11;
    }
    header h1 {
      font-size: 2.1rem;
      font-weight: 900;
      letter-spacing: 1.2px;
      margin-bottom: 0.7rem;
      text-shadow: 2px 3px 10px #1e90ff44;
    }
    header p {
      font-size: 1.1rem;
      font-weight: 500;
      margin-bottom: 1.1rem;
      color: var(--accent);
    }
    .cta-btn {
      background: var(--accent);
      color: var(--dark);
      font-weight: bold;
      padding: 0.75rem 1.6rem;
      border-radius: 40px;
      font-size: 1.05rem;
      border: none;
      box-shadow: 0 4px 20px #ffd70033;
      transition: background 0.2s, color 0.2s, transform 0.13s;
      letter-spacing: 1px;
      text-decoration: none;
      display: inline-block;
    }
    .cta-btn:hover {
      background: var(--neutral);
      color: var(--main);
      border: 2px solid var(--main);
      transform: scale(1.05);
    }
    .main-section {
      max-width: 650px;
      margin: 1.2rem auto 0 auto;
      padding: 0 0.5rem;
    }
    .howworks-section {
      background: #fff;
      border-radius: 14px;
      margin: 1.5rem 0 1.5rem 0;
      box-shadow: 0 4px 16px #1e90ff09;
      padding: 1.2rem 1rem 1.3rem 1rem;
      text-align: center;
    }
    .howworks-title {
      color: var(--main);
      font-weight: 800;
      font-size: 1.13rem;
      margin-bottom: 0.9rem;
    }
    .howworks-steps {
      display: flex;
      flex-wrap: wrap;
      gap: 1.1rem;
      justify-content: center;
    }
    .howworks-step {
      flex: 1 1 120px;
      min-width: 110px;
      max-width: 180px;
      background: #f6faff;
      border-radius: 10px;
      padding: 0.7rem 0.5rem;
      box-shadow: 0 2px 8px #1e90ff0c;
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    .howworks-step i {
      color: var(--main);
      font-size: 2rem;
      margin-bottom: 0.38em;
    }
    .howworks-step-title {
      font-weight: 700;
      color: var(--main);
      font-size: 1.04rem;
      margin-bottom: 0.2rem;
    }
    .howworks-step-desc {
      color: #444;
      font-size: 0.94rem;
      margin-bottom: 0.1em;
    }
    .faq-section {
      margin: 2.1rem auto 1.5rem auto;
      max-width: 650px;
      background: #fff;
      border-radius: 12px;
      box-shadow: 0 4px 18px #1e90ff10;
      padding: 1.35rem 1.1rem 1.2rem 1.1rem;
    }
    .faq-title {
      color: var(--main);
      font-weight: 800;
      font-size: 1.13rem;
      margin-bottom: 1.1rem;
      text-align: center;
    }
    .faq-list {
      margin: 0; padding: 0;
      list-style: none;
    }
    .faq-item + .faq-item { margin-top: 0.7rem;}
    .faq-q {
      font-weight: 700;
      color: var(--main);
      cursor: pointer;
      font-size: 1.05rem;
      display: flex;
      align-items: center;
      gap: 0.5em;
      user-select: none;
    }
    .faq-a {
      color: #333;
      font-size: 0.97rem;
      margin-left: 1.7rem;
      margin-top: 0.25em;
      display: none;
      transition: max-height 0.2s;
    }
    .faq-item.active .faq-a { display: block;}
    .faq-q .bi-chevron-down {
      transition: transform 0.2s;
    }
    .faq-item.active .faq-q .bi-chevron-down {
      transform: rotate(180deg);
    }
    .ways-list {
      margin: 1.3rem 0;
      padding: 0;
      list-style: none;
      width: 100vw;
      max-width: 650px;
      margin-left: 0;
      margin-right: 0;
    }
    .way-item {
      display: flex;
      align-items: flex-start;
      background: var(--neutral);
      border-radius: 14px;
      box-shadow: 0 4px 16px #1e90ff09;
      border: 2px solid var(--main);
      margin-bottom: 1rem;
      padding: 0.9rem 0.7rem 0.6rem 0.7rem;
      gap: 0.7rem;
      width: 100%;
      min-height: 70px;
      overflow: hidden;
      margin-left: 0;
      margin-right: 0;
    }
    .way-number {
      font-size: 1.2rem;
      font-weight: bold;
      color: var(--neutral);
      background: var(--main);
      border-radius: 50%;
      width: 2.1rem;
      height: 2.1rem;
      display: flex;
      align-items: center;
      justify-content: center;
      margin-right: 0.5rem;
      margin-top: 0.15rem;
      flex-shrink: 0;
      box-shadow: 0 2px 8px #1e90ff33;
    }
    .way-icon {
      font-size: 2.1rem;
      margin-right: 0.7rem;
      margin-top: 0.15rem;
      flex-shrink: 0;
      display: flex;
      align-items: center;
      justify-content: center;
      color: var(--main);
    }
    .way-tiktok { color: #010101;}
    .way-youtube { color: #ff0000;}
    .way-trivia { color: #7c3aed;}
    .way-meme { color: #fd7e14;}
    .way-ads { color: #20c997;}
    .way-netflix { color: #e50914;}
    .way-trophy { color: #ffd700;}
    .way-spin { color: #1e90ff;}
    .way-referral { color: #28a745;}
    .way-gift { color: #ff69b4;}
    .way-info {
      flex: 1;
      min-width: 0;
    }
    .way-title {
      font-weight: 700;
      color: var(--main);
      margin: 0 0 0.1rem 0;
      font-size: 1.05rem;
      letter-spacing: 0.5px;
      line-height: 1.1;
      white-space: normal;
      word-break: break-word;
      display: flex;
      align-items: center;
      gap: 0.4rem;
    }
    .way-desc {
      color: var(--dark);
      font-size: 0.92rem;
      margin: 0.12rem 0 0 0;
      line-height: 1.35;
      white-space: normal;
      word-break: break-word;
    }
    .links-section {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 0.7rem;
      margin-bottom: 1.5rem;
      margin-top: 1.2rem;
      width: 100%;
    }
    .links-section a {
      min-width: 170px;
      text-align: center;
      width: 90%;
    }
    .download-app {
      background: var(--main);
      color: var(--neutral);
      border-radius: 12px;
      padding: 1.5rem 0.7rem;
      text-align: center;
      margin: 1.7rem 0;
      box-shadow: 0 6px 24px #1e90ff18;
      width: 100%;
    }
    .download-app h2 {
      font-size: 1.25rem;
      font-weight: 700;
      margin-bottom: 0.7rem;
      color: var(--accent);
    }
    .download-btn {
      background: var(--accent);
      color: var(--dark);
      font-weight: 700;
      padding: 0.7rem 1.2rem;
      border-radius: 30px;
      font-size: 1rem;
      border: none;
      box-shadow: 0 3px 8px #ffd70044;
      text-decoration: none;
      margin-top: 0.7rem;
      display: inline-block;
      transition: background 0.13s, color 0.13s, transform 0.13s;
    }
    .download-btn:hover {
      background: var(--neutral);
      color: var(--main);
      transform: scale(1.04);
      border: 2px solid var(--main);
    }
    .testimonials-section {
      padding: 1.2rem 0.5rem 1.1rem 0.5rem;
      background: var(--accent);
      border-radius: 12px;
      margin: 1.7rem 0;
      width: 100%;
    }
    .testimonials-title {
      color: var(--main);
      font-size: 1.15rem;
      font-weight: 700;
      text-align: center;
      margin-bottom: 1rem;
    }
    .testimonials {
      display: grid;
      grid-template-columns: 1fr;
      gap: 0.6rem;
      justify-items: center;
      width: 100%;
    }
    @media (min-width: 540px) {
      .testimonials { grid-template-columns: 1fr 1fr; }
    }
    .testimonial-card {
      background: var(--neutral);
      border-radius: 8px;
      padding: 0.7rem 0.6rem;
      box-shadow: 0 1px 10px #1e90ff13;
      display: flex;
      flex-direction: column;
      align-items: center;
      min-height: 75px;
      max-width: 100%;
      text-align: center;
      position: relative;
      border: 1.5px solid var(--main);
      width: 100%;
    }
    .testimonial-img {
      width: 33px;
      height: 33px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 0.5rem;
      border: 2px solid var(--accent);
    }
    .testimonial-name {
      font-weight: 600;
      color: var(--main);
      margin-bottom: 0.15rem;
      font-size: 0.98rem;
    }
    .testimonial-text {
      color: var(--dark);
      font-size: 0.91rem;
      margin-bottom: 0;
      font-style: italic;
    }
    .flags-section {
      margin: 1.2rem 0 1.5rem 0;
      display: flex;
      justify-content: center;
      align-items: flex-start;
      width: 100%;
    }
    .flags-section > div {
      display: flex;
      flex-wrap: wrap;
      gap: 2.2rem;
      justify-content: center;
      width: 100%;
      max-width: 1100px;
    }
    .flags-section > div > div {
      text-align: center;
      min-width: 70px;
    }
    .flag-img {
      width: 36px;
      height: 25px;
      border-radius: 3px;
      box-shadow: 0 2px 8px #22222210;
      border: 1px solid var(--main);
      background: var(--neutral);
      object-fit: cover;
      display: block;
      margin: 0 auto;
    }
    .footer {
      background: var(--main);
      color: var(--neutral);
      text-align: center;
      padding: 1rem 0 0.8rem 0;
      font-size: 0.93rem;
      letter-spacing: 1px;
      margin-top: 1.1rem;
      border-radius: 10px 10px 0 0;
      box-shadow: 0 -4px 14px #1e90ff13;
      width: 100%;
      overflow-x: hidden;
    }
    .footer-links {
      margin: 0.8em 0 0.2em 0;
      display: flex;
      gap: 1em;
      justify-content: center;
      flex-wrap: wrap;
    }
    .footer-links a {
      color: var(--accent);
      text-decoration: underline;
      font-size: 0.98em;
    }
    .contact-section {
      max-width: 600px;
      margin: 1.6rem auto 0 auto;
      background: #f5f8ff;
      border-radius: 12px;
      padding: 1.2rem 0.8rem 1rem 0.8rem;
      box-shadow: 0 2px 12px #1e90ff0b;
      text-align: center;
    }
    .contact-options {
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
      justify-content: center;
      align-items: center;
      margin-top: 0.6rem;
    }
    .contact-link {
      display: flex;
      align-items: center;
      gap: 0.4rem;
      background: var(--main);
      color: var(--neutral);
      border-radius: 24px;
      padding: 0.5rem 1.1rem;
      font-size: 1rem;
      font-weight: 600;
      text-decoration: none;
      transition: background 0.15s, color 0.15s, transform 0.13s;
      box-shadow: 0 2px 8px #1e90ff22;
      border: none;
    }
    .contact-link:hover {
      background: var(--accent);
      color: var(--dark);
      transform: scale(1.06);
    }
    .contact-link.whatsapp { background: var(--wa-green); color: #fff; }
    .contact-link.whatsapp:hover { background: var(--wa-green-dark); color: #fff;}
    .contact-link.email { background: #ea4335; color: #fff;}
    .contact-link.email:hover { background: #ffd700; color: var(--dark);}
    .contact-link.care { background: #1e90ff; color: #fff;}
    .contact-link.comment { background: #ffd700; color: var(--dark);}
    .cookie-banner {
      position: fixed;
      bottom: 0; left: 0; right: 0;
      background: #1e90ff;
      color: #fff;
      z-index: 9999;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 1.1em;
      padding: 0.6em 1em;
      font-size: 1em;
      box-shadow: 0 -2px 12px #1e90ff44;
      transition: transform 0.3s;
    }
    .cookie-banner button {
      background: #ffd700;
      color: #222;
      border: none;
      padding: 0.45em 1.1em;
      border-radius: 18px;
      font-weight: 700;
      cursor: pointer;
      margin-left: 0.3em;
      transition: background 0.15s, color 0.13s;
    }
    .cookie-banner button:hover { background: #fffbe7; color: #1e90ff;}
    @media (max-width: 1100px) {
      .flags-section > div { gap: 1.1rem; }
    }
    @media (max-width: 600px) {
      .main-section { padding: 0 0rem; }
      .ways-list { padding: 0; margin-left: 0; margin-right: 0;}
      .way-item { margin-left: 0; margin-right: 0;}
      .stats-section { gap: 0.9rem;}
      .faq-title, .howworks-title, .testimonials-title { font-size: 1rem;}
      .flags-section > div { gap: 0.65rem; }
      .flags-section > div > div { min-width: 60px; }
    }
    @media (max-width: 430px) {
      .navbar-brand { font-size: 1.2rem; }
      .main-section, .testimonials-section, .ways-grid, .footer, .flags-section, .contact-section { padding-right: 0; padding-left: 0; }
      .ways-list { padding: 0; margin-left: 0; margin-right: 0;}
      .way-item { margin-left: 0; margin-right: 0;}
      .ways-grid, .testimonials { grid-template-columns: 1fr; }
      .faq-q { font-size: 0.99rem;}
      .faq-a { font-size: 0.93rem;}
      .stat-item { min-width: 90px;}
      .contact-options { flex-direction: column; gap: 0.7rem;}
      .navbar-actions { padding-left: 0.5rem; padding-right: 0.5rem; }
      .flags-section > div { gap: 0.42rem; }
      .flags-section > div > div { min-width: 48px; }
    }
  </style>
</head>
<body>
  <!-- Floating WhatsApp -->
  <div class="wa-float" aria-label="Quick WhatsApp">
    <a href="https://api.whatsapp.com/send?phone=254112834621&text=Hello!+I'm+interested+in+the+business" target="_blank" title="Chat on WhatsApp">
      <i class="bi bi-whatsapp"></i>
    </a>
  </div>
  <nav class="navbar" aria-label="Main navigation">
    <div class="navbar-actions">
      <span class="navbar-brand">REMACASH</span>
      <div class="navbar-tagline">Africa's favorite way to earn money online—fast, fun, and secure.</div>
      <div class="nav-links">
        <a href="#howitworks">How it Works</a>
        <a href="#ways">Ways to Earn</a>
        <a href="#testimonials">Testimonials</a>
        <a href="#faq">FAQ</a>
        <a href="#contact">Contact</a>
      </div>
      <div class="social-icons" aria-label="Social links">
        <a href="https://facebook.com/" class="facebook" title="Facebook" target="_blank" rel="noopener"><i class="bi bi-facebook"></i></a>
        <a href="https://twitter.com/" class="x" title="X" target="_blank" rel="noopener"><i class="bi bi-twitter-x"></i></a>
        <a href="https://instagram.com/" class="instagram" title="Instagram" target="_blank" rel="noopener"><i class="bi bi-instagram"></i></a>
        <a href="https://tiktok.com/" class="tiktok" title="TikTok" target="_blank" rel="noopener"><i class="bi bi-tiktok"></i></a>
      </div>
      <div class="nav-btns">
        <a href="https://www.trendqash.com/user/register.php?ref=Prixess">Register</a>
        <a href="https://www.trendqash.com/user/register.php?ref=Prixess" class="login">Login</a>
      </div>
      <div class="whatsapp-bar">
        <a href="https://api.whatsapp.com/send?phone=254112834621&text=Hello!+I'm+interested+in+the+business" target="_blank" class="wa-btn"><i class="bi bi-whatsapp"></i> WhatsApp</a>
      </div>
    </div>
  </nav>
  <section class="stats-section" aria-label="Trust and Stats">
    <div class="stat-item"><span class="stat-number" aria-label="Users">15,000+</span><span class="stat-label">Users</span></div>
    <div class="stat-item"><span class="stat-number" aria-label="Payouts">KES 3M+</span><span class="stat-label">Paid Out</span></div>
    <div class="stat-item"><span class="stat-number" aria-label="Countries">20+</span><span class="stat-label">Countries</span></div>
    <div class="stat-item"><span class="stat-number" aria-label="Rating">4.8★</span><span class="stat-label">User Rating</span></div>
    <div class="trust-badges" aria-label="Payment options">
      <img src="https://uploads-ssl.webflow.com/602e188b2c5c14b5f7e6b5cf/603e6f1e70d90d1b9d851e7b_mpesa_logo.png" alt="M-Pesa">
      <img src="https://upload.wikimedia.org/wikipedia/commons/b/b5/PayPal.svg" alt="PayPal">
      <img src="https://upload.wikimedia.org/wikipedia/commons/2/2a/Mastercard-logo.svg" alt="Mastercard">
      <img src="https://upload.wikimedia.org/wikipedia/commons/4/41/Visa_Logo.png" alt="Visa">
    </div>
  </section>
  <header>
    <h1>10 Ways to Earn with Remacash!</h1>
    <p>Join our program and start earning with fun, simple activities and real rewards!</p>
    <a href="#register" class="cta-btn cta-animated">Join Now</a>
  </header>
  <main class="main-section">
    <section class="howworks-section" id="howitworks">
      <div class="howworks-title">How Remacash Works</div>
      <div class="howworks-steps">
        <div class="howworks-step">
          <i class="bi bi-person-plus-fill"></i>
          <div class="howworks-step-title">Sign Up</div>
          <div class="howworks-step-desc">Create your free account in seconds.</div>
        </div>
        <div class="howworks-step">
          <i class="bi bi-lightning-charge-fill"></i>
          <div class="howworks-step-title">Complete Tasks</div>
          <div class="howworks-step-desc">Watch, play, click, and refer to earn points and cash.</div>
        </div>
        <div class="howworks-step">
          <i class="bi bi-wallet-fill"></i>
          <div class="howworks-step-title">Withdraw Money</div>
          <div class="howworks-step-desc">Cash out instantly via M-Pesa, PayPal, and more.</div>
        </div>
      </div>
    </section>
    <h2 style="text-align:center; color:var(--main); font-weight:700; font-size:1.15rem; margin-top:0;" id="ways">Ways to Earn</h2>
    <ul class="ways-list">
      <li class="way-item">
        <span class="way-number">1</span>
        <span class="way-icon way-tiktok"><i class="bi bi-tiktok"></i></span>
        <div class="way-info">
          <span class="way-title">TIKTOK</span>
          <div class="way-desc">Earn rewards for watching trending TikTok videos daily.</div>
        </div>
      </li>
      <li class="way-item">
        <span class="way-number">2</span>
        <span class="way-icon way-youtube"><i class="bi bi-youtube"></i></span>
        <div class="way-info">
          <span class="way-title">YOUTUBE</span>
          <div class="way-desc">Get paid for watching and participating in YouTube campaigns.</div>
        </div>
      </li>
      <li class="way-item">
        <span class="way-number">3</span>
        <span class="way-icon way-trivia"><i class="bi bi-question-circle"></i></span>
        <div class="way-info">
          <span class="way-title">TRIVIA QUESTIONS</span>
          <div class="way-desc">Test your knowledge and earn for every correct answer.</div>
        </div>
      </li>
      <li class="way-item">
        <span class="way-number">4</span>
        <span class="way-icon way-meme"><i class="bi bi-emoji-laughing"></i></span>
        <div class="way-info">
          <span class="way-title">MEMES</span>
          <div class="way-desc">Laugh at memes and earn points for each view.</div>
        </div>
      </li>
      <li class="way-item">
        <span class="way-number">5</span>
        <span class="way-icon way-ads"><i class="bi bi-cursor"></i></span>
        <div class="way-info">
          <span class="way-title">ADS CLICKING</span>
          <div class="way-desc">Earn instant rewards for clicking and viewing ads.</div>
        </div>
      </li>
      <li class="way-item">
        <span class="way-number">6</span>
        <span class="way-icon way-netflix"><i class="bi bi-film"></i></span>
        <div class="way-info">
          <span class="way-title">NETFLIX</span>
          <div class="way-desc">Watch selected Netflix shows and get rewarded.</div>
        </div>
      </li>
      <li class="way-item">
        <span class="way-number">7</span>
        <span class="way-icon way-trophy"><i class="bi bi-trophy"></i></span>
        <div class="way-info">
          <span class="way-title">TOURNAMENTS</span>
          <div class="way-desc">Join fun tournaments for bigger prizes!</div>
        </div>
      </li>
      <li class="way-item">
        <span class="way-number">8</span>
        <span class="way-icon way-spin"><i class="bi bi-arrow-repeat"></i></span>
        <div class="way-info">
          <span class="way-title">SPIN THE WHEEL</span>
          <div class="way-desc">Try your luck daily for surprise bonuses!</div>
        </div>
      </li>
      <li class="way-item">
        <span class="way-number">9</span>
        <span class="way-icon way-referral"><i class="bi bi-person-plus"></i></span>
        <div class="way-info">
          <span class="way-title">AFFILIATE REFERRALS</span>
          <div class="way-desc">Invite friends to join and earn commission on their activities.</div>
        </div>
      </li>
      <li class="way-item">
        <span class="way-number">10</span>
        <span class="way-icon way-gift"><i class="bi bi-gift"></i></span>
        <div class="way-info">
          <span class="way-title">WELCOME BONUS</span>
          <div class="way-desc">Sign up and get an instant bonus to start your journey!</div>
        </div>
      </li>
    </ul>
    <section class="links-section">
      <a id="register" href="https://www.trendqash.com/user/register.php?ref=Prixess" class="cta-btn">Register Now</a>
      <a id="login" href="https://www.trendqash.com/user/register.php?ref=Prixess" class="cta-btn">Login</a>
      <a href="https://api.whatsapp.com/send?phone=254112834621&text=Hello!+I'm+interested+in+the+business" target="_blank" class="wa-btn"><i class="bi bi-whatsapp"></i> Chat on WhatsApp</a>
    </section>
    <section class="faq-section" id="faq">
      <div class="faq-title">Frequently Asked Questions</div>
      <ul class="faq-list">
        <li class="faq-item">
          <div class="faq-q"><i class="bi bi-chevron-down"></i>Is Remacash free to join?</div>
          <div class="faq-a">Yes! Signing up on Remacash is absolutely free. Some earning features may require minimal participation fees or deposits, but you can get started without any payment.</div>
        </li>
        <li class="faq-item">
          <div class="faq-q"><i class="bi bi-chevron-down"></i>How do I withdraw my earnings?</div>
          <div class="faq-a">Withdrawals are fast and simple. Go to your dashboard and select your preferred method (M-Pesa, PayPal, etc.), enter amount and details, and confirm. Most payouts are instant or within 24 hours.</div>
        </li>
        <li class="faq-item">
          <div class="faq-q"><i class="bi bi-chevron-down"></i>Is Remacash available in my country?</div>
          <div class="faq-a">Remacash is available in most African countries including Kenya, Uganda, Botswana, Ghana, Nigeria, South Africa, Tanzania, Ethiopia, Zambia, Malawi, Cameroon, Togo, Congo, Ivory Coast, Burkina Faso, Senegal, Benin, Rwanda, Burundi, Mozambique, Morocco and more. Check the registration form for up-to-date country options.</div>
        </li>
        <li class="faq-item">
          <div class="faq-q"><i class="bi bi-chevron-down"></i>How can I earn faster?</div>
          <div class="faq-a">Invite friends, participate daily in all activities, and check for bonus offers and tournaments to maximize your earnings!</div>
        </li>
        <li class="faq-item">
          <div class="faq-q"><i class="bi bi-chevron-down"></i>Is Remacash safe and legit?</div>
          <div class="faq-a">Absolutely. Remacash has paid out to thousands of members since 2022 and uses secure payment providers. For extra security, never share your password with anyone.</div>
        </li>
      </ul>
    </section>
    <section class="download-app">
      <h2>Download the App</h2>
      <p>For a better experience, download our app and start earning on the go!</p>
      <a href="https://www.trendqash.com/user/register.php?ref=Prixess" class="download-btn" target="_blank"><i class="bi bi-download"></i> Download App</a>
    </section>
    <section class="testimonials-section" id="testimonials">
      <div class="testimonials-title">What Our Users Say</div>
      <div class="testimonials">
        <div class="testimonial-card">
          <img src="https://randomuser.me/api/portraits/men/31.jpg" class="testimonial-img" alt="Samuel K. Remacash user" loading="lazy">
          <div class="testimonial-name">Samuel K. </div>
          <div class="testimonial-text">“This app changed my life! I earn extra cash every week just by watching videos and inviting friends.”</div>
        </div>
        <div class="testimonial-card">
          <img src="https://randomuser.me/api/portraits/women/44.jpg" class="testimonial-img" alt="Grace N. Remacash user" loading="lazy">
          <div class="testimonial-name">Grace N. </div>
          <div class="testimonial-text">“I love the trivia and spin wheel! It’s fun and rewarding. Highly recommended to everyone.”</div>
        </div>
        <div class="testimonial-card">
          <img src="https://randomuser.me/api/portraits/men/88.jpg" class="testimonial-img" alt="John K. Remacash user" loading="lazy">
          <div class="testimonial-name">John K. </div>
          <div class="testimonial-text">“The welcome bonus is real and the referral program works! I’ve invited all my friends.”</div>
        </div>
        <div class="testimonial-card">
          <img src="https://randomuser.me/api/portraits/women/68.jpg" class="testimonial-img" alt="Ama D. Remacash user" loading="lazy">
          <div class="testimonial-name">Ama D. </div>
          <div class="testimonial-text">“Easy to use, colourful and pays on time. Thank you for such a great platform!”</div>
        </div>
        <div class="testimonial-card">
          <img src="https://randomuser.me/api/portraits/men/53.jpg" class="testimonial-img" alt="Peter M. Remacash user" loading="lazy">
          <div class="testimonial-name">Peter M. </div>
          <div class="testimonial-text">“Now I can earn from home while having fun. The tournaments are my favourite!”</div>
        </div>
      </div>
    </section>
    <section class="flags-section" aria-label="country flags">
      <div>
        <div><img src="https://upload.wikimedia.org/wikipedia/commons/4/49/Flag_of_Kenya.svg" alt="Kenya" class="flag-img" loading="lazy"><div style="font-size:1rem;color:#fff;margin-top:0.28em;">Kenya</div></div>
        <div><img src="https://upload.wikimedia.org/wikipedia/commons/4/4e/Flag_of_Uganda.svg" alt="Uganda" class="flag-img" loading="lazy"><div style="font-size:1rem;color:#fff;margin-top:0.28em;">Uganda</div></div>
        <div><img src="https://upload.wikimedia.org/wikipedia/commons/f/fa/Flag_of_Botswana.svg" alt="Botswana" class="flag-img" loading="lazy"><div style="font-size:1rem;color:#fff;margin-top:0.28em;">Botswana</div></div>
        <div><img src="https://upload.wikimedia.org/wikipedia/commons/1/19/Flag_of_Ghana.svg" alt="Ghana" class="flag-img" loading="lazy"><div style="font-size:1rem;color:#fff;margin-top:0.28em;">Ghana</div></div>
        <div><img src="https://upload.wikimedia.org/wikipedia/commons/7/79/Flag_of_Nigeria.svg" alt="Nigeria" class="flag-img" loading="lazy"><div style="font-size:1rem;color:#fff;margin-top:0.28em;">Nigeria</div></div>
        <div><img src="https://upload.wikimedia.org/wikipedia/commons/a/af/Flag_of_South_Africa.svg" alt="South Africa" class="flag-img" loading="lazy"><div style="font-size:1rem;color:#fff;margin-top:0.28em;">South Africa</div></div>
        <div><img src="https://upload.wikimedia.org/wikipedia/commons/3/38/Flag_of_Tanzania.svg" alt="Tanzania" class="flag-img" loading="lazy"><div style="font-size:1rem;color:#fff;margin-top:0.28em;">Tanzania</div></div>
        <div><img src="https://upload.wikimedia.org/wikipedia/commons/1/17/Flag_of_Rwanda.svg" alt="Rwanda" class="flag-img" loading="lazy"><div style="font-size:1rem;color:#fff;margin-top:0.28em;">Rwanda</div></div>
        <div><img src="https://upload.wikimedia.org/wikipedia/commons/5/50/Flag_of_Burundi.svg" alt="Burundi" class="flag-img" loading="lazy"><div style="font-size:1rem;color:#fff;margin-top:0.28em;">Burundi</div></div>
        <div><img src="https://upload.wikimedia.org/wikipedia/commons/0/06/Flag_of_Zambia.svg" alt="Zambia" class="flag-img" loading="lazy"><div style="font-size:1rem;color:#fff;margin-top:0.28em;">Zambia</div></div>
        <div><img src="https://upload.wikimedia.org/wikipedia/commons/d/d1/Flag_of_Malawi.svg" alt="Malawi" class="flag-img" loading="lazy"><div style="font-size:1rem;color:#fff;margin-top:0.28em;">Malawi</div></div>
        <div><img src="https://upload.wikimedia.org/wikipedia/commons/4/4e/Flag_of_Cameroon.svg" alt="Cameroon" class="flag-img" loading="lazy"><div style="font-size:1rem;color:#fff;margin-top:0.28em;">Cameroon</div></div>
        <div><img src="https://upload.wikimedia.org/wikipedia/commons/6/68/Flag_of_Togo.svg" alt="Togo" class="flag-img" loading="lazy"><div style="font-size:1rem;color:#fff;margin-top:0.28em;">Togo</div></div>
        <div><img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Flag_of_the_Republic_of_the_Congo.svg" alt="Congo" class="flag-img" loading="lazy"><div style="font-size:1rem;color:#fff;margin-top:0.28em;">Congo</div></div>
        <div><img src="https://upload.wikimedia.org/wikipedia/commons/8/89/Flag_of_Côte_d%27Ivoire.svg" alt="Ivory Coast" class="flag-img" loading="lazy"><div style="font-size:1rem;color:#fff;margin-top:0.28em;">Ivory Coast</div></div>
        <div><img src="https://upload.wikimedia.org/wikipedia/commons/3/31/Flag_of_Burkina_Faso.svg" alt="Burkina Faso" class="flag-img" loading="lazy"><div style="font-size:1rem;color:#fff;margin-top:0.28em;">Burkina Faso</div></div>
        <div><img src="https://upload.wikimedia.org/wikipedia/commons/f/fd/Flag_of_Senegal.svg" alt="Senegal" class="flag-img" loading="lazy"><div style="font-size:1rem;color:#fff;margin-top:0.28em;">Senegal</div></div>
        <div><img src="https://upload.wikimedia.org/wikipedia/commons/0/0a/Flag_of_Benin.svg" alt="Benin" class="flag-img" loading="lazy"><div style="font-size:1rem;color:#fff;margin-top:0.28em;">Benin</div></div>
        <div><img src="https://upload.wikimedia.org/wikipedia/commons/d/d0/Flag_of_Mozambique.svg" alt="Mozambique" class="flag-img" loading="lazy"><div style="font-size:1rem;color:#fff;margin-top:0.28em;">Mozambique</div></div>
        <div><img src="https://upload.wikimedia.org/wikipedia/commons/2/2c/Flag_of_Morocco.svg" alt="Morocco" class="flag-img" loading="lazy"><div style="font-size:1rem;color:#fff;margin-top:0.28em;">Morocco</div></div>
      </div>
    </section>
    <section class="contact-section" id="contact">
      <h3 style="color:var(--main);margin-bottom:0.7rem;">Contact & Support</h3>
      <div class="contact-options">
        <a href="https://api.whatsapp.com/send?phone=254112834621&text=Hello!+I'm+interested+in+the+business" class="contact-link whatsapp" target="_blank"><i class="bi bi-whatsapp"></i> Contact CEO</a>
        <a href="mailto:mentorprixess2@gmail.com" class="contact-link email"><i class="bi bi-envelope-fill"></i> Email Us</a>
        <a href="tel:+254112834621" class="contact-link care"><i class="bi bi-telephone-fill"></i> Call Customer Care</a>
        <a href="#leave-comment" class="contact-link comment"><i class="bi bi-chat-left-text-fill"></i> Leave a Comment</a>
      </div>
      <form id="leave-comment" style="margin-top:1.4rem;text-align:left;">
        <label for="comment" style="font-weight:600;display:block;margin-bottom:0.3rem;color:var(--main);">Your Comment:</label>
        <textarea id="comment" name="comment" rows="2" maxlength="250" style="width:100%;border-radius:8px;border:1px solid var(--main);padding:0.45rem;font-family:inherit;font-size:1rem;resize:vertical;margin-bottom:0.6rem;" aria-label="Your comment"></textarea>
        <button type="submit" style="background:var(--main);color:var(--neutral);border:none;border-radius:18px;padding:0.5rem 1.3rem;font-weight:700;cursor:pointer;box-shadow:0 1px 8px #1e90ff22;font-size:1rem;transition:background 0.12s;">Submit</button>
      </form>
    </section>
  </main>
  <footer class="footer">
    <div class="footer-links">
      <a href="/privacy.html" target="_blank">Privacy Policy</a>
      <a href="/terms.html" target="_blank">Terms of Service</a>
      <a href="/disclaimer.html" target="_blank">Earnings Disclaimer</a>
    </div>
    &copy; 2025 Remacash. All Rights Reserved.
  </footer>
  <div class="cookie-banner" id="cookie-banner" aria-live="polite" style="display:none;">
    This site uses cookies to improve your experience. See our <a href="/privacy.html" style="color:#ffd700;text-decoration:underline;">Privacy Policy</a>.
    <button id="cookie-accept-btn">Accept</button>
  </div>
  <script>
    document.querySelectorAll('.faq-q').forEach(function(q){
      q.addEventListener('click', function(){
        var parent = q.closest('.faq-item');
        parent.classList.toggle('active');
      });
    });
    document.getElementById('leave-comment').onsubmit = function(e){
      e.preventDefault();
      var textarea = document.getElementById('comment');
      if(textarea.value.trim().length < 2) {
        alert("Please enter a comment.");
        textarea.focus();
        return false;
      }
      alert("Thank you for your feedback!");
      textarea.value = "";
    }
    window.addEventListener('DOMContentLoaded', function(){
      if(!localStorage.getItem('cookieAccepted')) {
        document.getElementById('cookie-banner').style.display = 'flex';
      }
      document.getElementById('cookie-accept-btn').onclick = function(){
        localStorage.setItem('cookieAccepted', '1');
        document.getElementById('cookie-banner').style.display = 'none';
      }
    });
    document.querySelectorAll('.nav-links a').forEach(function(link){
      link.addEventListener('click', function(e){
        var href = link.getAttribute('href');
        if(href.startsWith('#') && document.querySelector(href)){
          e.preventDefault();
          document.querySelector(href).scrollIntoView({behavior:'smooth'});
        }
      });
    });
  </script>
</body>
</html>
