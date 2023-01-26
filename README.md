# Ex-06-Book-Cover-Design

# AIM:
To develop a website to display the cover page design of a book

# Design Steps:
## Step 1:
Create a Django Project using Django commands.

## Step 2:
Create Django app and Create Static html file and write the html code for creating a bookcover

## Step 3:
Use CSS to design the book cover and upload it to the github account

## Code:
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta name="viewport"
content="width=device-width,initial-scale=1.0">
<style>
.bookpage {
    width: 400px;
    height: 600px;
    color: red;
    margin-left: auto;
    margin-right:auto;
    padding: 20px;
    font-family:'FranklinGothicMedium','ArialNarrow',Arial,sans-serif;
    background-image: url(download.jpeg);
    background-size: cover;
}
.insight {
    color: brown;
}
.author {
    color: white;
    display: inline;
    position: relative;
    color: aqua;
    top: 190px;
    font-family: Georgia;
    font-size: medium;
}
.booktitle {
    font-family: 'Courier New',Courier,monospace;
    font-size: larger;
    text-align:center;
    position: relative;
    top: 30px;
}
.id {
    width: 400px;
    position: relative;
    top: 180px;
}
.pub {
    font-size: medium;
    position: relative;
    top: 155px;
    left: 330px;
}
.ed {
    color: blue;
    font-size: medium;
    font-family: Verdana;
    position: relative;
    top: 85px;
}
.subtitle {
    font-family: Tahoma;
    font-size: large;
    position: relative;
    top: 40px;
}
.mypic {
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
        <hr style="color:red;"> 
    </div>
    <div class="booktitle">
        <h1>Fundamentals of Web Application Development</h1></div>
        <div class="subtitle">
            HTML and CSS Combined with Django Architecture
        </div>
        <div class="mypic">
            <img src="./Photo.jpg" width="130" height="145" alt="">
        </div>
        <div class="id">
            <hr style="color: orange;">
        </div>
        <div class="author">
            <p><b>By Jude Sam J</b></p>
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
![OUTPUT](./static/Image/BookCover1.png)

## Result:
The Program is executed Successfully.