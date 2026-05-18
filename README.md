# Tdrone
Open source coaxial drone
-------------------------
![SHOUYE](https://github.com/ShenZhenAccelerationTechCo/Tdrone/blob/master/pictures/SHOUYE.png)
In recent years, multi-rotor aerodynamic aircraft have been widely used in consumer UAVs and some special industries. Mention of hovering aircraft, the first thing we have in mind is multi-rotor, which ignoring the potential of other hovering aerodynamic configurations. There is no denying the fact that multi-rotor occupied most of the market share, while UAVs should not only has one form. It is necessary that a flexible choice of pneumatic layout for different applications and scenarios.         
In this context, we have developed a coaxial two-propeller UAV Tdrone. This article provides a complete information and an open source solution to share this. I hope you are interested in  this kind of aircraft，even make one by yourself!Why Coaxial drone？

## Why Coaxial Tdrone?
The flight principle of coaxial twin-propeller aerodynamic configuration aircraft is similar to that of our common helicopter. Unlike helicopters, the coaxial twin-propeller aerodynamic configuration cancels the common tail rotor on helicopters and uses two propellers with the same diameter and coaxial arrangement. Like helicopters, tilting discs are used as pitch-changing mechanisms to control the pitch and roll degrees of freedom of aircraft. The following video describes how the tilting disk works:

* [youtube Helicopter Swashplate/Prato Ciclico Principle Video](https://www.youtube.com/watch?v=-kWhNi-MZAM)  
* [bilibili Helicopter Swashplate/Prato Ciclico Principle Video](https://www.bilibili.com/video/av36403262)

For a small coaxial twin-propeller aerodynamic configuration, a single-layer pitch-changeable structure is usually adopted, that is to say, only one rotor can be pitched in the upper and lower layers, while the other is fixed-pitch. The advantage of this layout is to simplify the mechanical structure to the greatest extent, which is conducive to the manufacture and later maintenance of aircraft. Of course, if we pursue better performance, we can also design more complex double-layer variable-pitch structure to achieve better flight performance.

The advantages of coaxial twin-propeller over multi-rotor aircraft are as follows:
* 1. Coaxial twin-propeller aircraft has larger rotor area and higher flight efficiency under the same working size (in flight).
* 2. The coaxial twin-propeller vehicle has larger payload under the same working size (in flight).
* 3. Under the same payload, the rotor speed is lower than that of multi-rotor, which results in less noise and better silence.
* 4. When generating pitch and roll control moments, the main rotor does not need to be accelerated or decelerated frequently, which reduces the energy loss. Especially in the case of large aircraft size, this advantage over multi-rotor will be more obvious.
* 5. The propeller can be folded and accepted conveniently without the complicated folding and locking mechanism of the multi-rotor aircraft arm. The folded fuselage is more regular and easy to carry and transport.

The disadvantages of coaxial twin-propeller compared with multi-rotor aircraft are as follows:
* 1. Comparing with multi-rotor aircraft, the mechanical structure of coaxial twin-propeller aircraft is relatively complex, resulting in lower manufacturing cost and maintainability than multi-rotor aircraft.
* 2. Flight mode is more complex than multi-rotor, which has some challenges in flight control design.

Every aircraft is designed for target use and use environment. There is no absolute difference between different aerodynamic layouts. Not only on Earth, but on other planets our theory still holds true

![RME1](https://github.com/ShenZhenAccelerationTechCo/Tdrone/blob/master/pictures/RME1.jpg)

* [NASA Coaxial Aircraft](https://www.nasa.gov/press-release/mars-helicopter-to-fly-on-nasa-s-next-red-planet-rover-mission)

Aircraft！

More than 100 years after the Wright brothers completed their first manned flight using fixed-wing aircraft, we are hopeful to witness the first use of UAVs on planets other than Earth, which is a coaxial drone!

## Tdrone Project

### 1.Overview:
The Tdrone UAV project began development in October 2015. By April 2016, the first-generation Tdrone had achieved basic flight capability, as shown in the video (link).
Tdrone uses two modified 1806 brushless motors for propulsion. Two servos are used to control the swashplate, while yaw is controlled via differential motor speed. The flight controller is a CC3D. It is equipped with a two-axis stabilized gimbal and an action camera. The flight time is approximately 10 minutes.

### 1. general situation:

The Tdrone UAV was developed in October 2015, and by April 2016 the first generation of Tdrone had initial flight capabilities, as shown in the video. Tdrone uses two modified 1806 brushless motors as power, two steering motors to control the swashplate and differential control for yaw. Flight control uses CC3D flight control. It is equipped with a two-axis stable platform and a motion camera. The duration is about 10 minutes.

Tdrone Project![RME2](https://github.com/ShenZhenAccelerationTechCo/Tdrone/blob/master/pictures/RME2.jpg) 
![TU4](https://github.com/ShenZhenAccelerationTechCo/Tdrone/blob/master/pictures/TU4.png)

### 2.Flight Controller Section:
Tdrone uses the CC3D flight controller. The CC3D natively supports this type of aircraft, but requires some special settings.
This is the configuration file I used (link). You can use this configuration file directly. However, the radio transmitter settings need to be reconfigured according to the specific transmitter you are using. This step is the same as with multi-rotors — simply refer to the multi-rotor section for guidance.
The Ground Station firmware version is 15.02.02.
We will continue to improve and update the flight controller setup tutorial here. Please stay tuned for future updates.
   
### 3. Manufacturing methods and materials:
Tdrone is manufactured by 3D printing technology. All parts are optimized for 3D printing, which can be printed directly. The printing materials are made of ordinary ABS plastics. Aluminum tubes are used in the central core. 98% of the parts are fixed by screw, which is convenient for later maintenance and replacement.

![3D Structural Side View](https://github.com/ShenZhenAccelerationTechCo/Tdrone/blob/master/pictures/3D结构侧面.png)
![3D Structural Side View](https://github.com/ShenZhenAccelerationTechCo/Tdrone/blob/master/pictures/3D结构正面.png)

### 4.DIY points for attention:
I fully understand your urgency to build your own aircraft as soon as possible. But before everything starts, you need to figure out the following points:
* 1. All part sizes are optimized according to the tolerance accuracy of my 3D printer. Maybe it is not suitable for your 3D printer. You need to adjust the parts appropriately according to your own printer. You can print out some parts that need to be matched to test.
* 2. Use the motor and steering gear as much as possible, and do not deviate too much from the model we recommend or approximate.
* 3. The manufacture of the aircraft needs a certain practical ability. Although the printer has completed most of the work, you still need to manually process some metal parts wiring and adjust the motor.

### More Information
Click the YouTube or Bilibili video links below to watch the actual flight footage of the Tdrone.

* [YouTube Flight Video](https://www.youtube.com/watch?v=wCfMVMhZFWQ&t=2s)
* [bilibili Flight Video](https://www.bilibili.com/video/av36347739/?redirectFrom=h5)


### Contact Us
    Email：linkalladmin@163.com
    
If you have any questions or suggestions, please feel free to join the discussion in the forum below under our post:：
* [Domestic Discussion Forum](http://bbs.5imx.com/forum.php?mod=viewthread&tid=1445702&extra=page%3D1)

### Donate

If you think this project is helpful to you, but also for better service to the community and constantly update the new design, please donate to us!

* [Donate via Paypal](PayPal.Me/accelerationtech)

* Donate via Alipay !  [Donate via Alipay](https://github.com/ShenZhenAccelerationTechCo/Tdrone/blob/master/pictures/支付宝捐赠.jpg)

* Donate via WeChatpay !  [Donate via WeChatpay](https://github.com/ShenZhenAccelerationTechCo/Tdrone/blob/master/pictures/微信捐赠.png)





