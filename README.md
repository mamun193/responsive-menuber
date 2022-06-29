# responsive-menuber


# html file..........


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>10 th class / menu design</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <div class="menu">
        <ul>
            <li><a href="#">home</a></li>
            <li><a href="#">about</a></li>
            <li><a href="#">Services</a>
               <ul>
                <li><a href="">web design</a></li>
                <li><a href="">logo design</a></li>
                <li><a href="">apps design</a></li>
                <li><a href="">photo design</a></li>
                <li><a href="">video design</a></li>
                <li><a href="">graphices design</a>
                
                    <ul>
                        <li><a href="">web design</a></li>
                        <li><a href="">logo design</a></li>
                        <li><a href="">apps design</a></li>
                        <li><a href="">photo design</a></li>
                        <li><a href="">video design</a></li>
                        <li><a href="">graphices design</a></li>
                    </ul>
                 </li>
            </ul>
         </li>

            <li><a href="#">blog</a>
                <ul>
                    <li><a href="">web design</a></li>
                    <li><a href="">logo design</a></li>
                    <li><a href="">apps design</a></li>
                    <li><a href="">photo design</a></li>
                    <li><a href="">video design</a></li>
                    <li><a href="">graphices design</a></li>
                </ul>
            </li>
            <li><a href="#">contract</a></li>
        </ul>
    </div>
    
</body>
</html>



#css..........

body{
    margin: 0;
    padding
}

.menu{
    background-color: #fac180;
}
ul {
    margin:0;
    padding:0;
    text-align: center;
}
ul li {
    list-style: none;
    display:inline-block;
    text-align: center;
    position: relative;

}
ul li a{
    text-transform: capitalize;
    text-decoration: none;
    padding: 20px;
    display: block;
    font-weight: 200;
    font-size: 20px;
    transition: 0.5s;
    border-bottom: 5px solid transparent;
    
}
ul li:hover > a{
    background-color: black;
    color: bisque;
    border-bottom: 5px solid blue;
}
/*main menu design end*/

ul ul li{
    display: block;
    width: 180px;
}
ul ul{
    position: absolute;
    background-color: aqua;
    top: 100%;
    display: none;

}
ul li:hover> ul{
    display: block;
    background-color:chartreuse;

}
/* sub menu design end*/

ul ul ul {
   position: absolute;
   left: 100%;
   top: 0;
}

