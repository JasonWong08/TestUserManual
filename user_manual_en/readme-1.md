---
description: Good preparation saves time in the long run.
---

# 1 🧘‍♂️ Preparation

## **Check the Package**

Thank you very much for purchasing our product! We highly value your user experience and hope you will enjoy this delightful journey. To ensure the device was not damaged during transportation and verify all accessories are complete, we recommend following these steps after receiving the package:

1. Verify the recipient's name, address, order number, and other details on the product packaging to confirm they match your order. If any information is incorrect, please do not open the box and contact us or the logistics provider immediately.
2. Inspect the shipping box for integrity. Check for apparent damage, moisture, deformation, or signs of tampering. If packaging damage is found, please photograph it for documentation purposes and avoid accepting, signing for, or opening the package before confirming the device's condition. As shown in the example below, your Nybble Q should arrive fully intact, without any damage, clean and well-presented.

<figure><img src=".gitbook/assets/image (32).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/image (34).png" alt=""><figcaption></figcaption></figure>

## Unboxing

<figure><img src=".gitbook/assets/image (35).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
Note: Nybble Q is FDM 3D-printed, and its Z-axis strength is limited. Please do not apply excessive force during use. Avoid placing it near the edge of a table to prevent accidental falls, which may cause component breakage.
{% endhint %}

<table><thead><tr><th width="487.390625">Name</th><th>Quantity</th></tr></thead><tbody><tr><td>Main Unit: Nybble Q robotic cat</td><td>1</td></tr><tr><td>Assembly Components: Tail/Calibrator parts</td><td>1</td></tr><tr><td>Manual: Stickers/Postcard (with voice commands on the back)/Calibrator manual</td><td>1</td></tr><tr><td>Tools: Self-tapping screwdriver/USB cable</td><td>1</td></tr><tr><td>Spare Parts: Spare tail servo horn/Spare servo/Raspberry Pi mount/Springs &#x26; screws</td><td>1</td></tr></tbody></table>

### Assembly

Upon initial unboxing, you only need to assemble the tail and calibrator yourself before interacting with the robot.

If you need to perform operations such as battery removal or replacement, or opening the back cover during use, please refer to the "**Commonly Used Removable Parts**" section below.

#### Assembling the Tail

The tail rotates around a metal shaft and automatically adjusts its vertical range in response to gravity.

It enables Nybble Q to perform advanced movements, such as rolling over, standing upright during boxing actions, and more.

For shipping safety, the body and tail are packed separately. Please assemble them according to the instructions.

<figure><img src=".gitbook/assets/尾巴安装.gif" alt=""><figcaption></figcaption></figure>

Steps:

1. Check if the contour surface of the tail rudder disk has a smooth transition, avoiding any right-angle bends.
2. Locate the notch on the tail rudder disk, then place the metal shaft of the tail onto the notch of the rudder disk.
3. Keep the tail body flush against the metal shaft and rotate it downward around the shaft. During this process, the tail body may come into contact with the servo arm. Continue applying downward force until you hear a click, indicating that the metal shaft of the tail has snapped into the notch of the rudder disk.
4. To disassemble the tail, follow the reverse of the installation steps.

<figure><img src=".gitbook/assets/image (39).png" alt=""><figcaption><p>The red circled area is the surface after the 3D printed supports are removed. It may sometimes be uneven and could affect the installation of the tail. You can use nippers/side cutters to trim it.</p></figcaption></figure>



{% hint style="info" %}
If the wheel on the tail is not rotating smoothly, possible causes could be:

1. Small burrs remaining on the wheel or tail - Trim them with a sprue cutter.
2. The wheel and tail are positioned too closely. Pinch the tail to hold it in place, then grip the wheel and pull it along the axial direction to adjust the spacing.
{% endhint %}

<figure><img src=".gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>

#### Assemble the Calibrator

To facilitate debugging the robot and prevent falls, we have designed a specialized bracket. Please assemble the bracket according to the images below, and then gently place the robot onto it. Small snap fasteners between the robot and the bracket will ensure a secure and stable connection.

<figure><img src=".gitbook/assets/image (21).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure>

### Commonly Used Removable Parts

**Battery**

When the battery is dead (the indicator light is red) or needs replacement, the battery must be removed from the body.

The battery and the body are connected via a sliding groove with a snap latch. To detach the battery, slide it horizontally in the direction of the cat's head.

<figure><img src=".gitbook/assets/spaces_sH8LElvsjsHIa2uNVZzo_uploads_LFk7PL2TQ2PDHn6BD0XU_ 拆下电池.webp" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
To prevent the battery from accidentally detaching during vigorous robot movements, we have designed the buckle mechanism to be secure, which means you will feel some resistance when pushing the battery into place.

Installing and removing the battery are reverse processes.

Please ensure the charging port of the battery aligns with the direction of the robot's head.

<img src=".gitbook/assets/image (9).png" alt="" data-size="original">
{% endhint %}

**Back Cover**

{% hint style="warning" %}
Please do not forcibly separate the back cover from the body, as a flex cable connects the touch circuit board between them. Excessive force may cause the flex cable to come off or even break.
{% endhint %}

<figure><img src=".gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>

The back cover and the body are interlocked with each other via small protrusions. To remove the back cover, locate the indicated points shown in the image and gently squeeze both sides toward the center axis to release the snap-fit connectors.

For proper orientation during reinstallation, align the back cover by referencing its logo—the cat ears should face forward, indicating the correct front orientation.

<figure><img src=".gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>

**Back Cover Touch Circuit Board**

Under normal circumstances, there is no need to remove the flexible printed circuit (FPC) for touch functionality from the back cover. If you wish to detach the back cover FPC completely, please follow these steps:

After removing the back cover, note the relative orientation between the circuit board and the back cover. There is a flip tab on the connector - lift this tab upward. Once the tab is flipped open, the cable beneath it can be fully detached along with the back cover and circuit board.

Reconnecting the cable to the circuit board is the reverse process: align the cable, ensuring proper orientation, and press it firmly into place.

<figure><img src=".gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>

**Side Panel**

The side panels are decorative components that conceal the servo wires inside the robot. They connect to the main body via snap-fit connectors.

During subsequent use, when components such as servos or batteries need replacement, the abdominal side panels of the Nybble Q must be removed. The process is simple: locate the notches on both sides of the panel, grip them with your fingernail, and pry outward to detach the side panel.

<figure><img src=".gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/image (17).png" alt=""><figcaption></figcaption></figure>

## Tools and Accessories

| Tool                         | Notes                                                                                                                                                                                                                                                                                                 |
| ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| A Windows/Mac/Linux Computer | <p>Download the <a href="https://docs.petoi.com/desktop-app/introduction">Petoi Desktop APP</a><br>Download <a href="https://www.arduino.cc/en/software">Arduino IDE</a> (Optional)<br>Download <a href="https://docs.petoi.com/block-based-programming/petoi-coding-blocks">Mind+</a> (Optional)</p> |
| USB charging port            | 5V 1A output should be enough                                                                                                                                                                                                                                                                         |
| A smartphone(Android/iOS)    | Download [mobile app](https://docs.petoi.com/mobile-app/app-guide) (Optional)                                                                                                                                                                                                                         |
