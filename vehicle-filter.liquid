{% comment %}
  MARKAXD Auto Group - Araç Uyumluluk Filtresi
  Sıfırdan düzenlenmiş tam sürüm - Web tam genişlik güncellemesi
{% endcomment %}

<style>
  #vehicle-filter-{{ section.id }} {
    --vf-orange: #ff7a00;
    --vf-orange-2: #ff9d1f;
    --vf-black: #0d0f14;
    --vf-dark: #15171d;
    --vf-card-dark: #101217;
    --vf-white: #ffffff;
    --vf-muted: rgba(255,255,255,0.72);
    --vf-border: rgba(255,255,255,0.14);
    --vf-shadow: 0 22px 55px rgba(0,0,0,0.22);
  }

  #vehicle-filter-{{ section.id }} * {
    box-sizing: border-box;
  }

  /* Shopify tema genişlik sınırını kırar: bölüm webde sağ-sol tam ekran olur */
  .shopify-section.vehicle-filter-section {
    width: 100vw;
    max-width: 100vw;
    margin-left: calc(50% - 50vw);
    margin-right: calc(50% - 50vw);
    padding-left: 0 !important;
    padding-right: 0 !important;
  }

  #vehicle-filter-{{ section.id }}.vf-section {
    position: relative;
    overflow: hidden;
    width: 100vw;
    max-width: 100vw;
    margin-left: calc(50% - 50vw);
    margin-right: calc(50% - 50vw);
    background: {{ section.settings.bg_color }};
    padding: 56px 0;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Arial, sans-serif;
    isolation: isolate;
  }

  #vehicle-filter-{{ section.id }}.vf-section::before {
    content: "";
    position: absolute;
    width: 360px;
    height: 360px;
    left: -160px;
    top: -170px;
    border-radius: 999px;
    background: rgba(255,122,0,0.17);
    z-index: -1;
  }

  #vehicle-filter-{{ section.id }}.vf-section::after {
    content: "";
    position: absolute;
    width: 420px;
    height: 420px;
    right: -190px;
    bottom: -220px;
    border-radius: 999px;
    background: rgba(255,122,0,0.10);
    z-index: -1;
  }

  #vehicle-filter-{{ section.id }} .vf-container {
    width: 100%;
    max-width: none;
    margin: 0;
    padding: 0;
  }

  #vehicle-filter-{{ section.id }} .vf-hero {
    display: grid;
    grid-template-columns: minmax(0, 1fr) minmax(420px, 1fr);
    gap: 24px;
    align-items: stretch;
  }

  #vehicle-filter-{{ section.id }} .vf-left-panel {
    position: relative;
    min-height: 560px;
    overflow: hidden;
    border-radius: 28px;
    padding: 42px;
    background:
      radial-gradient(circle at 88% 12%, rgba(255,255,255,0.22) 0 18%, transparent 19%),
      radial-gradient(circle at 100% 12%, rgba(255,255,255,0.14) 0 30%, transparent 31%),
      linear-gradient(135deg, var(--vf-orange), var(--vf-orange-2));
    box-shadow: var(--vf-shadow);
    display: flex;
    align-items: center;
  }

  #vehicle-filter-{{ section.id }} .vf-left-content {
    position: relative;
    z-index: 2;
  }

  #vehicle-filter-{{ section.id }} .vf-badge {
    display: inline-flex;
    align-items: center;
    gap: 10px;
    width: fit-content;
    background: #08090d;
    color: var(--vf-white);
    border-radius: 999px;
    padding: 11px 18px;
    font-size: 12px;
    font-weight: 900;
    letter-spacing: 1.8px;
    text-transform: uppercase;
    box-shadow: 0 15px 32px rgba(0,0,0,0.22);
  }

  #vehicle-filter-{{ section.id }} .vf-badge svg {
    animation: vf-drive 2.2s ease-in-out infinite;
  }

  #vehicle-filter-{{ section.id }} .vf-title {
    max-width: 560px;
    margin: 28px 0 0;
    color: var(--vf-white);
    font-size: clamp(42px, 5vw, 72px);
    line-height: 0.98;
    font-weight: 950;
    letter-spacing: -2.2px;
  }

  #vehicle-filter-{{ section.id }} .vf-title-black {
    display: inline-block;
    background: #07080c;
    color: var(--vf-white);
    padding: 0.02em 0.17em 0.09em;
    border-radius: 16px;
    transform: rotate(-1deg);
  }

  #vehicle-filter-{{ section.id }} .vf-card {
    position: relative;
    min-height: 560px;
    border-radius: 28px;
    padding: 14px;
    background: {{ section.settings.card_bg }};
    box-shadow: var(--vf-shadow);
  }

  #vehicle-filter-{{ section.id }} .vf-card-inner {
    position: relative;
    width: 100%;
    min-height: 532px;
    overflow: hidden;
    border-radius: 23px;
    padding: 28px;
    background:
      radial-gradient(circle at 96% 0%, rgba(255,122,0,0.26) 0 17%, transparent 18%),
      var(--vf-card-dark);
  }

  #vehicle-filter-{{ section.id }} .vf-card-content {
    position: relative;
    z-index: 2;
  }

  #vehicle-filter-{{ section.id }} .vf-kicker {
    display: inline-flex;
    align-items: center;
    gap: 10px;
    width: fit-content;
    padding: 10px 14px;
    border-radius: 999px;
    background: rgba(255,255,255,0.10);
    border: 1px solid var(--vf-border);
    color: var(--vf-white);
    font-size: 12px;
    font-weight: 900;
    letter-spacing: 0.4px;
  }

  #vehicle-filter-{{ section.id }} .vf-kicker-icon,
  #vehicle-filter-{{ section.id }} .vf-label-icon {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    flex: 0 0 auto;
    width: 30px;
    height: 30px;
    border-radius: 999px;
    background: var(--vf-orange);
    color: var(--vf-white);
    box-shadow: 0 8px 18px rgba(255,122,0,0.26);
  }

  #vehicle-filter-{{ section.id }} .vf-visual-box {
    position: relative;
    height: 126px;
    margin: 22px 0 22px;
    border-radius: 22px;
    overflow: hidden;
    background:
      linear-gradient(145deg, rgba(255,122,0,0.97), rgba(255,157,31,0.88));
    border: 1px solid rgba(255,255,255,0.18);
  }

  #vehicle-filter-{{ section.id }} .vf-road {
    position: absolute;
    left: 0;
    right: 0;
    bottom: 30px;
    height: 7px;
    background: repeating-linear-gradient(
      90deg,
      rgba(255,255,255,0.9) 0 28px,
      transparent 28px 48px
    );
    animation: vf-road 1.15s linear infinite;
  }

  #vehicle-filter-{{ section.id }} .vf-car-icon {
    position: absolute;
    left: 34px;
    bottom: 40px;
    width: 68px;
    height: 68px;
    color: var(--vf-white);
    filter: drop-shadow(0 14px 24px rgba(0,0,0,0.24));
    animation: vf-car 2.2s ease-in-out infinite;
  }

  #vehicle-filter-{{ section.id }} .vf-mat-icon {
    position: absolute;
    right: 34px;
    top: 28px;
    width: 66px;
    height: 66px;
    padding: 14px;
    border-radius: 22px;
    color: var(--vf-black);
    background: rgba(255,255,255,0.94);
    box-shadow: 0 18px 34px rgba(0,0,0,0.20);
    animation: vf-pulse 2.4s ease-in-out infinite;
  }

  #vehicle-filter-{{ section.id }} .vf-dot {
    position: absolute;
    width: 11px;
    height: 11px;
    border-radius: 999px;
    background: #ffffff;
    opacity: 0.82;
    animation: vf-spark 2.5s ease-in-out infinite;
  }

  #vehicle-filter-{{ section.id }} .vf-dot-1 {
    left: 45%;
    top: 26px;
  }

  #vehicle-filter-{{ section.id }} .vf-dot-2 {
    right: 27%;
    bottom: 46px;
    animation-delay: 0.4s;
  }

  #vehicle-filter-{{ section.id }} .vf-form-title {
    margin: 0 0 16px;
    color: var(--vf-white);
    font-size: 28px;
    line-height: 1.1;
    font-weight: 950;
    letter-spacing: -0.8px;
  }

  #vehicle-filter-{{ section.id }} .vf-selects {
    display: grid;
    grid-template-columns: 1fr;
    gap: 14px;
    margin-bottom: 14px;
  }

  #vehicle-filter-{{ section.id }} .vf-select-wrap {
    display: flex;
    flex-direction: column;
    text-align: left;
  }

  #vehicle-filter-{{ section.id }} .vf-label {
    display: flex;
    align-items: center;
    gap: 10px;
    margin-bottom: 7px;
    color: var(--vf-white);
    font-size: 12px;
    line-height: 1.25;
    font-weight: 950;
    letter-spacing: 1.6px;
    text-transform: uppercase;
  }

  #vehicle-filter-{{ section.id }} .vf-label-icon {
    width: 28px;
    height: 28px;
    border-radius: 10px;
    animation: vf-pop 2.8s ease-in-out infinite;
  }

  #vehicle-filter-{{ section.id }} .vf-select {
    appearance: none;
    -webkit-appearance: none;
    width: 100%;
    min-height: 56px;
    border-radius: 16px;
    border: 1px solid rgba(255,255,255,0.22);
    background:
      rgba(255,255,255,0.10)
      url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='13' height='8' viewBox='0 0 13 8'%3E%3Cpath d='M1 1l5.5 5.5L12 1' stroke='%23ffffff' stroke-width='2' fill='none' stroke-linecap='round'/%3E%3C/svg%3E")
      no-repeat right 17px center;
    color: var(--vf-white);
    font-size: 15px;
    font-weight: 800;
    padding: 14px 46px 14px 16px;
    cursor: pointer;
    outline: none;
    transition: 0.22s ease;
  }

  #vehicle-filter-{{ section.id }} .vf-select:hover {
    transform: translateY(-1px);
    border-color: rgba(255,122,0,0.9);
    background-color: rgba(255,255,255,0.14);
  }

  #vehicle-filter-{{ section.id }} .vf-select:focus {
    border-color: var(--vf-orange);
    box-shadow: 0 0 0 4px rgba(255,122,0,0.22);
  }

  #vehicle-filter-{{ section.id }} .vf-select:disabled {
    opacity: 0.45;
    cursor: not-allowed;
    transform: none;
  }

  #vehicle-filter-{{ section.id }} .vf-select option {
    color: #111111;
    background: #ffffff;
  }

  #vehicle-filter-{{ section.id }} .vf-preview {
    display: flex;
    align-items: flex-start;
    gap: 12px;
    margin: 14px 0;
    padding: 13px;
    border-radius: 18px;
    background: rgba(255,122,0,0.16);
    border: 1px solid rgba(255,122,0,0.38);
    color: var(--vf-white);
  }

  #vehicle-filter-{{ section.id }} .vf-preview-icon {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    width: 38px;
    height: 38px;
    flex: 0 0 auto;
    border-radius: 14px;
    background: var(--vf-orange);
    color: var(--vf-white);
    animation: vf-float 2.8s ease-in-out infinite;
  }

  #vehicle-filter-{{ section.id }} .vf-preview strong {
    display: block;
    margin-bottom: 4px;
    color: var(--vf-white);
    font-size: 13.5px;
    line-height: 1.25;
    font-weight: 950;
  }

  #vehicle-filter-{{ section.id }} .vf-preview span {
    display: block;
    color: var(--vf-muted);
    font-size: 12.5px;
    line-height: 1.4;
    font-weight: 600;
  }

  #vehicle-filter-{{ section.id }} .vf-error {
    display: none;
    margin: 10px 0 14px;
    padding: 12px 14px;
    border-radius: 15px;
    background: rgba(255, 74, 74, 0.14);
    border: 1px solid rgba(255, 99, 99, 0.46);
    color: #ffffff;
    font-size: 13px;
    font-weight: 850;
    text-align: left;
  }

  #vehicle-filter-{{ section.id }} .vf-error.show {
    display: block;
    animation: vf-shake 0.34s ease;
  }

  #vehicle-filter-{{ section.id }} .vf-btn {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    gap: 10px;
    width: 100%;
    min-height: 54px;
    border: 0;
    border-radius: 17px;
    background: var(--vf-orange);
    color: var(--vf-white);
    font-size: 15px;
    font-weight: 950;
    letter-spacing: 0.2px;
    cursor: pointer;
    box-shadow: 0 15px 30px rgba(255,122,0,0.33);
    transition: 0.2s ease;
  }

  #vehicle-filter-{{ section.id }} .vf-btn:hover {
    transform: translateY(-3px);
    background: #ff8b19;
    box-shadow: 0 20px 40px rgba(255,122,0,0.42);
  }

  #vehicle-filter-{{ section.id }} .vf-btn svg {
    animation: vf-search 2.4s ease-in-out infinite;
  }

  #vehicle-filter-{{ section.id }} .vf-footer {
    margin-top: 14px;
    text-align: center;
    color: rgba(255,255,255,0.68);
    font-size: 13px;
    line-height: 1.45;
    font-weight: 600;
  }

  #vehicle-filter-{{ section.id }} .vf-footer a {
    color: var(--vf-white);
    text-decoration: none;
    font-weight: 950;
    border-bottom: 1px dashed rgba(255,255,255,0.45);
  }

  #vehicle-filter-{{ section.id }} .vf-footer a:hover {
    color: #ffd7ad;
  }

  @keyframes vf-drive {
    0%, 100% { transform: translateX(0) rotate(0deg); }
    50% { transform: translateX(5px) rotate(-2deg); }
  }

  @keyframes vf-road {
    from { background-position: 0 0; }
    to { background-position: -48px 0; }
  }

  @keyframes vf-car {
    0%, 100% { transform: translateX(0) translateY(0); }
    50% { transform: translateX(10px) translateY(-4px); }
  }

  @keyframes vf-pulse {
    0%, 100% { transform: scale(1) rotate(0deg); }
    50% { transform: scale(1.06) rotate(2deg); }
  }

  @keyframes vf-spark {
    0%, 100% { transform: scale(0.7); opacity: 0.35; }
    50% { transform: scale(1.25); opacity: 0.95; }
  }

  @keyframes vf-pop {
    0%, 100% { transform: scale(1); }
    50% { transform: scale(1.08); }
  }

  @keyframes vf-float {
    0%, 100% { transform: translateY(0); }
    50% { transform: translateY(-5px); }
  }

  @keyframes vf-search {
    0%, 100% { transform: rotate(0deg) scale(1); }
    50% { transform: rotate(-8deg) scale(1.08); }
  }

  @keyframes vf-shake {
    0%, 100% { transform: translateX(0); }
    25% { transform: translateX(-4px); }
    75% { transform: translateX(4px); }
  }



  /* MARKAXD - Web yatay araç seçim düzeni */
  #vehicle-filter-{{ section.id }} .vf-action-row {
    display: block;
  }

  @media (min-width: 981px) {
    #vehicle-filter-{{ section.id }} .vf-container {
      width: 100%;
      max-width: none;
      margin: 0;
      padding: 0;
    }

    #vehicle-filter-{{ section.id }} .vf-hero {
      width: 100%;
      grid-template-columns: minmax(360px, 0.85fr) minmax(760px, 1.45fr);
      gap: 24px;
      align-items: stretch;
    }

    #vehicle-filter-{{ section.id }} .vf-left-panel,
    #vehicle-filter-{{ section.id }} .vf-card {
      min-height: 430px;
    }

    #vehicle-filter-{{ section.id }} .vf-left-panel {
      border-radius: 0 28px 28px 0;
    }

    #vehicle-filter-{{ section.id }} .vf-card {
      border-radius: 28px 0 0 28px;
    }

    #vehicle-filter-{{ section.id }} .vf-card-inner {
      min-height: 402px;
      padding: 30px;
      display: flex;
      align-items: center;
    }

    #vehicle-filter-{{ section.id }} .vf-card-content {
      width: 100%;
    }

    #vehicle-filter-{{ section.id }} .vf-visual-box {
      height: 82px;
      margin: 14px 0 20px;
    }

    #vehicle-filter-{{ section.id }} .vf-car-icon {
      width: 50px;
      height: 50px;
      left: 30px;
      bottom: 28px;
    }

    #vehicle-filter-{{ section.id }} .vf-mat-icon {
      width: 50px;
      height: 50px;
      right: 30px;
      top: 17px;
    }

    #vehicle-filter-{{ section.id }} .vf-form-title {
      margin-bottom: 18px;
      font-size: 26px;
    }

    #vehicle-filter-{{ section.id }} .vf-selects {
      display: grid !important;
      grid-template-columns: repeat(3, minmax(0, 1fr));
      gap: 14px;
      align-items: end;
      margin-bottom: 16px;
    }

    #vehicle-filter-{{ section.id }} .vf-select-wrap {
      min-width: 0;
    }

    #vehicle-filter-{{ section.id }} .vf-label {
      min-height: 34px;
      margin-bottom: 8px;
      font-size: 11px;
      letter-spacing: 1.1px;
      white-space: nowrap;
    }

    #vehicle-filter-{{ section.id }} .vf-label-icon {
      width: 26px;
      height: 26px;
    }

    #vehicle-filter-{{ section.id }} .vf-select {
      min-height: 54px;
      font-size: 14px;
      padding: 13px 42px 13px 14px;
    }

    #vehicle-filter-{{ section.id }} .vf-preview {
      margin: 12px 0 14px;
      padding: 12px 14px;
    }

    #vehicle-filter-{{ section.id }} .vf-action-row {
      display: grid;
      grid-template-columns: minmax(240px, 0.75fr) minmax(300px, 1fr);
      gap: 14px;
      align-items: center;
    }

    #vehicle-filter-{{ section.id }} .vf-btn {
      min-height: 54px;
      white-space: nowrap;
    }

    #vehicle-filter-{{ section.id }} .vf-footer {
      margin-top: 0;
      text-align: left;
      font-size: 12.5px;
      line-height: 1.45;
    }
  }

  @media (max-width: 980px) {
    .shopify-section.vehicle-filter-section {
      width: 100%;
      max-width: 100%;
      margin-left: 0;
      margin-right: 0;
    }

    #vehicle-filter-{{ section.id }}.vf-section {
      width: 100%;
      max-width: 100%;
      margin-left: 0;
      margin-right: 0;
      padding: 34px 12px;
    }

    #vehicle-filter-{{ section.id }} .vf-container {
      max-width: 560px;
      margin: 0 auto;
      padding: 0;
    }

    #vehicle-filter-{{ section.id }} .vf-hero {
      grid-template-columns: 1fr;
    }

    #vehicle-filter-{{ section.id }} .vf-left-panel,
    #vehicle-filter-{{ section.id }} .vf-card {
      min-height: auto;
    }

    #vehicle-filter-{{ section.id }} .vf-card-inner {
      min-height: auto;
    }
  }

  @media (max-width: 640px) {
    #vehicle-filter-{{ section.id }}.vf-section {
      padding: 34px 12px;
    }

    #vehicle-filter-{{ section.id }} .vf-left-panel {
      border-radius: 22px;
      padding: 28px 20px;
      min-height: 330px;
    }

    #vehicle-filter-{{ section.id }} .vf-title {
      font-size: 38px;
      letter-spacing: -1.3px;
    }

    #vehicle-filter-{{ section.id }} .vf-badge {
      font-size: 10px;
      letter-spacing: 1px;
      padding: 9px 13px;
    }

    #vehicle-filter-{{ section.id }} .vf-card {
      border-radius: 22px;
      padding: 10px;
    }

    #vehicle-filter-{{ section.id }} .vf-card-inner {
      border-radius: 18px;
      padding: 20px 15px;
    }

    #vehicle-filter-{{ section.id }} .vf-kicker {
      font-size: 11px;
      padding: 9px 12px;
    }

    #vehicle-filter-{{ section.id }} .vf-visual-box {
      height: 104px;
      margin: 16px 0 18px;
      border-radius: 18px;
    }

    #vehicle-filter-{{ section.id }} .vf-car-icon {
      width: 56px;
      height: 56px;
      left: 20px;
      bottom: 34px;
    }

    #vehicle-filter-{{ section.id }} .vf-mat-icon {
      width: 54px;
      height: 54px;
      right: 18px;
      top: 24px;
      border-radius: 18px;
      padding: 12px;
    }

    #vehicle-filter-{{ section.id }} .vf-form-title {
      font-size: 24px;
    }

    #vehicle-filter-{{ section.id }} .vf-select {
      min-height: 52px;
      font-size: 14px;
      padding: 13px 44px 13px 14px;
    }

    #vehicle-filter-{{ section.id }} .vf-btn {
      min-height: 52px;
      font-size: 14px;
    }
  }
</style>

<section class="vf-section" id="vehicle-filter-{{ section.id }}">
  <div class="vf-container">
    <div class="vf-hero">

      <div class="vf-left-panel">
        <div class="vf-left-content">
          <div class="vf-badge">
            <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.4" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
              <path d="M5 17h14l-1.5-5.2A3 3 0 0 0 14.6 10H9.4a3 3 0 0 0-2.9 1.8L5 17Z"/>
              <path d="M7 17v1.2"/>
              <path d="M17 17v1.2"/>
              <circle cx="8" cy="17" r="1.8"/>
              <circle cx="16" cy="17" r="1.8"/>
              <path d="M8 10l1-3h6l1 3"/>
            </svg>
            MARKAXD Araç Uyumluluk Sistemi
          </div>

          <h2 class="vf-title">
            {{ section.settings.title | replace: 'Ürünleri', '<span class="vf-title-black">Ürünleri</span>' }}
          </h2>
        </div>
      </div>

      <div class="vf-card">
        <div class="vf-card-inner">
          <div class="vf-card-content">

            <div class="vf-kicker">
              <span class="vf-kicker-icon" aria-hidden="true">
                <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round">
                  <path d="M3 11h18"/>
                  <path d="M5 7h14"/>
                  <path d="M7 15h10"/>
                  <path d="M9 19h6"/>
                </svg>
              </span>
              Aracını seç, uyumlu ürünü gör
            </div>

            <div class="vf-visual-box" aria-hidden="true">
              <span class="vf-dot vf-dot-1"></span>
              <span class="vf-dot vf-dot-2"></span>

              <svg class="vf-car-icon" viewBox="0 0 64 64" fill="none" stroke="currentColor" stroke-width="3.2" stroke-linecap="round" stroke-linejoin="round">
                <path d="M13 39h38l-4-13c-.7-2.3-2.8-3.9-5.2-3.9H22.2c-2.4 0-4.5 1.6-5.2 3.9L13 39Z"/>
                <path d="M17 39v5"/>
                <path d="M47 39v5"/>
                <circle cx="22" cy="42" r="4"/>
                <circle cx="42" cy="42" r="4"/>
                <path d="M23 22l2-8h14l2 8"/>
                <path d="M25 30h14"/>
              </svg>

              <svg class="vf-mat-icon" viewBox="0 0 64 64" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round">
                <path d="M20 9h24c4 0 7 3 7 7v32c0 4-3 7-7 7H20c-4 0-7-3-7-7V16c0-4 3-7 7-7Z"/>
                <path d="M23 20h18"/>
                <path d="M23 30h18"/>
                <path d="M23 40h12"/>
                <path d="M45 18v28"/>
              </svg>

              <div class="vf-road"></div>
            </div>

            <h3 class="vf-form-title">Uyumlu ürünleri bul</h3>

            <div class="vf-selects">
              <div class="vf-select-wrap">
                <label class="vf-label" for="vf-brand-{{ section.id }}">
                  <span class="vf-label-icon" aria-hidden="true">
                    <svg width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.4" stroke-linecap="round" stroke-linejoin="round">
                      <circle cx="12" cy="12" r="8"/>
                      <path d="M12 4v8l5 3"/>
                    </svg>
                  </span>
                  Araç Markası
                </label>
                <select class="vf-select" id="vf-brand-{{ section.id }}">
                  <option value="">Marka Seçiniz</option>
                </select>
              </div>

              <div class="vf-select-wrap">
                <label class="vf-label" for="vf-model-{{ section.id }}">
                  <span class="vf-label-icon" aria-hidden="true">
                    <svg width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.4" stroke-linecap="round" stroke-linejoin="round">
                      <path d="M4 7h16"/>
                      <path d="M4 12h16"/>
                      <path d="M4 17h10"/>
                    </svg>
                  </span>
                  Araç Modeli
                </label>
                <select class="vf-select" id="vf-model-{{ section.id }}" disabled>
                  <option value="">Model Seçiniz</option>
                </select>
              </div>

              <div class="vf-select-wrap">
                <label class="vf-label" for="vf-year-{{ section.id }}">
                  <span class="vf-label-icon" aria-hidden="true">
                    <svg width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.4" stroke-linecap="round" stroke-linejoin="round">
                      <rect x="3" y="4" width="18" height="18" rx="2"/>
                      <path d="M16 2v4"/>
                      <path d="M8 2v4"/>
                      <path d="M3 10h18"/>
                    </svg>
                  </span>
                  Araç Yılı
                </label>
                <select class="vf-select" id="vf-year-{{ section.id }}" disabled>
                  <option value="">Yıl Seçiniz</option>
                </select>
              </div>
            </div>

            <div class="vf-preview">
              <span class="vf-preview-icon" aria-hidden="true">
                <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.4" stroke-linecap="round" stroke-linejoin="round">
                  <path d="M20 6 9 17l-5-5"/>
                </svg>
              </span>
              <div>
                <strong id="vf-preview-title-{{ section.id }}">Seçim bekleniyor</strong>
                <span id="vf-preview-text-{{ section.id }}">Marka, model ve yıl seçerek devam edin.</span>
              </div>
            </div>

            <div class="vf-error" id="vf-error-{{ section.id }}">
              ⚠️ Lütfen marka, model ve yıl seçiniz.
            </div>

            <div class="vf-action-row">
              <button class="vf-btn" id="vf-btn-{{ section.id }}" type="button">
                <svg width="19" height="19" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.7" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
                  <circle cx="11" cy="11" r="8"/>
                  <path d="m21 21-4.35-4.35"/>
                </svg>
                {{ section.settings.btn_label }}
              </button>

              <div class="vf-footer">
                <span>Aracınızı listede bulamadınız mı? </span>
                <a href="https://wa.me/{{ section.settings.whatsapp_number }}?text={{ section.settings.whatsapp_message | url_encode }}" target="_blank" rel="noopener">
                  WhatsApp'tan bize yazın →
                </a>
              </div>
            </div>

          </div>
        </div>
      </div>

    </div>
  </div>
</section>

<script>
(function() {
  var SID = '{{ section.id }}';
  var LS_KEY = 'markaxd_vehicle_filter_' + SID;

  var VEHICLE_DATA = [];
  try {
    VEHICLE_DATA = JSON.parse({{ section.settings.vehicle_json | json }});
  } catch(e) {
    VEHICLE_DATA = [];
  }

  var MODEL_EXTRA_PRICE_DATA = [];
  try {
    MODEL_EXTRA_PRICE_DATA = JSON.parse({{ section.settings.model_extra_price_json | json }});
  } catch(e) {
    MODEL_EXTRA_PRICE_DATA = [];
  }

  var SHOW_EXTRA_PRICE = {{ section.settings.show_extra_price | json }};
  var YEAR_START = parseInt({{ section.settings.year_start | json }}, 10) || 2000;
  var YEAR_END = parseInt({{ section.settings.year_end | json }}, 10) || 2026;
  var TARGET_COLLECTION = {{ section.settings.target_collection | json }};

  var selBrand = document.getElementById('vf-brand-' + SID);
  var selModel = document.getElementById('vf-model-' + SID);
  var selYear = document.getElementById('vf-year-' + SID);
  var btnShow = document.getElementById('vf-btn-' + SID);
  var errBox = document.getElementById('vf-error-' + SID);
  var prevTitle = document.getElementById('vf-preview-title-' + SID);
  var prevText = document.getElementById('vf-preview-text-' + SID);

  if (!selBrand || !selModel || !selYear || !btnShow) return;

  function cleanString(value) {
    return String(value || '').trim();
  }

  function getBrands() {
    return VEHICLE_DATA
      .filter(function(item) { return item && item.brand; })
      .map(function(item) { return cleanString(item.brand); });
  }

  function getBrandData(brandName) {
    return VEHICLE_DATA.find(function(item) {
      return item && cleanString(item.brand) === cleanString(brandName);
    }) || null;
  }

  function getModels(brandName) {
    var brandData = getBrandData(brandName);
    if (!brandData || !Array.isArray(brandData.models)) return [];

    return brandData.models
      .filter(function(item) {
        return item && (item.name || item.model);
      })
      .map(function(item) {
        return cleanString(item.name || item.model);
      });
  }

  function fillSelect(selectEl, items, placeholder, disabled) {
    selectEl.innerHTML = '';
    var firstOption = document.createElement('option');
    firstOption.value = '';
    firstOption.textContent = placeholder;
    selectEl.appendChild(firstOption);

    items.forEach(function(item) {
      var opt = document.createElement('option');
      opt.value = item;
      opt.textContent = item;
      selectEl.appendChild(opt);
    });

    selectEl.disabled = !!disabled;
  }

  function resetSelect(selectEl, placeholder) {
    fillSelect(selectEl, [], placeholder, true);
  }

  function getYearList() {
    var years = [];
    for (var y = YEAR_END; y >= YEAR_START; y--) {
      years.push(String(y));
    }
    return years;
  }

  function slugify(str) {
    return cleanString(str)
      .toLowerCase()
      .replace(/ğ/g,'g')
      .replace(/ü/g,'u')
      .replace(/ş/g,'s')
      .replace(/ı/g,'i')
      .replace(/ö/g,'o')
      .replace(/ç/g,'c')
      .replace(/\s+/g,'-')
      .replace(/[^a-z0-9\-]/g,'');
  }

  function toNumber(value) {
    if (value === null || value === undefined || value === '') return 0;
    if (typeof value === 'number') return value;

    var normalized = String(value)
      .replace(/TL/gi, '')
      .replace(/₺/g, '')
      .replace(/\s/g, '')
      .replace(/\./g, '')
      .replace(',', '.')
      .replace(/[^0-9.\-]/g, '');

    var numberValue = parseFloat(normalized);
    return isNaN(numberValue) ? 0 : numberValue;
  }

  function formatTL(amount) {
    amount = toNumber(amount);
    try {
      return amount.toLocaleString('tr-TR') + ' TL';
    } catch(e) {
      return amount + ' TL';
    }
  }

  function findPriceBrand(brandName) {
    return MODEL_EXTRA_PRICE_DATA.find(function(item) {
      return item && cleanString(item.brand) === cleanString(brandName);
    }) || null;
  }

  function findPriceModel(brandName, modelName) {
    var brandData = findPriceBrand(brandName);
    if (!brandData || !Array.isArray(brandData.models)) return null;

    return brandData.models.find(function(item) {
      return item && cleanString(item.name || item.model) === cleanString(modelName);
    }) || null;
  }

  function getModelExtraPrice(brandName, modelName, yearValue) {
    var priceModel = findPriceModel(brandName, modelName);
    if (!priceModel) return 0;

    var basePrice = toNumber(
      priceModel.extra_price ||
      priceModel.extraPrice ||
      priceModel.price_extra ||
      priceModel.priceExtra
    );

    var yearExtra = 0;
    var yearMap = priceModel.year_extra_prices || priceModel.yearExtraPrices || priceModel.year_prices || priceModel.yearPrices;

    if (yearMap && typeof yearMap === 'object') {
      yearExtra = toNumber(yearMap[String(yearValue)]);
    }

    return basePrice + yearExtra;
  }

  function getCurrentSelection() {
    var brand = cleanString(selBrand.value);
    var model = cleanString(selModel.value);
    var year = cleanString(selYear.value);
    var extraPrice = getModelExtraPrice(brand, model, year);

    return {
      brand: brand,
      model: model,
      year: year,
      model_extra_price: extraPrice,
      model_extra_price_text: formatTL(extraPrice)
    };
  }

  function updatePreview() {
    var s = getCurrentSelection();

    if (s.brand && s.model && s.year) {
      prevTitle.textContent = s.brand + ' ' + s.model + ' - ' + s.year;

      if (SHOW_EXTRA_PRICE && s.model_extra_price > 0) {
        prevText.textContent = 'Bu model için +' + s.model_extra_price_text + ' ekstra fiyat uygulanır.';
      } else {
        prevText.textContent = 'Bu araca uyumlu MARKAXD ürünlerini görüntülemeye hazırsınız.';
      }

      return;
    }

    if (s.brand && s.model) {
      prevTitle.textContent = s.brand + ' ' + s.model;
      prevText.textContent = 'Son adım: araç yılını seçin.';
      return;
    }

    if (s.brand) {
      prevTitle.textContent = s.brand;
      prevText.textContent = 'Şimdi araç modelini seçerek devam edin.';
      return;
    }

    prevTitle.textContent = 'Seçim bekleniyor';
    prevText.textContent = 'Marka, model ve yıl seçerek devam edin.';
  }

  function saveSelection() {
    try {
      localStorage.setItem(LS_KEY, JSON.stringify(getCurrentSelection()));
    } catch(e) {}
  }

  function restoreSelection() {
    try {
      var saved = JSON.parse(localStorage.getItem(LS_KEY) || '{}');

      if (saved.brand) {
        selBrand.value = saved.brand;
        selBrand.dispatchEvent(new Event('change'));
      }

      if (saved.model) {
        setTimeout(function() {
          selModel.value = saved.model;
          selModel.dispatchEvent(new Event('change'));

          if (saved.year) {
            setTimeout(function() {
              selYear.value = saved.year;
              updatePreview();
            }, 0);
          }
        }, 0);
      }
    } catch(e) {}
  }

  selBrand.addEventListener('change', function() {
    errBox.classList.remove('show');

    var brand = cleanString(selBrand.value);
    resetSelect(selModel, 'Model Seçiniz');
    resetSelect(selYear, 'Yıl Seçiniz');

    if (brand) {
      fillSelect(selModel, getModels(brand), 'Model Seçiniz', false);
    }

    saveSelection();
    updatePreview();
  });

  selModel.addEventListener('change', function() {
    errBox.classList.remove('show');

    var model = cleanString(selModel.value);
    resetSelect(selYear, 'Yıl Seçiniz');

    if (model) {
      fillSelect(selYear, getYearList(), 'Yıl Seçiniz', false);
    }

    saveSelection();
    updatePreview();
  });

  selYear.addEventListener('change', function() {
    errBox.classList.remove('show');
    saveSelection();
    updatePreview();
  });

  btnShow.addEventListener('click', function() {
    var s = getCurrentSelection();

    if (!s.brand || !s.model || !s.year) {
      errBox.classList.add('show');
      updatePreview();
      return;
    }

    saveSelection();

    try {
      sessionStorage.setItem('markaxd_vehicle_selection', JSON.stringify(s));
    } catch(e) {}

    var baseUrl = TARGET_COLLECTION || '/collections/all';
    var params = new URLSearchParams({
      vehicle_brand: s.brand,
      vehicle_model: s.model,
      vehicle_year: s.year,
      model_extra_price: s.model_extra_price
    });

    window.location.href =
      baseUrl +
      '?vehicle_brand=' + encodeURIComponent(s.brand) +
      '&vehicle_model=' + encodeURIComponent(s.model) +
      '&vehicle_year=' + encodeURIComponent(s.year) +
      '&model_extra_price=' + encodeURIComponent(s.model_extra_price) +
      '&vehicle_tag=' + encodeURIComponent(slugify(s.brand) + '+model_' + slugify(s.model) + '+year_' + s.year);
  });

  fillSelect(selBrand, getBrands(), 'Marka Seçiniz', false);
  resetSelect(selModel, 'Model Seçiniz');
  resetSelect(selYear, 'Yıl Seçiniz');
  updatePreview();
  restoreSelection();
})();
</script>

{% schema %}
{
  "name": "Araç Uyumluluk Filtresi",
  "tag": "section",
  "class": "vehicle-filter-section",
  "settings": [
    {
      "type": "text",
      "id": "title",
      "label": "Başlık",
      "default": "Aracına Özel Ürünleri Bul"
    },
    {
      "type": "text",
      "id": "btn_label",
      "label": "Buton Metni",
      "default": "Uyumlu Ürünleri Göster"
    },
    {
      "type": "text",
      "id": "target_collection",
      "label": "Yönlendirme Koleksiyonu",
      "default": "/collections/all"
    },
    {
      "type": "text",
      "id": "whatsapp_number",
      "label": "WhatsApp Numarası",
      "default": "905551234567"
    },
    {
      "type": "text",
      "id": "whatsapp_message",
      "label": "WhatsApp Mesajı",
      "default": "Merhaba, aracım için uyumlu ürün kontrolü yapmak istiyorum."
    },
    {
      "type": "color",
      "id": "bg_color",
      "label": "Arka Plan Rengi",
      "default": "#080a0f"
    },
    {
      "type": "color",
      "id": "card_bg",
      "label": "Kart Dış Rengi",
      "default": "#ff7a00"
    },
    {
      "type": "text",
      "id": "year_start",
      "label": "Başlangıç Yılı",
      "default": "2000"
    },
    {
      "type": "text",
      "id": "year_end",
      "label": "Bitiş Yılı",
      "default": "2026"
    },
    {
      "type": "textarea",
      "id": "vehicle_json",
      "label": "Araç Verisi JSON",
      "default": "[{\"brand\":\"BMW\",\"models\":[{\"name\":\"3 Serisi\"},{\"name\":\"5 Serisi\"},{\"name\":\"X1\"},{\"name\":\"X3\"},{\"name\":\"X5\"}]},{\"brand\":\"Mercedes-Benz\",\"models\":[{\"name\":\"A Serisi\"},{\"name\":\"C Serisi\"},{\"name\":\"E Serisi\"},{\"name\":\"GLA\"},{\"name\":\"GLC\"},{\"name\":\"GLE\"}]},{\"brand\":\"Audi\",\"models\":[{\"name\":\"A3\"},{\"name\":\"A4\"},{\"name\":\"A5\"},{\"name\":\"A6\"},{\"name\":\"Q2\"},{\"name\":\"Q3\"},{\"name\":\"Q5\"},{\"name\":\"Q7\"}]},{\"brand\":\"Volkswagen\",\"models\":[{\"name\":\"Polo\"},{\"name\":\"Golf\"},{\"name\":\"Passat\"},{\"name\":\"Tiguan\"},{\"name\":\"T-Roc\"}]},{\"brand\":\"Toyota\",\"models\":[{\"name\":\"Corolla\"},{\"name\":\"Yaris\"},{\"name\":\"C-HR\"},{\"name\":\"RAV4\"}]},{\"brand\":\"Ford\",\"models\":[{\"name\":\"Fiesta\"},{\"name\":\"Focus\"},{\"name\":\"Ecosport\"},{\"name\":\"Kuga\"},{\"name\":\"Mondeo\"}]},{\"brand\":\"Renault\",\"models\":[{\"name\":\"Clio\"},{\"name\":\"Megane\"},{\"name\":\"Kadjar\"},{\"name\":\"Captur\"}]},{\"brand\":\"Hyundai\",\"models\":[{\"name\":\"i20\"},{\"name\":\"i30\"},{\"name\":\"Tucson\"},{\"name\":\"Santa Fe\"}]},{\"brand\":\"Kia\",\"models\":[{\"name\":\"Ceed\"},{\"name\":\"Sportage\"},{\"name\":\"Sorento\"}]},{\"brand\":\"Peugeot\",\"models\":[{\"name\":\"208\"},{\"name\":\"308\"},{\"name\":\"3008\"},{\"name\":\"508\"}]}]"
    },
    {
      "type": "textarea",
      "id": "model_extra_price_json",
      "label": "Model Ekstra Fiyat Verisi JSON",
      "info": "Örnek: [{\"brand\":\"BMW\",\"models\":[{\"name\":\"X5\",\"extra_price\":1500,\"year_extra_prices\":{\"2026\":750}}]}]",
      "default": "[{\"brand\":\"BMW\",\"models\":[{\"name\":\"X5\",\"extra_price\":1500},{\"name\":\"X3\",\"extra_price\":750}]},{\"brand\":\"Mercedes-Benz\",\"models\":[{\"name\":\"GLE\",\"extra_price\":1500},{\"name\":\"GLC\",\"extra_price\":750}]},{\"brand\":\"Audi\",\"models\":[{\"name\":\"Q7\",\"extra_price\":1500},{\"name\":\"Q5\",\"extra_price\":750}]}]"
    },
    {
      "type": "checkbox",
      "id": "show_extra_price",
      "label": "Ekstra fiyatı müşteriye göster",
      "default": false
    }
  ],
  "presets": [
    {
      "name": "Araç Uyumluluk Filtresi"
    }
  ]
}
{% endschema %}
