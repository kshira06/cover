# Ex.06 Book Front Cover Page Design
## Date: 02-05-2025

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
<html>

<head>
    <title>Book cover</title>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: ' Arial, sans-serif';
            background-image:"photo.jpeg";
            background-size: cover;
        }
            
        
        .insight{
            color:rgb(76, 169, 169);
        
        }
        
        
        .hrstyle{
            width:400px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:rgb(13, 125, 230);
            top:100px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:rgb(199, 22, 22);
            font-family: Roquen;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 40px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:90px;
            left:-5px;
            
        }
        .subtitle{
            color:rgb(16, 228, 228);
            font-family:unicorn;
            font-size: larger;
            position: relative;
            top:100px;
        }
        .mypic{
            position: relative;
            top: 200px;
            left: 260px;
            width: 90px;
            height: 80px;
            background-size:contain;
        }
        body {
            background-image: url("book cover background image.jpg");
            background-size:contain; /* or contain */
            background-position:center;
            background-repeat: no-repeat;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
                LIFE
            </div>
            <div class="hrstyle">
                <hr style="color:rgb(16, 116, 230)">
            </div>
            <div class="booktitle">
                <h1 style="font-family: cursive; color:rgb(16, 13, 5);">UNIVERSE <BR> AND ME</h1></div>
            <div class="subtitle" style="text-align: center;color: rgb(214, 29, 103);">
                 FANTASIES 
            </div><br>
            <div class="subtitle" style="color: rgb(17, 5, 62);text-align: center;">
                 EDITION 1
            </div>

            <div class="mypic">
                <img src= "123.jpg" width="120" height="100" >
            </div>
            <div class="id">
                <hr style="color:rgb(238, 17, 68)">
            </div>
            <div class="author">
               <p><b>KSHIRA <br> ICT PUBLICATIONS</b></p>
            </div>

        </div>
        </body>
        

</html>
```

## OUTPUT:

![alt text](<Screenshot 2025-05-02 130526.png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
