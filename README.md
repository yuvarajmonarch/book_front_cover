# Ex.06 Book Front Cover Page Design
## Date : 19-06-2025
## Name : YUVARAJ B
## Reg No : 212222040186

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
<html>
<head>
  <title>Book Cover</title>
</head>
<body style="margin: 0; padding: 0; background: #fff; display: flex; justify-content: center; align-items: center; height: 100vh; font-family: Arial, sans-serif;">

  <div style="position: relative; width: 400px; height: 600px; background: url('cover.png') center/cover no-repeat; border-radius: 12px; overflow: hidden; box-shadow: 0 4px 15px rgba(0,0,0,0.2);">

    <!-- Overlay -->
    <div style="position: absolute; inset: 0; background: rgba(0, 0, 0, 0.5); padding: 20px; color: white; box-sizing: border-box;">

      <!-- Title -->
      <h1 style="font-size: 24px; font-weight: bold; margin-top: 10px; line-height: 1.3;">
        WEB DESIGNING <br> USING <br> HTML AND CSS
      </h1>

      <!-- Description -->
      <p style="font-size: 12px; margin-top: 100px; line-height: 1.4;">
        Learn the basics of web designing with this easy guide. Build cool websites using HTML and CSS with hands-on examples.
      </p>

      <!-- Author Info -->
      <div style="position: absolute; bottom: 20px; right: 20px; text-align: right;">
        <img src="photo.jpg" alt="Author" style="width: 70px; height: 70px; border-radius: 50%; border: 2px solid #fff;">
        <p style="font-size: 14px; font-weight: bold; margin: 10px 0 0;">
          YUVARAJ B<br>212222040186
        </p>
      </div>

    </div>

  </div>

</body>
</html>
```

## OUTPUT:

![output](https://github.com/user-attachments/assets/dc729c58-8784-4a54-8d9c-5c7cf2913c47)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
