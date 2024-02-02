## Onshape Certification Prep: The Swing Arm


### Assignment Description

  * One of the goals of this class is to get you ready to earn your Certified Onshape Associate certification. This is a timed test that requires mastery of many different CAD concepts. As Engineering 3 or 4 students you have worked extensively with CAD, but you may have a different level of mastery from your fellow students. This assignment will help you determine what additional concepts you need to focus on for the certification exam. 

### Evidence

  * ![image](https://github.com/akondo58/engineering3/assets/143534857/8627ce73-d363-47c3-b23a-76396fb86855)

  * ![image](https://github.com/akondo58/engineering3/assets/143534857/eae74bd6-faba-48f0-b967-1e200b71a984)


### Part Link 

   * https://cvilleschools.onshape.com/documents/2ea21ed135423ced48656dc8/w/1e3e233dd8ee1e752dd00b34/e/b0d8931afd4d8e73498070d7?renderMode=0&uiState=6537dee2a500002c13dae79f


### Reflection

   * This assignment was hard for me because I was not used to onahape this assignment helped me get used to onahpe. hard and I work with my friends and I help them also in this part of onshape I like onahspe and I enjoy onshape.
   *  For this assignment there was two parts and different masses the first mass was 871.72 and the second one was 2389.8.
____________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________
##  Practice design from onshape : The hanger


### Assignment Description
  The purpose of this assignment is to design a hanger and practice with onshape
  and have to match the mass  from your design to the assignment mass

 

### Evidence
![Screenshot 2023-10-26 11 17 22](https://github.com/akondo58/engineering3/assets/143534857/b8d270f6-60f0-4469-9ac8-efcc9ba3f022)
<img src="blob:chrome-untrusted://media-app/8e8bc796-65a9-4660-94f5-47023c27af23" alt="Screenshot 2023-10-26 11.18.13.png"/>![image](https://github.com/akondo58/engineering3/assets/143534857/e00dd788-b7e1-4275-9dc4-a716f59c8225)

### Part Link 
https://cvilleschools.onshape.com/documents/7be537867b4571f12e72676a/w/9591afca90b894658b8b3a9f/e/14e722a00904493bd9c2d096?renderMode=0&uiState=653a839b61bc7d2483d15a86


### Reflection
The hanger  was easy to build and design. it was fun too because it made me get used to onshape after summer break
the teacher also helped me to finish the assignment
______________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________
 
##   photointerrupters

### Description and Code
 I need to Wire up your photointerrupter and have it keep track of how many times it has been interrupted.
Your program outputs the count using a full sentence like "The number of interrupts is: ___" or "I have been interrupted ___ times."
The program outputs the sentence every 4 seconds.
Don't use sleep(), use time.monotonic()Links to an external site. .
For your submission, if you have an LCD working, you can just take a video of you interrupting and then show the LCD.  Otherwise, you'll need to take a screenshot as well and upload that to your github repo.

  * from digitalio import DigitalInOut, Direction, Pull
import time
import board

interrupter = DigitalInOut(board.D7)
interrupter.direction = Direction.INPUT
interrupter.pull = Pull.UP

counter = 0

photo = False
state = False

max = 1
start = time.time()

while True:
    photo = interrupter.value
    if photo and not state:
            counter += 1
    state = photo

    remaining = max - time.time()

    if remaining <= 0:
        print("Interrupts:", str(counter))
        max = time.time() + 1
        counter = 0

### Evidence
https://img_5041.1.mov/

### Wiring  
![image](https://github.com/akondo58/engineering3/assets/143534857/ece292ad-aa70-4726-95e3-51644d6385d6)


### Reflection

This assignment is not easy and not hard because when I start this assignment it take me a lot of time because of coding so the thing was that my coding was right but the Photo-interrupters was not working and I pet so many different coding but the thing was that my coding was not working I ask for help from teacher and the teacher tell me that my Photo Interrupters was not working.

_______________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________


##  Practice design from on shape : alignment plate


### Assignment Description

The Onshape CAD Challenges are a great way to practice for the Onshape Certification Exam. These challenges record the time you spent designing your Onshape document and allow you to compare your results with the average amount of time spent. It also checks your work automatically when you record the mass of a part. 


 
### Evidence
![image](https://github.com/akondo58/engineering3/assets/143534857/8498342a-3126-4cfa-8340-6c7e3c363cfb)

![image](https://github.com/akondo58/engineering3/assets/143534857/854dc662-2da8-476a-9034-6e94192d540a)

![image](https://github.com/akondo58/engineering3/assets/143534857/9b1793da-7d45-444a-a251-56ab4c181088)


### Part Link 
https://cvilleschools.onshape.com/documents/9f62f95744bfe458ad7f1b1a/w/68d88d859b5e8417f3b312d4/e/64ad56451042499a39d9fe26?renderMode=0&uiState=654d0ae5fce6cc5c6a9d0efd



### Reflection
 this assignment helped me learn more about how to use new tools on Onshape, it was a little bit hard but with the help of my friends 
 I did it 




_____________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________
## CircuitPython Distance Sensor


Description & Code Snippets
I've broken the assignment into 3 stages, to make your life easier:

Use the HC-SR04 to measure the distance to an object and print that out to your serial monitor or LCD in cm. Next, you will get the neopixel to turn red when your object is less than 5cm, and green when its 35cm. Ignore the blue and 20cm for now, let's just keep it simple. For your final version of this code, you'll smoothly shift the color of the onboard neopixel, corresponding to the distance, according to the graphic below. (Neopixel should stay red when below 5cm and green when above 35cm)

if  btn2.value:
    print("BTN2 is pressed")
   

time.sleep(0.1) # sleep for debounce

### Evidence
https://www.wevideo.com/class#view-media/3196343174/
https://www.wevideo.com/class#view-media/3196343047/
### Wiring 

![image](https://github.com/akondo58/engineering3/assets/143534857/ee51969e-aec7-4b7e-960a-b977bfccb24a)

### Reflection

In this assignment, I had little trouble with the coding pats but i finally did   and more wiring and the goal was that it should show us the Distance and help us to get used to coding.
___________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________


##  Practice design from on shape :  awssemblies 

### Assignment Description
OPEN THIS DOCUMENT: CLICK HERELinks to an external site.

Follow the instructions for each question. Refer to the Certified Onshape Associate Practice Exam if needed.Download Refer to the Certified Onshape Associate Practice Exam if needed.

Record the answer from the following options detailed in the instructions.

Enter the answer into this quiz. 
 


 
### Evidence
![image](https://github.com/akondo58/engineering3/assets/143534857/d0d3d56c-c472-4848-b1c6-43a34b0d056e)
![image](https://github.com/akondo58/engineering3/assets/143534857/70211aba-52be-422a-8386-d3edb8b6e123)
![image](https://github.com/akondo58/engineering3/assets/143534857/986087c0-c1bd-4a4f-a9c8-0d6c5d0a8348)

### Part Link 
https://cvilleschools.onshape.com/documents/c675ac33775d3baadcc0c393/w/e894dcc51aaebf0248026b76/e/c15df9e3f003d8d8d843e381?renderMode=0&uiState=656a0a8127b95c4624082e2b

### Reflection
 this assignment helped me learn more about how to use new tools on Onshape, it was not that hard because it was just assemblies stuff
_________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________
Motor control

The goal of the assignment was to control motor with the speeding button.
I accomplish to my goal by using goal and ask firend for help and using my idea also I take a step by step top accomplish to my goial.
motors can draw a lot more juice (current) than LEDs. In fact, they draw so much current, we don't want to power them directly from the Arduino. That might fry the Arduino. So, we will power our motor directly from a 6 V battery pack.
    import time
    import board
    import pwmio
    from analogio import AnalogIn
    from digitalio import DigitalInOut, Direction, Pull

    motor = pwmio.PWMOut(board.D9, frequency=50)




   pot = AnalogIn(board.A1)



while True:
     print(pot.value)
     time.sleep(0.1)
     motor.duty_cycle=pot.value
Evidence
![image](https://github.com/akondo58/engineering3/assets/143534857/c8c76870-2724-4188-93a5-2c067ee8569b)

Wiring
![image](https://github.com/akondo58/engineering3/assets/143534857/cffd2dce-eb5d-45eb-b23d-85809a861764)

Reflection
It is very helpful to use something like a Motor because it can go forward and backward when I was using the Motor it was fun for me because it is going forward and backward but it is more when you are using the Motor on your projects. whenever I have projects I use motor control or TT motor. However, the motor control is something to use in your project. It was a little hard to find the wiring but the code was easy to find for motor control it was a very short code for motor control and I ask Liam and Irfan to help me record and help me on the assignmemt

___________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________     
 
photointeruptor

Description & Code Snippets
The goal of the assignment was to use the Photointerrupters.
I accomplish to my goal by using my ideas and ask firend for help and using my friend idea also I take a step by step top accomplish to my goial.
Photointerrupters Wire up a circuit that will turn on when something is in between the legs of the photointerrupter.


  * from digitalio import DigitalInOut, Direction, Pull
import time
import board

interrupter = DigitalInOut(board.D7)
interrupter.direction = Direction.INPUT
interrupter.pull = Pull.UP

counter = 0

photo = False
state = False

max = 1
start = time.time()

while True:
    photo = interrupter.value
    if photo and not state:
            counter += 1
    state = photo

    remaining = max - time.time()

    if remaining <= 0:
        print("Interrupts:", str(counter))
        max = time.time() + 1
        counter = 0


   ### Evidence
        IMG_5041.1.mov 


    ###   Wiring
    ![image](https://github.com/akondo58/engineering3/assets/143534857/a9703edf-0587-4669-b508-2c23f87a4a17)

