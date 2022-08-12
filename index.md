# Garden Monitoring System
Hi, my name is Aditi and I picked the garden monitoring system as my project. I was interested in this project because it has important real life applications, and on a bigger scale, could majorly help farmers maintain the health of their crops. This project works by using a soil moisture sensor to sense the amount of moisture in the soil, comparing that to the adequate value of moisture, and turning on a red or green LED depending on the result. It also buzzes to remind you to water your plant!

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Aditi | Fremont High School | Industrial Design | Incoming Junior | 

<p align ="center">
<a href="https://ibb.co/W5VkLBw"><img src="https://i.ibb.co/c3Y6j2H/unnamed.jpg" alt="unnamed" border="0" height="400" width="370"></a>
</p>

# My Project
Here is a photo of my finished project. 

<p align="center">
<a href="https://ibb.co/Ptnw4rZ"><img src="https://i.ibb.co/M94MpgD/image.jpg" alt="image" border="0"></a>
</p>

# Slideshow 
Here is the link to the slideshow I used to present on Demo Night.

<p align="center">
<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRlfkM2OK5UqNq05ZDzH8zxFgkVAdhnv4GeYBtHM1QzxNnnRvv5JQ-bD5VS345lmkIzw8xod2ipFmeU/embed?start=false&loop=true&delayms=3000" frameborder="0" width="550" height="325" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
</p>

# Final Milestone
For my final milestone, I tested the sensor and fine tuned it. Now, it works with 100% accuracy. Now that I added a battery, the arduino no longer had to be plugged into a computer to work, which made it much more portable. To make it even more condensed and easy to use, I used rubberbands to attach the arduino to the top of the breadboard and the battery to the bottom. Now, you can carry the entire machine in one hand and use the sensor with the other. Overall, I enjoyed making my project and thinking of modifications. My favorite part was using the tone() command to make the buzzer make noise, which was difficult, but rewarding when it finally worked. If I had more time, I would create something to cover the control board of the sensor like I mentioned in my milestone 2 video, but because it works very accurately and serves its purpose, I am satisifed.

[![Aditi Milestone 3](https://res.cloudinary.com/marcomontalbano/image/upload/v1660249528/video_to_markdown/images/youtube--1IBvHLctiQA-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=1IBvHLctiQA "Aditi Milestone 3"){:target="_blank" rel="noopener"}

# Second Milestone
For my second milestone, I added a buzzer. Now, when the soil is dry, the buzzer beeps repeatedly and the red LED glows. When the soil is sufficiently moist, the buzzer plays a short tune and the green LED glows. I learned how to use the tone() command to make the buzzer beep, which takes in 3 inputs : the pin the buzzer is connected to, the frequency of the note in hertz, and the duration in miliseconds. Taking inspiration from the sound a phone makes when you plug it in to charge, I made my own sound for the wet soil, and for the dry soil, played a repeated B flat. Another change I made was the addition of a 9 volt Energizer battery, because I wanted the device to be portable and not rely on a laptop for power. This week, the sensor was being innacurate but worked most of the time despite that. Next week, I'm going to focus on making something to hide all the parts of the device you don't need to see, like the arduino, breadboard, and battery. 

[![Aditi Milestone 2](https://res.cloudinary.com/marcomontalbano/image/upload/v1660249507/video_to_markdown/images/youtube--ewLE1gIv9vw-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=ewLE1gIv9vw&t=27s "Aditi Milestone 2"){:target="_blank" rel="noopener"}

# First Milestone

My first milestone was to get familiar with the sensor and to make a basic project that detects if there is enough moisture in the soil. There are two types of soil moisture sensors widely used - capacitive sensors and resistive sensors. Capacitive soil moisture sensors work by sensing the dissolved ions in the moisture. Resistive sensors work by measuring the amount of electricity conducted in the soil (dry soil conducts electricity poorly). I used the capacitive soil moisture sensor v1.2 because it is more accurate than its resisitive counterpart. When the sensor is in dry soil, the red LED glows and the message "Time to water your plant" is printed to the serial monitor. When the sensor is in wet soil, the green LED glows and the message "No need to water" is printed to the serial monitor. The biggest challenge I had with this first milestone was my sensor, because it wasn't giving me reliable values which casued a lot of issues. However, it suddenly started working so my overall project began working so that was relieving. 

[![Aditi Milestone 1](https://res.cloudinary.com/marcomontalbano/image/upload/v1660249479/video_to_markdown/images/youtube--0P7yvY682BA-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=0P7yvY682BA "Aditi Milestone 1"){:target="_blank" rel="noopener"}

# Materials
Below are all the materials required to create this project.

| Item | Amount | Price | Buy here |
| ------------- | ------------- | ------------- | ------------- |
| Arduino UNO REV3  | 1  | $24.49  | https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6  |
| Breadboard  | 1  | $8.75  | https://www.amazon.com/BB830-Solderless-Plug-BreadBoard-tie-Points/dp/B0040Z4QN8  |
| Jumper Wires  | 8  | $0.20 each  | https://www.amazon.com/BOJACK-Solderless-Flexible-Breadboard-Connecting/dp/B08YRPWC8L  |
| Capacitive Soil Moisture Sensor v1.2  | 1  | $6.99 for 3  | https://www.amazon.com/DAOKI-Capacitive-Corrosion-Resistant-Electronic/dp/B085XSQXC5 |
| LEDs  | 2 (1 red, 1 green)  | $6.99 for 100  | https://www.amazon.com/eBoot-Pieces-Emitting-Diodes-Assorted/dp/B06XPV4CSH |
| Resistors  | 2  | $6.93 for 100  | https://www.amazon.com/Projects-100EP514100R-100-Resistors-Pack/dp/B00AVSDYFO |
| Piezo Buzzer | 1  | $7.79 for 10  | https://www.amazon.com/a15091400ux0103-Electronic-Mounting-Passive-Sounder/dp/B018I1WBNQ |
| 9 Volt Energizer Battery | 1  | $7.99 for 2  | https://www.amazon.com/Energizer-2513-Alkaline-Battery-522BP/dp/B079NNB63D |

# Code
This is the code you have to use to calibrate your air and water values.

```
void setup(){
  Serial.begin(9600);
}

void loop(){
  int val;
  val = analogRead(0);
  Serial.println(val);
  delay(100); 
}
```

This is the code that actually determines if there is enough moisture in the soil or not, but you have to implement the air and water values you calculated using the code above in this part, otherwise it won't work. Replace airValue and waterValue accordingly.

```
int rainPin = A0;
int greenLED = 6;
int buzzPin = 11;
int redLED = 7;
int thresholdValue = 800;
const int AirValue = 442; 
const int WaterValue = 172; 
int intervals = (AirValue - WaterValue)/3;
int sensorValue = 0;
int soilMoistureValue = 0;
int runOnce = 0;

void setup(){
  pinMode(rainPin, INPUT);
  pinMode(greenLED, OUTPUT);
  pinMode(redLED, OUTPUT);
  pinMode(buzzPin, OUTPUT); 
  digitalWrite(greenLED, LOW);
  digitalWrite(redLED, LOW);
  Serial.begin(9600);
}

void loop() {
  // read the input on analog pin 0:
  soilMoistureValue = analogRead(rainPin);
  Serial.print(soilMoistureValue);
  if ((soilMoistureValue > WaterValue && soilMoistureValue < (WaterValue + intervals)) || (soilMoistureValue > (WaterValue + intervals) && soilMoistureValue < (AirValue - intervals)))
  {
    Serial.println(" - Doesn't need watering");
    digitalWrite(redLED, LOW);
    digitalWrite(greenLED, HIGH);
    digitalWrite(buzzPin, HIGH);
    
    while(runOnce == 0){
    tone(buzzPin, 523.25, 500);
    delay(200);
    tone(buzzPin, 622.25, 200);
    delay(100);
    tone(buzzPin, 698.46, 200);
    delay(100);
    tone(buzzPin, 783.99, 400);
    delay(1000);
    runOnce++; 
    }
    
  }
  else {
    Serial.println(" - Time to water your plant");
    digitalWrite(redLED, HIGH);
    digitalWrite(greenLED, LOW);
    digitalWrite(buzzPin, HIGH);

    // add duration to delay amt 
    tone(buzzPin, 466.16, 700);
    delay(1000); 
    if(runOnce > 0){
    runOnce = 0;
    }
  }
  delay(500);
}
```

# My Tips
If you're thinking about making this project, here are some tips I wish I knew before I started : 

- When you calibrate your values, your sensor should be giving you one value with a slight fluctuation. For example, let's say it is 400, it shouldn't go any more than 401 or 399. If it is giving you numbers all over the place, check two things.


Firstly, make sure the black, red, and yellow wires are properly in the white holder that is on the edge of the sensor's control board. Sometimes removing it and then pushing it back in with some pressure fixes the issue.

Secondly, look carefully at the sensor's control board for the letters in front of the white holder. You will notice that each wire corresponds to a different pin (GND, VCC, and AOUT). Make sure that the wire that connects to the GND pin is in the GND pin and so on. This might seem obvious but I missed it at first so just check that you did that correctly.


- Be careful with which pin you decide to place the VCC wire in, 3.3 volts or 5 volts. For me, when I put it in the 5 volt pin, the sensor started smoking and was fried, so I had to use my second one. I reccomend using 3.3v instead. 

- I highly reccomend using an Energizer battery like I did to power the arduino, because if you want to walk around and use the sensor, it will be very difficult to carry a laptop around on top of the 3 different parts. Using rubberbands and a battery really simplifies the machine and makes it much easier to use. 

- The buzzer can be difficult to put into the breadboard, because it needs to be really perfectly in there for it to make noise. Just press hard and make sure it stays firmly inside. 

# Helpful Websites
Finally, here are the websites I used to help me with this project.
- https://www.circuits-diy.com/how-to-interface-soil-moisture-sensor-yl-69-hl-69-with-arduino-uno/
- https://wiki.dfrobot.com/Capacitive_Soil_Moisture_Sensor_SKU_SEN0193 
- https://www.arduino.cc/reference/en/language/functions/advanced-io/tone/ 
- https://youtu.be/1_LMAgO14z0 

### Thank you for looking at my website! 
