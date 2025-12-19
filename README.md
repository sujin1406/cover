# Ex.06 Book Front Cover Page Design
## Date:

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
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>BOOK COVER PAGE</title>

<style>
body{
    margin: 0;
    background: #eaeaea;
    font-family: Arial, sans-serif;
}

/* Book container */
.bookpage{
    width: 400px;
    height: 600px;
    margin: 40px auto;
    padding: 25px;
    background-image: url("../images/bg.jpg");
    background-size: cover;
    background-position: center;
    position: relative;
    box-shadow: 0 0 15px rgba(0,0,0,0.3);
    box-sizing: border-box;
}

/* Top label */
.insight{
    font-size: 14px;
    font-weight: bold;
    color: brown;
}

/* Small red line below SEC INSIGHT */
.top-line{
    width: 80px;
    border: 1px solid red;
    margin: 6px 0 15px 0;
}

/* Title block above image */
.title-block{
    text-align: center;
    margin-bottom: 20px;
}

.booktitle{
    font-size: 22px;
    font-weight: bold;
    color: #c0392b;
    line-height: 1.9;
}

.subtitle{
    margin-top: 10px;
    font-size: 15px;
    color: #333;
    line-height: 2.0;
}

/* Profile image */
.mypic{
    position: absolute;
    right: 25px;
    bottom: 150px;
}

.mypic img{
    width: 120px;
    height: 135px;
    border: 2px solid #555;
    object-fit: cover;
}

/* Edition (above bottom line) */
.edition{
    position: absolute;
    bottom: 125px;
    left: 25px;
    color: blue;
    font-weight: bold;
}

/* Bottom line */
.bottom-line{
    position: absolute;
    bottom: 110px;
    left: 25px;
    width: 350px;
    border: 1px solid orange;
}

/* Bottom text */
.author{
    position: absolute;
    bottom: 70px;
    left: 25px;
    color: red;
    font-weight: bold;
}

.pub{
    position: absolute;
    bottom: 70px;
    right: 25px;
    font-weight: bold;
}
</style>
</head>

<body>

<div class="bookpage">

    <div class="insight">SEC INSIGHT</div>
    <hr class="top-line">

    <!-- TITLE ABOVE IMAGE -->
    <div class="title-block">
        <div class="booktitle">
            FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT
        </div>
        <div class="subtitle">
            HTML and CSS Combined with Django Architecture
        </div>
    </div>

    <!-- PROFILE IMAGE -->
    <div class="mypic">
        <img src="../images/pro.jpg" alt="profile">
    </div>

    <!-- EDITION ABOVE LINE -->
    <div class="edition">SEVENTH EDITION</div>

    <!-- BOTTOM LINE -->
    <hr class="bottom-line">

    <!-- BOTTOM TEXT -->
    <div class="author">SUJIN</div>
    <div class="pub">SEC</div>

</div>

</body>
</html>
```

## OUTPUT:
<img width="1920" height="1080" alt="Screenshot 2025-12-19 185138" src="https://github.com/user-attachments/assets/344884a0-1739-4b00-8caf-860270e268e9" />


## HTML VALIDATOR:
<img width="1920" height="1080" alt="Screenshot 2025-12-19 185815" src="https://github.com/user-attachments/assets/f6f80b7c-cbd6-4937-961a-2ed265f5bf40" />


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
