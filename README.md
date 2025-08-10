<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Linktree</title>
    <style>
        body {
            /* Blasser Lime-Verlauf (hellere Farben) */
            background: linear-gradient(135deg, rgba(191, 255, 0, 0.3), rgba(124, 252, 0, 0.3));
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            min-height: 100vh;
            margin: 0;
        }

        .profile-pic {
            width: 120px;
            height: 120px;
            background-color: #d3d3d3; /* hellgrau */
            border-radius: 50%;
            margin-bottom: 15px;
            background-image: url('https://upload.wikimedia.org/wikipedia/commons/9/99/Sample_User_Icon.png');
            background-size: 60%;
            background-repeat: no-repeat;
            background-position: center;
        }

        h1 {
            margin-bottom: 25px;
            color: #333;
            font-size: 24px;
        }

        .button {
            width: 250px;
            height: 50px;
            background-color: #90ee90; /* Hellgrün */
            border: none;
            border-radius: 10px;
            margin: 10px 0;
            cursor: pointer;
            transition: transform 0.2s ease, background-color 0.3s ease;
            font-size: 18px;
            color: #333;
            font-weight: bold;
        }

        .button:hover {
            transform: scale(1.05);
            background-color: #77dd77;
        }
    </style>
</head>
<body>
    <div class="profile-pic"></div>

    <h1>Linktree</h1>

    <a href="#"><button class="button">TikTok</button></a>
    <a href="#"><button class="button">YouTube</button></a>
    <a href="#"><button class="button">Instagram</button></a>
    <a href="#"><button class="button">Webseite</button></a>
    <a href="#"><button class="button">Kontakt</button></a>
</body>
</html>