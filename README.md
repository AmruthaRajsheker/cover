# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Clon the Github repositery and create a Django admin interface.

### Step 2:
Write HTML and CSS code for designing book cover page and execute them.
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
            color:crimson;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(/static/images/back.jpg);
            background-size: cover;
        }
            

        .insight{
            color: olivedrab;
        } 
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: purple;
            top:130px;
            left:40px;
            font-family:Georgia;
            font-size: large;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
            left: 20px;
        
        }
        .id {
            width:200px;
            position: relative;
            top:145px;
            left:40px;
        }
        .pub{
            font-size: medium;
            position: relative;
            top:130px;
            left:330px;
    
        }
        .ed{
            color:palevioletred;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:40px;
            left:40px;

        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:30px;
            left:150px;
        }
        .mypic{
            position: relative;
            top: 40px;
            left: 210px;
            width: 80px;
            height: 80px;
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
                <hr style="color: red;">
            </div>
            <div class="booktitle">
                <h1>The Power of </h1>
                <h1>Positive </h>
                <h1>Thinking !!!</h1>
                
            </div>
            <div class="subtitle">
                Over 100 copies sold :) 
            </div>
            <div class="mypic">
                <img src="/static/images/my.jpg" width="150" height="170" alt="">
            </div>
            <div class="id">
                <hr style="color: indigo;">
            </div>
            <div class="author">
               <p><b>Amrutha Rajsheker</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>The Ultimate Edition</b>
            </div>
        </div>
    </body>
</html>
```
## Output:
![output](/cover.png)

## HTML Validator:
![validator](/valid.png)

## Result:
The program for designing book cover page using HTML and CSS is executed successfully.
