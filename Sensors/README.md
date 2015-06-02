<h1>HC-SR04 Ultrasonic Ranging Sensor</h1>
<h3>About the product</h3>
<p>
The ultrasonic ranging module HC-SR04 uses sonar to determine distance to an object. It provides from 2cm to 400cm non-contact measurement function with high accuracy and stable readings in an easy-to-use package, the ranging accuracy can reach to 3mm. The module includes ultrasonic transmitter, receiver and control circuit. The basic principle of work:
</p>
<h3>Features</h3>
<p>
  <ul>
    <li>Power Supply:+5V DC</li>
    <li>Quiescent Current : &lt;2mA</li>
    <li>Working Current: 15mA</li>
    <li>Effectual Angle: &lt;15°</li>
    <li>Ranging Distance : 2cm – 400 cm/1&#8243; &#8211; 13ft</li>
    <li>Resolution : 0.3 cm</li>
    <li>Measuring Angle: 30 degree</li>
    <li>Trigger Input Pulse width: 10uS</li>
    <li>Dimension: 45mm x 20mm x 15mm</li>
  </ul>
</p>
<h3>Pins</h3>
<p>
 <ul>
  <li>VCC: +5VDC Supply</li>
  <li>Trig: Trigger Pulse Input</li>
  <li>Echo: Echo Pulse Output</li>
  <li>GND: 0V Ground </li>
 </ul>
</p>
<p>and more <a href="http://www.micropik.com/PDF/HCSR04.pdf" target="_blank">here</a></p>
<h3>Projects Summary</h3>
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
<h4>1 - Description</h4>
<p>
This simple project will use the HC-SR04 sensor with an Arduino and a arocessing sketch to provide you a little interactive display on your computer screen.
</p>
<h4>2 - Parts Required</h4>
<p>
<ul>
  <li>Arduino buy one <a href="">buy one here</a></li>
  <li>HC-SR04 Ultrasonic Sensor <a href="">buy one here</a></li>
  <li>Jumper Wires</li>
</ul>
</p>
<h4>Schematic</h4>
<p>
Connect the components and wires as shown in this <a href="https://github.com/AhmedDjebali/Getting-Started-With/blob/master/Sensors/HC-SR04_Test/Schematic.jpg">schematic</a> or following the instructions below : <br/>
<ul>
  <li>VCC to Arduino 5V</li>
  <li>GND to Arduino GND</li>
  <li>Echo to Arduino pin 12</li>
  <li>Trig to Arduino pin 13</li>
</ul>
</p>
<h4>Code</h4>
<p>
Upload this <a href="https://github.com/AhmedDjebali/Getting-Started-With/blob/master/Sensors/HC-SR04_Test/HC-SR04_Test.ino">code</a> to the Arduino
</p>
</p>
<h3 id="Project2">Project 2:Testing the HC-SR04 Ultrasonic Sensor with LCD dispaly</h3>
<p>
Download the whole project <a href="https://github.com/AhmedDjebali/Getting-Started-With/tree/master/Sensors/HC-SR04_with_LCD">here<a><br/>
<h4>Description</strong><h4>
<p>
In addition to the HC-SR04 sensor and an Arduino this project will use an LCD display.<br/>
</p>
<h4>Parts Required</h4>
<p>
<ul>
  <li>Arduino buy one <a href="">buy one here</a></li>
  <li>HC-SR04 Ultrasonic Sensor <a href="">buy one here</a></li>
  <li>LCD display</li>
  <li>Jumper Wires</li>
</ul>
</p>
<h4>Schematic</h4>
<p>
Connect the components and wires as shown in this <a href="https://github.com/AhmedDjebali/Getting-Started-With/blob/master/Sensors/HC-SR04_with_LCD/Schematic.jpg">schematic</a> or following the instructions below : <br/>
<ul>
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
</ul>
</p>
<h4>Code</h4>
<p>
Upload this <a href="https://github.com/AhmedDjebali/Getting-Started-With/blob/master/Sensors/HC-SR04_with_LCD/HC-SR04_with_LCD.ino">code</a> to the Arduino
</p>
</p>
