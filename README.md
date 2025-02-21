<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Navigation bar</title>
    <style>
        body {
            margin: 0;
            font-family: sans-serif;
            background-color: #1a237e;
            color: white;
        }
        header {
            display: flex;
            align-items: center;
            padding: 15px 20px;
        }
        .logo {
            flex: 1;
            display: flex;
            align-items: center;
        }
        .logo img {
            max-height: 80px;
            max-width: 150px;
        }
        .search-bar {
            flex: 2;
            text-align: center;
        }
        .search-bar input {
            width: 70%;
            padding: 10px;
            border: none;
            border-radius: 5px;
            background-color: #3f51b5;
            color: white;
        }
        .search-bar input::placeholder {
            color: #ccc;
        }
        .user-profile {
            flex: 1;
            display: flex;
            align-items: center;
            justify-content: flex-end;
        }
        .profile-info {
            display: flex;
            align-items: center;
            margin-right: 20px;
        }
        .profile-picture {
            width: 101px; /*Adjusted to match the image size more accurately*/
            height: 96px;
            border-radius: 50%;
            background-color: #5c6bc0;
            margin-left: 10px; /* moved to left */
            overflow:hidden;
        }
        .profile-picture img {
            width:108%;
            height:113%;
            object-fit: cover;
        }
        .profile-details {
            display: flex;
            flex-direction: column;
            text-align: left; /* Align text to the right */
        }
        .profile-name {
            font-weight: bold;
        }
        .welcome-message {
            font-size: 14px;
        }
        .icons {
            display: flex;
            align-items: center;
        }
        .icons img {
            width: 29px;
            height: 29px;
            margin-left: 10px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">
            <img src="transperent.png" alt="Logo">
        </div>
        <div class="search-bar">
            <input type="text" placeholder="Search...">
        </div>
        <div class="user-profile">
            <div class="profile-info">
                <div class="profile-picture"><img src="mephoto.jpg" alt="Profile Picture"></div>
            </div>
                <div class="profile-details">
                    <div class="profile-name">MISTRY NIKUNJ</div>
                    <div class="welcome-message">WELCOME TO GOKUL TECH VENTURES!</div>
                </div>
            <div class="icons">
                <img src="bell-1096280_640.webp" alt="Notifications">
                <img src="settinglogo.avif" alt="Settings">
            </div>
        </div>
    </header>
</body>
</html>
