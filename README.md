This is a C++, OpenCV-based project.

The project was based on Visual Studio 2022 and OpenCV 4.9.0-window.

@@caution!!@@
First, OpenCV must be linked in Visual Studio. 
Of course, you must install OpenCV first and then link it.
The above is not described in this project.
Let's assume that the above has been done.

If you check the second line of the main function, you can see that the location of the pic_1 file is stored in C. Please specify a storage space that suits your computer situation.

Cause I'm Korean, I've added a Korean description to the code annotation, and Korean can be found throughout other projects. If you're feeling difficult, I recommend using a translator.
@@caution!!@@

![image](https://github.com/user-attachments/assets/b480bc6d-ac3c-497b-803a-df54e84b538a)

How to play the game
The project is planed to create a Halli Galli game, and when it starts, you'll have a computer-to-human match. 
By looking at the pic_1 file, you'll see a picture of one to five circles of the same color.
When you are ready press button b. ( It is same button with bell)
The winning formula for the game is simple. When five circles of the same color gather on the screen, you can press the bell (b) within 0.5 seconds.  
If you can't ring the bell in 0.5 seconds, you'll be dealt with a defeat and if you don't have 5 circles of the same color, you'll get an image of a defeat when you ring the bell, but the game will continue. This is to apply the rules of the real game.

If you have any other difficulties or problems, please feel free to tell me.

Thank you.
