# Ex.07 Software Product Company Website
## Date:

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DD_Home</title>
    <style>
        *{
            margin:0;
            padding:0
        }
        #nav{
            background-color:plum;
            color:#007cb9;
            padding: 15px;
    
        }
        li,h1,ul{
            display:inline;
        }
        ul{
            margin-left:45%;
        }
        a{
            color:#007cb9;
            text-decoration: none;
        }
        a:hover{
            color:yellow;
            cursor:pointer;
 }
        input{
            width: 60%;
            padding: 15px;
        }
            .searchbar{
            padding:50px;
            text-align: center;
        }
      
        .box {
            display:inline-block;
            border-style:dotted ;
            border-radius: 10px;
            border-color: plum;
            width: 400px;
            min-height: 300px;
            font-size: 20px;
            background-color:plum;
        
        }
        .heading1{
            color:#007cb9;
            text-align: center;
            padding-top: 20px;
        }
        .heading2{
            color:#007cb9;
            text-align: justify;
            font-size: 30px;
            margin-left: 30px;
        }
        .edge{
            padding-left: 900px;
        }
        .box{
            text-align: center;
        }
 p{
            color:#9400b9;
            text-align: center;
        }
    
        .bottomdiv{
 background-color:plum;
            color:#007cb9;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 105px;

        }
        table{
            margin-left: 40px;
        }
    </style>
</head>
<body background="webbackcover2.jpg">
    <div class="header">
        <nav id="nav">
            <h1>
                ORACLE
            </h1>
                <ul>
                    <li class="li1"> 
                        <a href="panda.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="products.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="empolyee.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="Contactus.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
        </nav>
    </div>
    <div class="searchbar">
    <input placeholder="search">
    </div>
        <div><pre class="heading2"><i><b>
"Fastest ever database performance. Runs faster. 
Costs less. And never breaks."<b></i></pre></div>
        <div class="edge">
            <div class="box">
            <h1 class="heading1">LOGIN HERE</h1>
            <br>
            <br>
            <form>
                <table cellpadding="15px" cellspacing="15px">
                    <tr>
                        <td>
                           <p> Username:</p>
                        </td>
                        <td>
                            <input type="email" name="name" placeholder="Enter a Email">
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <p> Password:</p>
                        </td>
                        <td>
                            <input type="password" name="pwd" placeholder="Enter a Password">
                        </td>
                    </tr>
                    <tr>
                        <td colspan="2">
                            <input type="submit" value="LOGIN" style="background-color: purple; color:white;">
                        </td>
                    </tr>
                </table>
                
            </form>
            </div>
        </div>
    
</body>
<html>
```
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DD_Products</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:plum;
            color:#007cb9;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:45%
        }
        li{
            color:#007cb9;
        }
        li:hover{
            color:white;
            cursor:pointer;
        }
 input{
            width: 18%;
            padding: 15px;
        }
            .searchbar{
            padding:50px;
            text-align: center;
        }
        .box{
            border-color:purple;
            border-width:2px;
            border-style:solid;
            display: inline-block;
            width: 414px;
        }
        .product{

            text-align: center;
        }
        .box{
            background-color:plum;
            cursor:pointer;
        }
        a{
            color:#007cb9;
            text-decoration: none;
        }
        a:hover{
            color:white;
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color:#007cb9;
        }
      p{
            color:#007cb9;
            text-align: center;
        }
   b{
            width: 300px;
            height: 200px;
        }
    h1{
            color:#007cb9;
            text-align: center;
        }
        .bottomdiv{
 background-color:plum;
            color:#007cb9;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 230px;

        }
    </style>
</head>
<body background="webbackcover2.jpg">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">INFOSYS</h1>
                <ul>
                    <li class="li1"> 
                        <a href="panda.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="products.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="empolyee.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="Contactus.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">PRODUCTS</h1>
        <br>
        <div class="product">
            <div class="box">
               <b><img src="1..png" ></b>
                <h1>Learn about OCI</h1>
                <p>Oracle Cloud Infrastructure allows you to Experience tomorrow, today by efficiently building, deploying, integrating, securing, and managing all enterprise applications.uild, deploy, integrate, and extend applications in the cloud or on premises—quickly and elastically.</p>
            </div>
            <div class="box">
                <img src="2.png">
                <h1>Try Oracle Cloud</h1>
                <p>Experience Oracle Cloud Platform, a comprehensive, standards-based combination of Oracle and open source technologies.</p>
            </div>
            <div class="box">
                <img src="3.png">
                <h1>Buy Oracle Cloud</h1>
                <p>Experience tomorrow, today by efficiently building, deploying, integrating, securing, and managing all enterprise applications.</p>
            </div>
        </div>
    </div>
    
</body>
</html>
```
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DD_Employees</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:plum;
            color:#007cb9;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:45%
        }
        li{
            color:#007cb9;
        }
        li:hover{
            color:#007cb9;
            cursor:pointer;
        }
        input{
            width: 60%;
            padding: 15px;
        }
        a{
            color:#007cb9;
text-decoration: none;
        }
        a:hover{
            color:#007cb9;
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color:#007cb9;
        }
        .bottomdiv{
            background-color:plum;
            color:#007cb9;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 0.7px;

        }
        img{
            border-radius: 50%;
            width: 200px;
            display: inline;
            padding:3px;
            
        }
        .person{
            margin:100px;
            text-align: center;
        }
        b,p{
            color:#007cb9;
            text-align: center;
        }
      
</style>
</head>
<body background="webbackcover2.jpg">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">INFOSYS</h1>
                <ul>
                    <li class="li1"> 
                        <a href="panda.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="products.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="empolyee.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="Contactus.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">EMPLOYEES</h1>
        <table class="person">
            <tr>
                <td>
                    <img src="ceo.png" class="MyPic">
                </td>
		

                <td>
                    <img src="cofoundar.png" class="cofoundar">
                </td>
		
                <td>
                   <img src="cofoundar2.png" class="cofoundar">
                </td>
                <td>
                    <img src="director.png" class="PV Sindhu">
                </td>
                <td>
                    <img src="assin director.png" class="Sania Nehwal">
                </td>
            </tr>
            <tr>
                <td>
                    <b>Alia Bhatt</b>
                    <p>CEO</p>
                </td>
                <td>
                    <b>Ranbir Kapoor</b>
                    <p>CEO,Co-Founder</p>
                </td>
                <td>
                    <b>Kiara Advani</b>
                    <p>CTO,Co-Founder</p>
                </td>
                <td>
                    <b>Shah rukh khan</b>
                    <p>CEODirector</p>
                </td>
                <td>
                    <b>Siddarth Malhotra</b>
                    <p>Asst.Director</p>
                </td>
              
            </tr>
        </table>
    </div>
    
</body>
</html>
```
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DD_Contactus</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:plum;
            color:#007cb9;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:45%
        }
        li{
            color:#007cb9;
  }
        li:hover{
            color:white;
            cursor:pointer;
        }
        input{
            width: 60%;
            padding: 15px;
        }
            .searchbar{
            padding:50px;
            text-align: center;
        }
        .box{
            border-color:black;
            border-width:2px;
            border-style:solid;
            display: inline-block;
            width: 414px;
        }
        .product{

            text-align: center;
        }
        .box{
            background-color:plum;
            cursor:pointer;
        }
        a{
            color:b#007cb9;
            text-decoration: none;
        }
        a:hover{
color:white;
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color:#007cb9;
        }
        .table1{
            color:black;
            font-size: large;
        }
        .contactus{
            margin-left:400px;
        }
        .heading3{
            padding-top: 30px;
            padding-bottom: 10px;
            text-align: center;
            color:#007cb9;
        }
        .table2{
            color:#007cb9;
            font-size: large;
            background-color:plum;
            border-radius: 5px;
            border-style:dotted;
            border-color: plum;

        }
        .queries{
            margin-left:600px;
        }
        .bottomdiv{
            background-color:plum;
            color:#007cb9;
            text-align: center;
            position:relative;
display:block;
            margin-top: 24px;

        }
    </style>
</head>
<body background="webbackcover2.jpg">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">INFOSYS</h1>
                <ul>
                    <li class="li1"> 
                        <a href="panda.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="products.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="empolyee.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="Contactus.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">CONTACT US</h1>
        <div class="contactus">
            <table cellpadding="15px" cellspacing="15px" class="table1">
                <tr>
                    <td>
                        ADDRESS :
                    </td>
                    <td>
                        T - nagar,2nd main road south chennai
</td>
                </tr>
                <tr>
                    <td>
                        LANDMARK :
                    </td>
                    <td>
                        chennai
                    </td>
                </tr>
                <tr>
                    <td>
                        Email :
                    </td>
                    <td>
                        oracle@gmail.com
                    </td>
                </tr>
                <tr>
                    <td>
                        PHONE :
                    </td>
                    <td>
                        9360110743
                    </td>
                </tr>
            </table>
        </div>
        <div>
            <h3 class="heading3">QUERIES</h3>
            <div class="queries">
                <table cellpadding="15px" cellspacing="15px" class="table2">
                    <tr>
                        <td>
 NAME :
                        </td>
                        <td>
                            <input type="name" placeholder="Enter your name"> 
                        </td>
                    </tr>
                    <tr>
                        <td>
                            EMAIL :
                        </td>
                        <td>
                            <input type="email" placeholder="Enter your E-mail">
                        </td>
                    </tr>
                    <tr>
                        <td>
                            MESSAGE :
                        </td>
                        <td>
                            <input type="text" placeholder="Enter your text">
                        </td>
                    </tr>
                    <tr>
                        <td colspan="2">
                            <input type="submit" style="background-color: white; color:#007cb9;">

                        </td>
                    </tr>
            </table>
        </div>
        
    </div>
</body>

</html>
```

## OUTPUT:
![web 1](https://github.com/vishal23000591/softweb/assets/147139719/b10c2223-e0d5-481a-9a05-510bb06300b8)
![web 2](https://github.com/vishal23000591/softweb/assets/147139719/19f068fe-a307-4f49-9c25-ecaed2dad822)
![web 3](https://github.com/vishal23000591/softweb/assets/147139719/aa1afcea-5ac4-4398-87eb-b8889c8d56ec)
![web 4](https://github.com/vishal23000591/softweb/assets/147139719/557e6da8-f274-495f-bbb8-32309f7af705)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
