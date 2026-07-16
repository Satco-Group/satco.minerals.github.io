---
layout: default
title: Market Insights | SATCO
---

<style>
  .insight-container { max-width: 800px; margin: 0 auto; padding: 20px; font-family: sans-serif; }
  
  /* کارت‌ها با افکت حرکت */
  .insight-card {
    background: #ffffff;
    border-top: 6px solid #d4af37;
    border-radius: 12px;
    padding: 40px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.05);
    margin-bottom: 40px;
    transition: transform 0.3s ease;
  }
  .insight-card:hover { transform: translateY(-5px); box-shadow: 0 15px 40px rgba(0,0,0,0.1); }
  
  .insight-meta { color: #d4af37; font-weight: bold; text-transform: uppercase; font-size: 12px; letter-spacing: 1.5px; margin-bottom: 10px; }
  
  /* نشانگر وضعیت (بصری) */
  .trend-badge {
    display: inline-block;
    padding: 5px 12px;
    border-radius: 20px;
    font-size: 12px;
    font-weight: 700;
    margin-bottom: 15px;
    background: #fff3e0;
    color: #e65100;
  }

  .insight-title { color: #0d1b2a; font-size: 26px; margin: 0 0 20px 0; }
  
  .data-grid { display: flex; gap: 20px; background: #f8f9fa; padding: 20px; border-radius: 8px; border-left: 4px solid #d4af37; margin: 20px 0; }
  .data-item { flex: 1; }
  .data-label { font-size: 11px; color: #666; text-transform: uppercase; margin-bottom: 5px; }
  .data-value { font-weight: 800; color: #0d1b2a; font-size: 18px; }
  
  .insight-body { color: #444; line-height: 1.7; font-size: 15px; margin-bottom: 25px; }
  
  .cta-box { background: #0d1b2a; color: #fff; padding: 25px; border-radius: 8px; text-align: center; }
  .btn-gold { 
    background: #d4af37; color: #0d1b2a; padding: 12px 30px; text-decoration: none; 
    border-radius: 5px; font-weight: bold; display: inline-block; margin-top: 10px;
  }
</style>

<div class="insight-container">
  <h1 style="color: #0d1b2a;">Market Intelligence</h1>
  <p style="color: #666; margin-bottom: 40px;">Weekly analysis on commodity pricing and freight market dynamics.</p>

  <!-- کارت کلینکر -->
  <article class="insight-card">
    <div class="insight-meta">July 16, 2026 • Bulk Commodities</div>
    <div class="trend-badge">▲ Upward Pressure</div>
    <h2 class="insight-title">Bulk Clinker Market Insight</h2>
    <div class="data-grid">
      <div class="data-item"><div class="data-label">Product</div><div class="data-value">Bulk Clinker (35k+ MT)</div></div>
      <div class="data-item"><div class="data-label">FOB Price Range</div><div class="data-value">$33 – $37 / MT</div></div>
    </div>
    <div class="insight-body">
      <p>While FOB price levels remain steady, total delivered cost faces upward pressure due to rising crude oil prices and maritime disruptions in the Persian Gulf.</p>
    </div>
    <div class="cta-box">
      <h3 style="margin-top: 0; color: #d4af37;">Need a CFR Quote?</h3>
      <a href="/05_contact.html" class="btn-gold">Request CFR Analysis</a>
    </div>
  </article>

  <!-- کارت سیمان -->
  <article class="insight-card">
    <div class="insight-meta">July 16, 2026 • Construction Materials</div>
    <div class="trend-badge">▲ Upward Pressure</div>
    <h2 class="insight-title">Portland Cement Market Insight</h2>
    <div class="data-grid">
      <div class="data-item"><div class="data-label">Product</div><div class="data-value">Portland Cement (Base)</div></div>
      <div class="data-item"><div class="data-label">FOB Price Range</div><div class="data-value">$48 – $58 / MT</div></div>
    </div>
    <div class="insight-body">
      <p>FOB pricing is balanced, but CFR costs are under pressure. We recommend finalizing logistics early to mitigate potential fuel-driven freight spikes.</p>
    </div>
    <div class="cta-box">
      <h3 style="margin-top: 0; color: #d4af37;">Need a CFR Quote?</h3>
      <a href="/05_contact.html" class="btn-gold">Request CFR Analysis</a>
    </div>
  </article>

  <!-- کارت سنگ گچ -->
  <article class="insight-card">
    <div class="insight-meta">July 16, 2026 • Industrial Minerals</div>
    <div class="trend-badge">▲ Upward Pressure</div>
    <h2 class="insight-title">Gypsum Rock Market Insight</h2>
    <div class="data-grid">
      <div class="data-item"><div class="data-label">Product</div><div class="data-value">Gypsum Rock</div></div>
      <div class="data-item"><div class="data-label">FOB Price Range</div><div class="data-value">$10 – $14 / MT</div></div>
    </div>
    <div class="insight-body">
      <p>FOB pricing ranges from $10–$14. Note that maritime premiums due to fuel volatility also apply here, increasing total landed costs for end-buyers.</p>
    </div>
    <div class="cta-box">
      <h3 style="margin-top: 0; color: #d4af37;">Need a CFR Quote?</h3>
      <a href="/05_contact.html" class="btn-gold">Request CFR Analysis</a>
    </div>
  </article>
</div>
