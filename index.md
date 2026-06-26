# Shuttle Motion Simulator
The Shuttle Motion Simulator uses a cable controlled model shuttle to simulate landing and docking maneuvers. It is a simple way to model real-world docking events.


```HTML 
<!--- This is an HTML comment in Markdown -->
<!--- Anything between these symbols will not render on the published site -->
```

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Ethan W | Basis Independent Silicon Valley | Mechanical Engineering | Incoming Sophomore

**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)
  
# Final Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**



For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE



# Second Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**



For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone 

# First Milestone
<iframe width="560" height="315" src="https://www.youtube.com/embed/MAaRaNteI0c?si=KQu6bAZFjkO3p2qe" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
I finished the frame, completed the wiring, attached the servos, and uploaded the Arduino program. The servos all work, but I haven't tested them with the cables, as I am still waiting on the dowels. I also began designing the lander module model to place within the frame.

# Starter Milestone
<iframe width="560" height="315" src="https://www.youtube.com/embed/oA3Xlxy_Wso?si=tPOvhmSEODm8cOr3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> 

My starter project, the Weevil Eye, is a simple build which lights up when the environment around it is dark. It uses a photoresistor in order to change light output as light in the environment decreases because its resistance varies with light exposure.
 



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

| Elegoo Uno R3 | supports code for servo responses to input | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| PVC pipe|forms frame| $10.20 | <a href="https://www.amazon.com/1-1-Schedule-40-PVC-Pipe/dp/B0C547346F?th=1"> Link </a> |
| 3 continuous servos| control cable lengths through rotation | $9.82 | <a href="https://www.pololu.com/product/2820"> Link </a> |
| breadboard| connects buttons and servos to arduino | $7.99 | <a href="https://www.sciencepurchase.com/products/03mb801?variant=39970685583533&currency=USD&utm_source=google&utm_medium=organic&utm_campaign=SP%20-%20Google%20Shopping&utm_content=Solderless%20Breadboard%2C%20400%20Tie-Points%2C%202%20Distribution%20Strips%2C%203.3%20x%202.1%20x%200.3%20Inches&gad_source=1&gad_campaignid=19633918734&gbraid=0AAAAAohSh8DXgBlEBmZVh0XJjJS3tojJR"> Link </a> |

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
