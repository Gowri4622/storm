### EX NO: 06

# <p align="center">Create a Web-Layout using FLEXBOX</P>

## Aim:
The aim of the project is to create a web-layout using flexbox CSS

## Algorithm:

Step 1: Start by creating a container element in HTML, such as a <div>, which will
serve as the flex container.

Step 2: Apply the CSS properties to the container element

Step 3: Place the content inside the flex container by adding child elements, which will
become the flex items.

Step 4: Apply CSS properties to the flex items as needed

Step 5: Use additional flex properties and values as required
  
Step 6: Adjust the container and flex item sizes, margins, paddings, and other CSS
properties to achieve the desired layout.
  
Step 7: Test and refine the flexbox layout by previewing the HTML page in a web
browser, making adjustments as needed.
  

## Program

### index.html
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Storm</title>
    <link rel="stylesheet" href="/assets/css/style.css" />
  </head>
  <body>
      <div class="nav">
  
        <div class="header">STORM</div>
  
        <div class="bar">
          <div class="h1"><hr /></div>
          <div class="h2"><hr /></div>
        </div>
  
      </div>
      <div class="container">

        <div class="left">
  
          <img class="left-image" src="/assets/images/flex1.PNG" alt="" />
  
          <div class="content">
            OVERVIEW: WEATHER,<br />GLOBAL WARMING AND<br />
            CLIMATE CHANGE
          </div>
  
          <div class="about">
            "CLIMATE CHANGE" AND "GLOBAL WARMING"<br />
            ARE OFTEN USED INTERCHANGEABLY BUT<br />
            HAVE DISTINCT MEANINGS.
          </div>
  
        </div>
  
        <div class="right">
          <img class="right-image" src="/assets/images/flex2.PNG" alt="" />
          <div class="quote">THE WORLD IMPACT</div>
          <div class="quote">TIME FOR CHANGE</div>
          <div class="quote">SLOWING THE PROCESS</div>
        </div>
  
      </div>
  </body>
</html>


```

### style.css
```css
@import url('https://fonts.googleapis.com/css2?family=Noto+Serif:ital@1&family=Poppins&display=swap');

*
{
  font-family: 'Noto Serif', serif;
    font-family: 'Poppins', sans-serif;
  color: #F5F5F5;
}

body 
{
  margin: 0;
  background-color: #101010;
  color: white;
  font-family: 'Noto Serif', serif;
  font-family: 'Poppins', sans-serif;
}

.bar
{
margin-top: 26px;
margin-right: 10px;
display: flex;
width: 2rem;
display: flex;
flex-direction: column;
}

body {
  background-color: #000000;
  margin: 0 ;
}



.nav 
{
  display: flex;
  background-color: #000000;
  position: sticky;
  top: 0;
  z-index: 100;
  justify-content: space-between;
  gap: 2rem;
}

.header 
{
  font-size: 5rem;
  display: flex;
}

hr 
{
    border-top: 4px solid #ffffff;
    border-radius: 10px;
}


.container 
{
  display: flex;
  gap: 1.5rem;
  padding: 1rem;
}

.left 
{
  width: 60%;
  display: flex;
  flex-direction: column;
}

.left-image
 {
  height: 50vh;
  width:95%;
}

.right 
{
  width: 40%;
  display: flex;
  flex-direction: column;
}

.right-image 
{
  height: 50vh;
  width: 100%;
}

.quote 
{
  display: flex;
  padding: 1.5rem;
  border-bottom: 0.1px solid #F5F5F5;
}

.about {
    display: flex;
    justify-content: flex-end;
    font-weight: 250;
    color: gray;
  }

.content 
{
  display: flex;
  font-size: 2.5rem;
  justify-content: flex-start;
  margin: 0px;
}



```

## Output
![Screenshot 2023-06-04 121738](https://github.com/Gowri4622/storm/assets/75235455/2c29803a-16ca-4a0d-a069-6666b8dda2f0)


## Result
The Flexbox concept is implemented and verified.
