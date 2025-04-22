---
description: “Life is like a box of chocolate.”
---

# 2 🧩 Open the Box

## Pre-Startup Posture

To prevent the servos from getting stuck, please adjust the robot's legs to the correct position before powering it on.

<figure><img src=".gitbook/assets/image (40).png" alt=""><figcaption></figcaption></figure>

## Usage Scenario

First test it on the calibrator and use it on a stable table or floor only after familiarizing yourself with its operation.

<figure><img src=".gitbook/assets/image (41).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
When using it on a table, keep it within your arm's reach to prevent it from falling and avoid damage.
{% endhint %}

## Power On

Simply turn on the robot's battery to start using it. If you encounter any issues during operation, please refer to the Other Situations below.

### Battery Switch

Press and hold the battery button for 2 to 3 seconds to turn the power on/off. You will hear a short melody, and the battery indicator will light up blue. If the indicator is red, refer to the charging method below.

<figure><img src=".gitbook/assets/image (42).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
After turning on the battery, the robot requires approximately 5 seconds for initialization, and a melody will play upon completion;

During storage and transportation, the robot's battery charge may decrease. When using it for the first time, please ensure the battery is sufficiently charged;

It is recommended to place the robot on the calibration stand before long-pressing to activate the battery;

If you use the robot on the floor, please ensure the robot is positioned upright after activating the battery. Otherwise, it will continuously attempt to flip itself over or perform other corrective motions upon startup;

If the robot is placed on its side when powered on, it will automatically initiate the calibration posture.
{% endhint %}

### Battery Indicator

Before use, please read the instructions on the bottom of the packaging box carefully to ensure correct operation of the battery.

<figure><img src=".gitbook/assets/image (43).png" alt=""><figcaption><p>        Low Battery                                   Full Battery                              Intermediate Battery</p></figcaption></figure>

Press and hold the blue button on the battery for 2–3 seconds to turn the power on or off.\
During charging, the indicator light shows red; after charging is complete, the indicator light turns green.\
Press the blue button briefly to check the battery status:

· When fully charged, the indicator light is blue.

· When voltage is low, the indicator light is red.

· During battery depletion, the indicator color gradually changes from blue to red.

Note the correct use of battery interfaces: Use the Type-C interface for charging, and the 2P 2.54MM red-black wire terminal interface to power Nybble Q. Please don't mix them up:

If the robot detects low battery, it will pause movements and beep. At this time, you need to remove the battery and charge it using a standard 5V USB Type-C interface data cable. For safety reasons, the battery will automatically stop supplying power to the robot during charging.

### Buzzer Sounds**声音**

| **Sound**                  | **Trigger Timing**             | **Indication**                       |
| -------------------------- | ------------------------------ | ------------------------------------ |
| Short melody               | Power on or restart            | Program startup successful           |
| Program startup successful | During use                     | Program received command             |
| Repeating melody           | During pauses in use or action | Low battery or battery not connected |

## Other Situations

### Charging

The robot's battery socket has limited dimensions, so when the battery is installed on the battery seat, it cannot be directly charged via USB. The battery needs to be removed from the battery socket before charging.

{% hint style="info" %}
Before charging, turn off the battery (press and hold for 3 seconds). After connecting the charging cable, the battery will automatically shut down (cease external power supply).
{% endhint %}

{% hint style="warning" %}
Please do not confuse the circuit board’s download port with the battery charging port.
{% endhint %}

There are two charging methods:

1 Remove only the battery from the main body, which is quick and simple.

<figure><img src=".gitbook/assets/image (44).png" alt=""><figcaption></figcaption></figure>

2 Remove the side panel first, then detach the battery from the circuit board to fully separate the battery from the main body. This method is suitable for users with spare batteries.

<figure><img src=".gitbook/assets/image (45).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/image (46).png" alt=""><figcaption><p>When reinstalling the battery, please ensure the battery connector passes through the small hole shown in the image before connecting it to the circuit board on the main body.</p></figcaption></figure>

<figure><img src=".gitbook/assets/image (48).png" alt=""><figcaption></figcaption></figure>

### Replacing the Battery

The operation is the same as charging method 2 mentioned above.

### Device Freezing or Unresponsive

There are two solutions：

1\. Check the battery indicator light. If the battery level is too low, please charge it promptly.

2\. If the battery level is normal, remove the back cover and try pressing the reset button on the motherboard next to the LED logo to reboot the robot.

<figure><img src=".gitbook/assets/image (49).png" alt=""><figcaption></figcaption></figure>

### Servo

For plastic servos, we have added two protection mechanisms to extend their service life:

一、When subjected to short-term external force impacts, the protection mechanism activates, causing the servo to produce a clicking sound.\
二、When the servo is under prolonged force, the protection mechanism activates, causing the servo to release force.

### Clicking Sound

The plastic servo contains a clutch gear for protection.

When powered on, if the servo's rotation is blocked by external obstacles, the clicking clutch sound will occur. Examples include:

Manually rotating the servo away from its target angle;

The servo being physically jammed;

The servo being obstructed by other objects.

<figure><img src=".gitbook/assets/舵机离合.gif" alt=""><figcaption></figcaption></figure>

### Sudden Servo Stoppage or Force Release:

To enhance servo durability, we added stall current detection. If the servo is under prolonged force without triggering the clutch gear, it will automatically enter force-release mode.

The servo returns to normal mode when it receives a new angle command.

<figure><img src=".gitbook/assets/舵机卸力.gif" alt=""><figcaption></figcaption></figure>
