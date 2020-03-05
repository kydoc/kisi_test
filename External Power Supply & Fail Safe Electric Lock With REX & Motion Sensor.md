<h3>In this article we'll detail how to connect the Kisi Controller Pro to a fail-safe lock with external power, and also add a push to exit button as well as a motion sensor.</h3>

An access control installation consists of several parts. 
* Kisi Controller Pro
* 12 or 24V DC fail safe electric strike or magnetic lock
* Push to open button
* Motion sensor
* Keypad (optional)
* Reader (optional)

Connecting the Kisi Controller Pro to the lock will allow you to unlock the door with the Kisi App. With a "request to exit" (REX) on the inside of the secured space the door can be opened even without the app. You should also consider placing a keypad or card reader on the outside of the secured space just in case the Kisi Controller is not accessible from the internet. See the following articles for help with installing the keypad/cardreader

*Keypad Link

<h3>Connecting the controller to the first lock</h3> 
<p>
  
![The Controller](https://help.kisi.io/hc/article_attachments/360053218093/REX_and_Motion_Sensor.png)

</p>
<p>
Before you begin, pleae refer to the product documentation for your electric lock to ensure you choose the correct voltage, and for help in correctly identifying the wires.
</p>

* Begin by connecting the negative (-) lead from the Maglock to the Normally Closed (NC) connection on the Push to Exit button.

* Connect the Common (COM) connection on your Push to Exit to the Common (COM) connection of the Motion Sensor.

* Connect the Normally Closed (NC) connection of the Motion Sensor to the Common (COM) connection of the Power Supply's output.

* Connect the positive (+) lead from the Maglock to the Normally Closed (NC) output connection of the Power Supply's output.

* Finally, connect the low voltage wiring from Ground (GND) on the Kisi controller to Ground (GND) on the Power Supply's input, and Normally Open (NO) on the Kisi controller to In (IN) on the Power Supply's input.

[![Vid](http://img.youtube.com/vi/H0vQgyN_pN0/0.jpg)](https://www.youtube.com/watch?v=H0vQgyN_pN0)

You now have the door installation wired up. Click [here](https://help.kisi.io/hc/en-us/sections/115002573047-Kisi-Web-Dashboard) for information on how to configure the controller in the Kisi web dashboard
