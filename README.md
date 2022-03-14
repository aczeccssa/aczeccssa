<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="creative_style.css">
    <title>Create account</title>
    <!-- <link rel="shortcut icon" href="../images/favicon.png" type="image/x-icon"> -->
    <link rel="shortcut icon" href="../../images/cropped-TN-favicon-250x250.png" type="image/x-icon">
    <style>
        * {
    padding: 0;
    margin: 0;
    list-style: none;
    border: unset;
    outline: unset;
    animation-timing-function: ease-in-out;

    transition: 0.2s ease-in-out;
}
:root {
    --very-peri-purple: rgb(104, 105, 172);
    --very-dark: #111111;
    --ultra-black: #1e1e1e;
    --light-grey: #282828;
    --virual-blue: #0095d5;

    /* user select */
    user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    -webkit-user-select: none;
}
::-webkit-scrollbar {
	width: 6px;
	background: transparent;
}
::-webkit-scrollbar-thumb {
	background: rgba(117, 117, 117, 0.3);
	border-radius: 100px;
}
::-webkit-scrollbar-thumb:hover {
	background: rgba(117, 117, 117, 0.4);
}
.hidden {
    display: none;
}
body {
    width: 100vw;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    background: url(../../images/login/mount-fuji-2305606.jpg);
    background-repeat: no-repeat;
    background-size: cover;
}
body::after {
    content: "";
    display: block;
    position: fixed;
    top: 0;
    left: 0;
    height: 100vh;
    width: 100vw;
    background: rgba(0, 0, 0, 0.2);
}
#login_pad {
    width: 420px;
    height: 420px;
    display: flex;
    flex-direction: column;
    border-radius: 8px;
    background: rgba(255, 255, 255, 0.8);
    box-shadow: 0 0 40px rgba(0, 0, 0, 0.4);
    backdrop-filter: blur(40px);
    align-items: center;
    justify-content: center;
    z-index: 100;
    position: absolute
}
#login_pad #info {
    width: auto;
    height: auto;
    display: flex;
    flex-direction: column;
    align-items: center;
    position: relative;
    top: -20px;
}
#login_pad h3 {
    font-size: 1.6rem;
    color: var(--light-grey);
    margin: 20px;
    font-weight: 1000;
}
#login_pad .li {
    width: 280px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    background: transparent;
    margin: 10px;
}
#login_pad .li p {
    font-size: 0.9rem;
    font-weight: 100;
}
#login_pad .li input {
    width: 200px;
    height: 26px;
    background: rgba(170, 170, 170, 0.6);
    border-radius: 6px;
    box-shadow: 0 0 6px rgba(0, 0, 0, 0.1)inset;
    box-sizing: border-box;
    padding: 5px;
    color: #1d1d1d;
    font-size: 0.8rem;
}
#login_pad .li input:focus,
#login_pad .li input:active {
    color: #000;
    background: rgba(170, 170, 170, 0.8);
    box-shadow: 0 0 6px rgba(0, 0, 0, 0.2);
}
#login_pad .buttoms {
    width: 160px;
    display: flex;
    justify-content: space-between;
    margin-top: 20px;
}
#login_pad .buttoms button {
    width: 70px;
    height: 26px;
    border-radius: 6px;
    /* background: transparent; */
    box-shadow: 0 0 6px rgba(0, 0, 0, 0.2); 
    color: #fff;
    cursor: pointer;
}
#sign_in_button {
    background: rgb(34, 185, 41);    
}
#sign_in_button:active {
    background: #1d9b23;
}
#login_pad a {
    font-size: 0.6rem;
    position: absolute;
    bottom: 25px;
    right: 15px;
}

    </style>
</head>
<body>
    <!-- login pads -->
    <div id="login_pad">
        <div id="info">
            <h3>Set Your Account</h3>
            <div class="li">
                <p>UserName :</p>
                <input type="text" name="user_name" id="user_name" placeholder="UserName">
            </div>
            <div class="li">
                <p>Password :</p>
                <input type="password" name="password" id="password" placeholder="Password">
            </div>
            <div class="li">
                <p>Confirm :</p>
                <input type="password" name="password" id="password" placeholder="Enter Your Password Again">
            </div>
            <div class="li">
                <p>Email :</p>
                <input type="text" name="email" id="email" placeholder="Email">
            </div>
            <div class="li">
                <p>Safe Key :</p>
                <input type="text" name="email_key" id="key" placeholder="Safe Key">
            </div>
            <div class="buttoms">
                <button id="sign_in_button">Register</button>
            </div>
        </div>
        <!-- forget to reset -->
        <a href="../index.html">I have a account!</a>
    </div>
    <!-- content -->
    <div id="contents">

    </div>
    <!-- out-->
</body>
<script src="sbzl.js"></script>
</html>
