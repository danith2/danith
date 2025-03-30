<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website by danit</title>
    <style>
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        
        @keyframes profileImageFadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        
        @keyframes textFadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        
        @keyframes socialItemFadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        body {
            font-family: sans-serif;
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background-color: #f0f0f0;
        }
        
        .profile-card {
            width: 90%;
            max-width: 400px;
            background-color: white;
            border-radius: 20px;
            padding: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            opacity: 0;
            animation: fadeIn 1s ease-out forwards;
        }
        
        .profile-img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            margin: 0 auto;
            opacity: 0;
            animation: profileImageFadeIn 1s ease-out 0.5s forwards;
        }
        
        .social-link {
            display: flex;
            align-items: center;
            padding: 10px;
            border-radius: 20px;
            background-color: white;
            margin-bottom: 10px;
            transition: background-color 0.3s ease;
            opacity: 0;
            text-decoration: none;
            color: inherit;
        }
        
        .social-link img {
            width: 35px;
            height: 35px;
            margin-right: 10px;
            transition: transform 0.3s ease;
        }
    </style>
</head>
<body>
    <div class="profile-card">
        <div style="text-align: center; margin-bottom: 20px;">
            <img src="https://i.ibb.co/678CB7Jr/Untitled-2.png" alt="Profile Image" class="profile-img">
            <h1 style="margin: 10px 0 5px; font-size: 1.8em; opacity: 0; animation: textFadeIn 1s ease-out 0.8s forwards;">COpyRight</h1>
            <p style="margin: 0; font-size: 1em; color: #555; opacity: 0; animation: textFadeIn 1s ease-out 1s forwards;">Graphic Designer</p>
        </div>
        
        <div style="background-color: #f5f5f5; padding: 15px; border-radius: 20px;">
            <h2 style="font-size: 1.2em; margin-bottom: 15px; text-align: center; opacity: 0; animation: textFadeIn 1s ease-out 1.2s forwards;">MY SOCIAL MEDIA</h2>
            
            <a href="https://www.facebook.com/share/19Hm2jidtD/?mibextid=wwXIfr" class="social-link" style="animation: socialItemFadeIn 0.5s ease-out 1.4s forwards;">
                <img src="https://i.ibb.co/KpjkwFg7/d.png" alt="Facebook">
                <span style="flex-grow: 1;">Dānit</span>
            </a>
            
            <a href="https://t.me/+855965460963" class="social-link" style="animation: socialItemFadeIn 0.5s ease-out 1.6s forwards;">
                <img src="https://i.ibb.co/hJX8QWMS/Logo3.png" alt="Telegram">
                <span style="flex-grow: 1;">Voeun Danit</span>
                <span style="font-size: 0.8em; color: #555;">Admin</span>
            </a>
            
            <a href="https://www.pinterest.com/your-pinterest-page" class="social-link" style="animation: socialItemFadeIn 0.5s ease-out 1.8s forwards;">
                <img src="https://i.ibb.co/20KYY99M/Logo.png" alt="Pinterest">
                <span style="flex-grow: 1;">COpyRight</span>
                <span style="font-size: 0.8em; color: #555;">Group</span>
            </a>
            
            <a href="https://github.com/your-github-profile" class="social-link" style="animation: socialItemFadeIn 0.5s ease-out 2s forwards;">
                <img src="https://i.ibb.co/8gtrBB7D/Logo1.png" alt="GitHub">
                <span style="flex-grow: 1;">COpyRight Official</span>
                <span style="font-size: 0.8em; color: #555;">Channel</span>
            </a>
        </div>
        
        <div style="text-align: center; margin-top: 20px; color: #888; opacity: 0; animation: textFadeIn 1s ease-out 2.2s forwards;">
            <p>&copy; 2025 Danit</p>
        </div>
    </div>
</body>
</html>
