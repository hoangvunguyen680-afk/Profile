<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile - Nguyễn Hoàng Vũ</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        /* --- PHẦN CSS TRANG TRÍ --- */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }

        body {
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            /* Màu nền Gradient hiện đại */
            background: linear-gradient(135deg, #00c6ff, #0072ff);
            padding: 20px;
        }

        .card {
            position: relative;
            width: 100%;
            max-width: 400px;
            background: rgba(255, 255, 255, 0.9);
            border-radius: 20px;
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.2);
            overflow: hidden;
            text-align: center;
            transition: transform 0.3s ease;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        /* Phần ảnh bìa phía trên */
        .card-header {
            height: 120px;
            background: linear-gradient(to right, #11998e, #38ef7d);
        }

        /* Ảnh đại diện */
        .profile-img {
            width: 130px;
            height: 130px;
            border-radius: 50%;
            border: 5px solid #fff;
            object-fit: cover;
            margin-top: -65px;
            background-color: #eee;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }

        .info {
            padding: 20px;
        }

        .name {
            font-size: 24px;
            font-weight: 600;
            color: #333;
            margin-bottom: 5px;
        }

        .school {
            font-size: 14px;
            color: #666;
            font-weight: 400;
            margin-bottom: 20px;
            display: inline-block;
            background: #e1f5fe;
            padding: 5px 15px;
            border-radius: 20px;
            color: #0277bd;
        }

        /* Danh sách thông tin chi tiết */
        .details {
            list-style: none;
            text-align: left;
            margin-bottom: 25px;
            padding: 0 10px;
        }

        .details li {
            margin-bottom: 12px;
            color: #444;
            font-size: 15px;
            display: flex;
            align-items: center;
        }

        .details li i {
            width: 30px;
            color: #0072ff;
            font-size: 18px;
        }

        /* Nút liên hệ Facebook */
        .btn-contact {
            display: inline-block;
            padding: 12px 30px;
            background: linear-gradient(to right, #3b5998, #4c669f);
            color: #fff;
            text-decoration: none;
            border-radius: 30px;
            font-weight: 500;
            box-shadow: 0 5px 15px rgba(59, 89, 152, 0.4);
            transition: all 0.3s ease;
        }

        .btn-contact:hover {
            background: linear-gradient(to right, #4c669f, #3b5998);
            transform: scale(1.05);
            box-shadow: 0 8px 20px rgba(59, 89, 152, 0.6);
        }

        /* Footer nhỏ */
        .footer-text {
            margin-top: 20px;
            font-size: 12px;
            color: #aaa;
        }

    </style>
</head>
<body>

    <div class="card">
        <div class="card-header"></div>
        
        <img src="https://ui-avatars.com/api/?name=Nguyen+Hoang+Vu&background=random&size=200" alt="Avatar" class="profile-img">
        
        <div class="info">
            <h2 class="name">Nguyễn Hoàng Vũ</h2>
            <p class="school">Học sinh lớp 12C11 - THPT Trần Cao Vân</p>

            <ul class="details">
                <li>
                    <i class="fas fa-birthday-cake"></i>
                    <span>17/03/2008</span>
                </li>
                <li>
                    <i class="fas fa-venus-mars"></i>
                    <span>Nam</span>
                </li>
                <li>
                    <i class="fas fa-map-marker-alt"></i>
                    <span>Tỉnh Khánh Hòa
