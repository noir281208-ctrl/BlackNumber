index.html # BlackNumber
Chờ ngày yêu em🥰
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BlackNumber - Bio Link</title>
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        /* Reset & Base Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
        }

        body {
            background-color: #0d0d0d; /* Màu nền đen chủ đạo */
            color: #ffffff;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }

        /* Bio Container */
        .bio-container {
            width: 100%;
            max-width: 400px;
            background-color: #161616;
            border: 2px solid #e60000; /* Đường viền đỏ tương phản rõ rệt */
            border-radius: 16px;
            padding: 30px 20px;
            text-align: center;
            box-shadow: 0 8px 24px rgba(0, 0, 0, 0.8);
        }

        /* Profile Header */
        .avatar-placeholder {
            width: 90px;
            height: 90px;
            background-color: #0d0d0d;
            border: 2px solid #e60000;
            border-radius: 50%;
            margin: 0 auto 15px auto;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 36px;
            color: #e60000;
        }

        .title {
            font-size: 24px;
            font-weight: 700;
            color: #ffffff;
            margin-bottom: 8px;
            letter-spacing: 1px;
        }

        .bio {
            font-size: 15px;
            color: #cccccc;
            margin-bottom: 25px;
            font-weight: 400;
        }

        /* Link Buttons */
        .links-container {
            display: flex;
            flex-direction: column;
            gap: 14px;
        }

        .btn-link {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            width: 100%;
            padding: 14px 20px;
            background-color: #0d0d0d;
            color: #ffffff;
            text-decoration: none;
            font-size: 15px;
            font-weight: 600;
            border-radius: 8px;
            border: 1px solid #e60000; /* Nút viền đỏ nổi bật trên nền đen */
            transition: all 0.2s ease-in-out;
        }

        /* Hover Effect: Đổi nền sang đỏ thuần, chữ trắng */
        .btn-link:hover {
            background-color: #e60000;
            color: #ffffff;
            transform: translateY(-2px);
        }

        .btn-link i {
            font-size: 18px;
            color: #e60000;
        }

        .btn-link:hover i {
            color: #ffffff;
        }

        /* Footer */
        .footer {
            margin-top: 30px;
            font-size: 12px;
            color: #555555;
        }
    </style>
</head>
<body>

    <div class="bio-container">
        <!-- Avatar / Icon đại diện -->
        <div class="avatar-placeholder">
            <i class="fa-solid fa-user"></i>
        </div>

        <!-- Tên & Bio -->
        <h1 class="title">BlackNumber</h1>
        <p class="bio">Chờ ngày yêu em🥰</p>

        <!-- Danh sách liên kết -->
        <div class="links-container">
            <!-- Facebook -->
            <a href="https://www.facebook.com/share/1Dz7DXodJq/" target="_blank" class="btn-link">
                <i class="fa-brands fa-facebook-f"></i>
                <span>Facebook</span>
            </a>

            <!-- TikTok -->
            <a href="https://www.tiktok.com/@henemngayay?_r=1&_t=ZS-9AYHKRPcJ5I" target="_blank" class="btn-link">
                <i class="fa-brands fa-tiktok"></i>
                <span>TikTok</span>
            </a>

            <!-- Zalo / SĐT -->
            <a href="https://zalo.me/0971732943" target="_blank" class="btn-link">
                <i class="fa-solid fa-phone"></i>
                <span>Zalo / Gọi: 0971 732 943</span>
            </a>

            <!-- Gmail -->
            <a href="mailto:noir281208@gmail.com" class="btn-link">
                <i class="fa-solid fa-envelope"></i>
                <span>Email: noir281208@gmail.com</span>
            </a>
        </div>

        <div class="footer">
            &copy; BlackNumber. All rights reserved.
        </div>
    </div>

</body>
</html>

