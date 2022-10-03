<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

    <style>
        body {
            /* background-image: url("image/nature.jfif");
                      background-size: cover; */
margin: 0px;
        }

        .block {
            background-color: slateblue;
            padding: 10px;
            border-radius: 3px;
            width: 100px;
            border: 1px solid black;
            text-align: center;
            color: aliceblue;
            display: inline-block;
        }

        #nav {
            background-color: skyblue;
            text-align: center;
            position: sticky;
            top: 0px;
        }
        h1{
            text-align: center;
        }

        #home
        {
            height: 550px;
            background-color: brown;
            color: aliceblue;
        }
        
        #about
        {
            height: 550px;
            background-color:blue;
            color: aliceblue;
        }
        
        #gallery
        {
            height: 550px;
            background-color:blueviolet;
            color: aliceblue;
        }

        
        #contact
        {
            height: 550px;
            background-color:cadetblue;
            color: aliceblue;
        }
        
        #login
        {
            height: 550px;
            background-color:cornflowerblue;
            color: aliceblue;
        }
        h1{
            margin: 0px;
        }
        a{
            color: aliceblue;
            text-decoration: none;
        }
    </style>
</head>

<body>
    <div id="nav">
        <div class="block"><a href="#home">Home</a></div>
        <div class="block"><a href="#about">About</a></div>
        <div class="block"><a href="#gallery">Gallery</a></div>
        <div class="block"><a href="#contact">Contact</a></div>
        <div class="block"><a href="#login">Login</a></div>
    </div>


    <div id="home">
        <h1>Home banner</h1>
    </div>
    <div id="about">
        <h1>About banner</h1>
    </div>

    <div id="gallery">
        <h1>Gallery banner</h1>
    </div>

    <div id="contact">
        <h1>Contactbanner</h1>
    </div>

   
    <div id="login">
        <h1>Login banner</h1>
    </div>
</body>

</html>
