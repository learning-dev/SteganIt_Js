# SteganIt_Js
a JavaScript tool which implements steganography

SteganIt is a tool written in Js which does the following. 
   1. Prepares the container image
   2. Prepares the image to be hidden
  The project is in early stages. Most of the things should be done manually like resizing the image. 
  
  Algorithm 
  
We are taking two images and risizing the images to same dimensions. We are running the function "chop2hide" one container image( image which stores the image) to chop the left most bits and function "shift" on other image( which is to be hidden) which shifts the values towards right. Then, we run combine function which hides the second image in the first image. There is also an extract function which can be used to extract the image which is hidden.
  
  Url: http://codepen.io/daringdev/pen/grgRrb
  
  How to use this environment -http://www.dukelearntoprogram.com/course1/example/index.php
  and Upload the images and compile the code in the above environment. 

This the final assignment of the Course - Programming and the Web for Beginners on Coursera. 

FAQs
  
  The script is not working. Where I went wrong?
  1.Use the given environment to execute the script. As there are some functions which cannot be used outside the given environment. 
  2. Resize the image to the same size. 
  
  
  I wanna make this tool better. How should I get started?
  Please email me at mohammed[dot]ayaz[at]protonmail[dot]com
  
  When can I expect full working tool?
  It depends on my time and my prioties. Self help is the best help. Start learning things and you may improve this tool. 
  
