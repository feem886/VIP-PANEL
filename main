<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>กูฟีมพาแนลโปร</title>
    <style>
        /* สไตล์พื้นฐาน */
        body {
            margin: 0;
            padding: 0;
            font-family: 'Tahoma', sans-serif;
            background-color: #0a0a0a;
            color: white;
            display: flex;
            flex-direction: column;
            align-items: center;
            min-height: 100vh;
        }

        /* กล่องพาแนล */
        .panel {
            width: 90%;
            max-width: 380px;
            background: #111;
            margin: 20px auto;
            border-radius: 15px;
            border: 2px solid #ff0000;
            box-shadow: 0 0 15px rgba(255, 0, 0, 0.3);
            overflow: hidden;
        }

        /* ส่วนหัวและรูปโปรไฟล์ */
        .header {
            width: 100%;
            border-bottom: 2px solid #ff0000;
        }
        .header img {
            width: 100%;
            display: block;
        }

        /* ส่วนเมนู */
        .content {
            padding: 15px;
        }
        .title {
            text-align: center;
            color: #ff0000;
            font-size: 22px;
            margin-bottom: 15px;
            text-shadow: 0 0 5px #ff0000;
        }

        /* แถบเมนูแต่ละอัน */
        .menu-item {
            background: #1a1a1a;
            margin-bottom: 10px;
            padding: 12px 15px;
            border-radius: 10px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border: 1px solid #333;
        }

        /* ปุ่มเปิด-ปิด (Switch) */
        .switch {
            position: relative;
            display: inline-block;
            width: 46px;
            height: 22px;
        }
        .switch input {
            opacity: 0;
            width: 0;
            height: 0;
        }
        .slider {
            position: absolute;
            cursor: pointer;
            top: 0; left: 0; right: 0; bottom: 0;
            background-color: #333;
            transition: .3s;
            border-radius: 20px;
        }
        .slider:before {
            position: absolute;
            content: "";
            height: 16px; width: 16px;
            left: 3px; bottom: 3px;
            background-color: white;
            transition: .3s;
            border-radius: 50%;
        }

        /* เมื่อเปิดใช้งานให้เป็นสีเขียว */
        input:checked + .slider {
            background-color: #2ecc71; /* สีเขียว */
            box-shadow: 0 0 8px #2ecc71;
        }
        input:checked + .slider:before {
            transform: translateX(24px);
        }

        .footer {
            margin: 10px 0;
            font-size: 12px;
            color: #555;
        }
    </style>
</head>
<body>

    <div class="panel">
        <div class="header">
            <!-- รูปโปรไฟล์จากที่คุณส่งมา -->
            <img src="https://m1r.ai/9/r58j4.jpg" alt="Profile">
        </div>

        <div class="content">
            <div class="title">VIP-PANEL</div>

            <!-- เมนูต่างๆ -->
            <div class="menu-item">
                <span>ดูดหัว 99%</span>
                <label class="switch"><input type="checkbox"><span class="slider"></span></label>
            </div>

            <div class="menu-item">
                <span>กันแบน</span>
                <label class="switch"><input type="checkbox"><span class="slider"></span></label>
            </div>

            <div class="menu-item">
                <span>กันดำ</span>
                <label class="switch"><input type="checkbox"><span class="slider"></span></label>
            </div>

            <div class="menu-item">
                <span>ลงไฟล์</span>
                <label class="switch"><input type="checkbox"><span class="slider"></span></label>
            </div>

            <div class="menu-item">
                <span>บายพาส</span>
                <label class="switch"><input type="checkbox"><span class="slider"></span></label>
            </div>
        </div>
    </div>

    <div class="footer">BY FEEM886</div>

</body>
</html>
