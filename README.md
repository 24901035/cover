# Ex.06 Book Front Cover Page Design
## Date:16-11-2025

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
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <style type="text/css">
            .bookcover {
                width: 400px;
                height: 640px;
                color: rgb(16, 7, 7) (221, 39, 39);
                margin-left: auto;
                margin-right: auto;
                padding: 20px;
                font-family:Verdana, Geneva, Tahoma, sans-serif;
                background-image:url("noot.png");
                background-size: cover;
            }

            .insight {
                color: rgb(13, 13, 13) (221, 39, 39);
            }
            .hr1 {
                width: 130px;
                color: rgb(15, 15, 15) (221, 39, 39);
            }
            .h1 {
                font-size: 10px;
                font-family: Arial, Helvetica, sans-serif;
                text-align: center;
                position: relative;
                
                top: 30px;
                color: rgb(15, 14, 14) (221, 39, 39);
            }
            .para {
                font-size: medium;
                font-family: Arial, Helvetica, sans-serif;
                position: relative;
                top: 40px; 
                color: rgb(7, 7, 7) (221, 39, 39); 
            }
            .edition {
                font-size: large;
                font-family: Arial, Helvetica, sans-serif;
                color:rgb(9, 9, 9) (221, 39, 39);
                top: 225px;
                position: relative;
            }
            .pic {
                position: relative;
                top:280px;
                left: 250px;
                width: 100px;
                height: 100px;
                background-size: cover;
                color:rgb(15, 14, 14) (221, 39, 39);
            }
            .hr2 {
                position: relative;
                width: 400px;
                top: 325px;
                color:rgb(11, 11, 11) (221, 39, 39);
            }
            .name {
                font-size: medium;
                font-family: Arial, Helvetica, sans-serif;
                display: inline;
                position: relative;
                color:rgba(14, 14, 14, 0.852) (221, 39, 39);
                top: 310px;
            }
            .pub {
                font-size: large;
                position: relative;
                top: 280px;
                left: 330px;
                color:rgb(14, 14, 14) (221, 39, 39);
            }
        </style>
         <title> Book Front Cover Page  </title>
        </head>
        <body>
            <div class="bookcover">
                <div class="insight">
                        EXPERT INSIGHT
                </div>
                <div class="hr1">
                    <hr>
                </div>
                <div class="h1">
                    <h1> DEATH NOTE </h1>
                </div>
                <div class="para">
                    <p> The Mind is the Deadliest Weapon </p>
                    <p>Fear the Writer.</p>
                </div>
                <div class="pic">
                    <img src= "mohhan .jpg" width="150" height="150" >
                </div>
                <div class="hr2">
                    <hr>
                </div>
                <div class="name">
                    <p><b> MOHAN R </b></p>
                </div>
                <div class="pub">
                    <b> SEC </b>
                </div>
                <div class="edition">
                    <b> AUTHOR  </b>
                </div>
            </div>
        </body>
    </html>
```


## OUTPUT:
![alt text](<Screenshot 2025-11-16 122812.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
