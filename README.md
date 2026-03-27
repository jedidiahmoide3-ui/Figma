# Ex08 Event Registration Web Application
## Date: 27.03.2026
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
Home Page

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
    <div class="iphone">
      <img class="sbr" src="img/sbr-1.png" />
      <img class="logo-steel-ball-run" src="img/logo-steel-ball-run-1.png" />
      <div class="rectangle"></div>
      <div class="text-wrapper">REGISTER NOW</div>
      <div class="div"></div>
      <div class="text-wrapper-2">ViEW YOUR ACCOUNT</div>
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
/* @FONTWARNING[{"type": "restricted", "family": "Inter-ExtraBold", "weight": "800", "style": "normal", "allowsCrossOrigin": false}] */

@font-face {
  font-family: "Inter-ExtraBold";
  src: local("Inter-ExtraBold");
}
/* @FONTWARNING[{"type": "restricted", "family": "Inter-BlackItalic", "weight": "900", "style": "italic", "allowsCrossOrigin": false}] */

@font-face {
  font-family: "Inter-BlackItalic";
  src: local("Inter-BlackItalic");
}

style.css

.iphone {
  background-color: #ffd014;
  width: 100%;
  min-width: 445px;
  min-height: 965px;
  position: relative;
}

.iphone .sbr {
  position: absolute;
  top: 0;
  left: 0;
  width: 445px;
  height: 965px;
  aspect-ratio: 0.71;
  object-fit: cover;
}

.iphone .logo-steel-ball-run {
  position: absolute;
  top: 35px;
  left: 40px;
  width: 365px;
  height: 249px;
  aspect-ratio: 1.46;
  object-fit: cover;
}

.iphone .rectangle {
  position: absolute;
  top: 725px;
  left: 97px;
  width: 260px;
  height: 66px;
  background-color: #8f2704;
}

.iphone .text-wrapper {
  position: absolute;
  top: 744px;
  left: 131px;
  width: 192px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .div {
  position: absolute;
  top: 601px;
  left: 78px;
  width: 297px;
  height: 108px;
  background-color: #902704;
}

.iphone .text-wrapper-2 {
  position: absolute;
  top: 638px;
  left: 85px;
  width: 302px;
  font-family: "Inter-BlackItalic", Helvetica;
  font-weight: 900;
  font-style: italic;
  color: #f4cc00;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

Page 2 

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
    <div class="iphone">
      <img class="sbr" src="img/sbr-2-1.png" />
      <div class="rectangle"></div>
      <p class="element-march-stages">
        ★ 25th March <br /><br />★ 9 Stages <br /><br />★ Cross Americe<br /><br />★Get your
        horse&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp; ready<br /><br />★
        Become a spin<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;user
      </p>
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
/* @FONTWARNING[{"type": "restricted", "family": "Inter-BlackItalic", "weight": "900", "style": "italic", "allowsCrossOrigin": false}] */

@font-face {
  font-family: "Inter-BlackItalic";
  src: local("Inter-BlackItalic");
}

style.css

.iphone {
  background-color: #2d2532;
  width: 100%;
  min-width: 445px;
  min-height: 965px;
  position: relative;
}

.iphone .sbr {
  position: absolute;
  top: 119px;
  left: 0;
  width: 445px;
  height: 788px;
  aspect-ratio: 0.71;
  object-fit: cover;
}

.iphone .rectangle {
  position: absolute;
  top: 419px;
  left: 16px;
  width: 251px;
  height: 403px;
  background-color: #5d639733;
  border: 3px solid;
  border-color: #000000;
  backdrop-filter: blur(2px) brightness(100%);
  -webkit-backdrop-filter: blur(2px) brightness(100%);
}

.iphone .element-march-stages {
  position: absolute;
  top: 451px;
  left: 36px;
  width: 211px;
  text-shadow: 0px 4px 4px #00000040;
  -webkit-text-stroke: 2px #050505;
  font-family: "Inter-BlackItalic", Helvetica;
  font-weight: 900;
  font-style: italic;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0.24px;
  line-height: normal;
}

Page 3

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
    <div class="iphone">
      <img class="sbr" src="img/sbr-4-1.png" />
      <div class="rectangle"></div>
      <div class="text-wrapper">RACE REGISTRATION FORM</div>
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-2">Full Name</div>
      <div class="rectangle-3"></div>
      <div class="text-wrapper-3">Horse Name</div>
      <div class="text-wrapper-4">Player Race</div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <div class="text-wrapper-5">Country</div>
      <div class="text-wrapper-6">Gender</div>
      <div class="rectangle-6"></div>
      <div class="text-wrapper-7">Racer ID</div>
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
/* @FONTWARNING[{"type": "restricted", "family": "Inter-SemiBold Italic", "weight": "600", "style": "italic", "allowsCrossOrigin": false}] */

@font-face {
  font-family: "Inter-SemiBold Italic";
  src: local("Inter-SemiBold Italic");
}

style.css

.iphone {
  background-color: #60491f;
  overflow: hidden;
  width: 100%;
  min-width: 445px;
  min-height: 965px;
  position: relative;
}

.iphone .sbr {
  position: absolute;
  top: 22px;
  left: 0;
  width: 445px;
  height: 929px;
  aspect-ratio: 0.68;
  object-fit: cover;
}

.iphone .rectangle {
  top: 88px;
  left: 31px;
  width: 384px;
  height: 83px;
  background-color: #c87f0a;
  border-color: #ffffff;
  position: absolute;
  border: 3px solid;
}

.iphone .text-wrapper {
  position: absolute;
  top: 116px;
  left: 70px;
  width: 397px;
  -webkit-text-stroke: 1px #000000;
  font-family: "Inter-SemiBold Italic", Helvetica;
  font-weight: 600;
  font-style: italic;
  color: #ffffff;
  font-size: 22px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .div {
  top: 257px;
  left: 39px;
  width: 215px;
  height: 49px;
  background-color: #ec9900;
  border-color: #010101;
  position: absolute;
  border: 3px solid;
}

.iphone .rectangle-2 {
  top: 409px;
  left: 39px;
  width: 215px;
  height: 49px;
  background-color: #ec9900;
  border-color: #010101;
  position: absolute;
  border: 3px solid;
}

.iphone .text-wrapper-2 {
  position: absolute;
  top: 269px;
  left: 52px;
  width: 179px;
  font-family: "Inter-SemiBold Italic", Helvetica;
  font-weight: 600;
  font-style: italic;
  color: #ffffff;
  font-size: 22px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .rectangle-3 {
  top: 338px;
  left: 39px;
  width: 215px;
  height: 49px;
  background-color: #ec9900;
  border-color: #010101;
  position: absolute;
  border: 3px solid;
}

.iphone .text-wrapper-3 {
  position: absolute;
  top: 350px;
  left: 52px;
  width: 144px;
  font-family: "Inter-SemiBold Italic", Helvetica;
  font-weight: 600;
  font-style: italic;
  color: #ffffff;
  font-size: 22px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .text-wrapper-4 {
  position: absolute;
  top: 417px;
  left: 52px;
  width: 179px;
  font-family: "Inter-SemiBold Italic", Helvetica;
  font-weight: 600;
  font-style: italic;
  color: #ffffff;
  font-size: 22px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .rectangle-4 {
  top: 491px;
  left: 39px;
  width: 215px;
  height: 49px;
  background-color: #ec9900;
  border-color: #010101;
  position: absolute;
  border: 3px solid;
}

.iphone .rectangle-5 {
  position: absolute;
  top: 572px;
  left: 39px;
  width: 215px;
  height: 49px;
  background-color: #ec9900;
  border: 3px solid;
  border-color: #010101;
}

.iphone .text-wrapper-5 {
  position: absolute;
  top: 499px;
  left: 52px;
  width: 179px;
  font-family: "Inter-SemiBold Italic", Helvetica;
  font-weight: 600;
  font-style: italic;
  color: #ffffff;
  font-size: 22px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper-6 {
  position: absolute;
  top: 584px;
  left: 52px;
  width: 179px;
  font-family: "Inter-SemiBold Italic", Helvetica;
  font-weight: 600;
  font-style: italic;
  color: #ffffff;
  font-size: 22px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .rectangle-6 {
  top: 658px;
  left: 39px;
  width: 215px;
  height: 49px;
  background-color: #ec9900;
  border-color: #010101;
  position: absolute;
  border: 3px solid;
}

.iphone .text-wrapper-7 {
  position: absolute;
  top: 666px;
  left: 57px;
  width: 179px;
  font-family: "Inter-SemiBold Italic", Helvetica;
  font-weight: 600;
  font-style: italic;
  color: #ffffff;
  font-size: 22px;
  letter-spacing: 0;
  line-height: normal;
}


```

## OUTPUT:

![alt text](<Screenshot (62).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
