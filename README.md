# Ex04 Places Around Me
## Date: 

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```map.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Image Map Example</title>
</head>
<body>

  <!-- Image with clickable areas -->
  <img src="Screenshot 2025-09-22 161744.png" alt="Interactive Map" usemap="#image-map">

  <!-- Define the map areas -->
  <map name="image-map">
    <area target="_blank" alt="kalanivasal" title="kalanivasal" href="kalanivasal.html" coords="787,113,996,216" shape="rect">
    <area target="_blank" alt="koviloor" title="koviloor" href="koviloor.html" coords="302,243,491,327" shape="rect">
    <area target="_blank" alt="the bangala" title="the bangala" href="the bangala.html" coords="610,640,823,723" shape="rect">
    <area target="_blank" alt="pon nagar" title="pon nagar" href="pon nagar.html" coords="1379,432,1549,528" shape="rect">
  </map>

</body>
</html>

kalanivasal
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kalanivasal</title>
  <style>
    body {
      background-color: lightcoral;
      font-family: Arial, sans-serif;
      color: white;
      text-align: center;
      padding: 50px;
    }
  </style>
</head>
<body>
  <h1>Welcome to Kalanivasal</h1>
  <p>This is the Kalanivasal page.</p>
</body>
</html>



koviloor

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Koviloor</title>
  <style>
    body {
      background-color: lightseagreen;
      font-family: Arial, sans-serif;
      color: white;
      text-align: center;
      padding: 50px;
    }
  </style>
</head>
<body>
  <h1>Welcome to Koviloor</h1>
  <p>This is the Koviloor page.</p>
</body>
</html>

pon nagar

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pon Nagar</title>
  <style>
    body {
      background-color: goldenrod;
      font-family: Arial, sans-serif;
      color: white;
      text-align: center;
      padding: 50px;
    }
  </style>
</head>
<body>
  <h1>Welcome to Pon Nagar</h1>
  <p>This is the Pon Nagar page.</p>
</body>
</html>


the bangala

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>The Bangala</title>
  <style>
    body {
      background-color: lightslategray;
      font-family: Arial, sans-serif;
      color: white;
      text-align: center;
      padding: 50px;
    }
  </style>
</head>
<body>
  <h1>Welcome to The Bangala</h1>
  <p>This is The Bangala page.</p>
</body>
</html>


```





## OUTPUT
![alt text](<Screenshot 2025-09-24 113910.png>)
![alt text](<Screenshot 2025-09-24 113933.png>)
![alt text](<Screenshot 2025-09-24 114119.png>)
![alt text](<Screenshot 2025-09-24 114133.png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
