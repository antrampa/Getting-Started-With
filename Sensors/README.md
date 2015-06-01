<h1>HC-SR04 Ultrasonic Sensor</h1>
<h3>About the product</h3>
<p>
Ultrasonic ranging module HC-SR04 provides from 2cm to 400cm non-contact measurement function, the ranging accuracy can reach to 3mm. The modules includes ultrasonic transmitters, receiver and control circuit. The basic principle of work:
 <ol>
  <li>Using IO trigger for at least 10us high level signal,</li>
  <li>The Module automatically sends eight 40 kHz and detect whether there is a pulse signal back.</li>
  <li>IF the signal back, through high level , time of high output IO duration is the time from sending ultrasonic to returning.</li>
 </ol>
</p>
<h3>Wire connecting</h3>
<p>
 <ul>
  <li>5V Supply</li>
  <li>Trigger Pulse Input</li>
  <li>Echo Pulse Output</li>
  <li>0V Ground </li>
 </ul>
</p>
<p>and more <a href="http://www.micropik.com/PDF/HCSR04.pdf" target="_blank">here</a></p>
<h3>Summary</h3>
<p>
 <ol>
  <li><a href="#Project1">Project 1:Testing the HC-SR04 Ultrasonic Sensor</a></li>
  <li><a href="#Project2">Project 2:HC-SR04 Ultrasonic Sensor with LCD dispaly</a></li>
 </ol>
 So let's started
</p>
<h3 id="Project1">Project 1:Testing the HC-SR04 Ultrasonic Sensor</h3>
<p>
Download the whole project <a href="https://github.com/AhmedDjebali/Getting-Started-With/tree/master/Sensors/HC-SR04_Test">here<a><br/>
<strong>>>Description</strong><br/>
This simple project will use the HC-SR04 sensor with an Arduino and a arocessing sketch to provide you a little interactive display on your computer screen.<br/>
<strong>>>Parts Required</strong><br/>
<ul>
  <li>Arduino buy one <a href="">buy one here</a></li>
  <li>HC-SR04 Ultrasonic Sensor <a href="">buy one here</a></li>
  <li>Jumper Wirest</li>
</ul>
<strong>>>Schematic</strong><br/>
Connect the components and wires as shown in this <a href="https://github.com/AhmedDjebali/Getting-Started-With/blob/master/Sensors/HC-SR04_Test/Schematic.jpg">schematic</a> or following the instructions below : <br/>
<ul>
  <li>VCC to Arduino 5V</li>
  <li>GND to Arduino GND</li>
  <li>Echo to Arduino pin 12</li>
  <li>Trig to Arduino pin 13</li>
</ul>
<strong>>>Code</strong><br/>
Upload this <a href="https://github.com/AhmedDjebali/Getting-Started-With/blob/master/Sensors/HC-SR04_Test/HC-SR04_Test.ino">code</a> to the Arduino
</p>
<h3 id="Project2">Project 2:Testing the HC-SR04 Ultrasonic Sensor with LCD dispaly</h3>
<p>
Download the whole project <a href="https://github.com/AhmedDjebali/Getting-Started-With/tree/master/Sensors/HC-SR04_with_LCD">here<a><br/>
<strong>>>Description</strong><br/>
In addition to the HC-SR04 sensor and an Arduino this project will use an LCD display.<br/>
<strong>>>Parts Required</strong><br/>
<ul>
  <li>Arduino buy one <a href="">buy one here</a></li>
  <li>HC-SR04 Ultrasonic Sensor <a href="">buy one here</a></li>
  <li>LCD display<li/>
  <li>Jumper Wirest</li>
</ul>
<strong>>>Schematic</strong><br/>
Connect the components and wires as shown in this <a href="https://github.com/AhmedDjebali/Getting-Started-With/blob/master/Sensors/HC-SR04_with_LCD/Schematic.jpg">schematic</a> or following the instructions below : <br/>
<ol>
 <li>HC-SR04 Ultrasonic Sensor</li>
 <ul>
  <li>VCC to Arduino 5V</li>
  <li>GND to Arduino GND</li>
  <li>Trig to Arduino pin 13</li>
  <li>Echo to Arduino pin 12</li>
</ul>
<li>LCD Display (I used JHD162A)</li>
<ul>
  <li>VSS to Arduino GND</li>
  <li>VCC to Arduino 5V</li>
  <li>VEE to Arduino GND</li>
  <li>RS to Arduino pin 11</li>
  <li>R/W to Arduino pin 10</li>
  <li>E to Arduino pin 9</li>
  <li>DB4 to Arduino pin 2</li>
  <li>DB5 to Arduino pin 3</li>
  <li>DB6 to Arduino pin 4</li>
  <li>DB7 to Arduino pin 5</li>
  <li>LED+ to Arduino 5V</li>
  <li>LED- to Arduino GND</li>
</ul>
</ol>
<strong>>>Code</strong><br/>
Upload this <a href="https://github.com/AhmedDjebali/Getting-Started-With/blob/master/Sensors/HC-SR04_with_LCD/HC-SR04_with_LCD.ino">code</a> to the Arduino
</p>
