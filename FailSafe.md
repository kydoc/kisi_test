<h3>In this article we'll detail how to connect the Kisi Controller Pro to a fail-safe lock.</h3>

An access control installation consists of several parts. 
* Kisi Controller Pro
* 12 or 24V DC fail safe electric strike or magnetic lock
* REX (optional)
* Keypad (optional)
* Reader (optional)

Connecting the Kisi Controller Pro to the lock will allow you to unlock the door with the Kisi App. It's a good idea to add a "request to exit" (REX) on the inside of the secured space to allow egress without the app, and a keypad or other access device on the outside of the secured space just in case the Kisi Controller is not accessible from the internet. See the following artiles for help with this:

REX link
Keypad Link

<h3>Connecting the controller to the first lock</h3> 
<p>
![The Controller](https://help.kisi.io/hc/article_attachments/360052318934/Standalone_fail_safe_maglock.PNG)
</p>
<p>
Refer to the product documentation for your electric lock to ensure you’re choosing the correct voltage, and for help in correctly identifying the wires. 
  
To start, connect the positive wire to the correct voltage postition on the first relay. The negative wire should then be connected to NC (Normally Closed). Following this, connect a jumper wire from Common to Ground. 
</p>
<h3>Power and Network connections</h3>

Connect the black wire from the supplied power source to Ground (GND), and the white wire to the 24V position. When the device has power a blue LED should light up.

Plug your ethernet cable into the RJ45 port on the controller. 

