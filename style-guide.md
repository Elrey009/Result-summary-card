# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

- Light red: hsl(0, 100%, 67%)
- Orangey yellow: hsl(39, 100%, 56%)
- Green teal: hsl(166, 100%, 37%)
- Cobalt blue: hsl(234, 85%, 45%)

## Gradients

- Light slate blue (background): hsl(252, 100%, 67%)
- Light royal blue (background): hsl(241, 81%, 54%)

- Violet blue (circle): hsla(256, 72%, 46%, 1)
- Persian blue (circle): hsla(241, 72%, 46%, 0)



### Neutral

- White: hsl(0, 0%, 100%)
- Pale blue: hsl(221, 100%, 96%)
- Light lavender: hsl(241, 100%, 89%)
- Dark gray blue: hsl(224, 30%, 27%)

### Notes

Use transparency to get the colour variations necessary to match the design. Hint: look into using `hsla()`.

## Typography

### Body Copy

- Font size (paragraphs): 18px

### Font


- Weights: 500, 700, 800






<!-- :root {
  /*  Primary color */
  --light-red: hsl(0, 100%, 67%);
  --orange-yellow: hsl(39, 100%, 56%);
  --green-teal: hsl(166, 100%, 37%);
  --cobalt-blue: hsl(234, 85%, 45%);

  /* ## Gradients */
  /* (background) */
  --light-slate-blue: hsl(252, 100%, 67%);
  /* (background) */
  --light-royal-blue: hsl(241, 81%, 54%);
  /*(circle)*/
  --violetblue: hsla(256, 72%, 46%, 1);
  /* (circle) */
  --persian-blue: hsla(241, 72%, 46%, 0);

  /* ### Neutral */
  --white: hsl(0, 0%, 100%);
  --pale-blue: hsl(221, 100%, 96%);
  --light-lavender: hsl(241, 100%, 89%);
  --dark-gray-blue: hsl(224, 30%, 27%);

  /* font-family */
  --font-family: sans-serif;
}
* {
  margin: 0;
  box-sizing: border-box;
  padding: 0;
}

body {
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 16px;
}

.container {
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  background-color: white;
  border-radius: 10px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
}


h1,h2,p{
  font-family: var(--font-family);
}
  

 .blue {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background: linear-gradient(
    to bottom,
    hsl(252, 100%, 67%), 
    hsla(256, 72%, 46%, 1) 50%,
     hsl(241, 81%, 54%) 
  );
  border-radius: 10px;
  height: 350px;
  text-align: center;
  width: 270px;
  color: white;
}


.circle-box {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  background: linear-gradient(
    to bottom,
    hsl(241, 81%, 54%), 
    hsl(252, 100%, 67%) 
   );
  border-radius: 50%;
  width: 130px;
  height: 130px;
  padding: 10px;
  margin-top: 20px 0;
}
.result {
  margin-bottom: 25px;
}


.circle-box h1 {
  font-size: 50px;
  font-weight: 800;
  font-family: var(--font-family);
}
.container h2 {
  padding: 10px 0;
}
.blue p {
  width: 200px;
  font-size:15px ;
  opacity: 0.5;
}
. {
  display: flex;
  align-items: center;
  justify-content: center;
}

.white {
  text-align: left;
  background-color: white;
  height: 350px;
  border-radius: 10px;
  padding: 20px;
  width: 270px;
}

.white h2{
  color: var(--dark-gray-blue);
  font-size: 19px;
}
.icon {
  display: flex;
  justify-content: center;
  align-items: center;
  padding-right: 50px;
}
.icon img {
  padding-right: 10px;
}

span {
  font-weight: 700;
}
.reaction {
  display: flex;
  justify-content: space-around;
  align-items: center;
  background-color: hsl(0, 48%, 89%);
  border-radius: 5px;
  padding: 7px 20px;
  margin-bottom: 10px;
  margin-top: 10px;
}
.reaction .icon :nth-child(2) {
  color: var(--light-red);
}
.memory {
  display: flex;
  justify-content: space-around;
  align-items: center;
  background-color: hsl(38, 32%, 83%);
  border-radius: 5px;
  padding: 7px 20px;
  margin-bottom: 10px;
  margin-top: 20px;
}

.memory .icon :nth-child(2) {
  color: var(--orange-yellow);
}

.verbal {
  display: flex;
  justify-content: space-around;
  align-items: center;
  background-color: hsl(166, 62%, 80%);
  border-radius: 5px;
  padding: 7px 20px;
  margin-bottom: 10px;
  margin-top: 20px;
}
.verbal .icon :nth-child(2) {
  color: var(--green-teal);
}

.visual {
  display: flex;
  justify-content: space-around;
  align-items: center;
  background-color: hsl(242, 47%, 85%);
  border-radius: 5px;
  padding: 7px 20px;
  margin-bottom: 10px;
  margin-top: 20px;
}
.visual .icon :nth-child(2) {
  color: var(--light-royal-blue);
}
.link {
  text-align: center;
  text-decoration: none;
  background-color: var(--dark-gray-blue);
  padding: 10px 0;
  margin-top: 20px;
  border-radius: 50px;
}
.link a {
  text-decoration: none;
  color: white;
}
.link:active {
  color: white;
  background: linear-gradient(
    to bottom,
    hsl(252, 100%, 67%), 
     hsla(256, 72%, 46%, 1) 50%,
     Middle-top color at 50%  hsl(241, 81%, 54%) 
  );
}



/* mobile view */
@media screen and (max-width: 700px) {
    .container {
      flex-direction: column;
      margin-top: 10%;
      margin-bottom: 10%;
    }

  }
 -->



