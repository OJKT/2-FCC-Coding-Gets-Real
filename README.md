<!DOCTYPE html>
<link href="https://fonts.googleapis.com/css?family=Poor+Story" rel="stylesheet">
<link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css">
<html>
  
  <style>
  h1 {
    font-family: Poor+Story, 'Open Sans'
  }
  </style>
  
  <head>
    <title>
      <h1 style="color: red;">Coding-Gets-Real</h1>
    </title>
  </head>
  
  <style>
    p {
      color: purple;
    }
    li {
    color: red;
    }
  </style>
  
  <style>
    .orange-text {
      color: orange;
    }
    p {
      font-size: 16px
    }
    h4 {
      font-family: monospace;
    }
    .silver-background {
      background-color: silver;
    }
  </style>
  
  <!--
    <body>
      <p>I have shown three different methods above on how to color text; firstly just changing the h1 title style indiviuly, Use of CSS       Selectors to create style elements and finally using a CSS Class to Style Elements. you can do this to multiple elements in one CSS selector demonstrated above, and multiple elements with a CSS class demonstrated below. I have changed the font size of paragraphs, because its pointless doing it to a h element (or so I figured) so I changed the font-family of h4. maybe this is not working because the font is not pre-saved by github... or somthing like that. so im going to check out getting a google font, like explained in the list below. When one font isn't available, you can tell the browser to "degrade" to another font. As I have done with the 'poor story' font, I 'degraded' to 'Open Sans.'</p>
    </body>
  -->
  
 <body>
      <p class="orange-text silver-background">I will continue on from hello-world to create a more basic information I can come back and refer to</p>
      <h4>In this section I will cover the following basic CSS</h4>
      <ol>
        <li>Changing color of text and other elements</li>
        <li>importing a google font and uses of these fonts</li>
        <li class="orange-text">adding borders to elements</li>
        <li>formating images and editing them</li>
        <li>Introduction to Hex code and RGB</li>
      <ol>
 </body>
 
 <style>
  .smaller-image {
    width: 50px;
  }
  
  .thin-red-border {
    border-color: red;
    border-width: 5px;
    border-style: solid;
    border-radius: 10px;
  }
  
  .thick-green-border {
    border-color: green;
    border-width: 10px;
    border-style: solid;
    border-radius: 50%;
  }
  
  #list-form {
      background-color: silver;
  }

 </style>
 
 <h4>Here Is a Cat<h4>
 <a href="#"><img class="smaller-image
  thick-green-border" src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>
    <p class="thin-red-border, orange-text"> why is there a cat? why have I used this image? Well this is a lesson, I have surpassed the first 2 list Items above. Get onto the editor development to start learning it! <p>
  </caption>
  <!--
    <p>For not knowing staggered coding and section titles, such as heading body and cpation or legend, I have done really well to get an image in, having struggled before on previous repositories. for some reason again the CSS style elements are apearing on preview and are not working... not sure why... I keep trying to find out, but it must be githubs software. I must look for an adequate software to download and begin on (any suggestions?).</p>
    <p> remember you can add more than one class to an element, I chose the image from the free code camp lessons. If my lessons dont cut it they will... boarders around the elements don't seem to work with github on both texts and images. nevertheless note that a border radius set using pixels will likely create ronded edges to your borders or text boxes, note if you use 50% you will create a circle</p>
<p> I will attempt to change background to elements to create what I would call'text boxes'. knowing fine well it probably wont show on a github server.</p>
<p>See I have changed the ID attribute of the div using a hash</p>
  -->
 <div>
    <p>Things I think github lacks (maybe doesn't, I'm new):</p>
    <ul>
      <li>colour coded scripts</li>
      <li>auto-correct and fill scripts</li>
      <li>Different coding languages are not applicable ?</li>
    </ul>
    <p>Top 3 HTML5 Elements missing:</p>
    <ol>
      <li>Style Elements</li>
      <li>anchor Elements</li>
      <li>Form Elements</li>
    </ol>
 </div>
 
 <p>I'm going to test Free code camps code in a new repository called, 'TEST-FREECC' please check it out</p>
 
 <style>
  #cat-photo-form {
    background-color: green;
  }
 </style>
 
 <form action="/submit-cat-photo" id="cat-photo-form">
    <label><input type="radio" name="indoor-outdoor" checked> Indoor</label>
    <label><input type="radio" name="indoor-outdoor"> Outdoor</label><br>
    <label><input type="checkbox" name="personality" checked> Loving</label>
    <label><input type="checkbox" name="personality"> Lazy</label>
    <label><input type="checkbox" name="personality"> Energetic</label><br>
    <input type="text" placeholder="cat photo URL" required>
    <button type="submit">Submit</button>
  </form>
 
   <style>
    .injected-text {
      margin-bottom: -25px;
      text-align: center;
    }
    .box {
      border-style: solid;
      border-color: black;
      border-width: 5px;
      text-align: center;
    }
    .yellow-box {
      background-color: yellow;
      padding: 10px;
    }
    .red-box {
      background-color: crimson;
      color: #fff;
      padding: 20px;
    }
    .blue-box {
      background-color: blue;
      color: #fff;
      padding: 20px;
    }
  </style>
  <h5 class="injected-text">margin</h5>

  <div class="box yellow-box">
    <h5 class="box red-box">padding</h5>
    <h5 class="box blue-box">padding</h5>
  </div>

 <!--
  <style>
      .red-box {
        background-color: crimson;
        color: #fff;
        margin: 20px 40px 20px 40px;
      }
      .blue-box {
        background-color: blue;
        color: #fff;
        margin: 20px 40px 20px 40px;
      }
      [type='checkbox'] {
        margin: 10px 0px 15px 0px;
      }
      [type='radio'] {
        margin: 20px 
      }
  </style>
  <p> 
    You can also use clockwise notation to save lines... if you have a line limit... but I would suggest going full out so that     you dont get confused and other developers can quickly understand what their changing despite their experience. Under that       style I have also showed Basic CSS: Use Attribute Selectors to Style Elements. Note: There are several relative unit options     that are tied to the size of the viewport. They are covered in the Responsive Web Design Principles section.
  </p>
  <style>
    body {
      background-color: black;
      font-family: monospace;
      color: green;
    }
    #orange-text {
      color: orange;
    }
    .pink-text {
      color: pink;
    }
    .blue-text {
      color: blue;
    }
  </style>
  <h1 id="orange-text" class="pink-text blue-text" style="color: white">Hello World!</h1>
  <p>
    Overideing styles... as above to have the h1-text pink in order of how specific the codde is... so the h1 is first pink,         then white, then orange, then blue, then pink agian ?!, then green... mental eh.... so many different ways of colouring         text... .. in order of element importance... see if you can follow the resoning of the color order above ^^
  </p>
 -->
   <style>
    .red-text {
      color: #FF0000
  ;
    }
    .green-text {
      color: #00FF00;
    }
    .dodger-blue-text {
      color: #1E90FF;
    }
    .orange-text {
      color: #FFA500;
    }
        .red-text {
      color: #F00;
    }
    .fuchsia-text {
      color: #F0F;
    }
    .cyan-text {
      color: #0FF;
    }
    .green-text {
      color: #0F0;
    }
  </style>

  <h1 class="red-text">I am red!</h1>

  <h1 class="green-text">I am green!</h1>

  <h1 class="dodger-blue-text">I am dodger blue!</h1>

  <h1 class="orange-text">I am orange!</h1>
  <h1 class="red-text">I am red!</h1>

  <h1 class="fuchsia-text">I am fuchsia!</h1>

  <h1 class="cyan-text">I am cyan!</h1>

  <h1 class="green-text">I am green!</h1>
  
  <p> 
    I Have used color text to describe colours... above i have used both short... and long hex codes in the hope that github         will pick it up 
  </p>
  <style>
    .red-text {
      color: rgb(255, 0, 0);
    }
    .orchid-text {
      color: rgb(218, 112, 214);
    }
    .sienna-text {
      color: rgb(160, 82, 45);
    }
    .blue-text {
      color: rgb(0, 0, 255);
    }
  </style>

  <h1 class="red-text">I am red!</h1>

  <h1 class="orchid-text">I am orchid!</h1>

  <h1 class="sienna-text">I am sienna!</h1>

  <h1 class="blue-text">I am blue!</h1>
  
</html>
