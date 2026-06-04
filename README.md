/* Reset */
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:Arial, Helvetica, sans-serif;
    background-color:#ffffff;
    color:#333;
}

/* Navigation */
header{
    width:100%;
    background:#fff;
    padding:20px 50px;
}

nav{
    display:flex;
    justify-content:space-between;
    align-items:center;
}

nav ul{
    list-style:none;
}

nav ul li{
    display:inline-block;
    margin-left:20px;
}

nav ul li a{
    text-decoration:none;
    color:#333;
}

.btn{
    background:#3b82f6;
    color:white;
    padding:10px 20px;
    border-radius:20px;
    text-decoration:none;
}

/* Hero Section */
.hero{
    height:600px;
    background:url("images/banner.jpg");
    background-size:cover;
    background-position:center;
    display:flex;
    align-items:center;
}

.hero-content{
    margin-left:80px;
}

.hero-content h1{
    font-size:50px;
    margin-bottom:15px;
}

.hero-content p{
    color:#3b82f6;
}

/* About Section */
.about{
    padding:80px 50px;
    text-align:center;
}

.about h2{
    color:#3b82f6;
    margin-bottom:40px;
}

.about-boxes{
    display:flex;
    justify-content:center;
    gap:30px;
}

.box{
    width:300px;
}

.box img{
    width:100%;
}

.box h3{
    margin-top:15px;
    margin-bottom:10px;
}

/* Sale Section */
.sale{
    height:500px;
    background:url("images/sale.jpg");
    background-size:cover;
    background-position:center;
    text-align:center;
    display:flex;
    justify-content:center;
    align-items:center;
}

.sale h2{
    color:#1e6fff;
    font-size:40px;
}

.sale button{
    margin-top:20px;
    padding:12px 25px;
    border:none;
    background:#3b82f6;
    color:white;
    border-radius:20px;
}

/* Features */
.features{
    padding:80px 50px;
}

.features h2{
    color:#3b82f6;
    margin-bottom:40px;
}

.feature-container{
    display:grid;
    grid-template-columns:repeat(2,1fr);
    gap:30px;
}

.feature-box{
    padding:20px;
}

/* Products */
.products{
    padding:80px 50px;
    text-align:center;
}

.products h2{
    color:#3b82f6;
    margin-bottom:40px;
}

.product-grid{
    display:grid;
    grid-template-columns:repeat(2,1fr);
    gap:30px;
}

.product{
    text-align:center;
}

.product img{
    width:100%;
}

.product h4{
    margin-top:10px;
}

/* Newsletter */
.newsletter{
    background:#f5f5f5;
    padding:80px 20px;
    text-align:center;
}

.newsletter h2{
    color:#3b82f6;
}

.newsletter input{
    width:350px;
    padding:10px;
    margin-top:20px;
}

.newsletter button{
    padding:10px 20px;
    background:#3b82f6;
    color:white;
    border:none;
}

/* Gallery */
.gallery{
    padding:80px 50px;
}

.gallery-grid{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:20px;
}

.gallery img{
    width:100%;
}

/* News */
.news{
    padding:80px 50px;
    text-align:center;
}

.news h2{
    color:#3b82f6;
    margin-bottom:30px;
}

.news-container{
    display:flex;
    gap:20px;
    justify-content:center;
}

.news-card{
    width:300px;
}

.news-card img{
    width:100%;
}

/* Collection */
.collection{
    padding:80px 50px;
}

.collection h2{
    text-align:center;
    color:#3b82f6;
    margin-bottom:30px;
}

.collection-grid{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:15px;
}

.collection-grid img{
    width:100%;
}

/* Testimonials */
.testimonial{
    padding:80px 50px;
    text-align:center;
    background:#f8f8f8;
}

.testimonial h2{
    color:#3b82f6;
    margin-bottom:30px;
}

.testimonial img{
    width:80px;
    height:80px;
    border-radius:50%;
}

/* Location */
.location{
    padding:80px 50px;
}

.location h2{
    text-align:center;
    color:#3b82f6;
    margin-bottom:30px;
}

.location-box{
    display:flex;
    gap:20px;
}

.location-box img{
    width:50%;
}

/* Footer */
footer{
    background:#f2f2f2;
    padding:50px;
}

.footer-container{
    display:flex;
    justify-content:space-between;
}

.footer-column h3{
    margin-bottom:15px;
}

.footer-column ul{
    list-style:none;
}

.footer-column ul li{
    margin-bottom:8px;
}

.footer-column ul li a{
    text-decoration:none;
    color:#333;
}

.copyright{
    text-align:center;
    margin-top:20px;
    font-size:14px;
}