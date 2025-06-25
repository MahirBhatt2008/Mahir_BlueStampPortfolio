# Optical Character Recognition
Mahir Bhatt's portfolio for his summer robotics project

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Mahir B | Homestead High School | Mechanical Engineering | Incoming Senior


<img src="MahirB.png" width="450" height="600">

<!--
# Final Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**


For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE



# Second Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone 
-->

# First Milestone
<iframe width="560" height="315" src="https://www.youtube.com/embed/k87IMUkZeuk?si=inYRWzS7Dl8RDZRU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

My project is a Optical Character Recognition software that has a camera which looks for characters, and prints what characters the camera saw. To build this project, I first started by setting up my Raspberry Pi, which is the computer that contains the code for the project to work. To set up my Raspberry Pi, I followed a tutorial that helped me compile the parts together for the Pi to work properly, including attatching the Raspberry Pi camera to the motherboard. Then, I connected my Pi to a power source and my computer, and streamed the output of the Pi to a software on my computer called "OBS." My next step was to make the camera take pictures. To do this, I opened a new Python file in my Raspberry Pi software, and entered the proper code to take photos from the camera. These photos are stored as a single file in the Raspberry Pi, meaning each time you take a new photo, that photo overwrites the last photo. Currently, I am in the process of making the camera capture live feed, and brodcast it to my Raspberry Pi. I have found this to be very difficult and have had trouble coding this part.

<!---
For your first milestone, describe what your project is and how you plan to build it. You can include:
- An explanation about the different components of your project and how they will all integrate together
- Technical progress you've made so far
- Challenges you're facing and solving in your future milestones
- What your plan is to complete your project

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
-->

# Starter Project: Retro Arcade Game Console

<iframe width="560" height="315" src="https://www.youtube.com/embed/o0hxpk1ZnIw?si=7LS6ZI0-IqPjVep9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>



This project is a game board that has multiple different games that you can play, such as tetris. It has a start button, an end button, and 4 different buttons to let the user control what happens in the game. It also has a switch that turns the game board on/off. This project helped me gain better soldering skills.

# Schematics 
<img src="schematic.png">
# Bill of Materials: Retro Arcade Game Console
<!--
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 
-->

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Buzzer | Emits sound for alerts or signals | $1.48 | <a href="https://www.digikey.com/en/products/detail/soberton-inc/WST-1206UX/1245302?gad_source=1&gad_campaignid=20243136172&gbraid=0AAAAADrbLlhY9M3nUqqsyarwc_qMKusEt&gclid=CjwKCAjwvO7CBhAqEiwA9q2YJYYXGsf0jUZqDOTA14y7Kia2LQ5VwkYhJalravyX4HI_ZBvEOm5KtRoCokkQAvD_BwE&gclsrc=aw.ds"> Link </a> |
| Electric capacitor | Stores and releases electrical energy | $0.38 | <a href="https://www.digikey.com/en/products/detail/panasonic-electronic-components/EEU-FR1C221/2433527?gad_source=1&gad_campaignid=20228387720&gbraid=0AAAAADrbLljx--os3Oc-ERVDq4RA6mW2A&gclid=CjwKCAjwvO7CBhAqEiwA9q2YJXSsvPe9yKVBAn13_DxdN-5zDTu3uyHwzF0sb70BZF25uVkIMJZKcBoCeCEQAvD_BwE&gclsrc=aw.ds"> Link </a> |
| Micro USB | Connector for power or data transfer from a USB source | $1.02 | <a href="https://www.digikey.com/en/products/detail/kycon-inc/KMMX-BSMT35S-B30TR/9990231?gad_source=1&gad_campaignid=17336967819&gbraid=0AAAAADrbLljQ1XEqeAnpBEhhLVvQ0RmOT&gclid=CjwKCAjwvO7CBhAqEiwA9q2YJch7AeIPcqFWGTiXWI_gwZcN-MZE7zZu-pZeO7V634NsiVUDJxhlQRoCIlQQAvD_BwE&gclsrc=aw.ds"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |

<!---
# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
-->
