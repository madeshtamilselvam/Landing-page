# Landing-page
<html>
    <head>
        <title>LANDING PAGE</title>
    <style>
        *
{
    margin: 0;
    padding: 0;
}
body
{
    background: rgba(0, 0, 0, 0.7) url(image/back\ img.jpg);
    background-size: cover;
    background-blend-mode:darken;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    background-position: center;
}
.container
{
    display: flex;
    align-items: center;
    justify-content: space-between;
}
.container h1
{
    margin-left: 10px;
    color:rgb(84, 10, 187);
    font-size: 40px;
    padding: 10px;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    font-style: italic;
}
.navbar ul li
{
    display: inline-block;
    padding: 18px;
}
.navbar ul li a
{
    text-decoration: none;
    color:crimson;
    padding:4px;
    font-size: 20px;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana;
    transition: 1.5s;
}
.navbar ul li a:hover
{
    background-color:tan;
}
.content
{
    position: absolute;
    color:white ;
    top: 45%;
    left:1% ;
}
.content h2
{
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans';
    font-size: 30px;
    margin-left: 35%;
}
.content h1
{
    font-size: 55px;
    margin-left:27% ;
}
.content p
{
    text-align:center ;
    margin-top: 17px;
    font-size: 20px;
}
    </style>
    </head>
    <body>
        <div class="container">
            <h1>MERIDIAN</h1>
            <div class="navbar">
                <ul>
                    <li><a href="#">HOME</a></li>
                    <li><a href="#">ABOUT</a></li>
                    <li><a href="#">GALLERY</a></li>
                    <li><a href="#">SERVICE</a></li>
                    <li><a href="#">CONTACT</a></li>                    
                </ul>
            </div>
        </div>
        <div class="content">
            <h2>Best Non-Vegeterian Restaurant</h2>
            <h1>THE TASTES OF MERIDIAN</h1>
            <p>
                The restaurant has a warm and inviting ambiance, making it the perfect place 
                for a romantic dinner, a family gathering, or a business lunch. The decor is 
                elegant, with subtle lighting and comfortable seating arrangements that create 
                a cozy atmosphere.
            </p>
        </div>
    </body>
</html>
