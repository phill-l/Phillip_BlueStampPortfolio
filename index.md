# Third Eye For The Blind
Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails!

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Phillip L | Bellarmine College Preparatory | Bioengineering | Incoming Senior

**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)
  
# Final Milestone
For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Second Milestone
For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone

My second milestone is making modifications to the function of the system and modifying the code to fit these modifications. For this modification, I added a switch to change between two different ranges on the sensor. One setting is an "Indoor" mode and has a shorter range that will start signalling at 100 cm away from the sensor. Those with visual impairments will be able to use this setting in more crowded areas where there are more objects in a close proximity. The next setting is an "Outdoor" mode which has a larger range that will start signalling at 300 cm away. This setting would be used for larger, open areas. One challenging part of this milestone was creating the code to go with the switching of settings. I had to learn new techniques and change them to make them work with my situation. The final task that needs to be done before completing my project will be taking my project off the breadboard. I will need to work with connecting wires together and making the whole system work. Also, I will need to measure out all the wires lengths to make sure I have the correct dimensions for the final product.  The final product will be connecting the system to a baseball hat, with the sensor on the bill of the cap.

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# First Milestone
For your first milestone, describe what your project is and how you plan to build it. You can include:
- An explanation about the different components of your project and how they will all integrate together
- Technical progress you've made so far
- Challenges you're facing and solving in your future milestones
- What your plan is to complete your project

My project is the Third Eye for The Blind. In this project, I am using an ultrasonic sensor, a small vibrating motor, a buzzer, a switch, an LED light, and Arduino Micro. For my first milestone I created and coded a working system of this project on a breadboard. I was able to complete this task and got the project working. Once an object is close enough to the sensor the LED light flashes and either the buzzer or the motor turns on, depending on what side the switch is on. As the object gets closer to the sensor, the buzzes and flashes happen more frequently. A few challenges I had while making it to this first milestone were familiarizing myself with the materials and processes needed to complete this project. I needed to introduce myself the skills of soldering, breadboarding, and coding with Arduino. One problem I hope to fix with my project for the next milestone is a difficulty with the LED light. When the switch is on the buzzer, the LED light is very dim, but when flipped over to the motor, the light flashes significantly brighter.


**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/QWr6G2qiXZ8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```

# Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Arduino Pro Mini | Stores the code and allows the system to work when connected to power | $10.95 | <a href="https://www.amazon.com/Arduino-Pro-Mini-328-16MHz/dp/B004G53J5I/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Ultrasonic Sensor | Senses the proximity of nearby objects | $8.99 | <a href="https://www.amazon.com/Smraza-Ultrasonic-Distance-Mounting-Duemilanove/dp/B01JG09DCK/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Buzzer | Buzzes when triggered | $6.98 | <a href="https://www.amazon.com/mxuteuk-Electronic-Computers-Printers-Components/dp/B07VK1GJ9X/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Vibrating Motor | Vibrates when triggered | $10.69 | <a href="https://www.amazon.com/tatoko-vibration-Waterproof-8000-16000RPM-toothbrush/dp/B07KYLZC1S/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Perfboard | Connects all the components of the system | $9.99 | <a href="https://www.amazon.com/ELEGOO-Prototype-Soldering-Compatible-Arduino/dp/B072Z7Y19F/"> Link </a> |
|:--:|:--:|:--:|:--:|
| 5mm Red LED | Flashes on and off when triggered | $5.99 | <a href="https://www.amazon.com/Diffused-Lighting-Electronics-Components-Emitting/dp/B01C3ZZT0A/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Slide Switch | Switches the system between using the buzzer and using the motor | $5.39 | <a href="https://www.amazon.com/HiLetgo-SS-12D00-Toggle-Switch-Vertical/dp/B07RTJDW27/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Female Header 8 Position 1 Row (0.1") | What the item is used for | $5.99 | <a href="https://www.amazon.com/HiLetgo-Single-Female-2-54mm-Vertical/dp/B00VVI1L1W/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Male Header 40 Position 1 Row (0.1") | What the item is used for | $10.99 | <a href="https://www.amazon.com/ZYAMY-2-54mm-Breakable-Straight-Connector/dp/B0778KCHHR/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Jumper wires | Connects different parts of the system | $11.99 | <a href="https://www.amazon.com/AUSTOR-Lengths-Assorted-Preformed-Breadboard/dp/B07CJYSL2T/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Power bank | Suppplies power to the system | $17.99 | <a href="https://www.amazon.com/Anker-PowerCore-Ultra-Compact-High-Speed-Technology/dp/B01CU1EC6Y/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Soldering iron | Solders all the wires together | $16.99 | <a href="https://www.amazon.com/Soldering-Kit-Temperature-Desoldering-Electronics/dp/B07GTGGLXN/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Hot Glue Gun and Hot Glue Sticks | Allows the system to be glued onto a wearable piece of clothing | $27.49 | <a href="https://www.amazon.com/Gorilla-8401509-Hot-Glue-Sticks/dp/B088HF5ZQ1/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Baseball Hat | Makes the system wearable | $9.95 | <a href="https://www.amazon.com/NPJY-Baseball-Adjustable-Original-Unconstructed/dp/B0BPXDDQF3/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|


# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
