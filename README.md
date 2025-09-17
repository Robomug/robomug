<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Kukido — Handcrafted Cookies (Demo)</title>
  <meta name="description" content="Demo site inspired by kukido.ph — handcrafted cookies, boxes, and cakes." />
  <style>
    *{box-sizing:border-box;margin:0;padding:0}
    body{font-family:Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;line-height:1.4;color:#222;background:#fff}
    a{color:inherit;text-decoration:none}
    img{max-width:100%;display:block}

    .container{max-width:1200px;margin:0 auto;padding:0 20px}
    header{border-bottom:1px solid #eee;background:linear-gradient(180deg,#fff, #fff);}
    .topbar{display:flex;align-items:center;justify-content:space-between;padding:18px 0}
    .logo{display:flex;align-items:center;gap:12px}
    .logo img{width:48px;height:48px;border-radius:8px;object-fit:cover}
    nav ul{display:flex;gap:18px;list-style:none;align-items:center}
    nav li a{padding:8px 10px;border-radius:8px;font-weight:600}
    nav li a:hover{background:#f7f7f7}

    .hero{display:grid;grid-template-columns:1fr 420px;gap:28px;align-items:center;padding:40px 0}
    .hero h1{font-size:40px;margin-bottom:12px}
    .hero p{color:#555;margin-bottom:18px}
    .cta{display:inline-block;background:#ff6b35;color:#fff;padding:12px 18px;border-radius:10px;font-weight:700}

    .badges{display:flex;gap:12px;flex-wrap:wrap;margin:18px 0}
    .badge{padding:6px 10px;border-radius:8px;background:#fafafa;border:1px solid #eee;font-weight:600}

    .products{padding:28px 0}
    .grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(220px,1fr));gap:18px}
    .card{border:1px solid #eee;border-radius:12px;overflow:hidden;background:#fff}
    .card .media{height:180px;background:#f5f5f5;display:flex;align-items:center;justify-content:center}
    .card .content{padding:12px}
    .price{font-weight:800;margin-top:8px}
    .sale{color:#ff4d4d;text-decoration:line-through;font-weight:600;margin-left:8px;font-size:0.9rem}
    .btn{display:inline-block;padding:8px 12px;border-radius:8px;border:none;background:#1f2937;color:#fff;font-weight:700;cursor:pointer;text-align:center}

    .features{display:flex;gap:14px;flex-wrap:wrap;margin:24px 0}
    .feature{flex:1;min-width:160px;padding:16px;border-radius:10px;background:#fff;border:1px solid #f0f0f0;text-align:center}

    footer{border-top:1px solid #eee;padding:28px 0;margin-top:28px}
    .footer-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(160px,1fr));gap:18px}

    @media (max-width:880px){.hero{grid-template-columns:1fr;}.topbar{flex-wrap:wrap;gap:12px}.logo img{width:42px;height:42px}}
  </style>
</head>
<body>
  <header>
    <div class="container">
      <div class="topbar">
        <div class="logo">
          <img src="https://via.placeholder.com/120x120.png?text=K" alt="Kukido logo">
          <div>
            <strong>Kukido</strong>
            <div style="font-size:13px;color:#666">Handcrafted Cookies</div>
          </div>
        </div>
        <nav>
          <ul>
            <li><a href="#shop">Shop Kukies</a></li>
            <li><a href="#custom">Make Your Own</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
          </ul>
        </nav>
      </div>
    </div>
  </header>

  <main class="container">
    <section class="hero">
      <div>
        <h1>Freshly baked handcrafted cookies in Manila</h1>
        <p>Delivering freshly baked cookies every Mon, Wed, Thurs, Fri and Sat! Get free delivery for orders above ₱1,800.</p>
        <a class="cta" href="#shop">Order now</a>

        <div class="badges">
          <div class="badge">Baked fresh daily</div>
          <div class="badge">Delivery friendly</div>
          <div class="badge">Featured in local press</div>
        </div>

        <h3 style="margin-top:18px">Shop our Bestsellers</h3>
        <div class="products">
          <div class="grid">
            <!-- Product cards with PayPal links -->

            <div class="card">
              <div class="media"><img src="https://via.placeholder.com/400x300.png?text=Box+of+3" alt="Mix & Match Kuki Box of 3"></div>
              <div class="content">
                <div style="font-weight:700">Mix & Match Kuki Box of 3</div>
                <div class="price">₱391.50 <span class="sale">₱435.00</span></div>
                <div style="margin-top:10px">
                  <a href="https://www.paypal.com/ncp/payment/LINK1" target="_blank" class="btn">Buy Now</a>
                </div>
              </div>
            </div>

            <div class="card">
              <div class="media"><img src="https://via.placeholder.com/400x300.png?text=Munchies" alt="Munchies Sampler Box"></div>
              <div class="content">
                <div style="font-weight:700">Munchies Sampler Box</div>
                <div class="price">₱410.00</div>
                <div style="margin-top:10px">
                  <a href="https://www.paypal.com/ncp/payment/LINK2" target="_blank" class="btn">Buy Now</a>
                </div>
              </div>
            </div>

            <div class="card">
              <div class="media"><img src="https://via.placeholder.com/400x300.png?text=Kuki+Cake" alt="Kuki Cake"></div>
              <div class="content">
                <div style="font-weight:700">Kuki Cake</div>
                <div class="price">₱950.00</div>
                <div style="margin-top:10px">
                  <a href="https://www.paypal.com/ncp/payment/LINK3" target="_blank" class="btn">Buy Now</a>
                </div>
              </div>
            </div>

            <div class="card">
              <div class="media"><img src="https://via.placeholder.com/400x300.png?text=Kuki+Pie" alt="Kuki Pie"></div>
              <div class="content">
                <div style="font-weight:700">Kuki Pie</div>
                <div class="price">₱420.00</div>
                <div style="margin-top:10px">
                  <a href="https://www.paypal.com/ncp/payment/LINK4" target="_blank" class="btn">Buy Now</a>
                </div>
              </div>
            </div>

            <div class="card">
              <div class="media"><img src="https://via.placeholder.com/400x300.png?text=Brookie" alt="Brookie"></div>
              <div class="content">
                <div style="font-weight:700">Brookie</div>
                <div class="price">₱220.00</div>
                <div style="margin-top:10px">
                  <a href="https://www.paypal.com/ncp/payment/LINK5" target="_blank" class="btn">Buy Now</a>
                </div>
              </div>
            </div>

            <div class="card">
              <div class="media"><img src="https://via.placeholder.com/400x300.png?text=Biscoff" alt="Biscoff Bomb"></div>
              <div class="content">
                <div style="font-weight:700">Biscoff Bomb</div>
                <div class="price">₱230.00</div>
                <div style="margin-top:10px">
                  <a href="https://www.paypal.com/ncp/payment/LINK6" target="_blank" class="btn">Buy Now</a>
                </div>
              </div>
            </div>

          </div>
        </div>
      </div>

      <div style="text-align:center">
        <img src="https://via.placeholder.com/420x420.png?text=Hero+Cookie" alt="Hero cookie" style="border-radius:12px">
        <p style="color:#777;margin-top:8px">Mix n' Match Kukies — customize your cookie box.</p>
      </div>
    </section>

    <section class="features">
      <div class="feature">
        <h4>Customize</h4>
        <p>Pick dough, mix-ins and size — build your dream cookie.</p>
      </div>
      <div class="feature">
        <h4>Celebration Cakes</h4>
        <p>Cookie cakes and pies for birthdays and events.</p>
      </div>
      <div class="feature">
        <h4>Bulk Orders</h4>
        <p>Corporate gifting and large events — contact us for quotes.</p>
      </div>
    </section>

    <section id="about">
      <h2 style="margin-bottom:12px">Baking your Kuki dreams into reality</h2>
      <p style="color:#555;max-width:900px">That’s what Kukido is all about — being brave, bold, and having the courage to go for it. We bake cookies that make people smile. This demo replicates the layout and look & feel of the referenced site; replace images and copy with your brand assets and real prices to convert this into a production storefront.</p>
    </section>

  </main>

  <footer>
    <div class="container">
      <div class="footer-grid">
        <div>
          <strong>Kukido</strong>
          <p style="color:#666;margin-top:8px">Handcrafted Cookies — demo site</p>
        </div>
        <div>
          <h4>Shop</h4>
          <ul style="list-style:none;margin-top:8px;color:#444">
            <li><a href="#">Kuki Singles</a></li>
            <li><a href="#">Kuki Boxes</a></li>
            <li><a href="#">Kuki Cakes & Pies</a></li>
          </ul>
        </div>
        <div>
          <h4>About</h4>
          <ul style="list-style:none;margin-top:8px;color:#444">
            <li><a href="#">FAQ</a></li>
            <li><a href="#">Our Kuki Line-up</a></li>
            <li><a href="#contact">Contact</a></li>
          </ul>
        </div>
        <div>
          <h4>Follow</h4>
          <p style="margin-top:8px"><a href="#">Instagram</a> · <a href="#">Facebook</a> · <a href="#">Tiktok</a></p>
        </div>
      </div>

      <div style="margin-top:18px;color:#888;font-size:13px">© 2025 Kukido Handcrafted Cookies — Demo. Replace this with your legal links and powered-by info.</div>
    </div>
  </footer>
</body>
</html>
