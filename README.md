# EXPERIMENT-2 CREATING A COMMERCIAL WEBSITE USING HTML & CSS
## AIM:
To create a commercial website using html and css.

## SOFTWARE:
Visual Studio Code.

## ALGORITHM:
1) Create a new HTML file and save it with a .html extension.Begin with the basic structure by adding the <!DOCTYPE html> declaration at the top.
2) Set up the Head:

       Inside the <head> element, add the <title> element and give it a meaningful title for your website.
       Link your CSS file by adding the <link> element with the rel attribute set to "stylesheet" and 
       the href attribute pointing to your CSS file.

3) Develop the Content:

        Divide the main content area into sections using appropriate HTML elements like <section>, <div>, or <article>.
        Use headings <h1> to <h6> to structure your content hierarchically.
        Incorporate text, images, videos, and other media within the content sectionS

4) Style with CSS:

  Create a new CSS file and save it with a .css extension.
  Select the elements you want to style using CSS selectors.
  Apply styles using properties and values. 
  For example, you can change colors, fonts, sizes, margins, and padding.

5) Find a web hosting provider to host your website online.
Upload your HTML, CSS, and any other necessary files to the hosting server.

6) Test your website again after deployment to ensure it works as intended.
  
## PROGRAM:
  
### HTML CODE:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Foodka</title>
    <link rel="stylesheet" type="text/css" href="./style.css">
</head>
<body style="background-color: rgb(129, 159, 236);">
    
    <nav>
        <h2 class="logo">Food<span>ka</span></h2>
        <ul>
            <li><a href = "#">Home</a></li>
            <li><a href = "#">About</a></li>
            <li><a href = "#">catalog</a></li>
            
        </ul>
        <a href="#" class="btn">ORDER NOW</a>   
    </nav>
    <div style="padding-left: 150px;">
        <div class="content">
            <img src="burger.png" style="float: right;height: 300px; padding-right: 150px; 
            border-radius: 25px;">
            <p><b>Quality food </b><br> <B>Delivered !</B></p>
        </div>
    </div>
        <div style="padding-left: 150px;">
            <abt style="font-family:Arial, Helvetica, sans-serif;font-size: 22px;line-height: 29px;">A hamburger, or simply burger, is a sandwich consisting of fillings—usually 
                <br>a patty of ground meat, typically beef—placed inside a sliced bun or bread roll.
                <br>Hamburgers are often served with cheese, lettuce, tomato,
                <br> condiments such as ketchup, mustard, mayonnaise</abt></div>
            <br>
        <br>
        <br>
        <div style="padding-left: 150px;"><a href="#" class="btn">GET STARTED</a> </div> 
           <br>
            <br>
            <br>
            <br>
            <div style="padding-left: 150px;">
                <img src="dosa2.png" style="float: left;height: 300px;border: none;"></div>
    <div class="content">
        <p style="white-space:pre-wrap;text-align: left;"><b> Traditional Vegetarian Food</b></p>
        
    </div>
       <abt style="font-family:Arial, Helvetica, sans-serif;font-size: 22px;line-height: 29px;">Vegetarian food is good for health and that's what we provide<br> here in FoodKa, as we focus on customers health before<br>
    money reaches the table </abt>
<br>
<br>
<br> <div style="padding-left: 1200px; padding-top: 80px;"><a href="#" class="btn2">Order Veg Food</a></div>
<div style="padding-bottom: 100px;">    
<div class="service">
        <div class="title">
         <center>   <h4>Our Happy Customers</h4></center>
         <img src="french.jpg" style="float: left; width: 280px; height: 300px">
        </div>
        <div style="padding-right: 200px;">
            <div class="box" style="border-radius: 25px;">
                <div class="card" style="border-radius: 25px">
                
                    <h5><b>Andrew Banks</b></h5>
                    <div class="pra">
                    <p >"I dont always clop,but when I do,its because of food. Wow what great food has just
                    not let me leave the store until now for this very minute"
                    </p> 
                    <p style="text-align: center;">
                    
                    </p>
                </div>
            </div>
            <div class="card" style="border-radius: 25px">
                
                <h5>John Morrison</h5>
                <div class="pra">
                   <p >The food here is one of the human to eat but when I do,it's because of food.Wow what 
                    great food has just not let me to leave the store until now for this very minute.
                   </p> 
                   <p style="text-align: center;">
                     
                </p>
                </div>
            </div>
        </div>   
        </div>
    </div> 
</div>

</body>
</html>
```      

### CSS CODE:
```      
*{
    border: 2px slid black;
}
span{
    color: rgb(228, 223, 249);
}
nav{
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding-top: -2px;
    padding-left: 8%;
    padding-right: 8%;
}
.logo{
    color: black;
    font-size: 50px;
    letter-spacing: 1px;
    cursor: pointer;
}
nav ul li{
    list-style-type: none;
    display: inline-block;
    padding: 10px 25px;
}
nav ul li a{
    color:  black;
    text-decoration: none;
    font-weight: bold;
    text-transform: capitalize;
}
nav ul li a:hover{
    color: grey;
    transition: .4s;
}
.btn{
    background-color: rgb(27, 3, 98);
    color: rgb(255, 252, 249);
    text-decoration: none;
    border: 2px solid transparent;
    font-weight: bold;
    padding: 10px 25px;
    border-radius: 30px;
    transition: transform .4s;
}
.btn:hover{
    transform: scale(1.2);
}
.btn2{
    background-color: black;
    color: rgb(245, 243, 245);
    text-decoration: none;
    border: 2px solid transparent;
    font-weight: bold;
    padding: 10px 25px;
    border-radius: 30px;
    transition: transform .4s;
}
.about{
    width: 100%;
    padding: 100px 0px;
    background-color: #191919;
}
.about img{
    height: 300px;
    float: left;
    
}
.about-text{
    width: 550px;

}
.main{
    width: 1130px;
    max-width: 95%;
    margin: 0 auto;
    display: flex;
    align-items: center;
    justify-content: space-around;
}
.about-text h5{
    color: black;
    letter-spacing: 2px;
    font-size:22px;
    margin-bottom: 25px;
    text-transform: capitalize;
}
.about-text p{
    color: black;
    letter-spacing: 1px;
    line-height: 29px;
    font-size: 18px;
    margin-bottom: 45px;
}

.menu{
    display: flex;
    justify-content: space-around;
    
}
a{
    color: black;
    font-size: 20px;
}
.content{
    color: black;
    font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-size: 50px;

}
.service{
    background: rgb(244, 243, 239);
    width: 100%;
    padding: 100px 10px;
}
.title h4{
    color: black;
    font-size: 50px;
    width: 1130px;
    text-align: center;
}
.box{
    display: flex;
    justify-content: center;
    align-items: center;
    height: 400px;
    
    float: right;
    overflow: hidden;
background-color: rgb(61, 3, 87);

}
.card{
    height: 230px;
    width: 335px;
    padding: 20px 35px;
    background: whitesmoke;
    margin: 15px;
    position: relative;
    overflow: hidden;
    text-align: center;
}
h5{
    color: rgb(27, 7, 91);
    font-size: 25px;
    margin-bottom: 15px;
}
.pra p{
    color: rgb(110, 68, 13);
    font-size: 16px;
    line-height: 27px;
    margin-bottom: 25px;
 }
 .footer{
    width: 100%;
    background-color: black;
    background-size: cover;
}
```
## OUTPUT:
<img width="448" alt="comm op" src="https://github.com/divvisha/COMMERCIAL-WEBSITE/assets/127508123/4ace9064-ce49-45db-b84f-06c0b6a7029c">


## RESULT:
Thus the website is created.
