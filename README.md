# Ex.07 Software Product Company Website
## Date:28/04/2024

## AIM:
To develop a static company website to display the softwares and services provided by the company.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
home.html

<html>
<title>stp</title>
<style>
    body{
        background:url(bc.jpeg);
        background-size: cover;
        
    }

    h1{
        color: aliceblue;
    }
    h2{
        color: aliceblue;
    }
    h3{
        color:tomato;
        align:center;
    }


.styled form {
            margin margin-top: 20px;
            display: flex;
            justify-content: space-between;
        }
        .styled [type="button"] {
            padding: 10px 20px;
            background-color: #3498db;
            color: #ffffff;
            border: none;
            transition: background-color 0.3s, color 0.3s; 
        }
        .styled [type="button"]:hover {
            background-color:purple; 
            color:aliceblue;
        }
        .styled [type="submit"] {
            border-radius: 10px;
            padding: 5px 10px; 
            background-color: #3498db;
            color: #ffffff; 
            border: none;
            transition: background-color 0.3s, color 0.3s; 
        }
        .styled [type="submit"]:hover {
            background-color:purple; 
            color:#ffffff; 
        }
        .styled [type="text"] {
            margin-left: 500px;
            transition: background-color 0.3s; 
            background-color:bisque;
        }
        .styled input[type="text"]:focus {
    
    background-color:rgb(224, 127, 224); 
}

.login{
    margin-top: -100;
    margin-left: 1000;
    margin-right: 100;    
    background:black;

    scroll-padding-left: 5px;
    border:2px solid white;
}
.login input[type="button"] {
    padding: 10px 20px; 
    background-color: #3498db;
    color: #ffffff;
    border: none;
    cursor: pointer;
    transition: background-color 0.3s, color 0.3s;
}
.login input[type="button"]:hover {
    color:#000;
    background-color:rgb(204, 32, 204);
}
.login input[type="submit"]{
    padding: 10px 15px; 
    background-color:#4234db;
    color: #ffffff;
    border-radius: 10px;
    cursor: pointer;
    transition: background-color 0.3s, color 0.3s;
}
.login input[type="submit"]:hover {
    color:#000;
    background-color:chocolate;
}
.login input[type="text"] { 
    padding: 10px; 
    transition: background-color 0.3s; 
        
        background-color: #ffffff;
}
.login input[type="text"]:focus {
    
    background-color:slateblue; 
}
.join{
    padding: 10px 20px;
    background-color: #3498db;
    color: #ffffff;
    border: none;
    cursor: pointer;
    transition: background-color 0.3s, color 0.3s;
}
.join:hover {
    color: aquamarine;
    background-color: #4234db;
}

/main html/
</style>
<body >
    <form class="styled ">
        <div class=>
            <a href="home.html">
                <input type="button" value="HOME">
            </a>
            <a href="product.html">
                <input type="button" value="OUR PRODUCTS">
            </a>

            <a href="about.html">
                <input type="button" value="ABOUT US">
            </a>
            <a href="sign.html">
                <input type="button" value="SIGN IN">
            </a>
            <a href="contact.html">
                <input type="button" value="CONTACT">
            </a>  
            <input type="text">
            <input type="submit"value="SEARCH">  
        </div>
    </form>

    <h1>WELCOME TO SOFTRATE TECH PARK</h1>
    <h2>one of the most trusted and valuble company</h2>
    <h2>PRODUCTS</h2>
    <a href="sign.html">
        <input type="button" value="JOIN US" class="join">
    </a>  
    
    <h3>"People who need something really important they must know how what is the process to get it"</h3>

         <center>
        <div class="login">
            <div class="login-box">
            <p style="color: aliceblue;">DONT HAVE AN ACCOUNT</p>
            <a href="sign.html">
                <input type="button" value="SIGN IN"><br><br>
            </a>  
            <p style="color: aliceblue;">LOGIN</p>
            <input type="text" value="Username or email" ><br><br>
            <input type="text" value="Password"><br><br>
            <a href="product.html">
                <input type="submit" value="SUBMIT"><br><br>
            </a>  
        </div>
        </div>
    </center>

</body>
<footer style="background-color:darkmagenta;margin-top: 155; border: none;">
    <P style="color:#ffffff; ;"align="center">Designed and Devoloped by KEERTHANA S 212223040092 </P>
</footer>
</html>
```


```
product.html

<html>
    <title>our products</title>
    <style>  
    body{
        background:url(bc.jpeg);
        background-size:contain;
    } 
    h1{
        color: aliceblue;
    }  
    .styled form {
            margin margin-top: 20px;
            display: flex;
            justify-content: space-between;
        }
        .styled [type="button"] {
            padding: 10px 20px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #ffffff; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="button"]:hover {
            background-color:purple; /*background color on hover */
            color:aliceblue; /*text color on hover */
        }
        .styled [type="submit"] {
            border-radius: 10px;
            padding: 5px 10px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #ffffff; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="submit"]:hover {
            background-color:purple; /*background color on hover */
            color:#ffffff; /*text color on hover */
        }
        .styled [type="text"] {
            margin-left: 500px;
            transition: background-color 0.3s; 
            background-color:bisque;
        }
        .styled input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:rgb(224, 127, 224); /* Adjust the color as needed */
}
</style>
    
    <body>
        <form class="styled ">
            <div class=>
                <a href="home.html">
                    <input type="button" value="HOME">
                </a>
                <a href="product.html">
                    <input type="button" value="OUR PRODUCTS">
                </a>
                <a href="about.html">
                    <input type="button" value="ABOUT US">
                </a>
                <a href="sign.html">
                    <input type="button" value="SIGN IN">
                </a>
                <a href="contact.html">
                    <input type="button" value="CONTACT">
                </a>  
                <input type="text">
                <input type="submit"value="SEARCH">  
            </div>
        </form>
        
        <center>
            <h1 >OUR PRESTIGEOUS PROJECTS</h1>
        <img src="bc2.jpg" height="500" width="800">
    </center>
    </body>
    <footer style="background-color:darkmagenta;margin-top: 100; border: none;">
        <P style="color:#ffffff; ;"align="center">Designed and Devoloped by KEERTHANA S 212223040092 </P>
    </footer>
</html>

```
```
about.html
<html>
<title>about us</title>
<style>
    p{
        color: antiquewhite;
    }
    body{
        background:url(bc.jpeg);
        background-size: cover;
    }
    .styled form {
            margin margin-top: 20px;
            display: flex;
            justify-content: space-between;
        }
        .styled [type="button"] {
            padding: 10px 20px; 
            background-color: #3498db;
            color: #ffffff; 
            border: none;
            transition: background-color 0.3s, color 0.3s; 
        }
        .styled [type="button"]:hover {
            background-color:purple; 
            color:aliceblue; 
        }
        .styled [type="submit"] {
            border-radius: 10px;
            padding: 5px 10px; 
            background-color: #3498db; 
            color: #ffffff; 
            border: none;
            transition: background-color 0.3s, color 0.3s; 
        }
        .styled [type="submit"]:hover {
            background-color:purple; 
            color:#ffffff;
        }
        .styled [type="text"] {
            margin-left: 500px;
            transition: background-color 0.3s; 
            background-color:bisque;
        }
        .styled input[type="text"]:focus {
    
    background-color:rgb(224, 127, 224); 
}
.photos{
    display:flex;
    justify-content: space-around;
    margin-top: 200px;
}
.names{
    display:flex;
    justify-content: space-around;

}
.position {
    display: flex;
    justify-content: space-around;
    margin-left: 10px;
    border-image:5px;
    border-image: antiquewhite;
}

</style>
<body>
    <form class="styled ">
        <div class=>
            <a href="home.html".html">
                <input type="button" value="HOME">
            </a>
            <a href="product.html">
                <input type="button" value="OUR PRODUCTS">
            </a>
            <a href="about.html">
                <input type="button" value="ABOUT US">
            </a>
            <a href="sign.html">
                <input type="button" value="SIGN IN">
            </a>
            <a href="contact.html">
                <input type="button" value="CONTACT">
            </a>  
            <input type="text">
            <input type="submit"value="SEARCH">  
        </div>
    </form>
    <div class="photos">
    <img src="P2.jpg" height="150" width="150">
    <img src="P3.jpg" height="150" width="150">
    <img src="p5.jpg" height="150" width="150">
    <img src="p6.jpg" height="150" width="150">
    <img src="p8.jpg" height="150" width="150">
    <img src="p9.jpg" height="150" width="150">
    
</div>
<div CLASS="names">
    <P>KEERTHANA</P>    
    <P style="margin-left:30;">ANUSH</P>    
    <P style="margin-left:35;">INFANTINA </P>    
    <P style="margin-left:10;">SWATHI</P>    
    <P style="margin-left:50;">KRISHNA</P>    
    <P style="margin-left:30;">PRAVEENA</P>    

</div>
<DIV class="position">
    <p>FOUNDER </p>
    <p style="margin-left:40;">CEO </p>
    <p style="margin-left:60;">CO-FOUNDER </p>
    <p>CO-FOUNDER </p>
    <p>DIRECTOR </p>
    <p >CO-DIRECTOR</p>


</DIV>
</body>
<footer style="background-color:darkmagenta;margin-top: 225; border: none;">
    <P style="color:#ffffff; ;"align="center">Designed and Devoloped by KEERTHANA S 212223040092 </P>
</footer>
</html>




```
```
sign.html
<!DOCTYPE html>
<html>
<head>
    <title>Sign Up</title>
    <style>
        body {
            background:url(bc.jpeg);
            background-size: cover;
            color: antiquewhite;
            font-family: Arial, sans-serif;
        }

        .form {
            margin: 0 auto;
            width: 500px;
            padding: 20px;
        }

        label {
            color: chocolate;
        }

        .purpose {
            color: aqua;
        }

        .buttons {
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #3498db;
            color: #ffffff;
            border: none;
            cursor: pointer;
            transition: background-color 0.3s, color 0.3s;
        }

        .buttons:hover {
            color: aqua;
            background-color: #4234db;
        }
        .styled form {
            margin margin-top: 20px;
            display: flex;
            justify-content: space-between;
        }
        .styled [type="button"] {
            padding: 10px 20px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #ffffff; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="button"]:hover {
            background-color:purple; /*background color on hover */
            color:aliceblue; /*text color on hover */
        }
        .styled [type="submit"] {
            border-radius: 10px;
            padding: 5px 10px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #ffffff; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="submit"]:hover {
            background-color:purple; /*background color on hover */
            color:#ffffff; /*text color on hover */
        }
        .styled [type="text"] {
            margin-left: 500px;
            transition: background-color 0.3s; 
            background-color:bisque;
        }
        .styled input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:rgb(224, 127, 224); /* Adjust the color as needed */
}
.text{
    transition: background-color 0.3s, color 0.3s;

}
.text :focus{
    background-color:skyblue;  
}
.full{
    background:black;
    padding: 10px;
    border:4px double white;
}
    </style>
</head>
<body>
    <form class="styled ">
        <div class=>
            <a href="home.html">
                <input type="button" value="HOME">
            </a>
            <a href="product.html">
                <input type="button" value="OUR PRODUCTS">
            </a>
            <a href="about.html">
                <input type="button" value="ABOUT US">
            </a>
            <a href="sign.html">
                <input type="button" value="SIGN IN">
            </a>
            <a href="contact.html">
                <input type="button" value="CONTACT">
            </a>  
            <input type="text">
            <input type="submit"value="SEARCH">  
        </div>
    </form>
    <div class="form">
        <p align="center"><font color="black">JOIN THE FAMILY OF HPKSOFCO</font></p>
        <p align="center"><font color="black">DON'T HAVE AN ACCOUNT YET?</font></p>
        <div class="full">
        <div class="text">
           
        <label>Unique Username</label>
        <input type="text" value="username"><br><br>
        <label>Email</label>
        <input type="email" value="email"><br><br>
        </div>
        <label>DOB</label>
        <input type="date"><br><br>
        <label>Gender</label><br>
        <div class="purpose">
            <input type="radio" name="gender">Male<br>
            <input type="radio" name="gender">Female<br><br>
        </div>
        <label>Purpose</label><br>
        <div class="purpose">
            <input type="radio" name="purpose">Study<br>
            <input type="radio" name="purpose">Work<br>
            <input type="radio" name="purpose">Partnership<br><br>
        </div>
        <label>Click the checkbox to prove you are human</label>
        <input type="checkbox"><br><br>
        
            <input type="submit" value="CREATE ACCOUNT" class="buttons">
            <input type="submit" value="DOWNLOAD SOFTWARE"class="buttons">
        
    </div>
</div>
</body>
<footer style="background-color:darkmagenta;margin-top: 140px; border: none;">
    <P style="color:#ffffff ;"align="center">Designed and Devoloped by KEERTHANA S 212223040092</P>
</footer>
</html>


```
```
contact.html
<!DOCTYPE html>
<html>
<head>
    <title>Contact Us</title>
    <style>
        b{
            color:cornflowerblue
        }
        p {
            color: aliceblue;
        }

        body {
            background:url(bc.jpeg);
        }

        .yourinfo {
            background:url(bg4.jpg);
            border:5px solid rgb(183, 25, 25);
            margin-right: 800px ;
            
            margin-top: 200px; /* Adjusted margin-top */
            padding: 10px; /* Added padding for better spacing */
        }
        .yourinfo input[type="text"] {
            width: 500px;
            transition: background-color 0.3s; 
        }
        .yourinfo input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color: #2278c3; /* Adjust the color as needed */
}

        .buttons {
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #3498db;
            color: #ffffff;
            border: none;
            cursor: pointer;
            transition: background-color 0.3s, color 0.3s;
        }

        .buttons:hover {
            color: aqua;
            background-color: #4234db;
        }
        .styled form {
            display: flex;
            justify-content: space-evenly;
        }
        .styled form {
            margin margin-top: 20px;
            display: flex;
            justify-content: space-between;
        }
        .styled [type="button"] {
            padding: 10px 20px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #ffffff; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="button"]:hover {
            background-color:purple; /*background color on hover */
            color:aliceblue; /*text color on hover */
        }
        .styled [type="submit"] {
            border-radius: 10px;
            padding: 5px 10px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #ffffff; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="submit"]:hover {
            background-color:purple; /*background color on hover */
            color:#ffffff; /*text color on hover */
        }
        .styled [type="text"] {
            margin-left: 500px;
            transition: background-color 0.3s; 
            background-color:bisque;
        }
        .styled input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:rgb(224, 127, 224); /* Adjust the color as needed */
}
    
.company{

margin-left: 900px;
margin-top: -330px;


scroll-padding-left: 5px;
border:2px solid white;
}
.message textarea {
        background-color: white; /* Set the default background color */
        color: black; /* Set the default text color */
    }

    /* Styles for the text area when it is in focus */
.message    textarea:focus {
        background-color: cadetblue; /* Set the background color when in focus */
        color: white; /* Set the text color when in focus */
    }
    </style>
</head>
<body>
    <form class="styled">
        <div>
            <a href="home.html">
                <input type="button" value="HOME">
            </a>
            <a href="product.html">
                <input type="button" value="OUR PRODUCTS">
            </a>
            <a href="about.html">
                <input type="button" value="ABOUT US">
            </a>
            <a href="sign.html">
                <input type="button" value="SIGN IN">
            </a>
            <a href="contact.html">
                <input type="button" value="CONTACT">
            </a>
            <input type="text" >
            <input type="submit" value="SEARCH">
        </div>
    </form>
    <div class="yourinfo">
        <center>
        <p>Contact Information</p>
        <div>           
            <input type="text" maxlength="100" placeholder="Your Name"><br><br>
            <input type="text" maxlength="100" placeholder="Your Email"><br><br>
            <div class="message">
            <textarea rows="5" cols="65" placeholder="Your Message"></textarea><br><br>
        </div>
            <input type="button" value="SUBMIT" class="buttons">
        
        </center>
        </div>
    </div>
    <div class="company">
        <center>
        <h3 style="color: aliceblue;">COMPANY CONTACT INFORMATION</h3>
       <p> <b >Address</b></p>
        <p >64/60,Velleeswaran Kovil</p>
        <p >Street,Srinivasa Nagar</p>
        <p >Mangadu,Chennai,Tamil Nadu 600122</p>
        <b >Email:</b>
        <p >keerthana230@gmail.com</p>
        <b >Phone</b>
        <p >9345678902</p>
    </center>
    </div>
</body>
<footer style="background-color:darkmagenta;margin-top: 150px; border: none;">
    <P style="color:#ffffff ;"align="center">Designed and Devoloped by KEERTHANA S 212223040092</P>
</footer>
</html>




```

## OUTPUT:

![Screenshot 2024-04-28 210047](https://github.com/keerthanasivakumar02/softweb/assets/150827397/a8292028-c7d9-497c-baf2-3501d8d88f70)

![Screenshot 2024-04-28 210128](https://github.com/keerthanasivakumar02/softweb/assets/150827397/2e481020-59da-4fe3-8312-01e06ed8c826)

![Screenshot 2024-04-28 211326](https://github.com/keerthanasivakumar02/softweb/assets/150827397/46b0d422-e3bd-4d62-9906-fcb7e034b864)

![Screenshot 2024-04-28 211345](https://github.com/keerthanasivakumar02/softweb/assets/150827397/2cdafe18-54c7-4604-bc14-31dfe20cfe74)

![Screenshot 2024-04-28 213246](https://github.com/keerthanasivakumar02/softweb/assets/150827397/6c00104f-c311-4bf7-bdcb-d19187760668)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
