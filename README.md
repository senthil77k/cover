# Ex.06 Book Front Cover Page Design
## Date:
10.04.24
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
```
<!DOCTYPE html>
<html lang="en">
   <head>
        <meta name="viewport" 
        content="width=device-width, initial-scale=1.0">
        <style>

       .bookpage{
           width: 400px;
           height: 600px;
           color:rgb(0, 0, 124);
           margin-left: auto;
           margin-right: auto;
           padding: 20px;
           font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
           background-image: url(./gg.jpg);
           background-size: cover;
       }
           

       .insight{
           color: rgb(255, 111, 0);

       }

       
       .hrstyle{
           width:100px;
       }
       .author{
       
           display: inline;
           position: relative;
           color: rgb(202, 119, 246);
           top:190px;
           
           font-family:Georgia;
           font-size: medium;
       }
       .booktitle{
           font-family: 'Courier New', Courier, monospace;
           font-size: larger;
           text-align: center;
           position: relative;
           top: 30px;
       
       }
       .id {
           width:400px;
           position: relative;
           top:180px;
           
       }
       .ed{
           color: rgb(7, 139, 86);
           font-size: medium;
           font-family: Verdana;
           position:relative;
           top:85px;

       }
       .subtitle{
           color:rgb(18, 30, 255);
           font-family:Verdana;
           font-size: large;
           position: relative;
           top:40px;
       }
       .mypic{
           position: relative;
           top: 135px;
           left: 260px;
           width: 100px;
           height: 100px;
           background-size: cover;
       }
       
       </style>
       <title>Book Cover Page</title>
   </head>
   <body>
       <div class="bookpage">
           <div class="insight">
               SEC INSIGHT
           </div>
           <div class="hrstyle">
               <hr style="color: rgb(238, 20, 31);">
           </div>
           <div class="booktitle">
               <h1>Fundamentals of web application</h1></div>
           <div class="subtitle">
            Building the Foundation: how web application is contributed as front end tool
           </div>
           <div class="mypic">
               <img src="./vvv.jpg" width="125" height="150" alt="">
           </div>
           <div class="id">
               <hr style="color: rgb(34, 26, 2);">
           </div>
           <div class="author">
              <p><b>senthil kumaran C (212223220103)</b></p>
           </div>
           <div class="ed">
               <b>Third Edition</b>
           </div>
       </div>
   </body>
</html>
```

## OUTPUT:
![sk](https://github.com/senthil77k/cover/assets/148571479/352223ff-42cd-48b9-90c3-1a40c2f5fc7f)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
