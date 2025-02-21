<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Navigation Bar</title>
    <style>
        body {
            margin: 0;
            font-family: sans-serif;
            background-color: #add8e6; 
        }
        .navbar {
            display: flex;
            align-items: center;
            background-color: #2c3e50; 
            padding: 10px 20px;
            color: white;
            border-radius: 5px;
            margin: 20px;
        }
        .logo {
            width: 50px; 
            margin-right: 20px;
        }
        .search-bar {
            flex: 1;
            display: flex;
            align-items: center;
            background-color: #f0f0f0; 
            border-radius: 20px;
            padding: 5px 10px;
            margin-right: 20px;
        }
        .search-bar input[type="text"] {
            border: none;
            background-color: transparent;
            flex: 1;
            padding: 5px;
            font-size: 14px;
            outline: none;
        }
        .search-bar input::placeholder {
            color: #888;
        }
        .search-bar button {
            background-color: transparent;
            border: none;
            cursor: pointer;
            padding: 0;
        }
        .search-bar img {
            width: 20px; 
        }
        .profile {
            display: flex;
            align-items: center;
        }
        .profile-image {
            width: 40px; 
            height: 40px;
            border-radius: 50%;
            overflow: hidden;
            margin-right: 10px;
        }
        .profile-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        .profile-details {
            display: flex;
            flex-direction: column;
            margin-right: 20px;
        }
        .profile-details span:first-child {
            font-weight: bold;
            font-size: 14px;
        }
        .profile-details span:last-child {
            font-size: 12px;
        }
        .icons {
            display: flex;
            align-items: center;
        }
        .icons img {
            width: 20px; 
            margin-left: 10px;
        }
    </style>
</head>
<body>
    <div class="navbar">
        <img src="transperent.png" alt="Logo" class="logo">
        <div class="search-bar">
            <input type="text" placeholder="Hinted search text">
            <button><img src="searchsymbol.png" alt="Search"></button>
        </div>
        <div class="profile">
            <div class="profile-image">
                <img src="me2.jpg" alt="Profile Picture">
            </div>
            <div class="profile-details">
                <span>Welcome Back!</span>
                <span>Mistry Nikunj</span>
            </div>
        </div>
        <div class="icons">
            <img src="noti.webp" alt="Notifications">
            <img src="setting.png" alt="Settings">
        </div>
    </div>
</body>
</html>
