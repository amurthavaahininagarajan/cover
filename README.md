# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

## Step 1:
Create a new Django project and app.

## Step 2:
Create a static file directory and mention the changes in settings.

## Step 3:
Make a new folder templates inside your app and create a html and map them using views and url.

## Step 4:
Write down the code for book cover using HTML and CSS.

## Step 5:
Add images and other contents using CSS record a screenshot of it.

## Code:
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
            background-color: #3d3a3a;
            color:white;
            margin-left: auto;
            margin-right: auto;
            padding: 50px;
            font-family: 'Franklin Gothic Heavy', 'Arial Narrow', Arial, sans-serif;
            background-image: url(/static/images/cover.jpg);
            background-size: cover;
        }
            

        .toptext{
            color:white;

        }

        
        .tophr{
            width:140px;
        }
        .author{
            color: white;
            display: inline;
            position: relative;
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Franklin Gothic Heavy', monospace;
            font-size: 25px;
            text-align: left;
            position: relative;
            top: 30px;
        
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
            color:red;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;

        }
        .subtitle{
            font-family:T'Franklin Gothic Heavy';
            font-size: large;
            position: relative;
            top:40px;
        }
        .photo{
            position: relative;
            top: 175px;
            left: 300px;
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
                SEC INSIGHT
            </div>
            <div class="tophr">
                <hr style="color: red;">
            </div>
            <div class="booktitle">
                <h1>IT ENDS WITH US</h1></div>
            <div class="subtitle">
                 Fiction
            </div>
            <div class="photo">
                <img src="/static/images/author.jpg" width="100" height="110" alt="">
            </div>
            <div class="id">
                <hr style="color: orange;">
            </div>
            <div class="author">
               <p><b>Amurtha Vaahini</b></p>
            </div>
            <div class="publisher">
                PACKT
            </div>
            <div class="edition">
                <b>First Edition</b>
            </div>
            
        </div>
    </body>
</html>
```

## Output:
![Screenshot (45)](https://user-images.githubusercontent.com/118679102/215015374-8620c82c-6fe7-4ddc-adf6-de9d485b4896.png)


## Result:
Thus the program is developed to display book cover page
