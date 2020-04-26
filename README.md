# Sissi_CCA_Mechatronic_2020
Mechatronic HW &amp; Exercise

# Week 15 (Final Project Presentation)
-----------------------------------------------------
## "Hello ～ From The Other Side!"
- In the current situation, we are staying safe to keep a distance from other people, and even roommates are no exception. My design concepts have considered today’s special circumstances of COVID-19 and aim to help people communicate under quarantine through images. The Remote control communicator ("Hello～From The Other Side")  allows the user to express emotion across the other side of the room. 

![TCS](/image/PixelToMatrix.PNG)

###  Schematic:

### Breadboard:

### Code:
-  Locate in "FinalProject-Final" Folder

### HOW IT WORKS:
- The user in the room needs to use the remote control to press the corresponding expression button on the remote. At the same time, the LED matrix in their roommates' room will receive an image the user sends. It allows their roommates across the room will see the user's current mood without contact; they will immediately understand the user's feelings and reply by doing the same thing.

- Video Link:

# Week 14 (Final Project Part 2)
- This week through online research I learned how to write code in the ardurino to display images on the 8*8 LED Matrix. After reading some articles, I found a software called "Pixel To Matrix," which allows me to design the image I want on the computer and get the corresponding code that I can input to the Arduino. I drew three different expressions: smile😊, neutral😔,and frown😫 on the computer. I asked them to be displayed on my matrix in the loop. My next step is to connect and control the three expressions through the IR remote.

### Software:

![TCS](/image/PixelToMatrix.PNG)

### Schematic:

![TCS](/image/Schematic_2.png)

### Breadboard:

![TCS](/image/Breadboard_2.png)

### Code:
- Locate in "FinalProject-Part 2" Folder

### HOW IT WORKS:

![TCS](/image/Matrix.GIF)

### Resources: 
- 8*8 LED Matrix Tutorial: https://www.youtube.com/watch?v=vI3ipE2Wj8Y

# Week 13 (Final Project Part 1)
- This week, I searching online on how to use and collect basic data from IR remote and use it to control what you want to turn on and off. By watching the online tutorial, I learned how to read the receiver's data through the serial monitor and use the data to turn on and off of the led light from a distance. My next step is to learn how to use the 8*8 LED matrix with the Arduino and program the first emoji (A Happy face ˆ_ˆ).

### Schematic:

![LCD](/image/Fritzing2.png)

### Breadboard:

![LCD](/image/Fritzing1.png)

### HOW IT WORKS:

![LCD](/image/IRcontrol.GIF)

### Code:
- Locate in "FinalProject-Part 1" Folder

### Resources: 
- IR Receiver Electronic Brick : http://arduinoinfo.mywikis.net/wiki/IR-RemoteControl

# Week 12 (Final Project Proposal)
### Final Project Proposal
### #1 Remote Communicator (Hello from the other side):
- During this final project, I'd like to learn about how to use the IR Remote & Receiver. Because of the coronavirus, we were told to keep in distance with each other. For long-distance communication, I'd like to use the remote to play my roommate a particular melody that can make her day. And also, send messages (text/ voice/ or play a song) to my roommate living next to me (such as "Hi, Zoe ˆ-ˆ" ). We can communicate with 6 feet distance.This device can also be used outside for communication because we will be covered with the mask so we cannot see each other's face so we will need a device that can print my emotion or mood on the screen (8*8 LED Matrix)

![LCD](/image/Communicator.JPG)

### How it works: 
- When I push "1" on the remote, the first LED will light up to tell my roommate we will be communicated on Channel 1. Each channel will be different messages such as text message ("Hello Zoe!" "How's your day?"), When I push "2" on the remote, the second LED will light up to tell my roommate we will be communicated in Channel 2 which allow me to send her an emoji and she can use the remote to replay.

![LCD](/image/Flow.JPG)

### Must have:
- IR Remote control with the led light
- 8x8 LED Matrix (Print emoji)
- Message sent via the LCD Screen.


### Nice to have:
- Speaker to play the music or melody.
- Able to switch the melody. 
- Connect to computer processing to send images.

### Week One: Get the IR Remote & Receiver work, and be able to control the LED light on the Breadboard.
### Week Two: Able to Print emoji on an 8x8 LED Matrix and program to control by the remote. 
### Week Three: Connect the LCD screen to the project and send the message control by the remote.

### Sources: 
- IR Remote Tutorial:https://www.youtube.com/watch?v=3jeSfsnQOWk&t=1s
- 8x8 LED Matrix:https://www.hackster.io/SAnwandter1/programming-8x8-led-matrix-23475a

-----------------------------------------------------
### #2 Wearable Distance Reminder:

- In this situation, we have to be safe to keep a safe distance (six feet). My concept is to design a wearable distance safety reminder. When someone is close that 6 feet, the user will get a voice alert, and the warning light will light on to remind the person not to come up so close. 

![LCD](/image/DistanceReminder.JPG)

### Must have:
- Wearable device to take outside
- LED Light
- Voice Reminder

### Nice to have:
- A popup sign to show to the person ("Keep away from me !"


### Week One: Learn how to use the distance sensor and use it to control the LED light.

### Week Two: Add up the speaker and input the voice I want to say.

### Week Three: Create a popup sign that when the person comes close, a warning will pop up that tells the user to stop. 


# Week 7 (Midterm)
-Obstacle Avoiding Car Project (Group: Sissi, Zoey, Tianbai)

![LCD](/image/workingvehicle.GIF)

-Through this project, I learned to use the distance sensor. And use it to control four motors. When the distance between the obstacle and the car is less than 30, the inner wheels switch direction, and the car turns. Doing by the team, we can learn from each other and use teammates' strengths and also experience a large range of hardware with a well-accomplished project. After we did all these, we have time to add an led that lights up when the car turns and turns off when it's going in a straight line.

![LCD](/image/VehicleLED.GIF)

- Video Link: https://youtu.be/v_cpWiHK-LU

# Week 6
-This week I tried to make a car with moving wheels. I made an AI file that can be laser cut this car on cardboard, and the size needs to be further adjusted.
![LCD](/image/Minicars.png)

- In class, We decided to set up a team to build an electric car that could avoid obstacles. Doing by the team, we can learn from each other and use teamates' strengths and also experience a large range of hardware with a well-accomplished project.
![LCD](/image/Round1prototype.jpeg)

# Week 5
- This week I tried a new color sensor TCS34725 to identify the color of RGB, and my goal is to display the color on the led. But I face some connection problem, the light of my RGB did not light up. After several attempts, I still don't know where the issue is.
![LCD](/image/TCS.JPG)
-Update: I got this fixed in class.

# Week 4
-This week I did a small LED project: I decided to use a button to control the led. There are three LEDs total; they will switch light up every time I push the button.

![LEDs](/image/ButtonLED.GIF)
![LEDs](/image/ButtonLEDdraw.JPG)

# Week 3
- Drawing Machine
![Circle Machine](/image/DrawingMachine1.GIF)

# Week 2
- Check My Marble Ball project: https://www.youtube.com/watch?v=KI17auspEGo
![Marble Ball](/image/MarbleBall1.png)
![Marble Ball](/image/MarbleBall2.png)

# Week 1
![Marble Ball Process](/image/Process01.png)
