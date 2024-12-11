# Ex.07 Restaurant Website
# Date: 08.11.2024
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vintage Restaurant</title>
    <link rel="icon" href="icon 1.jpg">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }

        nav {
            padding: 20px;
            background-color: #8cf1a0;
            color: #c00d55;
            display: flex;
            align-items: center;
            flex-wrap: wrap;
            justify-content: space-between;
        }

        nav h1 {
            font-size: 50px;
            margin: 0;
            color: #444;
        }

        nav h3 {
            margin: 5px 20px;
            font-size: 16px;
            color: #333;
        }

        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
        }

        nav li {
            display: inline;
            margin: 0 15px;
            color: #555;
            font-weight: bold;
            cursor: pointer;
            transition: color 0.3s;
        }

        nav li:hover {
            color: #c00d55;
        }

        nav .box {
            background-color: #ff7043;
            color: white;
            padding: 10px 20px;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            transition: background-color 0.3s, transform 0.2s;
        }

        nav .box:hover {
            background-color: #e64a19;
            transform: scale(1.05);
        }

        .searchbar {
            display: flex;
            justify-content: center;
            margin: 30px 0;
        }

        .searchbar input {
            width: 50%;
            padding: 10px;
            border: 2px solid #ccc;
            border-radius: 5px;
            font-size: 16px;
            outline: none;
        }

        .searchbar input:focus {
            border-color: #8cf1a0;
            box-shadow: 0 0 8px rgba(140, 241, 160, 0.5);
        }

        h2 {
            text-align: center;
            font-size: 36px;
            color: #333;
            margin-bottom: 20px;
        }
        .con{
            display: inline-flex;
        }

        .img {
            flex:  1;
            margin: 20px auto;
            width: 500px;
            padding: 20px;
            border: 2px solid #ccc;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            background-color: #ffffff;
        }

        .img img {
            width: 100%;
            border-radius: 5px;
        }

        .img h3 {
            text-align: center;
            color: #444;
        }

        .img p {
            color: #666;
            font-size: 16px;
            line-height: 1.6;
            text-align: justify;
        }

        .img a {
            
            margin-top: 10px;
            text-decoration: none;
            color: white;
            background-color: #c00d55;
            padding: 10px 20px;
            border-radius: 5px;
            transition: background-color 0.3s, transform 0.2s;
        }

        .img a :hover {
            background-color: #a30945;
            transform: scale(1.05);
        }

        footer {
            background-color: #333;
            color: #fff;
            padding: 20px 10px;
            text-align: center;
            line-height: 1.6;
        }

        footer .info {
            margin: 20px auto;
            border: 2px dashed #8cf1a0;
            padding: 20px;
            width: fit-content;
        }

        footer p {
            margin: 10px 0;
            color: #ccc;
            font-size: 14px;
        }

        
    </style>
</head>

<body>
    <nav>
        <div>
            <h1>Vintage Restaurant</h1>
            <h3>Opening Hours 🕥: 10.00 am - 11.00 pm</h3>
        </div>
        <img src="restaurant image 1.jpg" alt="Restaurant" width="150px" height="120px">
        <ul>
            <li>MENU |</li>
            <li>RATINGS |</li>
            <li>BLOG |</li>
            <li>COUPON |</li>
        </ul>
        <a class="box" href="order.html">ORDER NOW!!!</a>
    </nav>

    <div class="searchbar">
        <input placeholder="Search for dishes, offers, or events">
    </div>

    <h2>Food Menu</h2>
    <div class="con">
        <div class="img">
            <img src="restaurant image 2.jpg" alt="Reservation">
            <h3>Reservation</h3>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Corrupti placeat minima recusandae cumque
                distinctio maiores porro ratione alias minus est praesentium.</p>
            <a href="file:///D:/Web%20Application/Restaurent%20Website/reservation.html">Book Now</a>
        </div>

        <div class="img">
            <img src="restaurant image 4.jpg" alt="Menu">
            <h3>Menu</h3>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Eligendi voluptates voluptatem nam tempora eius
                consequatur nisi error maiores.</p>
            <a href="file:///D:/Web%20Application/Restaurent%20Website/restaurant%20menu.html">View Menu</a>
        </div>

        <div class="img">
            <img src="restaurant image 3.jpg" alt="About Us">
            <h3>About Us</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatum ducimus ratione odit earum esse
                ullam, magnam perferendis rerum quisquam repellat.</p>
        </div>
    </div>
    <footer>
        <div>+91 733921961</div>
        <div>vinatgerestaurent@gmail.com</div>
        <div>Saveetha Nagar, Sriperumbudur</div>
        <div class="info">
            Visit us for an unforgettable dining experience!
        </div>
        <p>&copy; 2024 Vintage Restaurant | All Rights Reserved</p>
    </footer>
</body>

</html>
```
# OUTPUT:
![image](https://github.com/user-attachments/assets/8ea24edf-14c9-4b17-b912-b5dc80a461a6)
![image](https://github.com/user-attachments/assets/f862e9a4-294b-488c-a39b-dbbe75a84ce3)

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
