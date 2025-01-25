# Kuroko
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;500;600&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}

header {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    padding: 20px 100px;
    background: pink;
    display: flex;
    justify-content: space-between;
    align-items: center;
    z-index: 99;
}

.logo {
    font-size: 32px;
    color: #00FFFF;
    text-decoration: none;
    font-weight: 700;
    pointer-events: none;
}

.navbar a {
    font-size: 18px;
    color: #00FFFF;
    text-decoration: none;
    font-weight: 500;
    margin-right: 40px;
}

.navbar .btnLogin-popup {
    position: relative;
    background: transparent;
    border: none;
    outline: none;
    font-size: 20px;
    color: #fff;
    font-weight: 500;
    cursor: pointer;
}

.navbar .btnLogin-popup::before {
    content: '';
    position: absolute;
    left: 0;
    bottom: -4px;
    width: 100%;
    height: 2px;
    background: #00FFFF;
    opacity: .85;
}
