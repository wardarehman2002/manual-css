
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family:'Poppins',sans-serif;
}

body{
  color:#222;
  background:#fff;
}

a{
  text-decoration:none;
  color:inherit;
}

img{
  width:100%;
  display:block;
}

.container{
  width:min(1150px,92%);
  margin:auto;
}

.section{
  padding:70px 0;
}

.light{
  background:#f6f7fb;
}

.center{
  text-align:center;
}

.section-title{
  text-align:center;
  font-size:30px;
  font-weight:500;
  color:#3b82c4;
  margin-bottom:35px;
}

.section-title.left{
  text-align:left;
}

.topbar{
  position:sticky;
  top:0;
  z-index:1000;
  background:rgba(255,255,255,.95);
  backdrop-filter:blur(8px);
  box-shadow:0 1px 8px rgba(0,0,0,.05);
}

.nav{
  display:flex;
  align-items:center;
  justify-content:space-between;
  padding:14px 0;
}

.logo{
  font-size:22px;
  font-weight:700;
  color:#35a8e0;
}

.logo span{
  color:#222;
}

.menu{
  list-style:none;
  display:flex;
  gap:28px;
  font-size:14px;
  color:#666;
}

.menu a:hover{
  color:#35a8e0;
}

.btn{
  display:inline-block;
  padding:12px 24px;
  border-radius:30px;
  background:#2f8be6;
  color:#fff;
  font-size:14px;
  font-weight:500;
}

.btn.small{
  padding:10px 18px;
  border-radius:20px;
}

.hero{
  height:520px;
  background:url("img/hero.jpg") center/cover no-repeat;
  position:relative;
}

.hero::after{
  content:"";
  position:absolute;
  inset:0;
  background:rgba(255,255,255,.35);
}

.hero-content{
  position:absolute;
  left:7%;
  top:50%;
  transform:translateY(-50%);
  z-index:1;
  max-width:360px;
}

.hero h1{
  font-size:58px;
  line-height:1;
  color:#111;
  margin-bottom:12px;
}

.hero p{
  color:#444;
  margin-bottom:20px;
}

.grid-3{
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:24px;
}

.grid-2{
  display:grid;
  grid-template-columns:repeat(2,1fr);
  gap:24px;
}

.cards .card{
  background:#fff;
  padding-bottom:15px;
}

.cards .card img{
  height:160px;
  object-fit:cover;
  margin-bottom:12px;
}

.card h3,.product h4,.news-card h4{
  font-size:18px;
  color:#3b82c4;
  margin-bottom:8px;
}

.card p,.news-card p,.product p{
  font-size:13px;
  color:#777;
}

.sale-banner{
  height:420px;
  background:url("img/sale.jpg") center/cover no-repeat;
  position:relative;
}

.sale-banner::after{
  content:"";
  position:absolute;
  inset:0;
  background:rgba(255,255,255,.45);
}

.sale-banner .overlay{
  position:absolute;
  inset:0;
  display:flex;
  flex-direction:column;
  justify-content:center;
  align-items:center;
  z-index:1;
  text-align:center;
}

.sale-banner h2{
  color:#2c7ed6;
  font-size:34px;
  margin-bottom:16px;
}

.features-wrap{
  display:flex;
  gap:40px;
  align-items:center;
}

.features-title{
  flex:1;
}

.features-title span{
  color:#999;
  font-size:12px;
  letter-spacing:2px;
}

.features-title h2{
  color:#3b82c4;
  font-size:34px;
  margin-top:6px;
}

.feature-grid{
  flex:2;
  display:grid;
  grid-template-columns:repeat(2,1fr);
  gap:28px;
}

.feature-item{
  background:#fff;
  padding:18px;
  border-radius:12px;
  box-shadow:0 8px 25px rgba(0,0,0,.04);
}

.feature-item i{
  color:#3b82c4;
  font-size:24px;
  margin-bottom:10px;
}

.feature-item h4{
  margin-bottom:6px;
  color:#333;
}

.products-grid .product{
  text-align:center;
}

.products-grid .product img{
  height:240px;
  object-fit:cover;
  margin-bottom:10px;
}

.subscribe{
  margin-top:20px;
  display:flex;
  justify-content:center;
  gap:10px;
  flex-wrap:wrap;
}

.subscribe input{
  width:min(440px,90%);
  padding:14px 18px;
  border:1px solid #ddd;
  border-radius:6px;
  outline:none;
}

.subscribe button{
  padding:14px 24px;
  border:none;
  border-radius:6px;
  background:#2f8be6;
  color:#fff;
  cursor:pointer;
}

.gallery-grid{
  display:grid;
  grid-template-columns:2fr 1fr;
  gap:18px;
}

.g-big{
  position:relative;
  height:320px;
}

.g-small{
  position:relative;
  height:150px;
  margin-bottom:20px;
}

.g-big img,.g-small img{
  width:100%;
  height:100%;
  object-fit:cover;
}

.g-big span,.g-small span{
  position:absolute;
  right:12px;
  bottom:12px;
  background:rgba(47,139,230,.9);
  color:#fff;
  padding:6px 12px;
  font-size:12px;
  border-radius:4px;
}

.news-grid .news-card{
  background:#fff;
  padding:12px;
  box-shadow:0 8px 20px rgba(0,0,0,.05);
}

.news-card img{
  height:160px;
  object-fit:cover;
  margin-bottom:12px;
}

.collection-grid{
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:14px;
}

.collection-grid img{
  height:170px;
  object-fit:cover;
}

.testimonial-box{
  max-width:700px;
  margin:auto;
  background:#fff;
  padding:30px;
  border-radius:16px;
  box-shadow:0 8px 25px rgba(0,0,0,.05);
}

.avatar{
  width:70px;
  height:70px;
  border-radius:50%;
  object-fit:cover;
  margin:0 auto 14px;
}

.location-grid{
  display:grid;
  grid-template-columns:repeat(2,1fr);
  gap:24px;
}

.loc-card{
  background:#fff;
  padding:15px;
  box-shadow:0 8px 20px rgba(0,0,0,.05);
}

.loc-card img{
  height:220px;
  object-fit:cover;
  margin-top:12px;
}

.footer{
  padding:40px 0 10px;
}

.footer-grid{
  display:grid;
  grid-template-columns:2fr 1fr 1fr;
  gap:30px;
  align-items:start;
}

.footer h4{
  color:#3b82c4;
  margin-bottom:12px;
}

.footer ul{
  list-style:none;
}

.footer li{
  margin-bottom:8px;
  color:#666;
  font-size:14px;
}

.copy{
  text-align:center;
  font-size:12px;
  color:#888;
  padding-top:20px;
}

@media (max-width: 992px){
  .grid-3,.grid-2,.feature-grid,.collection-grid,.location-grid,.footer-grid,.gallery-grid,.features-wrap{
    grid-template-columns:1fr;
    display:grid;
  }

  .menu{
    display:none;
  }

  .hero{
    height:420px;
  }

  .hero h1{
    font-size:42px;
  }
}

@media (max-width: 600px){
  .section{
    padding:50px 0;
  }

  .hero-content{
    left:5%;
    right:5%;
  }

  .sale-banner h2{
    font-size:24px;
  }

  .section-title{
    font-size:24px;
  }
}