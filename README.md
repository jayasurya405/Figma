# Ex09 Event Registration Web Application
## Date:08/10/2025

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
homepage
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
      <img class="screenshot" src="img/screenshot-2025-10-08-142650-1.png" />
      <div class="rectangle"></div>
      <div class="text-wrapper">REGISTER</div>
      <div class="div"></div>
      <div class="text-wrapper-2">LOGIN</div>
      <div class="text-wrapper-3">SPORTS DAY EVENT</div>
    </div>
  </body>
</html>

.iphone {
  background-color: #75c1a7;
  width: 100%;
  min-width: 390px;
  min-height: 844px;
  position: relative;
}

.iphone .screenshot {
  position: absolute;
  top: 0;
  left: 0;
  width: 390px;
  height: 844px;
  aspect-ratio: 0.79;
  object-fit: cover;
}

.iphone .rectangle {
  position: absolute;
  top: 564px;
  left: 41px;
  width: 301px;
  height: 73px;
  background-color: #bf9c49;
  box-shadow: 50px 25px 4px 10px #00000040;
}

.iphone .text-wrapper {
  position: absolute;
  top: 572px;
  left: 77px;
  width: 265px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .div {
  position: absolute;
  top: 468px;
  left: 83px;
  width: 223px;
  height: 53px;
  background-color: #c9b743;
  box-shadow: 75px 10px 4px #00000040;
}

.iphone .text-wrapper-2 {
  position: absolute;
  top: 472px;
  left: 128px;
  width: 193px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .text-wrapper-3 {
  position: absolute;
  top: 390px;
  left: 101px;
  width: 245px;
  -webkit-text-stroke: 1px #c73838;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

page 2

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
      <img class="screenshot" src="img/screenshot-2025-10-08-142705-1.png" />
      <div class="text-wrapper">1.FOOTBALL</div>
      <div class="div">2.CRICKET</div>
      <p class="element-SOLO-AND">
        3.100MTS(SOLO AND GRP)<br /><br />4.200MTS(SOLO AND GRP)<br /><br />5.400MTS(SOLO AND GRP)<br /><br />6.LONG
        JUMP<br /><br />7.SHORT PUT<br /><br />8.GUNSHOT
      </p>
      <div class="text-wrapper-2">EVENTS</div>
    </div>
  </body>
</html>

.iphone {
  background-color: #48d49c;
  width: 100%;
  min-width: 390px;
  min-height: 844px;
  position: relative;
}

.iphone .screenshot {
  position: absolute;
  top: 0;
  left: 0;
  width: 390px;
  height: 844px;
  aspect-ratio: 0.58;
  object-fit: cover;
}

.iphone .text-wrapper {
  position: absolute;
  top: 162px;
  left: 26px;
  width: 245px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .div {
  position: absolute;
  top: 206px;
  left: 26px;
  width: 180px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .element-SOLO-AND {
  position: absolute;
  top: 259px;
  left: 26px;
  width: 298px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper-2 {
  position: absolute;
  top: 73px;
  left: 130px;
  width: 259px;
  text-shadow: 0px 4px 4px #00000040;
  -webkit-text-stroke: 1px #2b0808;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ae1c1c;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

page 3

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
      <img class="screenshot" src="img/screenshot-2025-10-08-143111-1.png" />
      <div class="EVENT-REGISTERATION">EVENT&nbsp;&nbsp;REGISTERATION&nbsp;&nbsp;FORM</div>
      <div class="text-wrapper">FILL THE DETIALS</div>
      <div class="rectangle"></div>
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="text-wrapper-2">NAME:</div>
      <div class="text-wrapper-3">REG:</div>
      <div class="text-wrapper-4">DEP:</div>
      <div class="text-wrapper-5">EVENTS:</div>
    </div>
  </body>
</html>

.iphone {
  background-color: #27c284;
  overflow: hidden;
  width: 100%;
  min-width: 390px;
  min-height: 844px;
  position: relative;
}

.iphone .screenshot {
  position: absolute;
  top: 0;
  left: 0;
  width: 390px;
  height: 844px;
  aspect-ratio: 0.63;
  object-fit: cover;
}

.iphone .EVENT-REGISTERATION {
  position: absolute;
  top: 75px;
  left: 25px;
  width: 337px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #3de917;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper {
  position: absolute;
  top: 121px;
  left: 25px;
  width: 334px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .rectangle {
  position: absolute;
  top: 186px;
  left: 32px;
  width: 295px;
  height: 71px;
  background-color: #c43131;
}

.iphone .text-on-a-path {
  position: absolute;
  top: 313px;
  left: -870px;
  width: 279px;
  height: 71px;
}

.iphone .div {
  position: absolute;
  top: 438px;
  left: 28px;
  width: 295px;
  height: 64px;
  background-color: #b63a3a;
}

.iphone .rectangle-2 {
  position: absolute;
  top: 570px;
  left: 32px;
  width: 291px;
  height: 63px;
  background-color: #b55252;
}

.iphone .rectangle-3 {
  position: absolute;
  top: 312px;
  left: 34px;
  width: 287px;
  height: 71px;
  background-color: #c53838;
}

.iphone .text-wrapper-2 {
  position: absolute;
  top: 208px;
  left: 44px;
  width: 263px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .text-wrapper-3 {
  position: absolute;
  top: 340px;
  left: 50px;
  width: 236px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .text-wrapper-4 {
  position: absolute;
  top: 466px;
  left: 44px;
  width: 236px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .text-wrapper-5 {
  position: absolute;
  top: 595px;
  left: 32px;
  width: 237px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

page 4

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
      <img class="screenshot" src="img/screenshot-2025-10-08-144222-1.png" />
      <p class="THANK-YOU-we-are">THANK YOU!<br /><br />we are eagerly waiting for your participation in sports day</p>
    </div>
  </body>
</html>

.iphone {
  background-color: #ffffff;
  width: 100%;
  min-width: 390px;
  min-height: 844px;
  position: relative;
}

.iphone .screenshot {
  position: absolute;
  top: 0;
  left: 0;
  width: 390px;
  height: 844px;
  aspect-ratio: 1.67;
  object-fit: cover;
}

.iphone .THANK-YOU-we-are {
  position: absolute;
  top: 359px;
  left: 9px;
  width: 285px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}


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

```
## OUTPUT:
![alt text](<Screenshot 2025-10-08 144659.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
