# Ex08 Event Registration Web Application
## Date:23-12-2025

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
android1.html

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
      <img class="name-saveetha" src="img/name-saveetha-1.png" />
      <img class="logo" src="img/logo-1.png" />
      <div class="rectangle"></div>
      <div class="text-wrapper">SPORTS DAY EVENT REGISTRATION</div>
      <div class="div"></div>
      <div class="text-wrapper-2">REGISTER</div>
      <div class="rectangle-2"></div>
      <div class="rounded-rectangle"></div>
      <div class="text-wrapper-3">LOGIN</div>
      <div class="text-wrapper-4">EVENTS</div>
    </div>
  </body>
</html>




android1.CSS


.android-medium {
  background-color: #e3fc00;
  width: 100%;
  min-width: 1457px;
  min-height: 2323px;
  position: relative;
}

.android-medium .name-saveetha {
  position: absolute;
  top: 69px;
  left: 0;
  width: 1455px;
  height: 293px;
  aspect-ratio: 4.97;
}

.android-medium .logo {
  position: absolute;
  top: 362px;
  left: 323px;
  width: 811px;
  height: 811px;
  aspect-ratio: 1;
  object-fit: cover;
}

.android-medium .rectangle {
  position: absolute;
  top: 1280px;
  left: 211px;
  width: 1034px;
  height: 188px;
  background-color: #d783da;
  border-radius: 50px;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 1345px;
  left: 338px;
  width: 781px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .div {
  position: absolute;
  top: 2000px;
  left: 503px;
  width: 451px;
  height: 114px;
  background-color: #13dfff;
  border-radius: 60px;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 2018px;
  left: 587px;
  font-family: "Itim-Regular", Helvetica;
  font-weight: 400;
  color: #d3263a;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle-2 {
  position: absolute;
  top: 1779px;
  left: 503px;
  width: 451px;
  height: 114px;
  background-color: #13dfff;
  border-radius: 60px;
}

.android-medium .rounded-rectangle {
  position: absolute;
  top: 1567px;
  left: 503px;
  width: 451px;
  height: 114px;
  background-color: #13dfff;
  border-radius: 60px;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 1798px;
  left: 633px;
  font-family: "Itim-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-4 {
  position: absolute;
  top: 1576px;
  left: 584px;
  height: 96px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Itim-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 80px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}


android2.HTML

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
      <div class="CRICKET-FOOTBALL">CRICKET <br /><br />FOOTBALL<br /><br />KABBADI<br /><br />CHESS</div>
      <div class="rectangle"></div>
      <div class="text-wrapper">sports events</div>
      <img class="star" src="img/star-1.svg" />
      <img class="img" src="img/star-2.svg" />
      <img class="star-2" src="img/star-3.svg" />
      <img class="star-3" src="img/star-4.svg" />
      <img class="undraw-bike-ride" src="img/undraw-bike-ride-ba0o-1.png" />
    </div>
  </body>
</html>

android2.css

.android-medium {
  background-color: #5fd4a9;
  width: 100%;
  min-width: 1457px;
  min-height: 2323px;
  position: relative;
}

.android-medium .CRICKET-FOOTBALL {
  position: absolute;
  top: 592px;
  left: 336px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #000000;
  font-size: 128px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle {
  position: absolute;
  top: calc(50.00% - 1054px);
  left: calc(50.00% - 635px);
  width: 1269px;
  height: 263px;
  background-color: #8171f9;
  border-radius: 40px;
  transform: rotate(-0.35deg);
}

.android-medium .text-wrapper {
  position: absolute;
  top: 162px;
  left: 291px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #000000;
  font-size: 128px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .star {
  top: 592px;
  position: absolute;
  left: 174px;
  width: 114px;
  height: 117px;
}

.android-medium .img {
  top: 897px;
  position: absolute;
  left: 174px;
  width: 114px;
  height: 117px;
}

.android-medium .star-2 {
  top: 1207px;
  position: absolute;
  left: 174px;
  width: 114px;
  height: 117px;
}

.android-medium .star-3 {
  top: 1517px;
  position: absolute;
  left: 174px;
  width: 114px;
  height: 117px;
}

.android-medium .undraw-bike-ride {
  position: absolute;
  top: 1712px;
  left: 635px;
  width: 780px;
  height: 570px;
  aspect-ratio: 1.37;
  object-fit: cover;
}


android3.HTML

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
      <div class="text-wrapper">REGISTRATION FORM</div>
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <div class="rectangle-6"></div>
      <div class="rounded-rectangle"></div>
      <div class="text-wrapper-2">MOBILE NO</div>
      <div class="text-wrapper-3">NAME</div>
      <div class="text-wrapper-4">REGISTER NO</div>
      <div class="text-wrapper-5">AGE</div>
      <div class="text-wrapper-6">GENDER</div>
      <div class="text-wrapper-7">EMAIL ID</div>
      <div class="text-wrapper-8">SUBMIT</div>
      <img class="image" src="img/image-1.png" />
    </div>
  </body>
</html>

android3.css

.android-medium {
  background-color: #f25de9;
  width: 100%;
  min-width: 1457px;
  min-height: 2323px;
  position: relative;
}

.android-medium .rectangle {
  position: absolute;
  top: 131px;
  left: 96px;
  width: 1265px;
  height: 221px;
  background-color: #bdff18;
  border-radius: 60px;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 183px;
  left: 216px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #000000;
  font-size: 96px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .div {
  top: 445px;
  left: 96px;
  width: 560px;
  height: 110px;
  background-color: #d9d9d9;
  position: absolute;
  border-radius: 50px;
}

.android-medium .rectangle-2 {
  top: 1912px;
  left: 376px;
  width: 738px;
  height: 142px;
  background-color: #0aeeff;
  position: absolute;
  border-radius: 50px;
}

.android-medium .rectangle-3 {
  top: 648px;
  left: 96px;
  width: 560px;
  height: 110px;
  background-color: #d9d9d9;
  position: absolute;
  border-radius: 50px;
}

.android-medium .rectangle-4 {
  top: 865px;
  left: 96px;
  width: 560px;
  height: 110px;
  background-color: #d9d9d9;
  position: absolute;
  border-radius: 50px;
}

.android-medium .rectangle-5 {
  top: 1540px;
  left: 96px;
  width: 560px;
  height: 110px;
  background-color: #d9d9d9;
  position: absolute;
  border-radius: 50px;
}

.android-medium .rectangle-6 {
  top: 1324px;
  left: 96px;
  width: 560px;
  height: 110px;
  background-color: #d9d9d9;
  position: absolute;
  border-radius: 50px;
}

.android-medium .rounded-rectangle {
  position: absolute;
  top: 1107px;
  left: 96px;
  width: 560px;
  height: 110px;
  background-color: #d9d9d9;
  border-radius: 50px;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 1121px;
  left: 197px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #000000;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 462px;
  left: 254px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #000000;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-4 {
  position: absolute;
  top: 669px;
  left: 162px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #000000;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-5 {
  position: absolute;
  top: 875px;
  left: 308px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #000000;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-6 {
  position: absolute;
  top: 1340px;
  left: 216px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #000000;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-7 {
  position: absolute;
  top: 1557px;
  left: 235px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #000000;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-8 {
  position: absolute;
  top: 1934px;
  left: 587px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #000000;
  font-size: 80px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .image {
  position: absolute;
  top: 851px;
  left: 745px;
  width: 562px;
  height: 562px;
  aspect-ratio: 1;
  object-fit: cover;
}


```

## OUTPUT:
![alt text](<Screenshot (71).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
