# Ex08 Event Registration Web Application
## Date:23/12/25

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

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro">
      <img class="SEC-logo" src="img/SEC-logo-1-1.png" />
      <div class="rectangle"></div>
      <div class="COLLEGE-FEST-EVENT">COLLEGE&nbsp;&nbsp;&nbsp;&nbsp;FEST&nbsp;&nbsp; EVENT</div>
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <img class="clg-banner" src="img/clg-banner-1.png" />
      <div class="div"></div>
      <div class="text-wrapper">LOGIN</div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="text-wrapper-2">REGISTER</div>
      <div class="text-wrapper-3">P</div>
    </div>
  </body>
</html>

.iphone-pro {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 12705.45px;
  min-height: 18532.48px;
  position: relative;
}

.iphone-pro .SEC-logo {
  position: absolute;
  top: 1771px;
  left: 3152px;
  width: 5101px;
  height: 4917px;
  transform: rotate(-0.17deg);
  aspect-ratio: 1.04;
  object-fit: cover;
}

.iphone-pro .rectangle {
  top: 7040px;
  left: 253px;
  width: 12136px;
  height: 1483px;
  background-color: #eed3da;
  position: absolute;
  transform: rotate(-0.17deg);
}

.iphone-pro .COLLEGE-FEST-EVENT {
  position: absolute;
  top: 7342px;
  left: 1046px;
  width: 10664px;
  transform: rotate(-0.17deg);
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #000000;
  font-size: 800px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .text-on-a-path {
  position: absolute;
  top: 20229px;
  left: 12171px;
  width: 4714px;
  height: 869px;
  transform: rotate(-0.17deg);
}

.iphone-pro .clg-banner {
  position: absolute;
  top: 11712px;
  left: 4101px;
  width: 4596px;
  height: 6722px;
  transform: rotate(-0.17deg);
  aspect-ratio: 0.68;
}

.iphone-pro .div {
  top: 8953px;
  left: 3554px;
  width: 5249px;
  height: 894px;
  background-color: #6b6337;
  position: absolute;
  transform: rotate(-0.17deg);
}

.iphone-pro .text-wrapper {
  position: absolute;
  top: 9180px;
  left: 5400px;
  transform: rotate(-0.17deg);
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #000000;
  font-size: 500px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .rectangle-2 {
  top: 10394px;
  left: 4878px;
  width: 100px;
  height: 100px;
  background-color: #d9d9d9;
  position: absolute;
  transform: rotate(-0.17deg);
}

.iphone-pro .rectangle-3 {
  top: 10201px;
  left: 3604px;
  width: 5157px;
  height: 979px;
  background-color: #4d4821;
  position: absolute;
  transform: rotate(-0.17deg);
}

.iphone-pro .text-wrapper-2 {
  position: absolute;
  top: 10404px;
  left: 4929px;
  transform: rotate(-0.17deg);
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 500px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .text-wrapper-3 {
  position: absolute;
  top: 10712px;
  left: 4334px;
  transform: rotate(-0.17deg);
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 57px;
  letter-spacing: 0;
  line-height: normal;
}

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
      <div class="rectangle"></div>
      <div class="text-wrapper">COLLEGE FEST EVENT</div>
      <div class="div">EVENT LIST SCREEN</div>
      <div class="text-wrapper-2">PROJECT EXPO</div>
      <div class="text-wrapper-3">QUIZ COMPETITION</div>
      <div class="text-wrapper-4">POSTER COMPETITION</div>
      <div class="text-wrapper-5">PAPER PRESENTATION</div>
      <div class="text-wrapper-6">DEBATE</div>
      <div class="text-wrapper-7">TECHNICAL WORKSHOP</div>
      <img class="star" src="img/star-2.svg" />
      <img class="img" src="img/star-10.svg" />
      <img class="star-2" src="img/star-11.svg" />
      <img class="star-3" src="img/star-6.svg" />
      <img class="star-4" src="img/star-7.svg" />
      <img class="star-5" src="img/star-8.svg" />
      <img class="star-6" src="img/star-9.svg" />
    </div>
  </body>
</html>

.iphone {
  background-color: #ffffff;
  width: 100%;
  min-width: 9702px;
  min-height: 15139px;
  position: relative;
}

.iphone .rectangle {
  position: absolute;
  top: 828px;
  left: 516px;
  width: 6158px;
  height: 1133px;
  background-color: #4961ff;
}

.iphone .text-wrapper {
  position: absolute;
  top: 1092px;
  left: 883px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 500px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .div {
  position: absolute;
  top: 2531px;
  left: 2074px;
  width: 5933px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 600px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper-2 {
  position: absolute;
  top: 5532px;
  left: 2523px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 600px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper-3 {
  position: absolute;
  top: 7124px;
  left: 1967px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 600px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper-4 {
  position: absolute;
  top: 8694px;
  left: 1376px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 600px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper-5 {
  position: absolute;
  top: 4100px;
  left: 1605px;
  width: 6492px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 600px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .text-wrapper-6 {
  position: absolute;
  top: 10121px;
  left: 3455px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 600px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper-7 {
  position: absolute;
  top: 11681px;
  left: 1516px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 600px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .star {
  top: 2535px;
  left: 746px;
  position: absolute;
  width: 750px;
  height: 648px;
}

.iphone .img {
  top: 4100px;
  left: 606px;
  position: absolute;
  width: 750px;
  height: 648px;
}

.iphone .star-2 {
  top: 5572px;
  left: 746px;
  position: absolute;
  width: 750px;
  height: 648px;
}

.iphone .star-3 {
  top: 6989px;
  left: 746px;
  position: absolute;
  width: 750px;
  height: 648px;
}

.iphone .star-4 {
  top: 8658px;
  left: 606px;
  position: absolute;
  width: 750px;
  height: 648px;
}

.iphone .star-5 {
  top: 10121px;
  left: 674px;
  position: absolute;
  width: 750px;
  height: 648px;
}

.iphone .star-6 {
  top: 11584px;
  left: 674px;
  position: absolute;
  width: 750px;
  height: 648px;
}

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <div class="rectangle"></div>
      <div class="text-wrapper">EVENT REGISTRATION FORM</div>
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-2">GENDER</div>
      <div class="rectangle-3"></div>
      <div class="text-wrapper-3">AGE</div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <div class="text-wrapper-4">DEPARTMENT</div>
      <img class="text-on-a-path" src="img/text-on-a-path-2.svg" />
      <div class="text-wrapper-5">FULL NAME</div>
      <div class="text-wrapper-6">REGISTER NO</div>
      <div class="rectangle-6"></div>
      <div class="text-wrapper-7">MOBILE NO</div>
      <div class="rectangle-7"></div>
      <div class="text-wrapper-8">EMAIL ID</div>
      <img class="img" src="img/text-on-a-path.svg" />
      <div class="rectangle-8"></div>
      <div class="EVENT-REGISTERED">EVENT<br />REGISTERED</div>
      <img class="text-on-a-path-2" src="img/image.svg" />
      <div class="rectangle-9"></div>
      <div class="text-wrapper-9">SUBMIT</div>
    </div>
  </body>
</html>

.iphone-pro-max {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 10038px;
  min-height: 18810px;
  position: relative;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 727px;
  left: 718px;
  width: 8886px;
  height: 1688px;
  background-color: #d9d9d9;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 1208px;
  left: 980px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 600px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .div {
  position: absolute;
  top: 3070px;
  left: 862px;
  width: 5622px;
  height: 937px;
  background-color: #8afe8a;
}

.iphone-pro-max .rectangle-2 {
  position: absolute;
  top: 4662px;
  left: 862px;
  width: 5622px;
  height: 894px;
  background-color: #98ff9c;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 4799px;
  left: 1583px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 600px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-3 {
  position: absolute;
  top: 6313px;
  left: 980px;
  width: 5504px;
  height: 865px;
  background-color: #90ffa8;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 6452px;
  left: 1799px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 600px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-4 {
  position: absolute;
  top: 7827px;
  left: 980px;
  width: 5504px;
  height: 865px;
  background-color: #89ffac;
}

.iphone-pro-max .rectangle-5 {
  position: absolute;
  top: 9449px;
  left: 980px;
  width: 5504px;
  height: 793px;
  background-color: #92ffab;
}

.iphone-pro-max .text-wrapper-4 {
  position: absolute;
  top: 9483px;
  left: 1658px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 600px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-on-a-path {
  position: absolute;
  top: 20627px;
  left: -15385px;
  width: 5504px;
  height: 757px;
}

.iphone-pro-max .text-wrapper-5 {
  position: absolute;
  top: 3179px;
  left: 1475px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 600px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-6 {
  position: absolute;
  top: 7970px;
  left: 1583px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 600px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-6 {
  position: absolute;
  top: 11034px;
  left: 1010px;
  width: 5474px;
  height: 865px;
  background-color: #8bf8a2;
}

.iphone-pro-max .text-wrapper-7 {
  position: absolute;
  top: 11034px;
  left: 1658px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 600px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-7 {
  position: absolute;
  top: 12584px;
  left: 1010px;
  width: 5474px;
  height: 861px;
  background-color: #99ffaf;
}

.iphone-pro-max .text-wrapper-8 {
  position: absolute;
  top: 12652px;
  left: 1799px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 600px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .img {
  position: absolute;
  top: 23837px;
  left: -15261px;
  width: 5177px;
  height: 1147px;
}

.iphone-pro-max .rectangle-8 {
  position: absolute;
  top: 14402px;
  left: 1104px;
  width: 5380px;
  height: 1689px;
  background-color: #97ffd0;
}

.iphone-pro-max .EVENT-REGISTERED {
  position: absolute;
  top: 14639px;
  left: 1799px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 600px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-on-a-path-2 {
  position: absolute;
  top: 27261px;
  left: -14879px;
  width: 4202px;
  height: 771px;
}

.iphone-pro-max .rectangle-9 {
  position: absolute;
  top: 17230px;
  left: 1780px;
  width: 3381px;
  height: 1065px;
  background-color: #ff0404;
}

.iphone-pro-max .text-wrapper-9 {
  position: absolute;
  top: 17400px;
  left: 2323px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 600px;
  letter-spacing: 0;
  line-height: normal;
}

```


## OUTPUT:
![alt text](<Screenshot 2025-12-23 201159.png>)


## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
