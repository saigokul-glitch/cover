# Ex.05 Book Cover Page Design
## Date:12.12.2025

## AIM:
To design a book back cover page using HTML and CSS.

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
cover.html

<html>
<head>
    <title>Book Cover</title>
    <link href="styles.css" rel="stylesheet">
</head>

<body>

<div class="box">
    <h2>About the Book</h2>
    <hr>

    <p>
        This book,<b>"Objectives Of Machine Learning"</b>this tells about the 
        features of machine learning in tech field
         Machine learning is a field of computer science that enables systems
         to learn from data and improve with experience.
         It focuses on building models that can recognize patterns, make predictions,
         and support decision-making.
         Instead of being explicitly programmed, ML systems adapt their behavior based on the
         information they receive.
         The main goal of machine learning is to create intelligent solutions 
         that become more accurate over time.


    <div class="motto">
        "Objectives Of Machine Learning --- is not just a objective it's a evolution "
    </div>

    
    <div class="Narrator">
        <img src="c:\Users\acer\Downloads\img 1.png.jpeg" alt="Narrator Photo">

        <p>
            <b>Saigokul.k (25004959)</b><br>
            <br>
            "As a developing graduate and evolving with the technologic field"
            

        </p>
    </div>

    <div class="footer">
        <div>KNS Publishers<br>Printed in India</div>
        <div><b>Price: $399</b></div>
    </div>

</div>

</body>
</html>

styles.css

body {
    font-size: arial;
    background: linear-gradient(to bottom, orange, violet);
}

.box {
    height: 650px;
    width: 400px;
    background-image: url(bg.jpg);
    background-size: cover;
    color: white;
    padding: 10px;
    margin: 20px auto;
    border: 3px solid cyan;
    border-radius: 12px;
}

.motto {
    background: slateblue;
    padding: 11px;
    border-left: 3px solid burlywood;
    margin: 18px 0;
    font-style: arial;
    text-align: center;
    border-end-end-radius: 12px;
}

.Narrator {
    display: flex;
    gap: 14px;
    background: goldenrod;
    padding: 11px;
    border-start-end-radius: 7px;
}

.Narrator b {
    color: lime;
}

.Narrator img {
    width: 110px;
    height: 110px;
    border-radius: px;
}

.footer {
    background: green;
    color: black;
    padding: 12px;
    display: flex;
    justify-content: space-between;
    margin-top: 80px;
    border-end-end-radius: 7px;
}

```



## OUTPUT:
![alt text](<Screenshot (35).png>)


## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
