# EX01 Developing a Simple Webserver
## Date:

## AIM:
To develop a simple webserver to serve html pages and display the list of protocols in TCP/IP Protocol Suite.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Import the necessary modules.

### Step 5:
Define a custom request handler.

### Step 6:
Start an HTTP server on a specific port.

### Step 7:
Run the Python script to serve web pages.

### Step 8:
Serve the HTML pages.

### Step 9:
Start the server script and check for errors.

### Step 10:
Open a browser and navigate to http://127.0.0.1:5500/First.html (or the assigned port).

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="simple.css">
    <style>
        body{
            background-color: hsla(184, 100%, 97%, 0.668);
        }
    </style>
    <style>
        body{
           background-image: url(img.jpg.jpeg);
           background-size: cover; 
           background-repeat: no-repeat;
           

        }
    </style>

</head>
<body> 
    <p style="color: rgba(242, 255, 0, 0.774); font-size: 30px;">This is an inline-styled paragraph.</p>

    <h1 id="texti">Fundamentals of web APPLICATIONS</h1>
    <h1 style="color: rgba(0, 174, 255, 0.748); font-size: 90px;">      HI HELLO EVERYONE       </h1>
    <h2 id="fontdesign">    FREAK IN GOOD    </h2>
    <h1 id="paddingmargin">      HI HELLO EVERYONE       </h1>
    <a href="registration.html">Register here</a>|
    <a href="home.html">Home</a>|
    <a href="aboutus.html">About us</a>|
    <a href="contact.html">Contact us here here</a>|
</body>
</html>
```

## OUTPUT:
![Screenshot 2025-03-24 205137](https://github.com/user-attachments/assets/dd25e3b2-391b-4e81-8a17-c1b5b2a87c79)


## RESULT:
The program for implementing simple webserver is executed successfully.
