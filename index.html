<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Between the Lines</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,500;1,300;1,400;1,500&family=Jost:wght@200;300;400&display=swap" rel="stylesheet">
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  :root {
    --ink: #1a1410;
    --ink-mid: #4a3f35;
    --ink-light: #8a7a6e;
    --ink-faint: #c4b8ae;
    --cream: #f7f3ee;
    --cream-deep: #ede6dc;
    --warm: #c9a98b;
    --rose: #c98b8b;
    --blue: #8b9ec9;
    --gold: #c9b08b;
    --sad-color: #7a8fb5;
    --happy-color: #c9905a;
  }

  html { scroll-behavior: smooth; }

  body {
    background: var(--cream);
    color: var(--ink);
    font-family: 'Jost', sans-serif;
    font-weight: 300;
    min-height: 100vh;
    overflow-x: hidden;
    position: relative;
  }

  /* Atmospheric background */
  body::before {
    content: '';
    position: fixed;
    inset: 0;
    background:
      radial-gradient(ellipse 60% 40% at 15% 20%, rgba(138,158,201,0.12) 0%, transparent 60%),
      radial-gradient(ellipse 50% 60% at 85% 75%, rgba(201,138,138,0.10) 0%, transparent 55%),
      radial-gradient(ellipse 40% 30% at 50% 50%, rgba(201,176,139,0.08) 0%, transparent 50%);
    pointer-events: none;
    z-index: 0;
  }

  /* Grain texture overlay */
  body::after {
    content: '';
    position: fixed;
    inset: 0;
    background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noise)' opacity='0.04'/%3E%3C/svg%3E");
    pointer-events: none;
    z-index: 0;
    opacity: 0.6;
  }

  .page-wrap {
    position: relative;
    z-index: 1;
    max-width: 720px;
    margin: 0 auto;
    padding: 72px 28px 100px;
  }

  /* ── HEADER ── */
  .site-header {
    text-align: center;
    margin-bottom: 72px;
    animation: riseIn 1s ease both;
  }

  .site-header .eyebrow {
    font-family: 'Jost', sans-serif;
    font-weight: 200;
    font-size: 11px;
    letter-spacing: 0.28em;
    text-transform: uppercase;
    color: var(--ink-light);
    margin-bottom: 18px;
    display: block;
  }

  .site-header h1 {
    font-family: 'Cormorant Garamond', serif;
    font-weight: 300;
    font-style: italic;
    font-size: clamp(38px, 7vw, 58px);
    line-height: 1.1;
    color: var(--ink);
    letter-spacing: -0.01em;
    position: relative;
    display: inline-block;
  }

  .site-header h1 .ampersand {
    font-style: normal;
    color: var(--ink-light);
  }

  .site-header .tagline {
    margin-top: 14px;
    font-size: 14px;
    color: var(--ink-light);
    letter-spacing: 0.04em;
    font-weight: 200;
  }

  .header-rule {
    width: 40px;
    height: 1px;
    background: linear-gradient(to right, transparent, var(--ink-faint), transparent);
    margin: 24px auto 0;
  }

  /* ── SECTION WRAPPER ── */
  .section {
    margin-bottom: 52px;
    animation: riseIn 0.9s ease both;
  }

  .section:nth-child(2) { animation-delay: 0.1s; }
  .section:nth-child(3) { animation-delay: 0.2s; }
  .section:nth-child(4) { animation-delay: 0.3s; }
  .section:nth-child(5) { animation-delay: 0.4s; }

  .section-label {
    font-size: 10px;
    font-weight: 400;
    letter-spacing: 0.22em;
    text-transform: uppercase;
    color: var(--ink-light);
    margin-bottom: 20px;
    display: flex;
    align-items: center;
    gap: 12px;
  }

  .section-label::after {
    content: '';
    flex: 1;
    height: 0.5px;
    background: var(--ink-faint);
  }

  /* ── MOOD SLIDER ── */
  .mood-slider-wrap {
    background: white;
    border: 0.5px solid var(--ink-faint);
    border-radius: 20px;
    padding: 28px 32px 24px;
    position: relative;
    overflow: hidden;
  }

  .mood-slider-wrap::before {
    content: '';
    position: absolute;
    inset: 0;
    background: linear-gradient(135deg, rgba(138,158,201,0.04), rgba(201,144,90,0.04));
    border-radius: 20px;
  }

  .mood-ends {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 20px;
    position: relative;
  }

  .mood-end {
    display: flex;
    align-items: center;
    gap: 9px;
  }

  .mood-end .moon { font-size: 22px; }
  .mood-end .label {
    font-size: 12px;
    font-weight: 300;
    letter-spacing: 0.1em;
    color: var(--ink-mid);
  }

  .mood-center {
    text-align: center;
    position: relative;
  }

  .mood-center .current-emoji {
    font-size: 28px;
    display: block;
    transition: transform 0.3s cubic-bezier(.34,1.56,.64,1);
    animation: floatBob 3s ease-in-out infinite;
  }

  @keyframes floatBob {
    0%,100% { transform: translateY(0); }
    50% { transform: translateY(-4px); }
  }

  .mood-center .current-label {
    font-family: 'Cormorant Garamond', serif;
    font-style: italic;
    font-size: 13px;
    color: var(--ink-light);
    margin-top: 4px;
    display: block;
    transition: color 0.4s;
  }

  .slider-track {
    position: relative;
    padding: 8px 0;
  }

  input[type="range"] {
    -webkit-appearance: none;
    appearance: none;
    width: 100%;
    height: 3px;
    background: linear-gradient(to right, var(--sad-color), #a89bc9, #c9905a);
    border-radius: 2px;
    outline: none;
    cursor: pointer;
  }

  input[type="range"]::-webkit-slider-thumb {
    -webkit-appearance: none;
    appearance: none;
    width: 22px;
    height: 22px;
    border-radius: 50%;
    background: white;
    border: 2px solid var(--ink-faint);
    box-shadow: 0 2px 12px rgba(0,0,0,0.12);
    cursor: pointer;
    transition: transform 0.2s ease, box-shadow 0.2s ease;
  }

  input[type="range"]::-webkit-slider-thumb:hover {
    transform: scale(1.15);
    box-shadow: 0 4px 20px rgba(0,0,0,0.16);
  }

  input[type="range"]::-moz-range-thumb {
    width: 22px; height: 22px; border-radius: 50%;
    background: white; border: 2px solid var(--ink-faint);
    box-shadow: 0 2px 12px rgba(0,0,0,0.12); cursor: pointer;
  }

  /* ── TEXTAREA ── */
  .text-area-wrap {
    position: relative;
  }

  textarea {
    width: 100%;
    background: white;
    border: 0.5px solid var(--ink-faint);
    border-radius: 16px;
    padding: 24px 28px;
    color: var(--ink);
    font-family: 'Cormorant Garamond', serif;
    font-weight: 300;
    font-style: italic;
    font-size: 20px;
    line-height: 1.75;
    resize: none;
    min-height: 148px;
    outline: none;
    transition: border-color 0.3s ease, box-shadow 0.3s ease;
    letter-spacing: 0.01em;
  }

  textarea::placeholder {
    color: var(--ink-faint);
    font-style: italic;
  }

  textarea:focus {
    border-color: var(--ink-light);
    box-shadow: 0 0 0 3px rgba(138,126,110,0.06);
  }

  .char-count {
    position: absolute;
    bottom: 12px;
    right: 18px;
    font-size: 11px;
    color: var(--ink-faint);
    letter-spacing: 0.06em;
    pointer-events: none;
  }

  /* ── BOOK LINES ── */
  .book-card {
    background: white;
    border: 0.5px solid var(--ink-faint);
    border-radius: 16px;
    padding: 24px 28px;
    position: relative;
    overflow: hidden;
    transition: border-color 0.3s;
    cursor: pointer;
  }

  .book-card::before {
    content: '\201C';
    position: absolute;
    top: -8px;
    left: 18px;
    font-family: 'Cormorant Garamond', serif;
    font-size: 80px;
    color: var(--ink-faint);
    opacity: 0.4;
    line-height: 1;
    pointer-events: none;
  }

  .book-card.selected {
    border-color: var(--ink-light);
    background: linear-gradient(135deg, white, rgba(196,184,174,0.07));
  }

  .book-quote {
    font-family: 'Cormorant Garamond', serif;
    font-style: italic;
    font-size: 19px;
    font-weight: 300;
    line-height: 1.7;
    color: var(--ink);
    padding-left: 4px;
    margin-bottom: 12px;
    transition: opacity 0.4s ease;
    min-height: 80px;
    display: flex;
    align-items: center;
  }

  .book-author {
    font-size: 11px;
    letter-spacing: 0.16em;
    text-transform: uppercase;
    color: var(--ink-light);
    font-weight: 400;
    transition: opacity 0.4s ease;
  }

  .book-footer {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: 18px;
    padding-top: 16px;
    border-top: 0.5px solid var(--cream-deep);
  }

  .use-line-btn {
    background: transparent;
    border: 0.5px solid var(--ink-faint);
    border-radius: 20px;
    padding: 7px 16px;
    font-family: 'Jost', sans-serif;
    font-weight: 300;
    font-size: 11px;
    letter-spacing: 0.1em;
    color: var(--ink-mid);
    cursor: pointer;
    transition: all 0.2s ease;
  }

  .use-line-btn:hover {
    border-color: var(--ink-mid);
    color: var(--ink);
    background: var(--cream);
  }

  .use-line-btn.using {
    background: var(--ink);
    border-color: var(--ink);
    color: var(--cream);
  }

  .refresh-btn {
    background: transparent;
    border: none;
    font-size: 11px;
    letter-spacing: 0.1em;
    color: var(--ink-light);
    cursor: pointer;
    font-family: 'Jost', sans-serif;
    font-weight: 300;
    display: flex;
    align-items: center;
    gap: 6px;
    padding: 7px 0;
    transition: color 0.2s;
  }

  .refresh-btn:hover { color: var(--ink); }

  .refresh-icon {
    display: inline-block;
    transition: transform 0.5s ease;
  }

  .refresh-btn:hover .refresh-icon { transform: rotate(180deg); }

  /* ── PARTNER MOOD CHIPS ── */
  .chips-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 9px;
  }

  .chip {
    padding: 8px 16px;
    border-radius: 24px;
    border: 0.5px solid var(--ink-faint);
    background: white;
    font-family: 'Jost', sans-serif;
    font-weight: 300;
    font-size: 13px;
    letter-spacing: 0.04em;
    color: var(--ink-mid);
    cursor: pointer;
    transition: all 0.22s ease;
    user-select: none;
  }

  .chip:hover {
    border-color: var(--ink-light);
    color: var(--ink);
    transform: translateY(-1px);
  }

  .chip.active {
    background: var(--ink);
    border-color: var(--ink);
    color: var(--cream);
    transform: translateY(-1px);
  }

  /* ── COMPOSE BUTTON ── */
  .compose-wrap {
    margin-bottom: 52px;
    animation: riseIn 0.9s ease 0.5s both;
  }

  .compose-btn {
    width: 100%;
    padding: 20px 32px;
    background: var(--ink);
    border: none;
    border-radius: 16px;
    font-family: 'Cormorant Garamond', serif;
    font-style: italic;
    font-size: 21px;
    font-weight: 300;
    color: var(--cream);
    cursor: pointer;
    letter-spacing: 0.04em;
    position: relative;
    overflow: hidden;
    transition: all 0.3s ease;
  }

  .compose-btn::before {
    content: '';
    position: absolute;
    inset: 0;
    background: linear-gradient(135deg, rgba(138,158,201,0.15), rgba(201,144,90,0.15));
    opacity: 0;
    transition: opacity 0.3s ease;
  }

  .compose-btn:hover::before { opacity: 1; }
  .compose-btn:hover { transform: translateY(-2px); box-shadow: 0 12px 40px rgba(26,20,16,0.18); }
  .compose-btn:active { transform: translateY(0); }

  .compose-btn .btn-inner {
    position: relative;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 12px;
  }

  .compose-btn .btn-sparkle { font-size: 18px; }

  /* ── LOADING ── */
  .loading-state {
    display: none;
    text-align: center;
    padding: 40px 0 28px;
  }

  .loading-state.show { display: block; }

  .loading-dots {
    display: flex;
    justify-content: center;
    gap: 8px;
    margin-bottom: 14px;
  }

  .loading-dots span {
    width: 6px; height: 6px;
    border-radius: 50%;
    background: var(--ink-faint);
    animation: dotPulse 1.4s ease-in-out infinite;
  }

  .loading-dots span:nth-child(2) { animation-delay: 0.2s; }
  .loading-dots span:nth-child(3) { animation-delay: 0.4s; }

  @keyframes dotPulse {
    0%,80%,100% { transform: scale(0.7); opacity: 0.4; }
    40% { transform: scale(1.1); opacity: 1; }
  }

  .loading-text {
    font-family: 'Cormorant Garamond', serif;
    font-style: italic;
    font-size: 15px;
    color: var(--ink-light);
    animation: breathe 2s ease-in-out infinite;
  }

  @keyframes breathe {
    0%,100% { opacity: 0.5; }
    50% { opacity: 1; }
  }

  /* ── OUTPUT CARD ── */
  .output-card {
    display: none;
    background: white;
    border: 0.5px solid var(--ink-light);
    border-radius: 20px;
    padding: 36px 36px 28px;
    margin-bottom: 52px;
    position: relative;
    overflow: hidden;
    animation: revealCard 0.6s cubic-bezier(.16,1,.3,1) both;
  }

  .output-card.show { display: block; }

  @keyframes revealCard {
    from { opacity: 0; transform: translateY(24px) scale(0.98); }
    to { opacity: 1; transform: translateY(0) scale(1); }
  }

  .output-card::before {
    content: '';
    position: absolute;
    top: 0; left: 0; right: 0;
    height: 3px;
    background: linear-gradient(to right, var(--sad-color), #a89bc9, var(--happy-color));
  }

  .output-pill {
    display: inline-flex;
    align-items: center;
    gap: 6px;
    background: var(--cream-deep);
    border-radius: 20px;
    padding: 5px 12px;
    font-size: 11px;
    letter-spacing: 0.1em;
    color: var(--ink-light);
    margin-bottom: 22px;
    font-weight: 400;
  }

  .output-message {
    font-family: 'Cormorant Garamond', serif;
    font-size: 21px;
    font-style: italic;
    font-weight: 300;
    line-height: 1.8;
    color: var(--ink);
    margin-bottom: 28px;
  }

  .output-actions {
    display: flex;
    gap: 10px;
    padding-top: 20px;
    border-top: 0.5px solid var(--cream-deep);
  }

  .action-btn {
    background: transparent;
    border: 0.5px solid var(--ink-faint);
    border-radius: 10px;
    padding: 9px 18px;
    font-family: 'Jost', sans-serif;
    font-weight: 300;
    font-size: 12px;
    letter-spacing: 0.08em;
    color: var(--ink-mid);
    cursor: pointer;
    transition: all 0.2s;
    display: flex;
    align-items: center;
    gap: 6px;
  }

  .action-btn:hover { border-color: var(--ink-mid); color: var(--ink); background: var(--cream); }
  .action-btn.copied { background: var(--ink); border-color: var(--ink); color: var(--cream); }

  /* ── TIPS ── */
  .tips-section {
    background: white;
    border: 0.5px solid var(--ink-faint);
    border-radius: 20px;
    padding: 36px;
    animation: riseIn 0.9s ease 0.6s both;
  }

  .tips-header {
    display: flex;
    align-items: flex-start;
    gap: 16px;
    margin-bottom: 30px;
  }

  .tips-icon {
    width: 36px;
    height: 36px;
    border-radius: 50%;
    background: var(--cream-deep);
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 16px;
    flex-shrink: 0;
    margin-top: 2px;
  }

  .tips-header-text h2 {
    font-family: 'Cormorant Garamond', serif;
    font-weight: 400;
    font-size: 22px;
    color: var(--ink);
    margin-bottom: 4px;
  }

  .tips-header-text p {
    font-size: 13px;
    color: var(--ink-light);
    font-weight: 200;
    letter-spacing: 0.02em;
  }

  .tip-item {
    display: grid;
    grid-template-columns: 28px 1fr;
    gap: 0 16px;
    padding: 16px 0;
    border-bottom: 0.5px solid var(--cream-deep);
    position: relative;
  }

  .tip-item:last-child { border-bottom: none; padding-bottom: 0; }

  .tip-num {
    font-family: 'Cormorant Garamond', serif;
    font-size: 22px;
    font-style: italic;
    color: var(--ink-faint);
    line-height: 1.2;
    grid-row: span 2;
    align-self: start;
    padding-top: 1px;
  }

  .tip-headline {
    font-family: 'Cormorant Garamond', serif;
    font-size: 17px;
    font-weight: 400;
    color: var(--ink);
    line-height: 1.4;
    margin-bottom: 4px;
  }

  .tip-headline em {
    font-style: italic;
    color: var(--ink-mid);
  }

  .tip-body {
    font-size: 13px;
    line-height: 1.65;
    color: var(--ink-light);
    font-weight: 200;
    letter-spacing: 0.01em;
  }

  /* ── FOOTER ── */
  .site-footer {
    text-align: center;
    margin-top: 64px;
    padding-top: 32px;
    border-top: 0.5px solid var(--ink-faint);
    animation: riseIn 0.9s ease 0.7s both;
  }

  .site-footer p {
    font-size: 12px;
    color: var(--ink-faint);
    letter-spacing: 0.1em;
    font-weight: 200;
  }

  /* ── ANIMATIONS ── */
  @keyframes riseIn {
    from { opacity: 0; transform: translateY(18px); }
    to { opacity: 1; transform: translateY(0); }
  }

  .fade-swap {
    transition: opacity 0.3s ease;
  }

  .fade-swap.fading { opacity: 0; }

  /* ── RESPONSIVE ── */
  @media (max-width: 520px) {
    .page-wrap { padding: 48px 18px 80px; }
    .mood-slider-wrap { padding: 20px 20px 18px; }
    textarea { font-size: 17px; padding: 18px 20px; }
    .book-quote { font-size: 17px; }
    .compose-btn { font-size: 18px; padding: 18px 24px; }
    .output-message { font-size: 18px; }
    .tips-section { padding: 24px 20px; }
  }
</style>
</head>
<body>

<div class="page-wrap">

  <!-- HEADER -->
  <header class="site-header">
    <span class="eyebrow">A space for two</span>
    <h1>Between the Lines</h1>
    <p class="tagline">Express what sits in the tender space between sadness and joy</p>
    <div class="header-rule"></div>
  </header>

  <!-- MOOD SLIDER -->
  <div class="section" style="animation-delay:0.1s">
    <div class="section-label">Your current mood</div>
    <div class="mood-slider-wrap">
      <div class="mood-ends">
        <div class="mood-end">
          <span class="moon">🌑</span>
          <span class="label">Sad</span>
        </div>
        <div class="mood-center">
          <span class="current-emoji" id="moodEmoji">🌗</span>
          <span class="current-label" id="moodLabel">somewhere in between</span>
        </div>
        <div class="mood-end" style="flex-direction:row-reverse">
          <span class="moon">✨</span>
          <span class="label">Happy</span>
        </div>
      </div>
      <div class="slider-track">
        <input type="range" min="0" max="100" value="50" id="moodSlider">
      </div>
    </div>
  </div>

  <!-- WRITE FEELINGS -->
  <div class="section" style="animation-delay:0.2s">
    <div class="section-label">What you want to say</div>
    <div class="text-area-wrap">
      <textarea
        id="userText"
        rows="5"
        maxlength="600"
        placeholder="Write freely — a thought, a feeling, something that's been sitting unsaid between the two of you..."
      ></textarea>
      <span class="char-count" id="charCount">0 / 600</span>
    </div>
  </div>

  <!-- BOOK LINE -->
  <div class="section" style="animation-delay:0.3s">
    <div class="section-label">Or borrow a line from literature</div>
    <div class="book-card" id="bookCard">
      <p class="book-quote fade-swap" id="bookQuote">"Even if we never speak again, I will carry this with me."</p>
      <span class="book-author fade-swap" id="bookAuthor">— Hanya Yanagihara</span>
      <div class="book-footer">
        <button class="use-line-btn" id="useLineBtn" onclick="toggleUseLine()">Use this line</button>
        <button class="refresh-btn" onclick="refreshQuote()">
          <span class="refresh-icon">↻</span> New line
        </button>
      </div>
    </div>
  </div>

  <!-- PARTNER MOOD -->
  <div class="section" style="animation-delay:0.4s">
    <div class="section-label">Your partner's current mood</div>
    <div class="chips-grid" id="chipsGrid">
      <div class="chip" data-mood="distant" onclick="toggleChip(this)">distant</div>
      <div class="chip" data-mood="overwhelmed" onclick="toggleChip(this)">overwhelmed</div>
      <div class="chip" data-mood="happy" onclick="toggleChip(this)">happy</div>
      <div class="chip" data-mood="quiet" onclick="toggleChip(this)">quiet</div>
      <div class="chip" data-mood="hurt" onclick="toggleChip(this)">hurt</div>
      <div class="chip" data-mood="longing" onclick="toggleChip(this)">longing</div>
      <div class="chip" data-mood="curious" onclick="toggleChip(this)">curious</div>
      <div class="chip" data-mood="tired" onclick="toggleChip(this)">tired</div>
      <div class="chip" data-mood="playful" onclick="toggleChip(this)">playful</div>
      <div class="chip" data-mood="uncertain" onclick="toggleChip(this)">uncertain</div>
    </div>
  </div>

  <!-- COMPOSE BUTTON -->
  <div class="compose-wrap">
    <button class="compose-btn" onclick="compose()">
      <span class="btn-inner">
        <span class="btn-sparkle">✦</span>
        Compose my message
      </span>
    </button>
  </div>

  <!-- LOADING -->
  <div class="loading-state" id="loadingState">
    <div class="loading-dots">
      <span></span><span></span><span></span>
    </div>
    <p class="loading-text">Weaving your words with care…</p>
  </div>

  <!-- OUTPUT -->
  <div class="output-card" id="outputCard">
    <div class="output-pill" id="outputPill">✦ Your message</div>
    <div class="output-message" id="outputMessage"></div>
    <div class="output-actions">
      <button class="action-btn" id="copyBtn" onclick="copyMessage()">
        <span>⧉</span> Copy message
      </button>
      <button class="action-btn" onclick="recompose()">
        <span>↻</span> Try again
      </button>
    </div>
  </div>

  <!-- TIPS -->
  <div class="tips-section">
    <div class="tips-header">
      <div class="tips-icon">🌱</div>
      <div class="tips-header-text">
        <h2>Tips for relationship change</h2>
        <p>Small shifts that build something lasting</p>
      </div>
    </div>

    <div class="tip-item">
      <div class="tip-num">1</div>
      <p class="tip-headline">Send small before it grows big</p>
      <p class="tip-body">A daily honest feeling builds more trust than waiting for big conversations.</p>
    </div>

    <div class="tip-item">
      <div class="tip-num">2</div>
      <p class="tip-headline">Name their mood first</p>
      <p class="tip-body"><em>"I think you're carrying something heavy today"</em> opens hearts before defenses rise.</p>
    </div>

    <div class="tip-item">
      <div class="tip-num">3</div>
      <p class="tip-headline">"And" over "but"</p>
      <p class="tip-body"><em>"I'm sad and I still love you"</em> keeps both truths; "but" erases one of them.</p>
    </div>

    <div class="tip-item">
      <div class="tip-num">4</div>
      <p class="tip-headline">Let a message land</p>
      <p class="tip-body">Don't follow up in 10 minutes demanding a reaction. Some words need time to settle.</p>
    </div>

    <div class="tip-item">
      <div class="tip-num">5</div>
      <p class="tip-headline">Return to a shared memory when words feel stuck</p>
      <p class="tip-body">Nostalgia softens walls that logic can't.</p>
    </div>
  </div>

  <footer class="site-footer">
    <p>Between the Lines &nbsp;·&nbsp; A quiet space for two</p>
  </footer>

</div>

<script>
// ── DATA ──
const quotes = [
  { text: "Even if we never speak again, I will carry this with me.", author: "Hanya Yanagihara" },
  { text: "I exist in two places — here and where you are.", author: "Margaret Atwood" },
  { text: "I do not always know what I want, but I know what I don't — losing you.", author: "James Baldwin" },
  { text: "The heart wants what it wants — or else it does not care.", author: "Emily Dickinson" },
  { text: "What is a meeting place if not a point where two lonelinesses find shelter?", author: "R.M. Rilke" },
  { text: "Some things can only be said in silence, and these are the most important things.", author: "Jeanette Winterson" },
  { text: "There is grief in wanting things to stay the same.", author: "Ocean Vuong" },
  { text: "Across the distance, my thoughts always find you first.", author: "Pablo Neruda" },
  { text: "Love is not a victory march — it's a cold and broken hallelujah.", author: "Leonard Cohen" },
  { text: "I keep turning it over in my mind, looking for a way back.", author: "Kazuo Ishiguro" },
  { text: "You are the first morning thought, the last evening sigh.", author: "Pablo Neruda" },
  { text: "I was not sad — I was hollow, which is worse.", author: "Ocean Vuong" },
  { text: "Perhaps all the dragons in our lives are princesses waiting to see us act with courage.", author: "R.M. Rilke" },
  { text: "I am not afraid of storms, for I am learning how to sail my ship.", author: "Louisa May Alcott" },
  { text: "Distance is just a test to see how far love can travel.", author: "Margaret Atwood" },
  { text: "What we call the beginning is often the end. And to make an end is to make a beginning.", author: "T.S. Eliot" },
];

const moodSteps = [
  { emoji: '🌑', label: 'deep sadness' },
  { emoji: '🌒', label: 'heavy and low' },
  { emoji: '🌓', label: 'carrying something' },
  { emoji: '🌔', label: 'tender and aching' },
  { emoji: '🌗', label: 'somewhere in between' },
  { emoji: '🌕', label: 'quietly hopeful' },
  { emoji: '🌤', label: 'light returning' },
  { emoji: '☀️', label: 'warm and open' },
  { emoji: '🌟', label: 'full of warmth' },
  { emoji: '✨', label: 'joyful and bright' },
];

// ── STATE ──
let currentQuoteIdx = 0;
let usingLine = false;
let activeChips = new Set();

// ── MOOD SLIDER ──
const slider = document.getElementById('moodSlider');
const moodEmoji = document.getElementById('moodEmoji');
const moodLabel = document.getElementById('moodLabel');

slider.addEventListener('input', () => {
  const v = parseInt(slider.value);
  const idx = Math.min(9, Math.floor(v / 10));
  const step = moodSteps[idx];
  moodEmoji.style.transform = 'scale(1.3)';
  moodEmoji.textContent = step.emoji;
  moodLabel.textContent = step.label;
  setTimeout(() => moodEmoji.style.transform = '', 200);
});

// ── CHAR COUNT ──
const userText = document.getElementById('userText');
const charCount = document.getElementById('charCount');
userText.addEventListener('input', () => {
  charCount.textContent = `${userText.value.length} / 600`;
});

// ── BOOK QUOTES ──
function refreshQuote() {
  const quoteEl = document.getElementById('bookQuote');
  const authorEl = document.getElementById('bookAuthor');
  quoteEl.classList.add('fading');
  authorEl.classList.add('fading');

  // reset line usage on refresh
  usingLine = false;
  document.getElementById('useLineBtn').textContent = 'Use this line';
  document.getElementById('useLineBtn').classList.remove('using');

  setTimeout(() => {
    currentQuoteIdx = (currentQuoteIdx + 1) % quotes.length;
    const q = quotes[currentQuoteIdx];
    quoteEl.textContent = `"${q.text}"`;
    authorEl.textContent = `— ${q.author}`;
    quoteEl.classList.remove('fading');
    authorEl.classList.remove('fading');
  }, 300);
}

function toggleUseLine() {
  usingLine = !usingLine;
  const btn = document.getElementById('useLineBtn');
  btn.textContent = usingLine ? 'Using this line ✓' : 'Use this line';
  btn.classList.toggle('using', usingLine);
}

// ── CHIPS ──
function toggleChip(el) {
  const mood = el.dataset.mood;
  if (activeChips.has(mood)) {
    activeChips.delete(mood);
    el.classList.remove('active');
  } else {
    activeChips.add(mood);
    el.classList.add('active');
  }
}

// ── COMPOSE ──
async function compose() {
  const text = userText.value.trim();
  const moodVal = parseInt(slider.value);
  const chosenLine = usingLine ? quotes[currentQuoteIdx].text : null;
  const partnerMoods = [...activeChips];

  if (!text && !chosenLine) {
    userText.focus();
    userText.style.borderColor = 'var(--rose)';
    setTimeout(() => userText.style.borderColor = '', 1500);
    return;
  }

  // Hide output, show loading
  const outputCard = document.getElementById('outputCard');
  outputCard.classList.remove('show');
  outputCard.style.display = 'none';
  document.getElementById('loadingState').classList.add('show');

  const moodIdx = Math.min(9, Math.floor(moodVal / 10));
  const moodDesc = moodSteps[moodIdx].label;
  const partnerCtx = partnerMoods.length ? `My partner seems to be feeling: ${partnerMoods.join(', ')}.` : '';
  const lineCtx = chosenLine ? `Please weave in or be inspired by this literary line: "${chosenLine}"` : '';

  const prompt = `You are a gentle emotional writer helping couples communicate across the tender space between sadness and happiness.

The person's current mood: ${moodDesc} (${moodVal}/100 on a sad→happy scale).
${partnerCtx}
What they want to say: "${text || '(they chose a literary line to express their feeling)'}"
${lineCtx}

Write ONE short, intimate message (3–5 sentences) they can send to their partner.
Requirements:
- Tone: honest, tender, bittersweet — not generic or saccharine
- Acknowledge both their own feeling AND show awareness of their partner
- If a literary line is provided, weave it in naturally
- Sound like a real human, not an AI
- Do not add any explanation, headers, or preamble — just the message itself`;

  try {
    const res = await fetch("https://api.anthropic.com/v1/messages", {
      method: "POST",
      headers: { "Content-Type": "application/json" },
      body: JSON.stringify({
        model: "claude-sonnet-4-20250514",
        max_tokens: 1000,
        messages: [{ role: "user", content: prompt }]
      })
    });

    const data = await res.json();
    const msg = data.content?.map(b => b.text || '').join('').trim() || "Something went quiet — please try again.";

    showOutput(msg, moodDesc, partnerMoods);
  } catch (err) {
    showOutput("Something went quiet on our end — please try again in a moment.", moodDesc, partnerMoods);
  }

  document.getElementById('loadingState').classList.remove('show');
}

function showOutput(msg, moodDesc, partnerMoods) {
  const outputCard = document.getElementById('outputCard');
  document.getElementById('outputMessage').textContent = msg;

  let pillText = `✦ Mood: ${moodDesc}`;
  if (partnerMoods.length) pillText += ` · Partner: ${partnerMoods.slice(0,3).join(', ')}`;
  document.getElementById('outputPill').textContent = pillText;

  outputCard.style.display = 'block';
  requestAnimationFrame(() => outputCard.classList.add('show'));
  outputCard.scrollIntoView({ behavior: 'smooth', block: 'nearest' });
}

async function copyMessage() {
  const msg = document.getElementById('outputMessage').textContent;
  try {
    await navigator.clipboard.writeText(msg);
    const btn = document.getElementById('copyBtn');
    btn.classList.add('copied');
    btn.innerHTML = '<span>✓</span> Copied';
    setTimeout(() => {
      btn.classList.remove('copied');
      btn.innerHTML = '<span>⧉</span> Copy message';
    }, 2200);
  } catch (e) {}
}

function recompose() {
  const outputCard = document.getElementById('outputCard');
  outputCard.classList.remove('show');
  setTimeout(() => { outputCard.style.display = 'none'; compose(); }, 350);
}
</script>
</body>
</html>
