# Ex04 Places Around Me
# Date:
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Map</title>
    <style>
        img{
            display: block;
            margin: auto;
            margin-top: 9%;
            border: 2px solid black;
        }
    </style>
</head>
<body>
    <img src="workplace.jpg" alt="Workplace" usemap="#workmap" width="400" height="379">

    <map name="workmap">
    <area shape="rect" coords="34,44,270,350" alt="Computer" href="https://www.google.com/search?q=computer">
    <area shape="rect" coords="290,172,333,250" alt="Phone" href="https://www.google.com/search?q=phone">
    <area shape="circle" coords="337,300,44" alt="Cup of coffee" href="https://www.google.com/search?q=cup+of+coffee">
    </map>
</body>
</html>
#OUTPUT
<img width="1900" height="849" alt="Screenshot (134)" src="https://github.com/user-attachments/assets/bf7e2ce8-d5db-4f65-b723-a48d00709a32" />
<img width="1809" height="918" alt="Screenshot (135)-1" src="https://github.com/user-attachments/assets/89460f92-71d2-499d-a369-a44284973d9d" />


<img width="1710" height="977" alt="Screenshot (136)" src="https://github.com/user-attachments/assets/47d8f236-3cf7-46af-b911-d3e709ff0225" />

# RESULT
The program for implementing image maps using HTML is executed successfully.
