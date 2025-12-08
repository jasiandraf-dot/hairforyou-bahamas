:root{
  --pink:#ffd6ea;
  --pink-strong:#ff8acb;
  --black:#111;
  --gold:#d4af37;
  --white:#fff;
  --shadow: 0 6px 20px rgba(0,0,0,0.08);
}

*{box-sizing:border-box}
body{
  margin:0;
  font-family: "Helvetica Neue", Arial, sans-serif;
  background:var(--pink);
  color:var(--black);
  -webkit-font-smoothing:antialiased;
}

.site-header{
  display:flex;
  justify-content:space-between;
  align-items:center;
  padding:18px 24px;
  background:rgba(255,255,255,0.85);
  border-bottom:4px solid var(--pink-strong);
}

.brand h1{
  margin:0;
  font-size:20px;
  color:var(--black);
}
.brand .tag{margin:3px 0 0; font-size:12px; color:#444;}

nav ul{
  list-style:none;
  display:flex;
  gap:16px;
  margin:0;
  padding:0;
  align-items:center;
}

nav ul li a{
  text-decoration:none;
  color:var(--black);
  font-weight:600;
}
nav ul li a.active{color:var(--pink-strong); border-bottom:3px solid var(--pink-strong); padding-bottom:6px;}

.hero{
  padding:48px 16px;
  text-align:center;
  background: linear-gradient(180deg, rgba(255,255,255,0.4), rgba(255,255,255,0.2));
}
.hero-inner{max-width:900px;margin:auto}
.hero h2{font-size:34px; margin-bottom:8px}
.hero p{margin-bottom:16px; color:#333}

.box{width:95%; max-width:1100px; margin:24px auto; background:rgba(255,255,255,0.95); padding:22px; border-radius:10px; box-shadow:var(--shadow)}

.products{display:grid; grid-template-columns:repeat(auto-fit,minmax(180px,1fr)); gap:18px}

.product-card{
  background:var(--white);
  padding:12px;
  border-radius:12px;
  text-align:center;
  box-shadow:var(--shadow);
  transition:transform .18s ease;
}
.product-card img{width:100%; height:160px; object-fit:cover; border-radius:8px; margin-bottom:10px;}
.product-card h3{margin:6px 0 6px; font-size:16px}
.price{color:var(--pink-strong); font-weight:700; margin-bottom:8px}

/* Buttons */
.btn{
  display:inline-block;
  background:var(--pink-strong);
  color:var(--white);
  padding:10px 14px;
  border-radius:10px;
  text-decoration:none;
  border: none;
  cursor:pointer;
}
.btn.ghost{background:transparent; color:var(--black); border:2px solid var(--black);}

.btn.primary{background:linear-gradient(90deg,var(--pink-strong),var(--gold)); box-shadow:0 6px 18px rgba(0,0,0,0.08);}

.product-card:hover{transform:translateY(-6px)}

/* Footer */
.site-footer{padding:20px; text-align:center; font-size:14px; color:#333}

/* Form */
input[type="text"], input[type="email"], textarea{
  width:100%; padding:10px; margin:6px 0 14px; border-radius:8px; border:1px solid #ddd;
}

/* Responsive */
@media (max-width:700px){
  .site-header{flex-direction:column; gap:10px; text-align:center}
  nav ul{flex-wrap:wrap; justify-content:center;}
  .hero h2{font-size:26px}
}
