# Book CoverPage Design
# AIM:
To design a static web site for a book cover page.
# DESIGN STEPS:
## Step 1:
Clone repository from github then create django project with name bookcover inside it and in bookcover create app with name design. 
## Step 2:
In settings.py make changes in Allowed_host as '*' and in installed_apps include your app name.
## Step 3:
Then in design app create templates folder and in this create one more folder with name of your app design.
## Step 4:
In this create html file in design folder inside templates.
## Step 5:
Now makemigrations and migrate all files and runserver
## Step 6:
Validate the HTML and CSS code.
## Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 700px;
            background-color: #3d3a3a;
            color:white; 
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(/static/images/back1.jpg);
            background-size: cover;
        }
            

        .toptext{
            color:white;

        }

        
        .tophr{
            width:140px;
            background-color:red;
        }
        .author{
            color: white;
            display: inline;
            position: relative;
            color:white;
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .publisher{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .edition{
            color:orange;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:65px;

        }
        hr{
            color:orange;
            border-color:orange;
        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position: relative;
        }
        .photo{
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
            <div class="toptext">
                EXPERT INSIGHT
            </div>
            <div class="tophr">
                <hr style="color: red;">
            </div>
            <div class="booktitle">
                <h1>Responsive Web Design With HTML5 and CSS</h1></div>
            <div class="subtitle">
                Develop future-proof responsive websites using the latest HTML5 and CSS Techniques
                <img src="/static/images/black2.jpeg" width="400" height="120" alt="">
            </di>
            <div class="photo">
                <img src="/static/images/elon.jpeg" width="130" height="120" alt="">
            </div>
            <div class="id">
                <hr style="color: red; background-color:red;">
            </div>
            <div class="author">
               <p><b>Shaik Shoaib Nawaz</b></p>
            </div>
            <div class="publisher">
                Packt>
            </div>
            <div class="edition">
                <b>Third Edition</b>
            </div>
            
        </div>
    </body>
</html>
```
# OUTPUT :
![output](./bookcover.png)
# HTML Validation:
![output](./cover.png)

# Result:
Thus the static web site for a book cover page is successfully developed