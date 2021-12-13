<!DOCTYPE html>
<html>
<head>
  <title> My First Website</title>

  <link rel="stylesheet" href="./css/style.css"> 

</head>
<body>
    <div class="hero">
        <nav>
            <h2 class = "logo">Portfo<span>lio</span></h2>
            <ul>
                <li><a href="./html/aboutme.html">About Me</a></li>
                <li><a href="https://www.senecacollege.ca/home.html">School</a></li>
                <li><a href="./html/tour.html">Tour</a></li>
                <li><a href="./html/images.html"">Images</a></li>
            </ul>           
        </nav>
        <div id="footer"> &copy; 2021 Ellis Sowah
        </div>
       
        <div class="loginBox">
            <img src="images/user.png" class="user">
            <h2>Login Here</h2>
            <form action="https://httpbin.org/post" method="get" autocomplete="on">
                <p>Email</p>
                <input type="email" name="" placeholder="Enter Email">
                    <p>Address<p/>
                    <input type="address" name="" placeholder="Enter Address" autocomplete="street-address">
                    <p>City<p/>
                    <input type="datalist" name="" placeholder="Enter City" autocomplete="City-name">
                    <p>Postal Code<p/>
                    <input type="text" name="" place="Postal Code">

                    <input type="submit" name="" value="Sign In" >
                    <a href="#"> Forget Password</a>
                    




            </form>
        </div>

</body>
