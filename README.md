# Ex.06 Book Front Cover Page Design
## Date:02/11/25

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
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>The Art of Being Alone</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Open+Sans:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      background: linear-gradient(135deg, #e0c3fc 0%, #8ec5fc 100%);
      font-family: 'Open Sans', sans-serif;
    }

    .cover {
      width: 420px;
      height: 620px;
      background: #fff;
      border-radius: 16px;
      box-shadow: 0 20px 60px rgba(0, 0, 0, 0.25);
      position: relative;
      overflow: hidden;
    }

    .cover::before {
      content: "";
      position: absolute;
      width: 100%;
      height: 100%;
      background: url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e?auto=format&fit=crop&w=700&q=80') center/cover;
      opacity: 0.35;
      z-index: 0;
    }

    .content {
      position: relative;
      z-index: 1;
      height: 100%;
      padding: 40px;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

    h1 {
      font-family: 'Playfair Display', serif;
      font-size: 46px;
      line-height: 1.1;
      color: #2c3e50;
      margin: 0;
    }

    h1 span {
      color: #6a11cb;
    }

    .subtitle {
      font-size: 14px;
      color: #555;
      margin-top: 10px;
      max-width: 80%;
    }

    .author {
      text-align: right;
      font-size: 16px;
      font-weight: 600;
      color: #2c3e50;
    }

    .spine {
      position: absolute;
      left: -40px;
      top: 50%;
      transform: rotate(-90deg) translateY(-50%);
      transform-origin: center;
      font-size: 12px;
      font-weight: 700;
      letter-spacing: 4px;
      color: rgba(0, 0, 0, 0.15);
    }

    .decoration {
      position: absolute;
      bottom: 0;
      left: 0;
      width: 100%;
      height: 120px;
      background: linear-gradient(0deg, rgba(255, 255, 255, 0.7), transparent);
    }
  </style>
</head>
<body>
  <div class="cover">
    <div class="content">
      <div>
        <h1>The Art of<br><span>Being Alone</span></h1>
        <p class="subtitle">A storybook about finding peace, creativity, and light in solitude.</p>
      </div>
      <div class="author">by <strong>Amaya Bennett</strong></div>
    </div>
    <div class="spine">THE ART OF BEING ALONE</div>
    <div class="decoration"></div>
  </div>
</body>
</html>
```


## OUTPUT:
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/cc685dcc-0c8b-406b-96c7-a2b365488d0d" />


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
