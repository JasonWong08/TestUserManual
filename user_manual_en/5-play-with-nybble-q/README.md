---
description: 会动的小猫
---

# 3 🕹 Play with Nybble Q

The Nybble Q robot is equipped with various sensors and modules including a gyroscope, touch sensors, ultrasonic sensors, voice recognition, and Bluetooth. You can try patting it or stroking its back to observe its reactions.

You can interact directly with the robot by following the simple quick start guide below. You can also download mobile or computer apps to explore more advanced controls. Developers familiar with coding can also program the robot through graphical interfaces, Arduino, Python, or Raspberry Pi platforms.

## Quick Start

### Voice Control

You can control the Petoi robot to perform various skills using voice commands without a wake word. The robot currently supports two languages (Chinese and English) and comes with 40 preset voice commands. Additionally, you can record any sound clip to create up to 10 custom commands.

**Testing**

When the robot starts up, voice recognition defaults to English mode. Try saying "hello" to the robot, and it will perform a greeting gesture.

{% hint style="info" %}
Please test in a quiet environment to reduce recognition failures and accidental activations. The louder the background noise, the louder you need to speak or the closer you need to be to the robot.

If you speak to the robot but receive no response, the language mode may have been changed.

You can say "Bing Bing" to switch to English mode, or "Di Di" to switch to Chinese mode.

**For More Voice Commands**

Please check the postcard included in the packaging box. The backside lists a variety of voice commands to control additional robot actions.
{% endhint %}

<figure><img src="../.gitbook/assets/image (29).png" alt=""><figcaption></figcaption></figure>

**Turning the Voice Recognition Feature on and off**

By default, voice commands are always enabled, so the robot continuously listens to ambient sounds, which can easily result in accidental activation of voice commands.

To avoid unintentionally triggering the robot’s response to voice commands—for example, when conversing with others—you can say "Be quiet" to the robot, and the voice command module will be disabled.

To re-enable the voice recognition feature, you can say "Play sound".

{% hint style="info" %}
Upon the next startup, the robot will still automatically enter voice recognition mode.
{% endhint %}

**Custom Commands (Advanced)**

When the robot is operating in English mode, you can activate the custom voice command mode by saying the voice command "Start learning" or entering XAe in the serial port monitor. Follow the voice prompts to record your custom voice commands. To exit the custom voice command mode, say "Stop learning" or enter XAf in the serial port monitor.

{% hint style="info" %}
If the module is not in English, you can say "Bing Bing" to switch to English mode.
{% endhint %}

You can record up to 10 custom voice commands.

After exiting the custom voice command mode, you can trigger the robot’s corresponding actions by speaking any of the recorded voice commands.

To delete all custom voice commands at once, say the voice command "Clear the learning data".

### Gyroscope Perception

**Hold and shake in hand, balance response**

GIF——

**Place on a flat surface with slight shaking, balance response**

GIF——

&#x20;

**Tip over, self-righting movement**

GIF——

&#x20;

**Grab by the neck or tail and release**

GIF——

&#x20;

**Place on a table and tap the back or push downward**

GIF——

### Back Touch Interaction

Nybble Q features four independent touch areas on its back, located on the left side, right side, center, and near the tail. Each touch area is pre-programmed with distinct interactive responses—let’s explore them!

#### Touch Point Layout

<figure><img src="../.gitbook/assets/image (30).png" alt=""><figcaption></figcaption></figure>

Touch Areas & Responses：

* Left Area: Lightly touch to make Nybble Q turn its head to the left and look back.
* Right Area: Lightly touch to make Nybble Q turn its head to the right and look back.
* Center Area: Lightly touch to wake up the device or trigger a random action.
* Touch near the tail to activate lively movements like tail wagging or back arching.

{% hint style="warning" %}
Usage Tips:

1.Nybble Q will not execute new actions if the same spot is touched repeatedly or if two touch points are pressed simultaneously.

2.Wait for the current action to complete before triggering a new command to ensure smooth interaction.
{% endhint %}

### **Ultrasonic**

**Obstacle Avoidance**

When an obstacle is detected ahead, the robot reacts differently based on the obstacle's distance.

Randomly sitting down, turning, or reversing.

图片或者GIF——

**LED Lights**

The lights change colors.

图片或者GIF——



### Micro:bit Controller (Optional)

Instructions:

The robot and micro:bit controller connect via Bluetooth.

Please turn on the micro:bit controller first, then power on or restart the robot. Please do not reverse this order.

After powering on, the controller and robot will automatically pair. If multiple robots are powered on, pairing follows a first-come-first-served rule.

A connection sound plays once paired, and the letter N (for Nybble) is displayed.

图片——看是否需要

**Basic Operations**

<figure><img src="../.gitbook/assets/image (24).png" alt=""><figcaption></figcaption></figure>

**Joystick (left side):**

Controls movement: forward, backward, left, right, and diagonally.

Pushing the joystick fully left/right makes the robot spin in place.

Quickly push the joystick forward twice to trigger a rapid forward dash.

**Single/Dual Button Actions:**

Logo (touch): Rest mode.

A: Long press to rotate the robot’s head.

B: Long press to synchronize the robot’s body movement with the controller’s gyroscope.

C: Crawl.

D: Kick.

E: Toggle sitting/standing.

F: Hug.

A+B: Cheer.

C+E: Boxing.

D+F: Face-washing.

E+F: "Lucky Cat" waving.

&#x20;

**Button + Joystick Combo:**

Hold a button and move the joystick to specify a direction.

By default, a single tap/release of the joystick triggers random direction movement.

**Limitations:**

The joystick requires 300 ms to detect double-tap events, causing slight delays in button+joystick forward actions.&#x20;

Single-button actions may trigger before combo commands.

Rapid button presses during control switching may fail to register.

&#x20;

**Customizing Controller Functions (Advanced):**

In code, button functions are defined as:

keyCmd = \[

\# Touch, A, B, C, D, E, F, A+B, C+E, D+F, E+F

\["d", "keyGyro","keyJoystick","kcr", "kkc" ,"stateSwitch" , "khi", "kchr", "kbx", "kwsf","klucky"], # Nybble

]

You can modify the action commands or remap button combinations.

Currently, only A+B, C+E, D+F, and E+F are reserved for dual-button combos.

Additional combos (e.g., A+F, B+D) can be added but may be less ergonomic to press simultaneously.
