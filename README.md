maianhh     
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Giới Thiệu Bản Thân - Nguyễn Thị Mai Anh</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

        :root {
            --primary-color: #4A90E2; /* Màu xanh dương hiện đại */
            --secondary-color: #F8E71C; /* Màu vàng nhấn */
            --background-color: #F4F7F6; /* Nền xám nhạt */
            --card-background: #FFFFFF; /* Nền thẻ trắng */
            --text-color: #333333; /* Màu chữ đen xám */
        }

        body {
            font-family: 'Roboto', sans-serif;
            background-color: var(--background-color);
            color: var(--text-color);
            margin: 0;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .container {
            width: 90%;
            max-width: 800px;
            background-color: var(--card-background);
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            padding: 30px;
            box-sizing: border-box;
        }

        header {
            text-align: center;
            padding-bottom: 20px;
            border-bottom: 3px solid var(--primary-color);
            margin-bottom: 30px;
        }

        header h1 {
            color: var(--primary-color);
            font-size: 2.5em;
            margin-bottom: 5px;
        }

        header p {
            color: #666;
            font-size: 1.1em;
            font-weight: 400;
        }

        /* Phần Nội Dung */
        .content-section {
            display: grid;
            grid-template-columns: 1fr;
            gap: 20px;
        }

        .info-card, .contact-card {
            background: var(--background-color);
            padding: 20px;
            border-radius: 10px;
            border-left: 5px solid var(--secondary-color);
        }

        .info-card h2, .contact-card h2 {
            color: var(--primary-color);
            margin-top: 0;
            border-bottom: 2px dashed #ccc;
            padding-bottom: 10px;
            margin-bottom: 15px;
        }

        .info-card ul, .contact-card ul {
            list-style: none;
            padding: 0;
        }

        .info-card li, .contact-card li {
            margin-bottom: 10px;
            line-height: 1.6;
        }

        .info-card li strong, .contact-card li strong {
            display: inline-block;
            width: 120px; /* Cố định độ rộng cho tiêu đề */
            color: var(--primary-color);
        }
        
        /* Thông tin liên hệ và Đường dẫn */
        .social-links {
            text-align: center;
            margin-top: 30px;
            padding-top: 20px;
            border-top: 1px solid #eee;
        }

        .social-links a {
            display: inline-block;
            background-color: var(--primary-color);
            color: white;
            text-decoration: none;
            padding: 10px 20px;
            border-radius: 25px;
            font-weight: 700;
            transition: background-color 0.3s, transform 0.3s;
            margin: 0 10px;
        }

        .social-links a:hover {
            background-color: #357ABD;
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }
        
        /* Icon (sử dụng emoji đơn giản) */
        .icon {
            margin-right: 10px;
        }

        /* Responsive */
        @media (min-width: 600px) {
            .content-section {
                grid-template-columns: 2fr 1fr; /* Chia cột cho màn hình lớn hơn */
            }
            .info-card {
                 grid-column: span 2; /* Phần thông tin cá nhân chiếm toàn bộ chiều rộng */
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <header>
            <h1>🎉 Nguyễn Thị Mai Anh 🎉</h1>
            <p>Học sinh lớp 12A2 - Đam mê khám phá và học hỏi</p>
        </header>

        <div class="content-section">
            
            <div class="info-card">
                <h2>📝 Thông Tin Chung & Học Vấn</h2>
                <ul>
                    <li><span class="icon">🎂</span><strong>Ngày sinh:</strong> 14/03/2008</li>
                    <li><span class="icon">♀️</span><strong>Giới tính:</strong> Nữ</li>
                    <li><span class="icon">📍</span><strong>Địa chỉ:</strong> Phú Xuyên, Hà Nội</li>
                    <li><span class="icon">🏫</span><strong>Học Vấn:</strong> Học Sinh 12A2-K59-Phú Xuyên A</li>
                    <li><span class="icon">🎬</span><strong>Sở Thích:</strong> Xem Phim, Nghe nhạc, Ăn uống</li>
                </ul>
            </div>
            
            <div class="contact-card">
                <h2>📞 Liên Hệ</h2>
                 <ul>
                    <li><span class="icon">📱</span><strong>SĐT:</strong> 0369458308</li>
                </ul>
                <div class="social-links">
                    <h3>Kết Nối Với Mai Anh!</h3>
                    <a href="https://www.facebook.com/share/16awY73Mus/" target="_blank" rel="noopener noreferrer">
                        <span class="icon">👍</span> FaceBook
                    </a>
                </div>
            </div>
        </div>
        
    </div>

</body>
</html>
