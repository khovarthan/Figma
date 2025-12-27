# Ex08 Event Registration Web Application
## Date:

## AIM:
To design, develop and deploy a web application for event registration using Figma UI tool.

## UI DESIGN TOOL:
Figma

## DESIGN STEPS:

### Step 1:
Use frames to represent screens or sections.

### Step 2:
Add column grids for consistent spacing and alignment.

### Step 3:
Insert shapes, text, buttons, and icons.

### Step 4:
Use Auto Layout for flexible, responsive design.

### Step 5:
Define color, text, and effect styles globally for consistency.

### Step 6:
Name layers logically and group related elements.

### Step 6:
Link frames to show navigation or interactions.

### Step 7:
Select the specific frame while generating code using Anima plugin.

## CODE:
```
home page

intex.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <div class="rectangle"></div>
      <img class="image" src="img/image-2.png" />
      <img class="img" src="img/image-3.png" />
      <p class="text-wrapper">Hackathon Event Day - 2</p>
      <div class="div"></div>
      <div class="text-wrapper-2">REGISTER</div>
      <img class="image-2" src="img/image-4.png" />
      <img class="image-3" src="img/image-5.png" />
      <div class="innovate-collaborate">&#34;Innovate. Collaborate. Code.&#34;</div>
    </div>
  </body>
</html>

globals.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css

.android-medium {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 696px;
  min-height: 1128px;
  position: relative;
}

.android-medium .rectangle {
  top: 304px;
  left: 127px;
  width: 443px;
  height: 96px;
  background-color: #78c9c2;
  position: absolute;
  border-radius: 20px;
}

.android-medium .image {
  position: absolute;
  top: 178px;
  left: 292px;
  width: 107px;
  height: 103px;
  aspect-ratio: 1.04;
  object-fit: cover;
}

.android-medium .img {
  position: absolute;
  top: 745px;
  left: 23px;
  width: 645px;
  height: 383px;
  aspect-ratio: 1.69;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 330px;
  left: 178px;
  font-family: "Jaro-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .div {
  top: 659px;
  left: 249px;
  width: 171px;
  height: 53px;
  background-color: #ab6363;
  position: absolute;
  border-radius: 20px;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 659px;
  left: 269px;
  width: 484px;
  font-family: "Jaro-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .image-2 {
  position: absolute;
  top: 445px;
  left: 486px;
  width: 188px;
  height: 188px;
  aspect-ratio: 1;
  object-fit: cover;
}

.android-medium .image-3 {
  position: absolute;
  top: 427px;
  left: 0;
  width: 196px;
  height: 196px;
  aspect-ratio: 1;
  object-fit: cover;
}

.android-medium .innovate-collaborate {
  position: absolute;
  top: 525px;
  left: 178px;
  width: 412px;
  font-family: "Jaro-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

second page

index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <img class="image" src="img/image-6.png" />
      <div class="text-wrapper">EVENT LIST</div>
      <p class="debugging-derby">
        =&gt;Debugging Derby<br /><br />=&gt;Skill-Up Hack<br /><br />=&gt;Visual Design Hack<br /><br />=&gt;Code
        Carnival<br /><br />=&gt;Solution Sprint<br /><br />=&gt;Networking Mixers
      </p>
      <img class="img" src="img/image-7.png" />
    </div>
  </body>
</html>

globals.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css

.android-medium {
  background-color: #ffffff;
  width: 100%;
  min-width: 696px;
  min-height: 1128px;
  position: relative;
}

.android-medium .image {
  top: 9px;
  left: 0;
  width: 696px;
  height: 1119px;
  aspect-ratio: 0.67;
  position: absolute;
  object-fit: cover;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 106px;
  left: 171px;
  width: 353px;
  font-family: "JejuHallasan-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
  text-decoration: underline;
  white-space: nowrap;
}

.android-medium .debugging-derby {
  position: absolute;
  top: 265px;
  left: 153px;
  width: 428px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #a0ca59;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .img {
  top: 768px;
  left: 25px;
  width: 611px;
  height: 360px;
  aspect-ratio: 1.5;
  position: absolute;
  object-fit: cover;
}

last page

index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="image"><img class="img" src="img/image-6.png" /></div>
  </body>
</html>

globals.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css

.image {
  width: 746px;
  height: 1119px;
}

.image .img {
  position: fixed;
  top: 0;
  left: 25px;
  width: 696px;
  height: 1119px;
  aspect-ratio: 0.67;
  object-fit: cover;
}
```

## OUTPUT:
![alt text](<Screenshot (68).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
