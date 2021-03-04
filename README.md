# Calculator-using-xcode

  Created a Basic Calculator in swift Language using XCode. This Program describes the thought of using the normal basic calculations. Initially it is build up using
StoryBoard with the help of UIButtons and UILabel. There are many UIButtons so using the option of "tag",giving each button a new tag,just connected "numbers" UIButtons to the single 
function called "numberCharacterEntered" of the ViewController and remaining "characters" such as +,-,*,/ to the character entered function of the ViewController.
Meanwhile UILabel is connected normally to the View Controller as "displayLabel".
 
  Then initialized variables such as previous number,present number and operation. 
  
In this "numberCharacterEntered" function, UILabel just displays the number that is entered through UIButton and is given to the present number. 
  
  But in the "characterEntered" function using "if" and "else if" statements we can perform basic calculation operation. The condition states the if text is not equal
to empty string and button "AC" ie., Tag 16 not pressed and button "=" ie., tag 15 is not pressed then it shows the following text in the UIlabel by pressing their
respective operators.

  Menwhile the number entered second is inside the variable previous number.

   Although the same concept of else if plays the roll, that when the condition of UIbutton "=" ie., tag 15 is true then the following operations takes place to their 
respective operators selected. and the UILabel displays the result.

  The last button "AC" ie,. tag 16 is pressed then then it sets all the variables to zero such that it removes the number from the UILabel.
  
  
  
  
