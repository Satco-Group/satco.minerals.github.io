---
layout: default
title: Commodities | SATCO
---

<style>
  /* Hero Section */
  .commodities-hero {
    text-align: center;
    margin-bottom: 50px;
  }
  .commodities-hero h2 {
    color: #0d1b2a;
    font-size: 2.2em;
    margin-bottom: 12px;
  }
  .commodities-hero p {
    color: #666;
    max-width: 750px;
    margin: 0 auto;
    line-height: 1.6;
    font-size: 16px;
  }

  /* Horizontal Layout Container */
  .rows-container {
    max-width: 1000px;
    margin: 0 auto 50px auto;
    padding: 0 20px;
  }

  /* Horizontal Row Style */
  .category-row {
    display: flex;
    background: #fff;
    border: 1px solid #e2e8f0;
    border-radius: 8px;
    margin-bottom: 20px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.02);
    overflow: hidden;
  }
  
  /* Responsive wrap for smaller screens */
  @media (max-width: 768px) {
    .category-row {
      flex-direction: column;
    }
    .row-sidebar {
      width: 100% !important;
      padding: 15px !important;
    }
  }

  /* Left Sidebar of the Row */
  .row-sidebar {
    width: 25%;
    background: #0d1b2a;
    color: #fff;
    padding: 25px 20px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    border-right: 3px solid #d4af37;
  }
  .row-sidebar .icon {
    font-size: 1.8em;
    margin-bottom: 8px;
  }
  .row-sidebar h3 {
    color: #fff;
    margin: 0;
    font-size: 1.05em;
    font-weight: bold;
    line-height: 1.3;
  }

  /* Right Content Area (Products Grid) */
  .row-products {
    width: 75%;
    padding: 25px;
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    align-content: center;
    background: #f8f9fa;
  }

  /* Product Tag Style */
  .product-tag {
    display: inline-block;
  }
  .product-tag a {
    display: block;
    background: #fff;
    color: #4a5568;
    border: 1px solid #cbd5e1;
    padding: 8px 16px;
    border-radius: 20px;
    text-decoration: none;
    font-size: 13.5px;
    transition: all 0.2s ease;
    font-weight: 500;
  }
  .product-tag a:hover {
    color: #0d1b2a;
    border-color: #d4af37;
    background: #fdfbf7;
    transform: translateY(-2px);
    box-shadow: 0 4px 6px rgba(13, 27, 42, 0.08);
  }

  /* CTA Section */
  .quote-box {
    background: linear-gradient(135deg, #0d1b2a 0%, #1b2a47 100%);
    color: white;
    padding: 35px;
    border-radius: 8px;
    text-align: center;
    max-width: 960px;
    margin: 40px auto;
    border: 1px solid #d4af37;
  }
</style>

<div class="commodities-hero">
  <h2>Our Commodities Portfolio</h2>
  <p>SATCO is a premium global supplier of industrial minerals, clinker, and construction materials. Click on any product below to view detailed chemical compositions, technical specifications, and packing options.</p>
</div>

<div class="rows-container">

  <!-- ROW 1: CEMENT -->
  <div class="category-row">
    <div class="row-sidebar">
      <span class="icon">🏗️</span>
      <h3>Cement Series</h3>
    </div>
    <div class="row-products">
      <div class="product-tag"><a href="#">OPC - Type 1</a></div>
      <div class="product-tag"><a href="#">OPC - Type 2</a></div>
      <div class="product-tag"><a href="#">OPC - Type 3</a></div>
      <div class="product-tag"><a href="#">OPC - Type 4</a></div>
      <div class="product-tag"><a href="#">OPC - Type 5</a></div>
      <div class="product-tag"><a href="#">White Portland Cement</a></div>
      <div class="product-tag"><a href="#">Oil Well Cement</a></div>
      <div class="product-tag"><a href="#">Portland Pozzolana (PPC)</a></div>
      <div class="product-tag"><a href="#">Special Pozzolanic Cement</a></div>
      <div class="product-tag"><a href="#">Composite & Blended Cement</a></div>
      <div class="product-tag"><a href="#">Portland Limestone Cement</a></div>
      <div class="product-tag"><a href="#">Masonry Cement</a></div>
      <div class="product-tag"><a href="#">High Blaine Cement</a></div>
      <div class="product-tag"><a href="#">Slag Cement</a></div>
      <div class="product-tag"><a href="#">Mixed Cement</a></div>
      <div class="product-tag"><a href="#">Advanced Composite Cement</a></div>
    </div>
  </div>

  <!-- ROW 2: CLINKER -->
  <div class="category-row">
    <div class="row-sidebar">
      <span class="icon">🔥</span>
      <h3>Portland Clinker</h3>
    </div>
    <div class="row-products">
      <div class="product-tag"><a href="#">OPC Clinker</a></div>
      <div class="product-tag"><a href="#">Low-Alkali Clinker</a></div>
      <div class="product-tag"><a href="#">SR Clinker</a></div>
      <div class="product-tag"><a href="#">HES Clinker</a></div>
      <div class="product-tag"><a href="#">LHC Clinker</a></div>
    </div>
  </div>

  <!-- ROW 3: GYPSUM -->
  <div class="category-row">
    <div class="row-sidebar">
      <span class="icon">🏔️</span>
      <h3>Gypsum Products</h3>
    </div>
    <div class="row-products">
      <div class="product-tag"><a href="#">Natural Gypsum Rock</a></div>
      <div class="product-tag"><a href="#">Gypsum Powder</a></div>
    </div>
  </div>

  <!-- ROW 4: INDUSTRIAL MINERALS -->
  <div class="category-row">
    <div class="row-sidebar">
      <span class="icon">💎</span>
      <h3>Industrial Minerals</h3>
    </div>
    <div class="row-products">
      <div class="product-tag"><a href="#">Limestone</a></div>
      <div class="product-tag"><a href="#">Calcium Carbonate</a></div>
      <div class="product-tag"><a href="#">Dolomite</a></div>
      <div class="product-tag"><a href="#">Bentonite</a></div>
      <div class="product-tag"><a href="#">Kaolin (China Clay)</a></div>
      <div class="product-tag"><a href="#">Barite</a></div>
      <div class="product-tag"><a href="#">Fluorspar</a></div>
      <div class="product-tag"><a href="#">Feldspar</a></div>
      <div class="product-tag"><a href="#">Potash</a></div>
    </div>
  </div>

  <!-- ROW 5: ECO-ADDITIVES & ENERGY -->
  <div class="category-row">
    <div class="row-sidebar">
      <span class="icon">⚡</span>
      <h3>Eco-Additives & Energy</h3>
    </div>
    <div class="row-products">
      <div class="product-tag"><a href="/products/slag.html">Blast Furnace Slag (GGBFS)</a></div>
      <div class="product-tag"><a href="#">Microsilica (Silica Fume)</a></div>
      <div class="product-tag"><a href="#">Zeolite</a></div>
      <div class="product-tag"><a href="#">Coal (Steam & Metallurgical)</a></div>
    </div>
  </div>

</div>

<!-- CTA Section -->
<div class="quote-box">
  <h3 style="color: #d4af37; margin-top: 0;">Looking for Custom Specifications?</h3>
  <p style="font-size: 15px;">We provide flexible shipping options in Bulk or Jumbo Bags tailored to international maritime standards.</p>
  <a href="/05_contact.html" style="display: inline-block; background: #d4af37; color: #0d1b2a; padding: 12px 25px; text-decoration: none; font-weight: bold; border-radius: 4px; margin-top: 15px; transition: background 0.3s;">Contact Our Trade Desk</a>
</div>
