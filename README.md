# annisa-zakiyah
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Main Gitar Yuk!</title>
    <style>
        /* --- CSS STYLING --- */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f4f4f4; /* Abu-abu sangat muda */
            color: #333333; /* Abu-abu tua untuk teks */
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            overflow: hidden; /* Mencegah scrollbar muncul saat tombol bergerak */
            padding: 20px;
        }

        .container {
            background: #ffffff; /* Putih */
            max-width: 450px;
            width: 100%;
            border-radius: 20px;
            padding: 40px 30px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.08);
            text-align: center;
            border: 1px solid #e0e0e0;
            position: relative;
        }

        /* Stiker/Dekorasi Pendukung */
        .sticker-bg {
            font-size: 2.5rem;
            position: absolute;
            opacity: 0.15;
        }
        .st-1 { top: 15px; left: 15px; }
        .st-2 { bottom: 15px; right: 15px; }

        .sticker-main {
            font-size: 4.5rem;
            margin-bottom: 20px;
            display: inline-block;
            animation: bounce 2s infinite ease-in-out;
        }

        @keyframes bounce {
            0%, 100% { transform: translateY(0) rotate(0deg); }
            50% { transform: translateY(-10px) rotate(5deg); }
        }

        h1 {
            font-size: 1.8rem;
            color: #222222;
            margin-bottom: 15px;
        }

        p.text-ajakan {
            font-size: 1.05rem;
            color: #666666;
            margin-bottom: 30px;
            
