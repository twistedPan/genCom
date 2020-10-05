<h1>Generative Computer Graphics HS2020</h1>

## Week 1:
  - ### Day 1
  
  
      idea: 
      get Mic input and create interactable sketch

      problem: 
      Web technologies safety standarts

      Web browser didn't get the input from the mic, p5 was throwing error messages, some older sketches still working the new ones didn't worked.

      Solution:
      Took an older sketch and copy paste the mic part, 
      wrote a intro page to get trough the chrome safety part
      ( create user input before audio can play ), 

      realization:
      Mic input consists only of volume, no frequenzies possible.



<img src="https://github.com/twistedPan/genCom/blob/master/pictures/week1.1%20randomBubbles%20(1).png" width="30%" padding="5px">
<img src="https://github.com/twistedPan/genCom/blob/master/pictures/week1.1%20randomBubbles%20(2).png" width="30%" padding="5px">
<img src="https://github.com/twistedPan/genCom/blob/master/pictures/week1.1%20randomBubbles%20(3).png" width="30%" padding="5px">







  - ### Day 2
  
  
      idea:
      bubbles grow in size through the mic input
      bubbbles pop if they collide


<img src="https://github.com/twistedPan/genCom/blob/master/pictures/week1.2%20poppingBubbles%20(1).png" width="30%" padding="5px">
<img src="https://github.com/twistedPan/genCom/blob/master/pictures/week1.2%20poppingBubbles%20(2).png" width="30%" padding="5px">



      started to look at three.js
      idea: foggy Cube grid to work  

  

<img src="https://github.com/twistedPan/genCom/blob/master/pictures/week1.3%20startWithThreejs%20(1).png" width="30%" padding="5px">
<img src="https://github.com/twistedPan/genCom/blob/master/pictures/week1.3%20startWithThreejs%20(2).png" width="30%" padding="5px">







  - ### Day 3
  
      Finallized the microphone input handler

      continued to work with three.js

      learned about materials and geometries














### Week 2:



  - ### Day 1


      idea: Display each of the 1024 frequencies as point on a circle and create a soundwave-like circle.


      1. created a 2D sketch in p5.js 

    
<img src="https://github.com/twistedPan/genCom/blob/master/pictures/Week2.1%20prototype2D%20(1).png" width="30%" padding="5px">
<img src="https://github.com/twistedPan/genCom/blob/master/pictures/Week2.1%20prototype2D%20(3).png" width="30%" padding="5px">
<img src="https://github.com/twistedPan/genCom/blob/master/pictures/Week2.1%20prototype2D%20(2).png" width="30%" padding="5px">



      2. moved the whole thing to three.js


<img src="https://github.com/twistedPan/genCom/blob/master/pictures/Week2.2%20protoMovedToThreejs%20(1).png" width="30%" padding="5px">
<img src="https://github.com/twistedPan/genCom/blob/master/pictures/Week2.2%20protoMovedToThreejs%20(2).png" width="30%" padding="5px">
<img src="https://github.com/twistedPan/genCom/blob/master/pictures/Week2.2%20protoMovedToThreejs%20(3).png" width="30%" padding="5px">






  
  - ### Day 2


      Switched the cubes with lines and ended up playing with it the whole day
    
    
<img src="https://github.com/twistedPan/genCom/blob/master/pictures/Week2.3%20linesNoCubes%20(1).png" width="30%" padding="5px">
<img src="https://github.com/twistedPan/genCom/blob/master/pictures/Week2.3%20linesNoCubes%20(3).png" width="30%" padding="5px">
<img src="https://github.com/twistedPan/genCom/blob/master/pictures/Week2.3%20linesNoCubes%20(4).png" width="30%" padding="5px">
<img src="https://github.com/twistedPan/genCom/blob/master/pictures/Week2.3%20linesNoCubes%20(1).gif" width="30%" padding="5px">



    deactivated the canvas refresh mode 


<img src="https://github.com/twistedPan/genCom/blob/master/pictures/Week2.4%20noCanRefresh%20(2).png" width="30%" padding="5px">
<img src="https://github.com/twistedPan/genCom/blob/master/pictures/Week2.4%20noCanRefresh%20(3).png" width="30%" padding="5px">
<img src="https://github.com/twistedPan/genCom/blob/master/pictures/Week2.4%20noCanRefresh%20(4).png" width="30%" padding="5px">
<img src="https://github.com/twistedPan/genCom/blob/master/pictures/Week2.4%20noCanRefresh%20(1).gif" width="30%" padding="5px">


  
  - ### Day 3


    Spend the day trying to rearrange the blocks to have a progressive amount from center to end (hangover)
    Did it after 3 hours

    Calculating new positioning for cubes:

          old 16 * 64 / 64 . 64 . 64 . 64 . 64 . 64 .... 1024

          new
          8 . 12 . 16 . 24 . 32 . 333 . 64 . 96 . 128 . 192 . 333 . 384 ....	no

          8 . 16 . 24 . 32 . 40 . 333 . 54 . 62 . 68 . 74 . 82 . 90 . 98 . 106 ...  no

          6 . 12 . 18 . 24 . 30 . 36 . 42 . 333 . 54 . 60 . . . . . 106 = 1024 ok
    
    
<img src="https://github.com/twistedPan/genCom/blob/master/pictures/Week2.5%20sortedSectors%20(1).png" width="30%" padding="5px">
<img src="https://github.com/twistedPan/genCom/blob/master/pictures/Week2.5%20sortedSectors%20(2).png" width="30%" padding="5px">
<img src="https://github.com/twistedPan/genCom/blob/master/pictures/Week2.5%20sortedSectors%20(3).png" width="30%" padding="5px">


  Realisation:
    Math is even harder if you've a hangover.



### Week 3:



  - ### Day 1






  - ### Day 2







  - ### Day 3








