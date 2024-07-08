# firtwed
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Quán Cà Phê của Trí</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Đầu trang (Header) -->
    <header>
        <div class="logo">Quán Cà Phê của Trí</div>
        <nav>
            <ul>
                <li><a href="#menu">Thực đơn</a></li>
                <li><a href="#order">Đặt hàng</a></li>
                <li><a href="#contact">Liên hệ</a></li>
                <li><a href="#faq">FAQ</a></li>
                <li><input type="text" placeholder="Tìm kiếm..."></li>
            </ul>
        </nav>
    </header>

    <!-- Banner chính -->
    <section class="banner">
        <div class="banner-content">
            <h1>Chào mừng đến với Quán Cà Phê của Trí</h1>
            <p>Trải nghiệm cà phê tuyệt vời và không gian ấm cúng</p>
            <div class="banner-buttons">
                <a href="#menu" class="btn">Xem thực đơn</a>
                <a href="#order" class="btn">Đặt hàng ngay</a>
            </div>
        </div>
    </section>

    <!-- Giới thiệu ngắn gọn về quán cà phê -->
    <section class="about">
        <h2>Về chúng tôi</h2>
        <p>Chúng tôi là quán cà phê với sứ mệnh mang lại trải nghiệm cà phê tuyệt vời nhất cho khách hàng. Với không gian ấm cúng và đội ngũ nhân viên tận tình, chúng tôi luôn sẵn sàng phục vụ bạn.</p>
        <img src="about-image.jpg" alt="Hình ảnh quán cà phê">
    </section>

    <!-- Sản phẩm nổi bật -->
    <section class="featured-products">
        <h2>Sản phẩm nổi bật</h2>
        <div class="products">
            <div class="product">
                <img src="product1.jpg" alt="Sản phẩm 1">
                <h3>Sản phẩm 1</h3>
                <p>Giá: 50,000 VND</p>
            </div>
            <div class="product">
                <img src="product2.jpg" alt="Sản phẩm 2">
                <h3>Sản phẩm 2</h3>
                <p>Giá: 60,000 VND</p>
            </div>
            <div class="product">
                <img src="product3.jpg" alt="Sản phẩm 3">
                <h3>Sản phẩm 3</h3>
                <p>Giá: 70,000 VND</p>
            </div>
        </div>
        <a href="#menu" class="btn">Xem thêm</a>
    </section>

    <!-- Đánh giá của khách hàng -->
    <section class="testimonials">
        <h2>Đánh giá của khách hàng</h2>
        <div class="testimonial">
            <p>"Quán cà phê tuyệt vời, không gian ấm cúng và cà phê rất ngon!" - Khách hàng 1</p>
        </div>
        <div class="testimonial">
            <p>"Nhân viên thân thiện và dịch vụ tuyệt vời. Tôi sẽ quay lại!" - Khách hàng 2</p>
        </div>
    </section>

    <!-- Thông tin liên hệ -->
    <section class="contact" id="contact">
        <h2>Liên hệ</h2>
        <p>Địa chỉ: 123 Đường ABC, Quận 1, TP. Hồ Chí Minh</p>
        <p>Số điện thoại: 0123-456-789</p>
        <p>Email: contact@quancaphecuatri.com</p>
        <div class="social-links">
            <a href="#">Facebook</a>
            <a href="#">Instagram</a>
            <a href="#">Twitter</a>
        </div>
    </section>

    <!-- Cuối trang (Footer) -->
    <footer>
        <p>Bản quyền &copy; 2024 Quán Cà Phê của Trí. Tất cả các quyền được bảo lưu.</p>
        <nav>
            <a href="#privacy">Chính sách bảo mật</a>
            <a href="#terms">Điều khoản sử dụng</a>
        </nav>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    background-color: #333;
    color: white;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 20px;
}

header .logo {
    font-size: 1.5em;
    font-weight: bold;
}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    display: flex;
    gap: 15px;
}

nav ul li {
    display: inline;
}

nav ul li a, nav ul li input {
    color: white;
    text-decoration: none;
    padding: 5px 10px;
}

nav ul li input {
    border: none;
    background-color: #555;
    color: white;
    padding: 5px;
    border-radius: 3px;
}

.banner {
    background: url('banner-image.jpg') no-repeat center center/cover;
    height: 400px;
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    text-align: center;
}

.banner-content {
    background-color: rgba(0, 0, 0, 0.5);
    padding: 20px;
}

.banner .btn {
    background-color: #ff6f61;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    margin: 10px;
    border-radius: 5px;
}

.about, .featured-products, .testimonials, .contact {
    padding: 20px;
    text-align: center;
}

.about img, .products .product img {
    width: 100%;
    height: auto;
}

.featured-products .products {
    display: flex;
    justify-content: space-around;
}

.product {
    width: 30%;
    padding: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.testimonials .testimonial {
    margin: 20px 0;
    font-style: italic;
}

.contact .social-links a {
    margin: 0 10px;
    text-decoration: none;
    color: #333;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
}

footer nav a {
    color: white;
    text-decoration: none;
    margin: 0 10px;
}
