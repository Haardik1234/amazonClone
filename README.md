# amazonClone
ecommerce website on amazon using html and css
HTML CODE:
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Amazon Website Clone</title>
  <link rel="stylesheet" href="style.css">
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200">
</head>
<body>
    <header>
      <nav class="navbar">
        <div class="nav-logo">
          <a href="#"><img src="amazon_logo.png" alt="logo"></a>
        </div>
        <div class="address">
          <a href="#" class="deliver">Deliver</a>
          <div class="map-icon">
            <span class="material-symbols-outlined">location_on</span>
            <a href="#" class="location">India</a>
          </div>
        </div>
        <div class="nav-search">
          <select class="select-search">
            <option>All</option>
            <option>All Categories</option>
            <option>Amazon Devices</option>
          </select>
          <input type="text" placeholder="Search Amazon" class="search-input">
          <div class="search-icon">
            <span class="material-symbols-outlined">search</span>
          </div>
        </div>
        <div class="sign-in">
         <a href="#"> <p>Hello, sign in</p>
          <span>Account &amp; Lists</span></a>
        </div>
        <div class="returns">
          <a href="#"><p>Returns</p>
            <span>&amp; Orders</span></a>
        </div>
        <div class="cart">
          <a href="#">
            <span class="material-symbols-outlined cart-icon">shopping_cart</span>
            </a>
            <p>Cart</p>
        </div>
      </nav>
      
      <div class="banner">
        <div class="banner-content">
          <div class="panel">
            <span class="material-symbols-outlined">menu</span>
            <a href="#">All</a>
          </div>
  
          <ul class="links">
            <li><a href="#">Today's Deals</a></li>
            <li><a href="#">Customer Service</a></li>
            <li><a href="#">Registry</a></li>
            <li><a href="#">Gift Cards</a></li>
            <li><a href="#">Sell</a></li>
          </ul>
          <div class="deals">
            <a href="#">Shop deals in Electronics</a>
          </div>
        </div>
      </div>
    </header>
    <section class="hero-section"></section>
    <section class="shop-section">
      <div class="shop-images">
        <div class="shop-link">
          <h3>Shop Laptops &amp; Tables</h3>
          <img src="https://encrypted-tbn2.gstatic.com/shopping?q=tbn:ANd9GcQuodez03yAL56WE7EQR2c9iZEM2iO-nez0TCEc
          snRmYs_b_Kbr9vxNcVJj66dCvIxtrgNy_YpWxnqdoLfoKXLkrGJWjE8DYNbU8LSKGF8RpYatrr
          k0uXwGgXl7_nNgt-KsQdiK8p-GW48&usqp=CAc" alt="card">
          <a href="#">Shop now</a>
        </div>
        <div class="shop-link">
          <h3>Shop Smartwatches</h3>
          <img src="https://encrypted-tbn1.gstatic.com/images?q=tbn:ANd9GcSYIgni8lKj9aQ79HuRsq2MSV64ahODr5kfo-_etb3q_Nt1xUS6" alt="card">
          <a href="#">Shop now</a>
        </div>
        <div class="shop-link">
          <h3>Create with Strip Lights</h3>
          <img src="data:image/webp;base64,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
          omGdWgAAAA==" alt="card">
          <a href="#">Shop now</a>
        </div>
        <div class="shop-link">
          <h3>Home Refresh Ideas</h3>
          <img src="data:image/jpeg;base64,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
          EEWdadP2e1JJYyaxVv9diIsGaSSQrSSSSVR//2Q==" alt="card">
          <a href="#">Shop now</a>
        </div>
      </div>
    </section>
    <footer>
      <a href="#" class="footer-title">
        Back to top
      </a>
      <div class="footer-items">
        <ul>
          <h3>Get to Know Us</h3>
          <li><a href="#">About us</a></li>
          <li><a href="#">Careers</a></li>
          <li><a href="#">Press Release</a></li>
          <li><a href="#">Amazon Science</a></li>
        </ul>
        <ul>
          <h3>Connect with Us</h3>
          <li><a href="#">Facebook</a></li>
          <li><a href="#">Twitter</a></li>
          <li><a href="#">Instagram</a></li>
        </ul>
        <ul>
          <h3>Make Money with Us</h3>
          <li><a href="#">Sell on Amazon</a></li>
          <li><a href="#">Sell under Amazon Accelerator</a></li>
          <li><a href="#">Protect and Build Your Brand</a></li>
          <li><a href="#">Amazon Global Selling</a></li>
          <li><a href="#">Become an Affiliate</a></li>
          <li><a href="#">Fulfillment by Amazon</a></li>
          <li><a href="#">Advertise Your Products</a></li>
          <li><a href="#">Amazon Pay on Merchants</a></li>
        </ul>
        <ul>
          <h3>Let Us Help You</h3>
          <li><a href="#">COVID-19 and Amazon</a></li>
          <li><a href="#">Your Account</a></li>
          <li><a href="#">Return Centre</a></li>
          <li><a href="#">100% Purchase Protection</a></li>
          <li><a href="#">Amazon App Download</a></li>
          <li><a href="#">Help</a></li>
        </ul>
      </div>
    </footer>
</body>
</html>
CSS code:
@import url("https://fonts.googleapis.com/css2?family=Open+Sans:wght@200;300;400;500;600;700&display=swap");
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Open Sans", sans-serif;
}
html {
  scroll-behavior: smooth;
}
a {
  text-decoration: none;
  color: #fff;
}
a:hover {
  color: #ddd;
}
/* Header or Navbar */
header {
  width: 100%;
  background-color: #0f1111;
}
.navbar {
  height: 60px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  cursor: pointer;
  color: #fff;
  max-width: 1280px;
  margin: 0 auto;
}
.nav-logo img {
  margin-top: 10px;
  width: 128px;
}
.address .deliver {
  margin-left: 20px;
  font-size: 0.75rem;
  color: #ccc;
}
.address .map-icon {
  display: flex;
  align-items: center;
}
.nav-search {
  display: flex;
  justify-content: space-evenly;
  max-width: 620px;
  width: 100%;
  height: 40px;
  border-radius: 4px;
}
.select-search {
  background: #f3f3f3;
  width: 50px;
  text-align: center;
  border-top-left-radius: 4px;
  border-bottom-left-radius: 4px;
  border: none;
}
.search-input {
  max-width: 600px;
  width: 100%;
  font-size: 1rem;
  border: none;
  outline: none;
  padding-left: 10px;
}
.search-icon {
  max-width: 45px;
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 1.2rem;
  background: #febd68;
  color: #000;
  cursor: pointer;
  border-top-right-radius: 4px;
  border-bottom-right-radius: 4px;
}
.sign-in p,
.returns p {
  font-size: 0.75rem;
}
.sign-in,
.returns span {
  font-size: 0.875rem;
  font-weight: 600;
}
.cart {
  display: flex;
}
.cart .cart-icon {
  font-size: 2.5rem
}
.cart p {
  margin-top: 20px;
  font-weight: 500;
}
.banner {
  padding: 10px 20px;
  background: #222f3d;
  color: #fff;
  font-size: 0.875rem;
}
.banner-content {
  margin: 0 auto;
  max-width: 1280px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.panel {
  max-width: 1280px;
  display: flex;
  align-items: center;
  gap: 5px;
  cursor: pointer;
}
.panel span {
  margin-right: 7px;
}
.links {
  display: flex;
  align-items: center;
  list-style: none;
  gap: 15px;
  flex-grow: 1;
  margin-left: 15px;
}
.links a {
  padding: 10px 0;
}
.deals a {
  font-size: 0.9rem;
  font-weight: 500;
  white-space: nowrap;
}
/* Hero Section */
.hero-section {
  height: 400px;
  background-image: url("hero_image.jpg");
  background-position: center;
  background-size: cover;
}
/* Shop Section */
.shop-section {
  display: flex;
  align-items: center;
  flex-direction: column;
  background-color: #f3f3f3;
  padding: 50px 0;
}
.shop-images {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 40px;
  max-width: 1280px;
  width: 100%;
}
.shop-link {
  background-color: #fff;
  padding: 30px;
  display: flex;
  cursor: pointer;
  flex-direction: column;
  white-space: nowrap;
}
.shop-link img {
  width: 100%;
  height: 280px;
  object-fit: cover;
  margin-bottom: 10px;
}
.shop-link h3 {
  margin-bottom: 10px;
}
.shop-link a {
  display: inline-block;
  margin-top: 10px;
  font-size: 0.9rem;
  color: blue;
  font-weight: 500;
  transition: color 0.3s ease;
}
.shop-link:hover a {
  color: #c7511f;
  text-decoration: underline;
}
/* Footer */
.footer-title {
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #37475a;
  color: #fff;
  font-size: 0.875rem;
  font-weight: 600;
  height: 60px;
}
.footer-items {
  display: flex;
  justify-content: space-evenly;
  width: 100%;
  margin: 0 auto;
  background: #232f3e;
}
.footer-items h3 {
  font-size: 1rem;
  font-weight: 500;
  color: #fff;
  margin: 20px 0 10px 0;
}
.footer-items ul {
  list-style: none;
  margin-bottom: 20px;
}
.footer-items li a {
  color: #ddd;
  font-size: 0.875rem;
}
.footer-items li a:hover {
  text-decoration: underline;
}
.nav-logo:hover{
scale:1.2;
}
.address:hover{
    scale:1.2;
}
.sign-in:hover{
    scale:1.2;
}
.returns:hover{
    scale:1.2;
}
.cart:hover{
    scale:1.2;
}
