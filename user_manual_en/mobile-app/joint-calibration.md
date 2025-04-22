---
description: 📱🤖
---

# Joint Calibration

Below is the display interface when you first use the app for calibration. We recommend placing the robot on the calibrator during this process.

## Nybble Q <a href="#nybble" id="nybble"></a>

<figure><img src="../.gitbook/assets/IMG_7174.png" alt=""><figcaption><p>后面会改成新的</p></figcaption></figure>

{% hint style="info" %}
You can also reopen this calibration interface by clicking the menu icon in the upper-right corner of the control panel and selecting "**Calibrate**".

![](../.gitbook/assets/IMG_7140.PNG)
{% endhint %}

Upon entering the calibration interface, click the "Calibrate" button to immediately rotate all servo output shafts to their calibration positions.

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

First select the joint servo index number from the calibration interface image (when adjusting leg servos, adjust the thigh first followed by the calf). Then use the "+" or "-" buttons to fine-tune the joint to a right-angle position.

{% hint style="info" %}
If calibration offset exceeds +/-9 degrees, remove the corresponding servo component, rotate it by one gear tooth position, reinstall it, then use the "+" or "-" buttons.

For example: If you need to use -10 as calibration value, remove the limb, rotate one gear tooth, then reinstall. The new calibration value should be around +4 (their absolute values sum to 14).

Note: Avoid rotating servo output shafts manually during adjustment.
{% endhint %}

You can test calibration results by switching between Rest/Stand/Walk statuses using the corresponding buttons.

图片】校准姿势、站立、休息姿势

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Note: A second calibration round may be required for optimal results.
{% endhint %}

After completing calibration, remember to click "Save" to preserve calibration offsets. Or click "<" in the upper-left corner to discard changes.
