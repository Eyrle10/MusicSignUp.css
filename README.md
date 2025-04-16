# MusicSignUp.css* {

    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}

body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background: linear-gradient(to right, #294E28, #084017);
}

.backgroundv{
    position: fixed;
    right: 0;
    bottom: 0;
    width: 100vw;
    height: 100vh;
    object-fit: cover;
    z-index: -1;
}

.input-group {
    display: flex;
    align-items: center;
    background: #f1f1f1;
    border-radius: 5px;
    padding: 10px;
    margin-bottom: 15px;
}
.signup-container {
    background: white;
    padding: 30px;
    border-radius: 10px;
    box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.2);
    max-width: 350px;
    width: 100%;
}
.title {
    font-size: 20px;
    font-weight: 600;
    color: #98b51a;
    margin-bottom: 20px;
}
.title img {
    height: 40px;
    width: 40px;
    position: relative;
    top: 10px;
}
.title span {
    font-weight: 800;
}
.signup-container input {
    width: 100%;
    padding: 10px;
    margin: 10px 0;
    border: 1px solid #ccc;
    border-radius: 5px;
}

.signup-container button {
    width: 100%;
    padding: 10px;
    background: #98b51a;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px;
}

.signup-container button:hover {
    background-color: #005bb5;
}

.back-to-login {
    background: #98b51a;
    margin-top: 10px;
}

.back-to-login:hover {
    background: #98b51a;
}
