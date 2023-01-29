# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Clone the github repository and create a django admin interface.
### Step 2:
write HTML and CSS code for designing book cover page and execute them.
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
            background-image: url(/static/images/wallpaper.jpeg);
            background-size: cover;
        }
            

        .insight{
            color: blue;

        }

        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: purple;
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
        .pub{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color:orange;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;

        }
        .subtitle{
            font-family:Tahoma;
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
                <hr style="color: red;">
            </div>
            <div class="booktitle">
                <h1>Coding for beginners</h1></div>
            <div class="subtitle">
                C,C++,Python and more.
            </div>
            <div class="mypic">
                <img src="/static/images/tara.jpg" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: indigo;">
            </div>
            <div class="author">
               <p><b>"Tharika"</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>Seventh Edition</b>
            </div>
        </div>
    </body>
</html>
```

## Output:

![out](https://user-images.githubusercontent.com/119475507/215304641-86187129-4a5a-49ba-ad6f-d39331f5f606.png)

## Home validator:

![valid](https://user-images.githubusercontent.com/119475507/215304672-77a31bf8-c7e2-4eee-bf9d-51d21e545312.png)

## Result:
The program for designing book cover page using HTML and CSS is executed successfully.
