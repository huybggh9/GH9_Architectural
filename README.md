# GH9_Architectural
Kiến tạo dấu ấn - Kiến tạo không gian
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HuyBGGH9 | Portfolio Kiến Trúc</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>HUYBGGH9</h1>
        <h2>KIẾN TRÚC SƯ</h2>
        
        <p class="description">
            Kiến tạo dấu ấn - Kiến tạo không gian.<br>
            Tập trung vào Thiết kế Bền vững và Ứng dụng công nghệ trong Quy trình Thiết kế (BIM & Generative Design).
        </p>

        <a href="#" class="button-link">XEM CÁC DỰ ÁN NỔI BẬT</a>

        <div class="contact-info">
            <p>Liên hệ: contact@emailcuadaica.com</p>
            <p>Hồ sơ LinkedIn: <a href="#">/in/link-linkedin</a></p>
        </div>
    </div>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f9;
    color: #333;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    text-align: center;
}

.container {
    background: #fff;
    padding: 40px 60px;
    border-radius: 10px;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
    max-width: 700px;
    width: 90%;
}

h1 {
    font-size: 3em;
    color: #007bff; /* Màu xanh nổi bật */
    margin-bottom: 5px;
}

h2 {
    font-size: 1.5em;
    color: #555;
    margin-top: 0;
    border-bottom: 2px solid #ccc;
    padding-bottom: 10px;
    display: inline-block;
}

.description {
    font-size: 1.1em;
    line-height: 1.6;
    margin: 30px 0;
}

.button-link {
    display: inline-block;
    background-color: #007bff;
    color: white;
    padding: 12px 30px;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
    letter-spacing: 1px;
    transition: background-color 0.3s ease;
}

.button-link:hover {
    background-color: #0056b3;
}

.contact-info {
    margin-top: 40px;
    font-size: 0.9em;
    color: #777;
}

.contact-info a {
    color: #007bff;
    text-decoration: none;
}
