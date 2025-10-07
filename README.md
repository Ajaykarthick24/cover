# Ex.06 Book Front Cover Page Design
## Date:07/10/2025

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
'''
book.html

<html>
    <head>
        <title>MyBook
        </title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <div class="page">
            
            <div class="insights">
                SEC Insights
            </div>
            <div class="hr">
                <hr>
            </div>
            <div class="title">
                THE ROLE OF TECHNOLOGY IN MORDERN EDUCATION
            </div>
            <div class="subtitle">
              Transforming Learing Through Innovation, Accessibility, and personalized Experience.<br>
              
            </div>
            <div class="edit">
            UNIQUE EDITION
             </div>
             <br><hr>
              <div class="name">
                By Ajay karthick M
                </div>
                <div class="bottom">
                    SEC
                </div>
            <div class="pic">
            </div> 
        </div>
    </body>
</html>

style.css

body{
    display: flex;
    justify-content:center;
    align-items: center;
    height: 100vh;
}
.page{
    width: 500px;
    height: 700px;
    background-image: url(bg.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    border: 20px solid blanchedalmond;
    padding:20px;
    box-sizing:border-box;
    background-clip: padding-box;
    position: relative;
       
}

.insights{
   color: yellow;
    font-size: 18px;
   font-weight: bold;
   margin-bottom: 10px;
}
.hr{
    color: whitesmoke;
    width: 120px;
    right: 200%;
    

}
.title{
    color: red;
    font-size: 45px;
     margin: 13px 0 15px 0;
     font-style: italic;
    
   font-weight: bold;
    text-align: center;
    
}
.subtitle{
    color: goldenrod;
    font-size: 18px;
    margin-bottom: 100px;
    font-style: oblique;
}
.edit{
    color: hotpink;
    font-size: 18px;
    font-weight: bold;
    margin-top: 200px;
}
.name{
    color: moccasin;
    font-size: 16px;
    font-weight: bold;
    margin-top: 5px;
   
}
.bottom{
    color: sandybrown;
    position: absolute;
    bottom: 60px;
    right: 60px;
    font-weight: bold;
}
.pic{
    position: absolute;
    bottom:90px;
    left: 75%;
    width: 100px;
    height:100px;
    background: url(ak.jpg) no-repeat;
    background-size: 80px;

}
'''

## OUTPUT:
![alt text](<Screenshot 2025-10-07 134605.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
