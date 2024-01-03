
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="landing.css">
    <style>
        .whole {
            height: 700px;
            margin-top: -1%;
            margin-left: -1%;
            margin-right: -0.5%;
            background: linear-gradient(to right, hsl(0, 0%, 0%,0.65), hsla(0, 3%, 29%, 0.65), hsl(0, 0%, 0%,0.65)), url(https://bgr.com/wp-content/uploads/2020/09/bgrpic-copy-19.jpg?quality=70&strip=all);
        }
        @media screen and (max-width: 800px) {
            .whole {
                height: 500px;
            }
        }
        .header {
            margin-left: 60%;
            padding-top: 4%;
            word-spacing: 40px;
            font-size: large;
        }
        @media screen and (max-width: 800px) {
            .header {
                margin-left: 15%;
            }
        }
        a {
            color: white;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        .content {
            margin-top: 13%;
            text-align: center;
            font-size: 90px;
        }
        @media screen and (max-width: 800px) {
            .content {
                font-size: 60px;
            }
        }
        h1 {
            color: white;
            font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            letter-spacing: -4px;
            transform: skew(-15deg);
        }
        h2 {
            font-size: 30px;
            color: white;
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        @media screen and (max-width: 800px) {
            h2 {
                font-size: 20px;
            }
        }
        .about {
            height: 550px;
            margin-top: 3%;
            margin-left: 1%;
            box-shadow: 3px 3px 10px black;
            background-color: white;
            color: black;
            padding-top: 5%;
            padding-left: 13%;
            font-size: xx-large;
        }
        @media screen and (max-width: 800px) {
            .about {
                height: 1000px;
            }
        }
        .abt {
            font-size: large;
            width: 600px;
            word-spacing: 10px;
            line-height: 30px;
        }
        @media screen and (max-width: 800px) {
            .abt {
                width:500px;
                margin-left: -1%;
            }
        }
        .im1 {
            height: 300px;
            width: 600px;
            object-fit: cover;
            margin-left: 50%;
            margin-top: -25%;
            margin-bottom: 25%;
        }
        @media screen and (max-width: 800px) {
            .im1 {
                margin-left: -9%;
                margin-top: 5%;
            }
        }
        .services {
            height: 700px;
            margin-top: 3%;
            margin-left: 1%;
            margin-bottom: 3%;
            box-shadow: 3px 3px 10px black;
            background-color: white;
            color: black;
            padding-top: 3%;
            padding-left: 4%;
            font-size: xx-large;
        }
        @media screen and (max-width: 800px) {
            .services {
                height: 1700px;
            }
        }
        .serv1 {
            margin-left: 0%;
            margin-top: 5%;
            height: 400px;
            width:400px;
            text-align: center;
        }
        @media screen and (max-width: 800px) {
            .serv1 {
                margin-left: 20%;
            }
        }
        .serv2 {
            margin-left: 35%;
            margin-top: -28.5%;
            height: 400px;
            width:400px;
            text-align: center;
        }
        @media screen and (max-width: 800px) {
            .serv2 {
                margin-left: 20%;
                margin-top: 20%;
            }
        }
        .serv3 {
            margin-left: 69%;
            margin-top: -28.5%;
            height: 400px;
            width:400px;
            text-align: center;
        }
        @media screen and (max-width: 800px) {
            .serv3 {
                margin-left: 20%;
                margin-top: 20%;
            }
        }
        .im2,.im3,.im4 {
            height: 400px;
            width:400px;
            object-fit: cover;
        }
        .footer {
            height: 200px;
            background-color: rgb(143, 139, 139);
            margin-left: -1%;
            margin-right: -1%;
            padding: 3% 0 0 5%;
        }
        .fa {
            padding: 20px;
            font-size: 30px;
            width: 30px;
            border-radius: 40px;
            text-align: center;
            text-decoration: none;
            margin: 5px 2px;
            color: white;
        }
        .fa:hover {
            text-decoration: none;
        }
        .final {
            margin-left: 50%;
            margin-top: -8%;
            font-size: 90px;
        }
    </style>
    <title>Zomato</title>
</head>

<body>
    <section class="whole">
        <div class="header">
            <a href="#">Home</a>
            <a href="#">About</a>
            <a href="#">services</a>
            <a href="#">Contact</a>
            <a href="#">Login</a>
            <a href="#">Signup</a>
        </div>
        <div class="content">
            <h1>Zomato</h1>
            <h2>Find the best restaurants, cafés and bars in India</h2>
        </div>
    </section>
    <section class="about">
        <h3>WHO ARE WE?</h3>
        <div class="abt">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Distinctio quo maxime nisi eum dignissimos dolore
                ducimus optio! Quia, quaerat a cumque distinctio perspiciatis cupiditate facilis, fugiat vero voluptate eos
                numquam? Optio perspiciatis debitis atque eos dicta commodi cupiditate incidunt sapiente explicabo quo odit porro
                voluptate omnis aliquid nostrum animi veniam, blanditiis laborum accusamus illo itaque! Esse soluta illo
                quas repellendus. Voluptatum earum fugit repellat distinctio dignissimos harum deleniti, velit ducimus neque molestias alias
                magni quaerat quasi atque non. Optio nesciunt rem, corporis voluptatem magni recusandae laboriosam quibusdam
                aut sunt delectus.</p>
        </div>
        <img class="im1" src="https://usmaniarestaurant.com/wp-content/uploads/2019/05/shutterstock_710628562-min-1.jpg" alt="fd">
    </section>
    <section class="services">
        <h3>SERVICES PROVIDED</h3>
        <div class="serv1">
            <img class="im2" src="https://www.blanketmunnar.com/images/restuarent1.jpg" alt="serv1">
            <p>Huge variety of restaurants</p>
        </div>
        <div class="serv2">
            <img class="im3" src="https://airspeed.ph/wp-content/uploads/2021/01/5-Advantages-of-Door-To-Door-Delivery.jpg" alt="serv2">
            <p>Fast delivery</p>
        </div>
        <div class="serv3">
            <img class="im4" src="https://assets.vogue.in/photos/61d84b1306ef70c5a24bc033/master/w_1600%2Cc_limit/Monkey%2520Bar.jpeg" alt="serv3">
            <p>Multicuisine dishes</p>
        </div>
    </section>
    <section class="footer">
        <h2>Contact us</h2>
        <a href="#" class="fa fa-twitter"></a>
        <a href="#" class="fa fa-instagram"></a>
        <a href="#" class="fa fa-linkedin"></a>
        <a href="#" class="fa fa-facebook"></a>
        <h1 class="final"><a href="#">Zomato</a></h1>
    </section>

</body>

</html>
