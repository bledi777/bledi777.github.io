<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto+Condensed:ital,wght@0,100..900;1,100..900&display=swap"
        rel="stylesheet">
    <link rel="icon" type="image/x-icon" href="img/shrinllkad.png">
    <style>
        :root {

--primary: rgba(132, 106, 221, 0.9);
--secondary: rgba(132, 106, 221, 0.9);
;

--pane-padding: 5px 42px;
}


body {
margin: 0;
background: linear-gradient(135deg, var(--primary), var(--secondary)), url(img/anders-jilden-nxCtO8W9JLo-unsplash.jpg) no-repeat center center / cover;
height: 0%;
font-family: "Roboto Condensed", sans-serif;
font-optical-sizing: auto;
color: black;
}

* {
scroll-behavior: smooth;
box-sizing: border-box;
}

/* Chrome, Safari, Edge, Opera */
input::-webkit-outer-spin-button,
input::-webkit-inner-spin-button {
-webkit-appearance: none;
margin: 0;
}




.input-container {
position: relative;
margin: 70px 20px;

}

.input-container input {
border-radius: 2px;
font-size: 20px;
width: 100%;
border: none;
border-bottom: 2px solid #1c1c1c;
padding: 5px 0;
background-color: transparent;
outline: none;
}

.input-container select {
font-size: 20px;
border-radius: 2px;
width: 100%;
border: none;
border-bottom: 2px solid #1c1c1c;
padding: 5px 0;
background-color: transparent;
outline: none;
}

.input-container .label {
font-size: 22px;
position: absolute;
top: 0;
left: 0;
color: #1c1c1c;
transition: all 0.3s ease;
pointer-events: none;
}

.input-container input:focus~.label,
.input-container input:valid~.label {
top: -27px;
font-size: 26px;
color: #6d6d6d;
}

.input-container select:focus~.label,
.input-container select:valid~.label {
top: -27px;
font-size: 25px;
color: #7b7b7b;
}

.input-container .underline {
border-radius: 30px;
position: absolute;
bottom: 0;
left: 0;
height: 2px;
width: 100%;
background-color: #1c1c1c;
transform: scaleX(0);
transition: all 0.3s ease;
}

.input-container input:focus~.underline,
.input-container input:valid~.underline {
transform: scaleX(1);
}


.head{
display: flex;
align-items: center;
flex-wrap: wrap;
flex-direction: column;
justify-content: center;
}
.wrapper {
padding: 0 25%;
margin: 5% auto;
position: relative;
z-index: 1;
}

h1 {
text-align: center;

font-size: 50px;
text-align: center;
font-weight: 300;
}

p {
font-size: 25px;
font-weight: 500;
}

img {
width: 200px;

}

.reg {
display: flex;
justify-content: center;
align-items: center;
}

.container {
border-radius: 5px;
background-color: #fbfbfb;
backdrop-filter: blur(20px);
padding: 20px;
}

button {
position: relative;
display: inline-block;
cursor: pointer;
outline: none;
border: 0;
vertical-align: middle;
text-decoration: none;
background: transparent;
padding: 0;
font-size: inherit;
font-family: inherit;
}

button.learn-more {
width: 12rem;
height: auto;
}

button.learn-more .circle {
transition: all 0.45s cubic-bezier(0.65, 0, 0.076, 1);
position: relative;
display: block;
margin: 0;
width: 3rem;
height: 3rem;
background: #282936;
border-radius: 1.625rem;
}

button.learn-more .circle .icon {
transition: all 0.45s cubic-bezier(0.65, 0, 0.076, 1);
position: absolute;
top: 0;
bottom: 0;
margin: auto;
background: #fff;
}

button.learn-more .circle .icon.arrow {
transition: all 0.45s cubic-bezier(0.65, 0, 0.076, 1);
left: 0.625rem;
width: 1.125rem;
height: 0.125rem;
background: none;
}

button.learn-more .circle .icon.arrow::before {
position: absolute;
content: "";
top: -0.29rem;
right: 0.0625rem;
width: 0.625rem;
height: 0.625rem;
border-top: 0.125rem solid #fff;
border-right: 0.125rem solid #fff;
transform: rotate(45deg);
}

button.learn-more .button-text {
transition: all 0.45s cubic-bezier(0.65, 0, 0.076, 1);
position: absolute;
top: 0;
left: 0;
right: 0;
bottom: 0;
padding: 0.75rem 0;
margin: 0 0 0 1.85rem;
color: #282936;
font-weight: 700;
line-height: 1.6;
text-align: center;
text-transform: uppercase;
}

button:hover .circle {
width: 100%;
}

button:hover .circle .icon.arrow {
background: #fff;
transform: translate(1rem, 0);
}

button:hover .button-text {
color: #fff;
}
@media (min-width:0px ) and (max-width: 1024px) {
body{
  height: 0%;
}
.head{
  display: flex;
  flex-direction: column;
  align-items: center;
}
h1{
  margin: 0;
}  
.wrapper{
  padding: 0%;
  margin: 7%;

}
button.learn-more .circle {
  width: 100%;
}
button.learn-more .button-text{
  color: #fff;
}



}

    </style>
    <title>Contact us</title>
</head>

<body>

    <section class="wrapper">
        <div class="container">
            <div class="content">
                <div class="head">
                    <div class="logo">
                        <img src="img/witeanblue-removebg-preview.png" alt="">
                    </div>
                    <h1>Akademia e Teknologjise dhe Digjitalizimit</h1>
                </div>
                <p style="text-align: center;">
                 Mirë se Vini në Akademin tonë
                    <br>
                    <span id="element" style="color: #3276bf"></span>
                </p>
                
            </div>
        </div>
    </section>
    <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>
    <script src="script.js"></script>
</body>

</html>
