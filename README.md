# Microbit - receiver and transmitter
Type short word (only letters) and send it to other 4 micorbits to show it (only one word per microbit) - all with some basic animations and easy controls. 

# Controls
*You have to have more then 1 microbit - in default, there is 5 microbits, transmitter included. If you want add more, just put more numbers in the list in the top left corner but with the correct name ofc. To reduce the number of microbits, you don't have to - it will work as well but I don't think, you can create such an original word only with 3 letters*
1. Put all your microbits at one line next to each other. With the A and B button choose the position in the line and to confirm it with presssing both buttons at the same time.(the first reciever ist with the number 1). Then put the transmitter as the first one and choose the number 0 and confirm it (A+B). To be sure if you have done it correctly, make sure that the recievers have some kind of animations - the first one (transmitter) should show the letter A (as in the alphabet).
2. Now with the buttons A and B (again) choose the first letter of your word. Make sure your word has maximum of 5 letters (if not then make sure to read *ADD MORE MICROBITS* below this). To confirm, push A and B buttons at the same time - it should make a small animation.
3. To transmit the word, shake the first microbit (number 0). At fitst, it will show the whole word and then you can watch the animations going from the first microbit to the last. When the animation ends it will show the one of the letter - depends to the order.
4. Pushing down both of the buttons at the same time on the first microbit (number 0), you will reset it.


ADD MORE MICROBITS
1. Put more numbers in the top left list with the correct name of course.
2. In the block, which controls the button A: *in the second block/condition*
- change *set N to 4* to *set N to 5*
4. In the block, which controls the button B: *in the second block/condition*
- change *if KONEC LOADING=0 and N=4* to *if KONEC LOADING=0 and N=5*

REDUCE THE NUMEBER OF MICROBITS
*You don't have to change anything - it will work as well but I don't think, you can create such an original word only with 3 letters*

# Screenshot of all
![Transmitter and Reciever](https://user-images.githubusercontent.com/91016931/134230465-1edfbc18-ac79-4200-abe5-e9f22e0dd236.png)

# Body explanation
-"konec loading" = devides the whole process to parts, so you can use the buttons for more than one thing
-"seznam" = possibe numbers of the microbits
-"n" = position of the microbit
-"abeceda" = all of the letters of alphabet
-"od shora dolu" = animation from the top to the bottom
-"ze zdola nahoru" = animation from the bottom to the top
-"ulož" = set the current letter
-"ulož2" = saves all chosen "ulož" *unites all "ulož"*
...
*other thing are easy to understand*

# Screenshot of parts
1. Animations (animace)
![Animace](https://user-images.githubusercontent.com/91016931/134230492-fa6a783b-3fcc-46ce-852a-111de7935c9e.png)
2. Transmitter (vysílač)
![Transmitter](https://user-images.githubusercontent.com/91016931/134230510-1cebcbb2-2120-4dbd-93a8-85fe3d1d7f59.png)
3. Reciever (příjmač)
![Reciever](https://user-images.githubusercontent.com/91016931/134230526-4ace3512-925c-4f89-b643-b730811b2ced.png)
