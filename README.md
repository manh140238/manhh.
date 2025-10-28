# manhh.
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thông Tin Cá Nhân - Nguyễn Thị Mai Anh</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4; /* Nền xám nhạt */
            color: #333; /* Màu chữ đen xám */
            margin: 0;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .profile-card {
            width: 100%;
            max-width: 600px;
            background-color: #ffffff;
            border-radius: 8px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1); /* Bóng nhẹ */
            padding: 30px;
        }

        header {
            text-align: center;
            border-bottom: 2px solid #ccc;
            padding-bottom: 15px;
            margin-bottom: 20px;
        }

        header h1 {
            color: #007bff; /* Màu xanh dương đơn giản */
            margin-top: 0;
            font-size: 2em;
        }

        /* Phần Nội Dung */
        .section {
            margin-bottom: 20px;
        }

        .section h2 {
            color: #555;
            border-left: 5px solid #007bff;
            padding-left: 10px;
            margin-bottom: 15px;
            font-size: 1.2em;
        }

        .info-list {
            list-style: none;
            padding: 0;
            line-height: 1.8;
        }

        .info-list li strong {
            display: inline-block;
            width: 100px; /* Cố định độ rộng cho tiêu đề */
            font-weight: bold;
            color: #333;
        }
        
        /* Thông tin liên hệ và Đường dẫn */
        .contact-link a {
            display: inline-block;
            background-color: #007bff;
            color: white;
            text-decoration: none;
            padding: 8px 15px;
            border-radius: 4px;
            font-weight: bold;
            margin-right: 10px;
            transition: background-color 0.3s;
        }

        .contact-link a:hover {
            background-color: #0056b3;
        }
        
    </style>
</head>
<body>

    <div class="profile-card">
        <header>
            <h1>Nguyễn Thị Mai Anh</h1>
            <p>Thông tin cá nhân cơ bản</p>
        </header>

        <div class="section">
            <h2>Thông Tin Cơ Bản</h2>
            <ul class="info-list">
                <li><strong>Ngày sinh:</strong> 14/03/2008</li>
                <li><strong>Giới tính:</strong> Nữ</li>
                <li><strong>Địa chỉ:</strong> Phú Xuyên, Hà Nội</li>
                <li><strong>Học Sinh:</strong> 12A2-K59-Phú Xuyên A</li>
                <li><strong>Sở Thích:</strong> Xem Phim, Nghe nhạc, Ăn uống</li>
            </ul>
        </div>
        
        <div class="section">
            <h2>Liên Hệ & Kết Nối</h2>
            <ul class="info-list">
                <li><strong>SĐT:</strong> 0369458308</li>
            </ul>
        </div>

        <div class="section contact-link">
            <h2>Đường Dẫn Khác</h2>
            <a href="https://www.facebook.com/share/16awY73Mus/" target="_blank" rel="noopener noreferrer">
                Truy Cập FaceBook
            </a>
            </div>
        
    </div>

</body>
</html>
