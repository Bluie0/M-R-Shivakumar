<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width,
    initial-scalf=1.0">
    <title>Personal Portfolio Website</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
</head>
<body>
    <div class="container">
        <div class="box">
            <nav>
                <a href="#" class="logo">Personal Portfolio</a>
                    <li><a href="www.google.com">Home</a></li>
                    <li><a href="www.google.com">Services</a></li>
                    <li><a href="www.google.com">About</a></li>
                    <li><a href="www.google.com">Contact</a></li>
            </nav>
            <div class="content">
                <div class="section-1">
                <h1> Hi, I am Shivakumar</h1>
                <h3>Full Stack Web developer </h3>
                <p>High level experiance in Web Design and Developing knowledge,producing quality of work i have 2 years of experience as full stack web developer.</p>
                <a href="#" class="btn">Download Resume</a>
                </div>
                <div class="section-2">
                    <img src="IMAGES.png">
                </div>
                <div class="social">
                    <a href="www.facebook.com" ><i class="fa-brands fa-facebook-f"></i></a> 
                    <a href="www.instagram.com" ><i class="fa-brands fa-instagram"></i></a>
                    <a href="www.twitter.com" ><i class="fa-brands fa-twitter"></i></a> 
                </div>
            </div>
            <div class="contact">
                <p>E-mail: qwerty@gmail.com</p>
                <p>Contact No:1234567890</p>
            </div>
        </div>
    </div>
</body> 
</html>
*{
    padding: 0%;
    margin: 0%;
    box-sizing: border-box;
    font-family: sans-serif;

}
.container
{
    height: 100vh;
    width: 100%;
    position: relative;
    background-image: url(8570.jpg);
    background-size: cover;
    background-position: center;
    justify-content: center;
    display: flex;
    align-items: center;

}
.container .box{
    height: 80vh;
    width: 75%;
    padding: 0 20px;
    background-color: rgba(255, 255, 255, 0.1);
    z-index: 10;
    border: 2px solid rgba(255, 255, 255,0.7);
    border-radius: 20px;
    display: flex;
    backdrop-filter: blur(25px);
    box-shadow: -15px 17px 17px rgba(10, 10, 10, 0.15);

}
.container nav{
    height: 4%;
    width: 60%;
    position: absolute;
    display: flex;
    gap: 30px;
    align-items: center;
    justify-content: space-between;
    margin: 15px;
    color: white;
}
.container .logo{
    font-size: 30px;
    font-weight: 700;
    font-family: cursive;
    color: rgba(227, 233, 228, 0.817);
    font-style: italic;
    align-items: start;
    margin-left: 5%;
    text-decoration: none;
}
.container nav li{
    display: flex;
    padding: -15%;
    margin-left: -19%;
} 
.container nav li a{
    text-decoration: none;
     font-size: 18px;
}
.container nav li a:hover{
    color: rgb(226, 43, 43);
}
 .content{
    position: relative;
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 100%;
     margin-top: 8%;
     padding-top: 80px;
 }
 .content .section-1{
    position: relative;
    width: 40%;
 }
 .content .section-1 h1{
    margin-top: -250px;
    margin-bottom: 20px;
    margin-left:50px;
    font-size: 50px;
    font-weight: 700px;
    color: black;
 }
 .content .section-1 h3{
    font-size: 24px;
    color: rgb(58, 43, 57);
    margin-bottom: 10px;
    margin-left:50px;
 }
 .content .section-1 p{
    font-size: 15px;
    color: rgb(19, 15, 15);
    margin-bottom: 50px;
    margin-left:50px;
 }
 .content .btn{
    padding: 15px 20px;
    border-radius: 50%;
    background-color: rgb(103, 183, 241);
    border: 3px solid;
    font-weight: 500;
    text-decoration: none;
    transition: 0.3s;
    margin-left:50px;
 }
 .content .btn:hover{
    color: rgba(227, 233, 228, 217);
 }
 .content .section-2 {
    width: 60%;
    position: relative;
 }

 .content .section-2 img{
    width: 90%;
    margin-bottom: 30%;
    margin-left: 10%;
 }
 .content .social{
    display: flex;
    flex-direction: row;
    gap: 30px;
    position: absolute;
    left: 10px;
    top: 30px;
    margin-top: 370px;
    margin-left: 60px;
    font-size: 28px;
 }
 .content .social:hover{
    color: rgb(226, 43, 43);
}
 .contact{
    font-size: 15px;
    color: rgb(19, 15, 15);
    margin-bottom: 50px;
    margin-left:-975px;
    margin-top: 540px;
    color: rgb(62, 65, 65);
}
 
