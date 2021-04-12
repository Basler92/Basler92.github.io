<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8"></meta>
    <meta name="viewport" content="width=device-width, initial-scale =1.0"></meta>
    <meta http-equiv="X-UA-Compatible" content="ie=edge"></meta>
    <tittle></tittle>
    <link rel="stylesheet" href="style.css"></link>    
    <link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet" integrity="sha384-wvfXpqpZZVQGK6TAh5PVlGOfQNHSoD2xbE+QkPxCAFlNEevoEH3Sl0sibVcOQVnN" crossorigin="anonymous">
</head>
<body>
    <canvas id="canvas1"></canvas>
    <script src="script.js"></script>

    <div class="container">
        <div class="btn"><a href="#photo">About</a></div>
        <div class="btn"><a href="#projects">Projects</a></div>
        <div class="btn"><a href="#contact1">Contact</a></div>
    </div>

    <div class="Hello">
        Hi!  I am Piotr Jamroz
    </div>

    <div class="arrow">
        <span></span>
        <span></span>
        <span></span>
    </div>

    <div id="photo">
        <img src="myAvatar.png" width="300" height="300" alt="" style="float:left;">
        <div class="about">
            <br>First name: Piotr</br>
            <br>Last name: Jamroz</br>
            <br>Location: Lublin, Poland <img src="1.jpg" width="25" height="20" alt="" ></br>
            <br>Skills: HTML, CSS, Vanilla JS, </br>
        </div>
    </div>

    <div id="projects">
        Projects:
    </div>

    <div id="contact1">
        <br></br>
        contact me:
        <br></br>
        <br> <i class="fa fa-facebook"></i>  <i class="fa fa-phone"></i>  <i class="fa fa-github"></i>    <i class="fa fa-envelope"></i></br>
    
        <br>or write below:</br>
    </div>

    <div class="contact">
            
              <label for="fname">First Name</label>
              <input type="text" id="fname" name="firstname" placeholder="Your name..">
              <label for="lname">Last Name</label>
              <input type="text" id="lname" name="lastname" placeholder="Your last name..">
              <label for="country">Country</label>
              <select id="country" name="country">
                  <option value="poland">Polska</option>
                  <option value="germany">Deutschen</option>
                  <option value="french">France</option>
                  <option value="spain">Espańa</option>
                <option value="australia">Australia</option>
                <option value="canada">Canada</option>
                <option value="usa">USA</option>
                <option value="japon">Nippon</option>
              </select>
              <label for="subject">Subject</label>
              <textarea id="subject" name="subject" placeholder="Write something.." style="height:25px"></textarea>
              <input type="submit" value="Submit">
    </div>

    <div id="stopka">
       Copyright &copy; Piotr Jamroz A.D. 2021 
    </div>

   

    
</body>    
</html>
