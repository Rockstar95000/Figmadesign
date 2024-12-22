# Ex09 Event Registration Web Application
## Date: 21 / 12 / 2024

## AIM:
To design, develop and deploy a web application for event registration. 

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sports Event Registration</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
        }

        .section {
            display: flex;
            height: 100vh;
            color: white;
            text-align: center;
            flex-direction: column;
            justify-content: center;
            background-size: cover;
            background-position: center;
        }

        .login-section {
            background: url('background1.jpg') no-repeat;
        }

        .events-section {
            background: url('background2.jpg') no-repeat;
        }

        .form-section {
            background: url('background3.jpg') no-repeat;
        }

        .thankyou-section {
            background: url('background4.jpg') no-repeat;
        }

        .title {
            font-size: 32px;
            margin-bottom: 10px;
            font-weight: bold;
        }

        .subtitle {
            font-size: 16px;
            margin-bottom: 20px;
        }

        .button {
            background: linear-gradient(45deg, #f542dd, #4286f4);
            padding: 10px 20px;
            border: none;
            color: white;
            font-size: 18px;
            cursor: pointer;
            border-radius: 5px;
            margin: 10px;
        }

        .form-container {
            width: 60%;
            margin: 0 auto;
            padding: 20px;
            background: rgba(0, 0, 0, 0.6);
            border-radius: 10px;
        }

        input[type="text"], input[type="number"], input[type="email"] {
            width: 90%;
            padding: 10px;
            margin: 10px auto;
            display: block;
            border-radius: 5px;
            border: none;
        }

        footer {
            font-size: 14px;
            margin-top: 20px;
        }

    </style>
</head>
<body>
    <div class="section login-section">
        <h1 class="title">SAVEETHA ENGINEERING COLLEGE</h1>
        <h2 class="subtitle">Believe in Yourself!</h2>
        <button class="button">Login</button>
        <button class="button">Register</button>
    </div>

    <div class="section events-section">
        <h2 class="title">Sports Day Events</h2>
        <p>• Cricket<br>• Football<br>• Badminton<br>• Dodge Ball<br>• 100m, 200m, 300m<br>• 4*100 relay</p>
    </div>

    <div class="section form-section">
        <h2 class="title">Event Registration Form</h2>
        <div class="form-container">
            <input type="text" placeholder="Full Name">
            <input type="text" placeholder="Gender">
            <input type="number" placeholder="Age">
            <input type="text" placeholder="Register Number">
            <input type="text" placeholder="Department">
            <input type="text" placeholder="Mobile Number">
            <input type="email" placeholder="Email ID">
            <input type="text" placeholder="Events to Register">
            <button class="button">Register</button>
        </div>
    </div>

    <div class="section thankyou-section">
        <h2 class="title">Thank You...</h2>
        <p>We are eagerly waiting for your participation in the sports event!</p>
        <footer>
            Contact us: saveethaengineeringcollege@gmail.com <br>
            Phone: 6369183394
        </footer>
    </div>
</body>
</html>

```

## OUTPUT:
![alt text](<Screenshot 2024-12-18 115325.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
